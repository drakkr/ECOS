# Makefile for ECOS method - English version

all: doc-odt doc-pdf doc-html

doc-odt:
	pandoc --toc -o ecos-1.0_en.odt ecos-head_en.md ecos-changelog_en.md ecos-intro_en.md ecos-manifesto_en.md ecos-process_en.md ecos-define-collect-evaluate_en.md ecos-opex_en.md ecos-capex_en.md ecos-compare-tools_en.md

doc-pdf:
	pandoc -N --toc --template=ecos-template_en.latex --variable lang=english -o ecos-1.0_en.pdf ecos-head_en.md ecos-changelog_en.md ecos-intro_en.md ecos-manifesto_en.md ecos-process_en.md ecos-define-collect-evaluate_en.md ecos-opex_en.md ecos-capex_en.md ecos-compare-tools_en.md

doc-html:
	pandoc --self-contained -o ecos-1.0_en.html ecos-head_en.md ecos-changelog_en.md ecos-intro_en.md ecos-manifesto_en.md ecos-process_en.md ecos-define-collect-evaluate_en.md ecos-opex_en.md ecos-capex_en.md ecos-compare-tools_en.md
