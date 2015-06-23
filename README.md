# Paper Template for Crypto Papers #

## Contents ##

* [crypto.bib](http://cryptobib.di.ens.fr/) for the bibliographies

* [cryptocode](https://www.ctan.org/pkg/cryptocode) for typesetting cryptography

* some convenient UTF-8 macros, e.g. write π for \pi to increase readabiliy

* `.dir-locals.el` for enabling visual-line-mode in [magit](https://github.com/magit/magit)

* some small macros to make life easier, like `\isanonymous{true}{false}`

## Cloning ##

You might want to first fork and then clone recursively to also get crypto.bib, e.g.:

    git clone --recursive https://malb@bitbucket.org/<you>/<name>.git

You might then also want to `git mv main.tex <name>.tex`
