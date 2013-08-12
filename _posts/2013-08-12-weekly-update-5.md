---
layout: post
title:  "Weekly update #5"
date:   2013-08-12 16:00:00
draft:  1
---

Engineering

* hoodie command-line interface (cli): Bug fixes and new hoodie app template based on [vertebrae](https://github.com/svnlto/backbone-hoodie) ([@svnlto](https://github.com/svnlto))
* hoodie-server: move open-browser functionality to hoodie cli - WIP ([@svnlto](https://github.com/svnlto))
* hoodie-server: add testing and linting capability - WIP ([@svnlto](https://github.com/svnlto))
* API change: removed hoodie.store.cache, hoodie.store.markAsChanged, hoodie.store.markAllAsChanged from public API - WIP ([@gr2m](https://github.com/gr2m))
* API change: hoodie.open(storeName, options) now supports passing an options.validate method to validate objects locally before they get stored - WIP ([@gr2m](https://github.com/gr2m))
* internal: simplified implementation of hoodie.remote by simply creating a remoteStore instance, with some extra parameters - WIP ([@gr2m](https://github.com/gr2m))
* internal: localStore and remoteStore do not longer inherit from storeBase, instead there is a storeApi module now that can be configured (validation, persistance hooks) - WIP ([@gr2m](https://github.com/gr2m))
* specs: fixing all the test for the upcoming (interal) rewrite in v0.3-cheesecake - WIP ([@gr2m](https://github.com/gr2m))
* added emoji :smiley_cat: support :heart:

Communications

* Blog post: [Weekly activity report #4](http://blog.hood.ie/2013/08/hoodie-weekly-activity-report-4/)  ([@ffffux](https://github.com/ffffux))
* Blog post: [Proof of Concept: Hoodie login with Persona](http://blog.hood.ie/2013/08/proof-of-concept-hoodie-login-with-persona/)  ([@janl](https://github.com/janl))
* Blog post: [Hoodie Presentation at Glasgow JS (incl. recording & slides](http://blog.hood.ie/2013/08/hoodie-presentation-at-glasgow-js/)  ([@janl](https://github.com/janl))
* Blog post: [Hoodie's top links of the week #2](http://blog.hood.ie/2013/08/tgif-hoodies-top-links-of-the-week-2-surveillance-the-future-of-programming-and-how-to-make-a-difference/)  ([@ffffux](https://github.com/ffffux))
