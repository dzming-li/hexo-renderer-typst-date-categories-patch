# hexo-renderer-typst-date-categories-patch
A patch to enable setting dates and categories in `.typ` files.
## how to install
First you have to install patch-package.
```
npm -i patch-package --force
mkdir patch
```
Then download `hexo-renderer-typst+0.6.0.patch` and put it into `patch/`.
## how to use
At the head of your `.typ` files, write like this:
```typst
// date: 2025-5-6
// categories:
// - Math
The typst content begins here
```
