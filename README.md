# How to use
* Run `pmbootstrap init` and force stop it (<kbd>CTRL</kbd>+<kbd>C</kbd>) after it clones pmaports.
* Copy these folders to `~/.local/var/pmbootstrap/cache_git/pmaports/device/downstream/` (as replace)
* Run `pmbootstrap checksum device-samsung-goyavewifi`
* Run `pmbootstrap build device-samsung-goyavewifi --force`, kernel compilation will take some time.
* Re-run init and contiune installing!
