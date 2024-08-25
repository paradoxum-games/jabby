# jorp

jorp is a debugger for [jecs](https://github.com/ukendio/jecs) based off [gorp](https://github.com/aloroid/gorp)

It's still in the early stages of development and is very experimental.

> [!NOTE]
> jorp is compatible with [jecs 0.2.9](https://github.com/Ukendio/jecs/releases/tag/v0.2.9) and up.
> Do not install jecs 0.3.0-rc.1, it is not compatible (for some reason, it's older than 0.2.9??)

> [!NOTE]
> jorp requires vide with the recursive queue fix patch (git commit [fbe2f01](https://github.com/centau/vide/commit/fbe2f01bb99e7f7744d5039f36c494044f044883))

While jorp is currently only compatible with jecs, the intent is to be able to use this as a alternative debugger for Matter and ECR.