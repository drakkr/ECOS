# Makefile for ECOS documentation

all: doc-odt doc-pdf doc-html

doc-odt:
	pandoc --toc -o ecos-1.0_fr.odt ecos-head_fr.md ecos-changelog_fr.md ecos-intro_fr.md ecos-manifesto_fr.md ecos-process_fr.md ecos-define-collect-evaluate_fr.md ecos-opex_fr.md ecos-capex_fr.md ecos-compare-tools_fr.md

doc-pdf:
	pandoc -N --toc --template=ecos-template_fr.latex --variable lang=french -o ecos-1.0_fr.pdf ecos-head_fr.md ecos-changelog_fr.md ecos-intro_fr.md ecos-manifesto_fr.md ecos-process_fr.md ecos-define-collect-evaluate_fr.md ecos-opex_fr.md ecos-capex_fr.md ecos-compare-tools_fr.md

doc-html:
	pandoc --self-contained -o ecos-1.0_fr.html ecos-head_fr.md ecos-changelog_fr.md ecos-intro_fr.md ecos-manifesto_fr.md ecos-process_fr.md ecos-define-collect-evaluate_fr.md ecos-opex_fr.md ecos-capex_fr.md ecos-compare-tools_fr.md
