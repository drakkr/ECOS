# Makefile for ECOS method - French version

DOC=ecos

VERSION=1.0

LANG=fr

TITLE=Méthode d’Évaluation des Coûts liés à l’Open Source (ECOS)

#List of edocs to be included in Gitit export
PAGES=ecos-intro_$(LANG).md ecos-manifesto_$(LANG).md ecos-process_$(LANG).md ecos-define_$(LANG).md ecos-collect_$(LANG).md ecos-evaluate_$(LANG).md ecos-opex_$(LANG).md ecos-capex_$(LANG).md ecos-compare_$(LANG).md ecos-tools_$(LANG).md

#List of edocs to be included in other exports
CHAPTERS=ecos-head_$(LANG).md ecos-changelog_$(LANG).md $(PAGES) ecos-drakkr_$(LANG).md

DOCNAME=$(DOC)-$(VERSION)_$(LANG)

doc-pdf:
	mkdir -p dist
	pandoc -N --toc --template=ecos-template_$(LANG).latex --variable lang=french -o dist/$(DOCNAME).pdf $(CHAPTERS)

doc-odt:
	mkdir -p dist
	pandoc --toc -o dist/$(DOCNAME).odt $(CHAPTERS)

doc-html:
	mkdir -p dist
	pandoc --self-contained -o dist/$(DOCNAME).html $(CHAPTERS)

gitit:
	mkdir -p dist
	cp -R Images dist/.
	#Create summary Gitit page
	echo '---' > dist/$(DOCNAME).page
	echo 'title: $(TITLE)' >> dist/$(DOCNAME).page
	echo '...' >> dist/$(DOCNAME).page
	echo -e '\n' >> dist/$(DOCNAME).page

	$(foreach PAGE, $(PAGES), echo -e "[$(subst # ,,$(shell head -1 $(PAGE)))]($(basename $(PAGE))) \n" >> dist/$(DOCNAME).page ;)

	#Create Gitit pages with titles
	$(foreach PAGE, $(PAGES), echo -e "---\ntitle: $(subst # ,,$(shell head -1 $(PAGE)))\n...\n" > dist/$(basename $(PAGE)).page ; cat $(PAGE) >> dist/$(basename $(PAGE)).page ;)

clean:
	rm -Rf dist/