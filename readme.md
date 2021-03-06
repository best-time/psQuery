﻿psQuery
=======

What is psQuery?
----------------
psQuery is a jQuery-like DOM library. It aims to cover just
the 'core' jQuery use cases (CSS, ajax, DOM) using 'modern'
native methods (`JSON`, `document.querySelectorAll`, etc) so
that it can be fast and light. In some ways it was inspired
by Zepto.js but with IE9+ compatibility in mind. It does this
all in less than 2kb gzipped+minified.

psQuery targets most non-deprecated methods from the jQuery 2.1+ API
except for these:

* Deferred
* Effects
* Animation
* Custom jQuery Selectors (e.g. `:eq`, `:has`, etc)
* Most event shorthands

How to use
----------
psQuery can be embedded in a page just like jQuery.
e.g. `<script src="psQuery.js"></script>`

Try it out
----------
You can try it for development without even downloading it by
leveraging the great Rawgit service. This code will always embed 
the latest version of psQuery: `<script src='https://rawgit.com/pseudosavant/psQuery/master/src/psQuery.min.js'></script>`.

psQuery is WIP
--------------
psQuery is a work-in-progress. So far only the core ajax, CSS, and some
DOM methods are supported. If there is something that isn't working for
you then drop me a line, or even better, a pull request.

License
-------
psQuery is open-source and uses the **MIT license**
