# Shiny Binder

Test of deploying Shiny apps with Binder


Notes:

* Doesn't work with renv
* Used holepunch to set up `./binder/install.R` (may need manual tweaking since it didn't `c()` multiple libraries), and `./binder/runtime.txt`


http://mybinder.org/v2/gh/mawds/shiny-binder/HEAD?urlpath=shiny/sample/

(Idea: would `renv::restore()` in `./binder/install.R` work?)

