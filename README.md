# CodingStyleNode.js
Node.js Coding Style for personal projects.

**Follow** : https://github.com/ludkiller/node-style-guide

###Few Imporant tips.
-------------------

* Never use with or eval, Use **===** over **==**.

* Always declare your variables with **var** in the appropriate scope - don't fallback to the global scope.

* Wrap your app in a closure **(function(){})()**, if you plan on releasing code that runs server-side as well as in the browser.(not for now).

* Callbacks should take err as the first argument and if they themselves take a callback as an argument.it should be last, e.g. **callback(err, param1, param2, callback)**.
