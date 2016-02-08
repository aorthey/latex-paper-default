latex-paper-default
===================

Default draft paper from the scratch:
```
  mkdir paper-directory
  cd paper-directory
  git init
  git submodule add git@github.com:orthez/latex-paper-default.git util
  cp util/default_draft.tex .
```
One-liner to add default paper and bib lib (https://github.com/orthez/latex-bibliography-default)

ICRA
```
  git init && git submodule add git@github.com:orthez/latex-paper-default.git util && git submodule add git@github.com:orthez/latex-bibliography-default.git bib && cp util/default_draft_icra.tex . 
```
TRO
```
  git init && git submodule add git@github.com:orthez/latex-paper-default.git util && git submodule add git@github.com:orthez/latex-bibliography-default.git bib && cp util/default_draft_tro.tex . 
```
WAFR
```
  git init && git submodule add git@github.com:orthez/latex-paper-default.git util && git submodule add git@github.com:orthez/latex-bibliography-default.git bib && cp util/default_draft_wafr.tex . 
```

