Slownie.js
==========

Little library for converting numbers into polish words. 
Ported from C version at found at http://4programmers.net/Pastebin/1668

Installation
------------

```
$ npm install slownie
```
or 

```
{ "name" : "my-project"
, "version" : "1.0.0"
, "dependencies" : { "slownie" : ">= 1.0.0" } }
```

and then 

```
$ npm install
```

Usage example
-------------
```

var Slownie = new require('slownie').Slownie();
console.log( Slownie.get(1939393822) );

```

TODO
----

* i18n
