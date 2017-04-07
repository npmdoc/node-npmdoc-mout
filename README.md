# api documentation for  [mout (v1.0.0)](http://moutjs.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-mout.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mout) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mout.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mout)
#### Modular Utilities

[![NPM](https://nodei.co/npm/mout.png?downloads=true)](https://www.npmjs.com/package/mout)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mout/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-mout_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mout/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mout/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mout/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Miller Medeiros",
        "email": "contact@millermedeiros.com",
        "url": "http://blog.millermedeiros.com"
    },
    "bugs": {
        "url": "https://github.com/mout/mout/issues/"
    },
    "contributors": [
        {
            "name": "Adam Nowotny"
        },
        {
            "name": "André Cruz",
            "email": "amdfcruz@gmail.com"
        },
        {
            "name": "Conrad Zimmerman",
            "url": "http://www.conradz.com"
        },
        {
            "name": "Friedemann Altrock",
            "email": "frodenius@gmail.com"
        },
        {
            "name": "Igor Almeida",
            "email": "igor.p.almeida@gmail.com"
        },
        {
            "name": "Jarrod Overson",
            "url": "http://jarrodoverson.com"
        },
        {
            "name": "Mathias Paumgarten",
            "email": "mail@mathias-paumgarten.com"
        },
        {
            "name": "Zach Shipley"
        }
    ],
    "dependencies": {},
    "description": "Modular Utilities",
    "devDependencies": {
        "commander": "~1.0.5",
        "handlebars": "~1.0.6",
        "istanbul": "~0.1.27",
        "jasmine-node": "~1.14.5",
        "jshint": "~2.9.1",
        "mdoc": "~0.3.2",
        "nodefy": "*",
        "regenerate": "~0.5.4",
        "requirejs": "~2.2.0",
        "rimraf": "~2.5.2",
        "rocambole": "~0.2.3"
    },
    "directories": {
        "doc": "./doc"
    },
    "dist": {
        "shasum": "9bdf1d4af57d66d47cb353a6335a3281098e1501",
        "tarball": "https://registry.npmjs.org/mout/-/mout-1.0.0.tgz"
    },
    "gitHead": "2ff20539568bfe53b8c1da521cd743cf0ba79c2a",
    "homepage": "http://moutjs.com/",
    "keywords": [
        "utilities",
        "functional",
        "amd-utils",
        "stdlib"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "millermedeiros",
            "email": "miller@millermedeiros.com"
        },
        {
            "name": "satazor",
            "email": "andremiguelcruz@msn.com"
        },
        {
            "name": "conradz",
            "email": "me@conradz.com"
        },
        {
            "name": "mathias.paumgarten",
            "email": "mail@mathias-paumgarten.com"
        }
    ],
    "name": "mout",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/mout/mout.git"
    },
    "scripts": {
        "pretest": "node build pkg",
        "test": "istanbul test tests/runner.js --hook-run-in-context"
    },
    "testling": {
        "preprocess": "node build testling",
        "browsers": {
            "ie": [
                7,
                8,
                9,
                10
            ],
            "firefox": [
                17,
                "nightly"
            ],
            "chrome": [
                23,
                "canary"
            ],
            "opera": [
                12,
                "next"
            ],
            "safari": [
                5.1,
                6
            ],
            "iphone": [
                6
            ],
            "ipad": [
                6
            ]
        },
        "scripts": [
            "tests/lib/jasmine/jasmine.js",
            "tests/lib/jasmine/jasmine.async.js",
            "tests/lib/jasmine/jasmine-tap.js",
            "tests/lib/requirejs/require.js",
            "tests/testling/src.js",
            "tests/testling/specs.js",
            "tests/runner.js"
        ]
    },
    "version": "1.0.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module mout](#apidoc.module.mout)
1.  [function <span class="apidocSignatureSpan">mout.</span>random.random ()](#apidoc.element.mout.random.random)
1.  [function <span class="apidocSignatureSpan">mout.</span>time.now ()](#apidoc.element.mout.time.now)
1.  object <span class="apidocSignatureSpan">mout.</span>array
1.  object <span class="apidocSignatureSpan">mout.</span>collection
1.  object <span class="apidocSignatureSpan">mout.</span>date
1.  object <span class="apidocSignatureSpan">mout.</span>date.i18n_
1.  object <span class="apidocSignatureSpan">mout.</span>fn
1.  object <span class="apidocSignatureSpan">mout.</span>function
1.  object <span class="apidocSignatureSpan">mout.</span>lang
1.  object <span class="apidocSignatureSpan">mout.</span>math
1.  object <span class="apidocSignatureSpan">mout.</span>number
1.  object <span class="apidocSignatureSpan">mout.</span>object
1.  object <span class="apidocSignatureSpan">mout.</span>queryString
1.  object <span class="apidocSignatureSpan">mout.</span>random
1.  object <span class="apidocSignatureSpan">mout.</span>string
1.  object <span class="apidocSignatureSpan">mout.</span>time
1.  string <span class="apidocSignatureSpan">mout.</span>VERSION

#### [module mout.array](#apidoc.module.mout.array)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>append (arr1, arr2)](#apidoc.element.mout.array.append)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>collect (arr, callback, thisObj)](#apidoc.element.mout.array.collect)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>combine (arr1, arr2)](#apidoc.element.mout.array.combine)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>compact (arr)](#apidoc.element.mout.array.compact)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>contains (arr, val)](#apidoc.element.mout.array.contains)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>difference (arr)](#apidoc.element.mout.array.difference)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>equals (a, b, callback)](#apidoc.element.mout.array.equals)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>every (arr, callback, thisObj)](#apidoc.element.mout.array.every)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>filter (arr, callback, thisObj)](#apidoc.element.mout.array.filter)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>find (arr, iterator, thisObj)](#apidoc.element.mout.array.find)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>findIndex (arr, iterator, thisObj)](#apidoc.element.mout.array.findIndex)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>findLast (arr, iterator, thisObj)](#apidoc.element.mout.array.findLast)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>findLastIndex (arr, iterator, thisObj)](#apidoc.element.mout.array.findLastIndex)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>flatten (arr, level)](#apidoc.element.mout.array.flatten)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>forEach (arr, callback, thisObj)](#apidoc.element.mout.array.forEach)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>groupBy (arr, categorize, thisObj)](#apidoc.element.mout.array.groupBy)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>indexOf (arr, item, fromIndex)](#apidoc.element.mout.array.indexOf)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>indicesOf (arr, item, fromIndex)](#apidoc.element.mout.array.indicesOf)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>insert (arr, rest_items)](#apidoc.element.mout.array.insert)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>intersection (arr)](#apidoc.element.mout.array.intersection)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>invoke (arr, methodName, var_args)](#apidoc.element.mout.array.invoke)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>join (items, separator)](#apidoc.element.mout.array.join)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>last (arr)](#apidoc.element.mout.array.last)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>lastIndexOf (arr, item, fromIndex)](#apidoc.element.mout.array.lastIndexOf)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>map (arr, callback, thisObj)](#apidoc.element.mout.array.map)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>max (arr, iterator, thisObj)](#apidoc.element.mout.array.max)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>min (arr, iterator, thisObj)](#apidoc.element.mout.array.min)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>pick (arr, nItems)](#apidoc.element.mout.array.pick)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>pluck (arr, propName)](#apidoc.element.mout.array.pluck)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>range (start, stop, step)](#apidoc.element.mout.array.range)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>reduce (arr, fn, initVal)](#apidoc.element.mout.array.reduce)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>reduceRight (arr, fn, initVal)](#apidoc.element.mout.array.reduceRight)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>reject (arr, callback, thisObj)](#apidoc.element.mout.array.reject)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>remove (arr, item)](#apidoc.element.mout.array.remove)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>removeAll (arr, item)](#apidoc.element.mout.array.removeAll)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>reverse (array)](#apidoc.element.mout.array.reverse)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>shuffle (arr)](#apidoc.element.mout.array.shuffle)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>slice (arr, start, end)](#apidoc.element.mout.array.slice)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>some (arr, callback, thisObj)](#apidoc.element.mout.array.some)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>sort (arr, compareFn)](#apidoc.element.mout.array.sort)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>sortBy (arr, callback, context)](#apidoc.element.mout.array.sortBy)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>split (array, segments)](#apidoc.element.mout.array.split)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>take (n, callback, thisObj)](#apidoc.element.mout.array.take)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>toLookup (arr, key)](#apidoc.element.mout.array.toLookup)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>union (arrs)](#apidoc.element.mout.array.union)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>unique (arr, compare)](#apidoc.element.mout.array.unique)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>xor (arr1, arr2)](#apidoc.element.mout.array.xor)
1.  [function <span class="apidocSignatureSpan">mout.array.</span>zip (arr)](#apidoc.element.mout.array.zip)

#### [module mout.collection](#apidoc.module.mout.collection)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>contains ()](#apidoc.element.mout.collection.contains)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>every ()](#apidoc.element.mout.collection.every)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>filter (list, iterator, thisObj)](#apidoc.element.mout.collection.filter)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>find ()](#apidoc.element.mout.collection.find)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>forEach ()](#apidoc.element.mout.collection.forEach)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>make_ (arrMethod, objMethod, defaultReturn)](#apidoc.element.mout.collection.make_)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>map (list, callback, thisObj)](#apidoc.element.mout.collection.map)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>max ()](#apidoc.element.mout.collection.max)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>min ()](#apidoc.element.mout.collection.min)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>pluck (list, key)](#apidoc.element.mout.collection.pluck)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>reduce ()](#apidoc.element.mout.collection.reduce)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>reject (list, iterator, thisObj)](#apidoc.element.mout.collection.reject)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>size (list)](#apidoc.element.mout.collection.size)
1.  [function <span class="apidocSignatureSpan">mout.collection.</span>some ()](#apidoc.element.mout.collection.some)

#### [module mout.date](#apidoc.module.mout.date)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>dayOfTheYear (date)](#apidoc.element.mout.date.dayOfTheYear)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>diff (start, end, unitName)](#apidoc.element.mout.date.diff)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>isLeapYear (fullYear)](#apidoc.element.mout.date.isLeapYear)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>isSame (date1, date2, period)](#apidoc.element.mout.date.isSame)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>parseIso (str)](#apidoc.element.mout.date.parseIso)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>quarter (date)](#apidoc.element.mout.date.quarter)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>startOf (date, period)](#apidoc.element.mout.date.startOf)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>strftime (date, format, localeData)](#apidoc.element.mout.date.strftime)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>timezoneAbbr (date)](#apidoc.element.mout.date.timezoneAbbr)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>timezoneOffset (date)](#apidoc.element.mout.date.timezoneOffset)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>totalDaysInMonth (fullYear, monthIndex)](#apidoc.element.mout.date.totalDaysInMonth)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>totalDaysInYear (fullYear)](#apidoc.element.mout.date.totalDaysInYear)
1.  [function <span class="apidocSignatureSpan">mout.date.</span>weekOfTheYear (date, firstDayOfWeek)](#apidoc.element.mout.date.weekOfTheYear)
1.  object <span class="apidocSignatureSpan">mout.date.</span>i18n_

#### [module mout.date.i18n_](#apidoc.module.mout.date.i18n_)
1.  [function <span class="apidocSignatureSpan">mout.date.i18n_.</span>set (localeData)](#apidoc.element.mout.date.i18n_.set)
1.  object <span class="apidocSignatureSpan">mout.date.i18n_.</span>days
1.  object <span class="apidocSignatureSpan">mout.date.i18n_.</span>days_abbr
1.  object <span class="apidocSignatureSpan">mout.date.i18n_.</span>months
1.  object <span class="apidocSignatureSpan">mout.date.i18n_.</span>months_abbr
1.  string <span class="apidocSignatureSpan">mout.date.i18n_.</span>X
1.  string <span class="apidocSignatureSpan">mout.date.i18n_.</span>am
1.  string <span class="apidocSignatureSpan">mout.date.i18n_.</span>c
1.  string <span class="apidocSignatureSpan">mout.date.i18n_.</span>pm
1.  string <span class="apidocSignatureSpan">mout.date.i18n_.</span>x

#### [module mout.function](#apidoc.module.mout.function)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>after (closure, times)](#apidoc.element.mout.function.after)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>awaitDelay ( callback, delay )](#apidoc.element.mout.function.awaitDelay)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>bind (fn, context, args)](#apidoc.element.mout.function.bind)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>compose ()](#apidoc.element.mout.function.compose)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>constant (value)](#apidoc.element.mout.function.constant)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>debounce (fn, threshold, isAsap)](#apidoc.element.mout.function.debounce)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>func (name)](#apidoc.element.mout.function.func)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>identity (val)](#apidoc.element.mout.function.identity)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>makeIterator_ (src, thisObj)](#apidoc.element.mout.function.makeIterator_)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>memoize (fn, resolver)](#apidoc.element.mout.function.memoize)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>partial (f)](#apidoc.element.mout.function.partial)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>prop (name)](#apidoc.element.mout.function.prop)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>series ()](#apidoc.element.mout.function.series)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>throttle (fn, delay)](#apidoc.element.mout.function.throttle)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>timeout (fn, millis, context)](#apidoc.element.mout.function.timeout)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>times (n, callback, thisObj)](#apidoc.element.mout.function.times)
1.  [function <span class="apidocSignatureSpan">mout.function.</span>wrap (fn, wrapper)](#apidoc.element.mout.function.wrap)

#### [module mout.lang](#apidoc.module.mout.lang)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>clone (val)](#apidoc.element.mout.lang.clone)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>createObject (parent, props)](#apidoc.element.mout.lang.createObject)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>ctorApply (ctor, args)](#apidoc.element.mout.lang.ctorApply)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>deepClone (val, instanceClone)](#apidoc.element.mout.lang.deepClone)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>deepEquals (a, b, callback)](#apidoc.element.mout.lang.deepEquals)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>defaults (var_args)](#apidoc.element.mout.lang.defaults)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>inheritPrototype (child, parent)](#apidoc.element.mout.lang.inheritPrototype)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>is (x, y)](#apidoc.element.mout.lang.is)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isArguments (val)](#apidoc.element.mout.lang.isArguments)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isArray ()](#apidoc.element.mout.lang.isArray)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isBoolean (val)](#apidoc.element.mout.lang.isBoolean)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isDate (val)](#apidoc.element.mout.lang.isDate)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isEmpty (val)](#apidoc.element.mout.lang.isEmpty)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isFinite (val)](#apidoc.element.mout.lang.isFinite)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isFunction (val)](#apidoc.element.mout.lang.isFunction)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isInteger (val)](#apidoc.element.mout.lang.isInteger)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isKind (val, kind)](#apidoc.element.mout.lang.isKind)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isNaN (val)](#apidoc.element.mout.lang.isNaN)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isNull (val)](#apidoc.element.mout.lang.isNull)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isNumber (val)](#apidoc.element.mout.lang.isNumber)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isObject (val)](#apidoc.element.mout.lang.isObject)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isPlainObject (value)](#apidoc.element.mout.lang.isPlainObject)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isPrimitive (value)](#apidoc.element.mout.lang.isPrimitive)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isRegExp (val)](#apidoc.element.mout.lang.isRegExp)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isString (val)](#apidoc.element.mout.lang.isString)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isUndefined (val)](#apidoc.element.mout.lang.isUndefined)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>isnt (x, y)](#apidoc.element.mout.lang.isnt)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>kindOf (val)](#apidoc.element.mout.lang.kindOf)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>toArray (val)](#apidoc.element.mout.lang.toArray)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>toNumber (val)](#apidoc.element.mout.lang.toNumber)
1.  [function <span class="apidocSignatureSpan">mout.lang.</span>toString (val)](#apidoc.element.mout.lang.toString)
1.  object <span class="apidocSignatureSpan">mout.lang.</span>GLOBAL

#### [module mout.math](#apidoc.module.mout.math)
1.  [function <span class="apidocSignatureSpan">mout.math.</span>ceil (val, step)](#apidoc.element.mout.math.ceil)
1.  [function <span class="apidocSignatureSpan">mout.math.</span>clamp (val, min, max)](#apidoc.element.mout.math.clamp)
1.  [function <span class="apidocSignatureSpan">mout.math.</span>countSteps (val, step, overflow)](#apidoc.element.mout.math.countSteps)
1.  [function <span class="apidocSignatureSpan">mout.math.</span>floor (val, step)](#apidoc.element.mout.math.floor)
1.  [function <span class="apidocSignatureSpan">mout.math.</span>inRange (val, min, max, threshold)](#apidoc.element.mout.math.inRange)
1.  [function <span class="apidocSignatureSpan">mout.math.</span>isNear (val, target, threshold)](#apidoc.element.mout.math.isNear)
1.  [function <span class="apidocSignatureSpan">mout.math.</span>lerp (ratio, start, end)](#apidoc.element.mout.math.lerp)
1.  [function <span class="apidocSignatureSpan">mout.math.</span>loop (val, min, max)](#apidoc.element.mout.math.loop)
1.  [function <span class="apidocSignatureSpan">mout.math.</span>map (val, min1, max1, min2, max2)](#apidoc.element.mout.math.map)
1.  [function <span class="apidocSignatureSpan">mout.math.</span>norm (val, min, max)](#apidoc.element.mout.math.norm)
1.  [function <span class="apidocSignatureSpan">mout.math.</span>overflow (number, min, max)](#apidoc.element.mout.math.overflow)
1.  [function <span class="apidocSignatureSpan">mout.math.</span>round (value, radix)](#apidoc.element.mout.math.round)

#### [module mout.number](#apidoc.module.mout.number)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>abbreviate (val, nDecimals, dict)](#apidoc.element.mout.number.abbreviate)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>currencyFormat (val, nDecimalDigits, decimalSeparator, thousandsSeparator)](#apidoc.element.mout.number.currencyFormat)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>enforcePrecision (val, nDecimalDigits)](#apidoc.element.mout.number.enforcePrecision)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>isNaN (val)](#apidoc.element.mout.number.isNaN)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>nth (i)](#apidoc.element.mout.number.nth)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>ordinal (n)](#apidoc.element.mout.number.ordinal)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>pad (n, minLength, char)](#apidoc.element.mout.number.pad)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>rol (val, shift)](#apidoc.element.mout.number.rol)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>ror (val, shift)](#apidoc.element.mout.number.ror)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>sign (val)](#apidoc.element.mout.number.sign)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>toInt (val)](#apidoc.element.mout.number.toInt)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>toUInt (val)](#apidoc.element.mout.number.toUInt)
1.  [function <span class="apidocSignatureSpan">mout.number.</span>toUInt31 (val)](#apidoc.element.mout.number.toUInt31)
1.  number <span class="apidocSignatureSpan">mout.number.</span>MAX_INT
1.  number <span class="apidocSignatureSpan">mout.number.</span>MAX_SAFE_INTEGER
1.  number <span class="apidocSignatureSpan">mout.number.</span>MAX_UINT
1.  number <span class="apidocSignatureSpan">mout.number.</span>MIN_INT

#### [module mout.object](#apidoc.module.mout.object)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>bindAll (obj, rest_methodNames)](#apidoc.element.mout.object.bindAll)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>contains (obj, needle)](#apidoc.element.mout.object.contains)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>deepFillIn (target, defaults)](#apidoc.element.mout.object.deepFillIn)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>deepMatches (target, pattern)](#apidoc.element.mout.object.deepMatches)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>deepMixIn (target, objects)](#apidoc.element.mout.object.deepMixIn)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>equals (a, b, callback)](#apidoc.element.mout.object.equals)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>every (obj, callback, thisObj)](#apidoc.element.mout.object.every)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>fillIn (obj, var_defaults)](#apidoc.element.mout.object.fillIn)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>filter (obj, callback, thisObj)](#apidoc.element.mout.object.filter)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>find (obj, callback, thisObj)](#apidoc.element.mout.object.find)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>flatten (obj, level)](#apidoc.element.mout.object.flatten)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>forIn (obj, fn, thisObj)](#apidoc.element.mout.object.forIn)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>forOwn (obj, fn, thisObj)](#apidoc.element.mout.object.forOwn)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>functions (obj)](#apidoc.element.mout.object.functions)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>get (obj, prop)](#apidoc.element.mout.object.get)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>has (obj, prop)](#apidoc.element.mout.object.has)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>hasOwn (obj, prop)](#apidoc.element.mout.object.hasOwn)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>keys ()](#apidoc.element.mout.object.keys)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>map (obj, callback, thisObj)](#apidoc.element.mout.object.map)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>matches (target, props)](#apidoc.element.mout.object.matches)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>max (obj, compareFn)](#apidoc.element.mout.object.max)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>merge ()](#apidoc.element.mout.object.merge)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>min (obj, iterator)](#apidoc.element.mout.object.min)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>mixIn (target, objects)](#apidoc.element.mout.object.mixIn)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>namespace (obj, path)](#apidoc.element.mout.object.namespace)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>omit (obj, var_keys)](#apidoc.element.mout.object.omit)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>pick (obj, var_keys)](#apidoc.element.mout.object.pick)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>pluck (obj, propName)](#apidoc.element.mout.object.pluck)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>reduce (obj, callback, memo, thisObj)](#apidoc.element.mout.object.reduce)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>reject (obj, callback, thisObj)](#apidoc.element.mout.object.reject)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>result (obj, prop)](#apidoc.element.mout.object.result)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>set (obj, prop, val)](#apidoc.element.mout.object.set)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>size (obj)](#apidoc.element.mout.object.size)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>some (obj, callback, thisObj)](#apidoc.element.mout.object.some)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>unset (obj, prop)](#apidoc.element.mout.object.unset)
1.  [function <span class="apidocSignatureSpan">mout.object.</span>values (obj)](#apidoc.element.mout.object.values)

#### [module mout.queryString](#apidoc.module.mout.queryString)
1.  [function <span class="apidocSignatureSpan">mout.queryString.</span>contains (url, paramName)](#apidoc.element.mout.queryString.contains)
1.  [function <span class="apidocSignatureSpan">mout.queryString.</span>decode (queryStr, shouldTypecast)](#apidoc.element.mout.queryString.decode)
1.  [function <span class="apidocSignatureSpan">mout.queryString.</span>encode (obj)](#apidoc.element.mout.queryString.encode)
1.  [function <span class="apidocSignatureSpan">mout.queryString.</span>getParam (url, param, shouldTypecast)](#apidoc.element.mout.queryString.getParam)
1.  [function <span class="apidocSignatureSpan">mout.queryString.</span>getQuery (url)](#apidoc.element.mout.queryString.getQuery)
1.  [function <span class="apidocSignatureSpan">mout.queryString.</span>parse (url, shouldTypecast)](#apidoc.element.mout.queryString.parse)
1.  [function <span class="apidocSignatureSpan">mout.queryString.</span>setParam (url, paramName, value)](#apidoc.element.mout.queryString.setParam)

#### [module mout.random](#apidoc.module.mout.random)
1.  [function <span class="apidocSignatureSpan">mout.</span>random ()](#apidoc.element.mout.random.random)
1.  [function <span class="apidocSignatureSpan">mout.random.</span>choice (items)](#apidoc.element.mout.random.choice)
1.  [function <span class="apidocSignatureSpan">mout.random.</span>guid ()](#apidoc.element.mout.random.guid)
1.  [function <span class="apidocSignatureSpan">mout.random.</span>rand (min, max)](#apidoc.element.mout.random.rand)
1.  [function <span class="apidocSignatureSpan">mout.random.</span>randBit ()](#apidoc.element.mout.random.randBit)
1.  [function <span class="apidocSignatureSpan">mout.random.</span>randBool ()](#apidoc.element.mout.random.randBool)
1.  [function <span class="apidocSignatureSpan">mout.random.</span>randHex (size)](#apidoc.element.mout.random.randHex)
1.  [function <span class="apidocSignatureSpan">mout.random.</span>randInt (min, max)](#apidoc.element.mout.random.randInt)
1.  [function <span class="apidocSignatureSpan">mout.random.</span>randSign ()](#apidoc.element.mout.random.randSign)
1.  [function <span class="apidocSignatureSpan">mout.random.</span>randString (length, dictionary)](#apidoc.element.mout.random.randString)

#### [module mout.random.random](#apidoc.module.mout.random.random)
1.  [function <span class="apidocSignatureSpan">mout.random.</span>random ()](#apidoc.element.mout.random.random.random)
1.  [function <span class="apidocSignatureSpan">mout.random.random.</span>get ()](#apidoc.element.mout.random.random.get)

#### [module mout.string](#apidoc.module.mout.string)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>camelCase (str)](#apidoc.element.mout.string.camelCase)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>contains (str, substring, fromIndex)](#apidoc.element.mout.string.contains)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>crop (str, maxChars, append)](#apidoc.element.mout.string.crop)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>endsWith (str, suffix)](#apidoc.element.mout.string.endsWith)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>escapeHtml (str)](#apidoc.element.mout.string.escapeHtml)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>escapeRegExp (str)](#apidoc.element.mout.string.escapeRegExp)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>escapeUnicode (str, shouldEscapePrintable)](#apidoc.element.mout.string.escapeUnicode)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>hyphenate (str)](#apidoc.element.mout.string.hyphenate)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>insert (string, index, partial)](#apidoc.element.mout.string.insert)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>interpolate (template, replacements, syntax)](#apidoc.element.mout.string.interpolate)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>lowerCase (str)](#apidoc.element.mout.string.lowerCase)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>lpad (str, minLen, ch)](#apidoc.element.mout.string.lpad)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>ltrim (str, chars)](#apidoc.element.mout.string.ltrim)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>makePath (var_args)](#apidoc.element.mout.string.makePath)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>normalizeLineBreaks (str, lineEnd)](#apidoc.element.mout.string.normalizeLineBreaks)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>pascalCase (str)](#apidoc.element.mout.string.pascalCase)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>properCase (str)](#apidoc.element.mout.string.properCase)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>removeNonASCII (str)](#apidoc.element.mout.string.removeNonASCII)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>removeNonWord (str)](#apidoc.element.mout.string.removeNonWord)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>repeat (str, n)](#apidoc.element.mout.string.repeat)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>replace (str, search, replacements)](#apidoc.element.mout.string.replace)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>replaceAccents (str)](#apidoc.element.mout.string.replaceAccents)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>rpad (str, minLen, ch)](#apidoc.element.mout.string.rpad)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>rtrim (str, chars)](#apidoc.element.mout.string.rtrim)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>sentenceCase (str)](#apidoc.element.mout.string.sentenceCase)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>slugify (str, delimeter)](#apidoc.element.mout.string.slugify)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>startsWith (str, prefix)](#apidoc.element.mout.string.startsWith)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>stripHtmlTags (str)](#apidoc.element.mout.string.stripHtmlTags)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>trim (str, chars)](#apidoc.element.mout.string.trim)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>truncate (str, maxChars, append, onlyFullWords)](#apidoc.element.mout.string.truncate)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>typecast (val)](#apidoc.element.mout.string.typecast)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>unCamelCase (str, delimiter)](#apidoc.element.mout.string.unCamelCase)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>underscore (str)](#apidoc.element.mout.string.underscore)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>unescapeHtml (str)](#apidoc.element.mout.string.unescapeHtml)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>unescapeUnicode (str)](#apidoc.element.mout.string.unescapeUnicode)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>unhyphenate (str)](#apidoc.element.mout.string.unhyphenate)
1.  [function <span class="apidocSignatureSpan">mout.string.</span>upperCase (str)](#apidoc.element.mout.string.upperCase)
1.  object <span class="apidocSignatureSpan">mout.string.</span>WHITE_SPACES

#### [module mout.time](#apidoc.module.mout.time)
1.  [function <span class="apidocSignatureSpan">mout.time.</span>convert (val, sourceUnitName, destinationUnitName)](#apidoc.element.mout.time.convert)
1.  [function <span class="apidocSignatureSpan">mout.time.</span>now ()](#apidoc.element.mout.time.now)
1.  [function <span class="apidocSignatureSpan">mout.time.</span>parseMs (ms)](#apidoc.element.mout.time.parseMs)
1.  [function <span class="apidocSignatureSpan">mout.time.</span>toTimeString (ms)](#apidoc.element.mout.time.toTimeString)

#### [module mout.time.now](#apidoc.module.mout.time.now)
1.  [function <span class="apidocSignatureSpan">mout.time.</span>now ()](#apidoc.element.mout.time.now.now)
1.  [function <span class="apidocSignatureSpan">mout.time.now.</span>get ()](#apidoc.element.mout.time.now.get)



# <a name="apidoc.module.mout"></a>[module mout](#apidoc.module.mout)

#### <a name="apidoc.element.mout.random.random"></a>[function <span class="apidocSignatureSpan">mout.</span>random.random ()](#apidoc.element.mout.random.random)
- description and source-code
```javascript
function random(){
    return random.get();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.time.now"></a>[function <span class="apidocSignatureSpan">mout.</span>time.now ()](#apidoc.element.mout.time.now)
- description and source-code
```javascript
function now(){
    // yes, we defer the work to another function to allow mocking it
    // during the tests
    return now.get();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.array"></a>[module mout.array](#apidoc.module.mout.array)

#### <a name="apidoc.element.mout.array.append"></a>[function <span class="apidocSignatureSpan">mout.array.</span>append (arr1, arr2)](#apidoc.element.mout.array.append)
- description and source-code
```javascript
function append(arr1, arr2) {
    if (arr2 == null) {
        return arr1;
    }

    var pad = arr1.length,
        i = -1,
        len = arr2.length;
    while (++i < len) {
        arr1[pad + i] = arr2[i];
    }
    return arr1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.collect"></a>[function <span class="apidocSignatureSpan">mout.array.</span>collect (arr, callback, thisObj)](#apidoc.element.mout.array.collect)
- description and source-code
```javascript
function collect(arr, callback, thisObj){
    callback = makeIterator(callback, thisObj);
    var results = [];
    if (arr == null) {
        return results;
    }

    var i = -1, len = arr.length;
    while (++i < len) {
        var value = callback(arr[i], i, arr);
        if (value != null) {
            append(results, value);
        }
    }

    return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.combine"></a>[function <span class="apidocSignatureSpan">mout.array.</span>combine (arr1, arr2)](#apidoc.element.mout.array.combine)
- description and source-code
```javascript
function combine(arr1, arr2) {
    if (arr2 == null) {
        return arr1;
    }

    var i = -1, len = arr2.length;
    while (++i < len) {
        if (indexOf(arr1, arr2[i]) === -1) {
            arr1.push(arr2[i]);
        }
    }

    return arr1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.compact"></a>[function <span class="apidocSignatureSpan">mout.array.</span>compact (arr)](#apidoc.element.mout.array.compact)
- description and source-code
```javascript
function compact(arr) {
    return filter(arr, function(val){
        return (val != null);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.contains"></a>[function <span class="apidocSignatureSpan">mout.array.</span>contains (arr, val)](#apidoc.element.mout.array.contains)
- description and source-code
```javascript
function contains(arr, val) {
    return indexOf(arr, val) !== -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.difference"></a>[function <span class="apidocSignatureSpan">mout.array.</span>difference (arr)](#apidoc.element.mout.array.difference)
- description and source-code
```javascript
function difference(arr) {
    var arrs = slice(arguments, 1),
        result = filter(unique(arr), function(needle){
            return !some(arrs, function(haystack){
                return contains(haystack, needle);
            });
        });
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.equals"></a>[function <span class="apidocSignatureSpan">mout.array.</span>equals (a, b, callback)](#apidoc.element.mout.array.equals)
- description and source-code
```javascript
function equals(a, b, callback){
    callback = callback || is;

    if (!isArray(a) || !isArray(b)) {
        return callback(a, b);
    }

    if (a.length !== b.length) {
        return false;
    }

    return every(a, makeCompare(callback), b);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.every"></a>[function <span class="apidocSignatureSpan">mout.array.</span>every (arr, callback, thisObj)](#apidoc.element.mout.array.every)
- description and source-code
```javascript
function every(arr, callback, thisObj) {
    callback = makeIterator(callback, thisObj);
    var result = true;
    if (arr == null) {
        return result;
    }

    var i = -1, len = arr.length;
    while (++i < len) {
        // we iterate over sparse items since there is no way to make it
        // work properly on IE 7-8. see #64
        if (!callback(arr[i], i, arr) ) {
            result = false;
            break;
        }
    }

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.filter"></a>[function <span class="apidocSignatureSpan">mout.array.</span>filter (arr, callback, thisObj)](#apidoc.element.mout.array.filter)
- description and source-code
```javascript
function filter(arr, callback, thisObj) {
    callback = makeIterator(callback, thisObj);
    var results = [];
    if (arr == null) {
        return results;
    }

    var i = -1, len = arr.length, value;
    while (++i < len) {
        value = arr[i];
        if (callback(value, i, arr)) {
            results.push(value);
        }
    }

    return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.find"></a>[function <span class="apidocSignatureSpan">mout.array.</span>find (arr, iterator, thisObj)](#apidoc.element.mout.array.find)
- description and source-code
```javascript
function find(arr, iterator, thisObj){
    var idx = findIndex(arr, iterator, thisObj);
    return idx >= 0? arr[idx] : void(0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.findIndex"></a>[function <span class="apidocSignatureSpan">mout.array.</span>findIndex (arr, iterator, thisObj)](#apidoc.element.mout.array.findIndex)
- description and source-code
```javascript
function findIndex(arr, iterator, thisObj){
    iterator = makeIterator(iterator, thisObj);
    if (arr == null) {
        return -1;
    }

    var i = -1, len = arr.length;
    while (++i < len) {
        if (iterator(arr[i], i, arr)) {
            return i;
        }
    }

    return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.findLast"></a>[function <span class="apidocSignatureSpan">mout.array.</span>findLast (arr, iterator, thisObj)](#apidoc.element.mout.array.findLast)
- description and source-code
```javascript
function findLast(arr, iterator, thisObj){
    var idx = findLastIndex(arr, iterator, thisObj);
    return idx >= 0? arr[idx] : void(0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.findLastIndex"></a>[function <span class="apidocSignatureSpan">mout.array.</span>findLastIndex (arr, iterator, thisObj)](#apidoc.element.mout.array.findLastIndex)
- description and source-code
```javascript
function findLastIndex(arr, iterator, thisObj){
    iterator = makeIterator(iterator, thisObj);
    if (arr == null) {
        return -1;
    }

    var n = arr.length;
    while (--n >= 0) {
        if (iterator(arr[n], n, arr)) {
            return n;
        }
    }

    return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.flatten"></a>[function <span class="apidocSignatureSpan">mout.array.</span>flatten (arr, level)](#apidoc.element.mout.array.flatten)
- description and source-code
```javascript
function flatten(arr, level) {
    if (arr == null) {
        return [];
    }

    level = level == null ? -1 : level;
    return flattenTo(arr, [], level);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.forEach"></a>[function <span class="apidocSignatureSpan">mout.array.</span>forEach (arr, callback, thisObj)](#apidoc.element.mout.array.forEach)
- description and source-code
```javascript
function forEach(arr, callback, thisObj) {
    if (arr == null) {
        return;
    }
    var i = -1,
        len = arr.length;
    while (++i < len) {
        // we iterate over sparse items since there is no way to make it
        // work properly on IE 7-8. see #64
        if ( callback.call(thisObj, arr[i], i, arr) === false ) {
            break;
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.groupBy"></a>[function <span class="apidocSignatureSpan">mout.array.</span>groupBy (arr, categorize, thisObj)](#apidoc.element.mout.array.groupBy)
- description and source-code
```javascript
function groupBy(arr, categorize, thisObj) {
    if (categorize) {
        categorize = makeIterator(categorize, thisObj);
    } else {
        // Default to identity function.
        categorize = identity;
    }

    var buckets = {};
    forEach(arr, function(element) {
        var bucket = categorize(element);
        if (!(bucket in buckets)) {
            buckets[bucket] = [];
        }

        buckets[bucket].push(element);
    });

    return buckets;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.indexOf"></a>[function <span class="apidocSignatureSpan">mout.array.</span>indexOf (arr, item, fromIndex)](#apidoc.element.mout.array.indexOf)
- description and source-code
```javascript
function indexOf(arr, item, fromIndex) {
    fromIndex = fromIndex || 0;
    if (arr == null) {
        return -1;
    }

    var len = arr.length,
        i = fromIndex < 0 ? len + fromIndex : fromIndex;
    while (i < len) {
        // we iterate over sparse items since there is no way to make it
        // work properly on IE 7-8. see #64
        if (arr[i] === item) {
            return i;
        }

        i++;
    }

    return -1;
}
```
- example usage
```shell
...
var queryArr = (queryStr || '').replace('?', '').split('&'),
    reg = /([^=]+)=(.+)/,
    i = -1,
    obj = {},
    equalIndex, cur, pValue, pName;

while ((cur = queryArr[++i])) {
    equalIndex = cur.indexOf('=');
    pName = cur.substring(0, equalIndex);
    pValue = decodeURIComponent(cur.substring(equalIndex + 1));
    if (shouldTypecast !== false) {
        pValue = typecast(pValue);
    }
    if (hasOwn(obj, pName)){
        if(isArray(obj[pName])){
...
```

#### <a name="apidoc.element.mout.array.indicesOf"></a>[function <span class="apidocSignatureSpan">mout.array.</span>indicesOf (arr, item, fromIndex)](#apidoc.element.mout.array.indicesOf)
- description and source-code
```javascript
function indicesOf(arr, item, fromIndex) {
    var results = [];
    if (arr == null) {
        return results;
    }

    fromIndex = typeof fromIndex === 'number' ? fromIndex : 0;

    var length = arr.length;
    var cursor = fromIndex >= 0 ? fromIndex : length + fromIndex;

    while (cursor < length) {
        if (arr[cursor] === item) {
            results.push(cursor);
        }
        cursor++;
    }

    return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.insert"></a>[function <span class="apidocSignatureSpan">mout.array.</span>insert (arr, rest_items)](#apidoc.element.mout.array.insert)
- description and source-code
```javascript
function insert(arr, rest_items) {
    var diff = difference(slice(arguments, 1), arr);
    if (diff.length) {
        Array.prototype.push.apply(arr, diff);
    }
    return arr.length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.intersection"></a>[function <span class="apidocSignatureSpan">mout.array.</span>intersection (arr)](#apidoc.element.mout.array.intersection)
- description and source-code
```javascript
function intersection(arr) {
    var arrs = slice(arguments, 1),
        result = filter(unique(arr), function(needle){
            return every(arrs, function(haystack){
                return contains(haystack, needle);
            });
        });
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.invoke"></a>[function <span class="apidocSignatureSpan">mout.array.</span>invoke (arr, methodName, var_args)](#apidoc.element.mout.array.invoke)
- description and source-code
```javascript
function invoke(arr, methodName, var_args){
    if (arr == null) {
        return arr;
    }

    var args = slice(arguments, 2);
    var i = -1, len = arr.length, value;
    while (++i < len) {
        value = arr[i];
        value[methodName].apply(value, args);
    }

    return arr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.join"></a>[function <span class="apidocSignatureSpan">mout.array.</span>join (items, separator)](#apidoc.element.mout.array.join)
- description and source-code
```javascript
function join(items, separator) {
    separator = separator || '';
    return filter(items, isValidString).join(separator);
}
```
- example usage
```shell
...

/**
 * Joins strings with the specified separator inserted between each value.
 * Null values and empty strings will be excluded.
 */
function join(items, separator) {
    separator = separator || '';
    return filter(items, isValidString).join(separator);
}

module.exports = join;
...
```

#### <a name="apidoc.element.mout.array.last"></a>[function <span class="apidocSignatureSpan">mout.array.</span>last (arr)](#apidoc.element.mout.array.last)
- description and source-code
```javascript
function last(arr){
    if (arr == null || arr.length < 1) {
        return undefined;
    }

    return arr[arr.length - 1];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.lastIndexOf"></a>[function <span class="apidocSignatureSpan">mout.array.</span>lastIndexOf (arr, item, fromIndex)](#apidoc.element.mout.array.lastIndexOf)
- description and source-code
```javascript
function lastIndexOf(arr, item, fromIndex) {
    if (arr == null) {
        return -1;
    }

    var len = arr.length;
    fromIndex = (fromIndex == null || fromIndex >= len)? len - 1 : fromIndex;
    fromIndex = (fromIndex < 0)? len + fromIndex : fromIndex;

    while (fromIndex >= 0) {
        // we iterate over sparse items since there is no way to make it
        // work properly on IE 7-8. see #64
        if (arr[fromIndex] === item) {
            return fromIndex;
        }
        fromIndex--;
    }

    return -1;
}
```
- example usage
```shell
...

    str = trim(str);
    if(str.length <= maxChars){
        return str;
    }
    str = str.substr(0, maxChars - append.length);
    //crop at last space or remove trailing whitespace
    str = onlyFullWords? str.substr(0, str.lastIndexOf(' ')) : trim(str);
    return str + append;
}
module.exports = truncate;
...
```

#### <a name="apidoc.element.mout.array.map"></a>[function <span class="apidocSignatureSpan">mout.array.</span>map (arr, callback, thisObj)](#apidoc.element.mout.array.map)
- description and source-code
```javascript
function map(arr, callback, thisObj) {
    callback = makeIterator(callback, thisObj);
    var results = [];
    if (arr == null){
        return results;
    }

    var i = -1, len = arr.length;
    while (++i < len) {
        results[i] = callback(arr[i], i, arr);
    }

    return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.max"></a>[function <span class="apidocSignatureSpan">mout.array.</span>max (arr, iterator, thisObj)](#apidoc.element.mout.array.max)
- description and source-code
```javascript
function max(arr, iterator, thisObj){
    if (arr == null || !arr.length) {
        return Infinity;
    } else if (arr.length && !iterator) {
        return Math.max.apply(Math, arr);
    } else {
        iterator = makeIterator(iterator, thisObj);
        var result,
            compare = -Infinity,
            value,
            temp;

        var i = -1, len = arr.length;
        while (++i < len) {
            value = arr[i];
            temp = iterator(value, i, arr);
            if (temp > compare) {
                compare = temp;
                result = value;
            }
        }

        return result;
    }
}
```
- example usage
```shell
...
     */
    function slice(arr, start, end){
var len = arr.length;

if (start == null) {
    start = 0;
} else if (start < 0) {
    start = Math.max(len + start, 0);
} else {
    start = Math.min(start, len);
}

if (end == null) {
    end = len;
} else if (end < 0) {
...
```

#### <a name="apidoc.element.mout.array.min"></a>[function <span class="apidocSignatureSpan">mout.array.</span>min (arr, iterator, thisObj)](#apidoc.element.mout.array.min)
- description and source-code
```javascript
function min(arr, iterator, thisObj){
    if (arr == null || !arr.length) {
        return -Infinity;
    } else if (arr.length && !iterator) {
        return Math.min.apply(Math, arr);
    } else {
        iterator = makeIterator(iterator, thisObj);
        var result,
            compare = Infinity,
            value,
            temp;

        var i = -1, len = arr.length;
        while (++i < len) {
            value = arr[i];
            temp = iterator(value, i, arr);
            if (temp < compare) {
                compare = temp;
                result = value;
            }
        }

        return result;
    }
}
```
- example usage
```shell
...
var len = arr.length;

if (start == null) {
    start = 0;
} else if (start < 0) {
    start = Math.max(len + start, 0);
} else {
    start = Math.min(start, len);
}

if (end == null) {
    end = len;
} else if (end < 0) {
    end = Math.max(len + end, 0);
} else {
...
```

#### <a name="apidoc.element.mout.array.pick"></a>[function <span class="apidocSignatureSpan">mout.array.</span>pick (arr, nItems)](#apidoc.element.mout.array.pick)
- description and source-code
```javascript
function pick(arr, nItems){
    if (nItems != null) {
        var result = [];
        if (nItems > 0 && arr && arr.length) {
            nItems = nItems > arr.length? arr.length : nItems;
            while (nItems--) {
                result.push( pickOne(arr) );
            }
        }
        return result;
    }
    return (arr && arr.length)? pickOne(arr) : void(0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.pluck"></a>[function <span class="apidocSignatureSpan">mout.array.</span>pluck (arr, propName)](#apidoc.element.mout.array.pluck)
- description and source-code
```javascript
function pluck(arr, propName){
    return map(arr, propName);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.range"></a>[function <span class="apidocSignatureSpan">mout.array.</span>range (start, stop, step)](#apidoc.element.mout.array.range)
- description and source-code
```javascript
function range(start, stop, step) {
    if (stop == null) {
        stop = start;
        start = 0;
    }
    step = step || 1;

    var result = [],
        nSteps = countSteps(stop - start, step),
        i = start;

    while (i <= stop) {
        result.push(i);
        i += step;
    }

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.reduce"></a>[function <span class="apidocSignatureSpan">mout.array.</span>reduce (arr, fn, initVal)](#apidoc.element.mout.array.reduce)
- description and source-code
```javascript
function reduce(arr, fn, initVal) {
    // check for args.length since initVal might be "undefined" see #gh-57
    var hasInit = arguments.length > 2,
        result = initVal;

    if (arr == null || !arr.length) {
        if (!hasInit) {
            throw new Error('reduce of empty array with no initial value');
        } else {
            return initVal;
        }
    }

    var i = -1, len = arr.length;
    while (++i < len) {
        if (!hasInit) {
            result = arr[i];
            hasInit = true;
        } else {
            result = fn(result, arr[i], i, arr);
        }
    }

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.reduceRight"></a>[function <span class="apidocSignatureSpan">mout.array.</span>reduceRight (arr, fn, initVal)](#apidoc.element.mout.array.reduceRight)
- description and source-code
```javascript
function reduceRight(arr, fn, initVal) {
    // check for args.length since initVal might be "undefined" see #gh-57
    var hasInit = arguments.length > 2;

    if (arr == null || !arr.length) {
        if (hasInit) {
            return initVal;
        } else {
            throw new Error('reduce of empty array with no initial value');
        }
    }

    var i = arr.length, result = initVal, value;
    while (--i >= 0) {
        // we iterate over sparse items since there is no way to make it
        // work properly on IE 7-8. see #64
        value = arr[i];
        if (!hasInit) {
            result = value;
            hasInit = true;
        } else {
            result = fn(result, value, i, arr);
        }
    }
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.reject"></a>[function <span class="apidocSignatureSpan">mout.array.</span>reject (arr, callback, thisObj)](#apidoc.element.mout.array.reject)
- description and source-code
```javascript
function reject(arr, callback, thisObj) {
    callback = makeIterator(callback, thisObj);
    var results = [];
    if (arr == null) {
        return results;
    }

    var i = -1, len = arr.length, value;
    while (++i < len) {
        value = arr[i];
        if (!callback(value, i, arr)) {
            results.push(value);
        }
    }

    return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.remove"></a>[function <span class="apidocSignatureSpan">mout.array.</span>remove (arr, item)](#apidoc.element.mout.array.remove)
- description and source-code
```javascript
function remove(arr, item){
    var idx = indexOf(arr, item);
    if (idx !== -1) arr.splice(idx, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.removeAll"></a>[function <span class="apidocSignatureSpan">mout.array.</span>removeAll (arr, item)](#apidoc.element.mout.array.removeAll)
- description and source-code
```javascript
function removeAll(arr, item){
    var idx = indexOf(arr, item);
    while (idx !== -1) {
        arr.splice(idx, 1);
        idx = indexOf(arr, item, idx);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.reverse"></a>[function <span class="apidocSignatureSpan">mout.array.</span>reverse (array)](#apidoc.element.mout.array.reverse)
- description and source-code
```javascript
function reverse(array) {
    var copy = array.slice();
    copy.reverse();
    return copy;
}
```
- example usage
```shell
...


/**
 * Returns a copy of the array in reversed order.
 */
function reverse(array) {
    var copy = array.slice();
    copy.reverse();
    return copy;
}

module.exports = reverse;
...
```

#### <a name="apidoc.element.mout.array.shuffle"></a>[function <span class="apidocSignatureSpan">mout.array.</span>shuffle (arr)](#apidoc.element.mout.array.shuffle)
- description and source-code
```javascript
function shuffle(arr) {
    var results = [],
        rnd;
    if (arr == null) {
        return results;
    }

    var i = -1, len = arr.length;
    while (++i < len) {
        if (!i) {
            results[0] = arr[0];
        } else {
            rnd = randInt(0, i);
            results[i] = results[rnd];
            results[rnd] = arr[i];
        }
    }

    return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.slice"></a>[function <span class="apidocSignatureSpan">mout.array.</span>slice (arr, start, end)](#apidoc.element.mout.array.slice)
- description and source-code
```javascript
function slice(arr, start, end){
    var len = arr.length;

    if (start == null) {
        start = 0;
    } else if (start < 0) {
        start = Math.max(len + start, 0);
    } else {
        start = Math.min(start, len);
    }

    if (end == null) {
        end = len;
    } else if (end < 0) {
        end = Math.max(len + end, 0);
    } else {
        end = Math.min(end, len);
    }

    var result = [];
    while (start < end) {
        result.push(arr[start++]);
    }

    return result;
}
```
- example usage
```shell
...



/**
 * Returns a copy of the array in reversed order.
 */
function reverse(array) {
    var copy = array.slice();
    copy.reverse();
    return copy;
}

module.exports = reverse;
...
```

#### <a name="apidoc.element.mout.array.some"></a>[function <span class="apidocSignatureSpan">mout.array.</span>some (arr, callback, thisObj)](#apidoc.element.mout.array.some)
- description and source-code
```javascript
function some(arr, callback, thisObj) {
    callback = makeIterator(callback, thisObj);
    var result = false;
    if (arr == null) {
        return result;
    }

    var i = -1, len = arr.length;
    while (++i < len) {
        // we iterate over sparse items since there is no way to make it
        // work properly on IE 7-8. see #64
        if ( callback(arr[i], i, arr) ) {
            result = true;
            break;
        }
    }

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.sort"></a>[function <span class="apidocSignatureSpan">mout.array.</span>sort (arr, compareFn)](#apidoc.element.mout.array.sort)
- description and source-code
```javascript
function mergeSort(arr, compareFn) {
    if (arr == null) {
        return [];
    } else if (arr.length < 2) {
        return arr;
    }

    if (compareFn == null) {
        compareFn = defaultCompare;
    }

    var mid, left, right;

    mid   = ~~(arr.length / 2);
    left  = mergeSort( arr.slice(0, mid), compareFn );
    right = mergeSort( arr.slice(mid, arr.length), compareFn );

    return merge(left, right, compareFn);
}
```
- example usage
```shell
...
function functions(obj){
    var keys = [];
    forIn(obj, function(val, key){
        if (typeof val === 'function'){
            keys.push(key);
        }
    });
    return keys.sort();
}

module.exports = functions;
...
```

#### <a name="apidoc.element.mout.array.sortBy"></a>[function <span class="apidocSignatureSpan">mout.array.</span>sortBy (arr, callback, context)](#apidoc.element.mout.array.sortBy)
- description and source-code
```javascript
function sortBy(arr, callback, context){
    callback = makeIterator(callback, context);

    return sort(arr, function(a, b) {
        a = callback(a);
        b = callback(b);
        return (a < b) ? -1 : ((a > b) ? 1 : 0);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.split"></a>[function <span class="apidocSignatureSpan">mout.array.</span>split (array, segments)](#apidoc.element.mout.array.split)
- description and source-code
```javascript
function split(array, segments) {
    segments = segments || 2;
    var results = [];
    if (array == null) {
        return results;
    }

    var minLength = Math.floor(array.length / segments),
        remainder = array.length % segments,
        i = 0,
        len = array.length,
        segmentIndex = 0,
        segmentLength;

    while (i < len) {
        segmentLength = minLength;
        if (segmentIndex < remainder) {
            segmentLength++;
        }

        results.push(array.slice(i, i + segmentLength));

        segmentIndex++;
        i += segmentLength;
    }

    return results;
}
```
- example usage
```shell
...

var isPrimitive = require('../lang/isPrimitive');

    /**
     * get "nested" object property
     */
    function get(obj, prop){
var parts = prop.split('.'),
    last = parts.pop();

while (prop = parts.shift()) {
    obj = obj[prop];
    if (obj == null) return;
}
...
```

#### <a name="apidoc.element.mout.array.take"></a>[function <span class="apidocSignatureSpan">mout.array.</span>take (n, callback, thisObj)](#apidoc.element.mout.array.take)
- description and source-code
```javascript
function take(n, callback, thisObj){
    var i = -1;
    var arr = [];
    if( !thisObj ){
        while(++i < n){
            arr[i] = callback(i, n);
        }
    } else {
        while(++i < n){
            arr[i] = callback.call(thisObj, i, n);
        }
    }
    return arr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.toLookup"></a>[function <span class="apidocSignatureSpan">mout.array.</span>toLookup (arr, key)](#apidoc.element.mout.array.toLookup)
- description and source-code
```javascript
function toLookup(arr, key) {
    var result = {};
    if (arr == null) {
        return result;
    }

    var i = -1, len = arr.length, value;
    if (isFunction(key)) {
        while (++i < len) {
            value = arr[i];
            result[key(value)] = value;
        }
    } else {
        while (++i < len) {
            value = arr[i];
            result[value[key]] = value;
        }
    }

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.union"></a>[function <span class="apidocSignatureSpan">mout.array.</span>union (arrs)](#apidoc.element.mout.array.union)
- description and source-code
```javascript
function union(arrs) {
    var results = [];
    var i = -1, len = arguments.length;
    while (++i < len) {
        append(results, arguments[i]);
    }

    return unique(results);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.unique"></a>[function <span class="apidocSignatureSpan">mout.array.</span>unique (arr, compare)](#apidoc.element.mout.array.unique)
- description and source-code
```javascript
function unique(arr, compare){
    compare = compare || isEqual;
    return filter(arr, function(item, i, arr){
        var n = arr.length;
        while (++i < n) {
            if ( compare(item, arr[i]) ) {
                return false;
            }
        }
        return true;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.xor"></a>[function <span class="apidocSignatureSpan">mout.array.</span>xor (arr1, arr2)](#apidoc.element.mout.array.xor)
- description and source-code
```javascript
function xor(arr1, arr2) {
    arr1 = unique(arr1);
    arr2 = unique(arr2);

    var a1 = filter(arr1, function(item){
            return !contains(arr2, item);
        }),
        a2 = filter(arr2, function(item){
            return !contains(arr1, item);
        });

    return a1.concat(a2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.array.zip"></a>[function <span class="apidocSignatureSpan">mout.array.</span>zip (arr)](#apidoc.element.mout.array.zip)
- description and source-code
```javascript
function zip(arr){
    var len = arr ? max(map(arguments, getLength)) : 0,
        results = [],
        i = -1;
    while (++i < len) {
        // jshint loopfunc: true
        results.push(map(arguments, function(item) {
            return item == null ? undefined : item[i];
        }));
    }

    return results;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.collection"></a>[module mout.collection](#apidoc.module.mout.collection)

#### <a name="apidoc.element.mout.collection.contains"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>contains ()](#apidoc.element.mout.collection.contains)
- description and source-code
```javascript
contains = function (){
    var args = slice(arguments);
    if (args[0] == null) {
        return defaultReturn;
    }
    // array-like is treated as array
    return (typeof args[0].length === 'number')? arrMethod.apply(null, args) : objMethod.apply(null, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.collection.every"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>every ()](#apidoc.element.mout.collection.every)
- description and source-code
```javascript
every = function (){
    var args = slice(arguments);
    if (args[0] == null) {
        return defaultReturn;
    }
    // array-like is treated as array
    return (typeof args[0].length === 'number')? arrMethod.apply(null, args) : objMethod.apply(null, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.collection.filter"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>filter (list, iterator, thisObj)](#apidoc.element.mout.collection.filter)
- description and source-code
```javascript
function filter(list, iterator, thisObj) {
    iterator = makeIterator(iterator, thisObj);
    var results = [];
    if (!list) {
        return results;
    }
    forEach(list, function(value, index, list) {
        if (iterator(value, index, list)) {
            results[results.length] = value;
        }
    });
    return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.collection.find"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>find ()](#apidoc.element.mout.collection.find)
- description and source-code
```javascript
find = function (){
    var args = slice(arguments);
    if (args[0] == null) {
        return defaultReturn;
    }
    // array-like is treated as array
    return (typeof args[0].length === 'number')? arrMethod.apply(null, args) : objMethod.apply(null, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.collection.forEach"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>forEach ()](#apidoc.element.mout.collection.forEach)
- description and source-code
```javascript
forEach = function (){
    var args = slice(arguments);
    if (args[0] == null) {
        return defaultReturn;
    }
    // array-like is treated as array
    return (typeof args[0].length === 'number')? arrMethod.apply(null, args) : objMethod.apply(null, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.collection.make_"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>make_ (arrMethod, objMethod, defaultReturn)](#apidoc.element.mout.collection.make_)
- description and source-code
```javascript
function makeCollectionMethod(arrMethod, objMethod, defaultReturn) {
    return function(){
        var args = slice(arguments);
        if (args[0] == null) {
            return defaultReturn;
        }
        // array-like is treated as array
        return (typeof args[0].length === 'number')? arrMethod.apply(null, args) : objMethod.apply(null, args);
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.collection.map"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>map (list, callback, thisObj)](#apidoc.element.mout.collection.map)
- description and source-code
```javascript
function map(list, callback, thisObj) {
    callback = makeIterator(callback, thisObj);
    // list.length to check array-like object, if not array-like
    // we simply map all the object values
    if( isObject(list) && list.length == null ){
        list = values(list);
    }
    return arrMap(list, function (val, key, list) {
        return callback(val, key, list);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.collection.max"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>max ()](#apidoc.element.mout.collection.max)
- description and source-code
```javascript
max = function (){
    var args = slice(arguments);
    if (args[0] == null) {
        return defaultReturn;
    }
    // array-like is treated as array
    return (typeof args[0].length === 'number')? arrMethod.apply(null, args) : objMethod.apply(null, args);
}
```
- example usage
```shell
...
     */
    function slice(arr, start, end){
var len = arr.length;

if (start == null) {
    start = 0;
} else if (start < 0) {
    start = Math.max(len + start, 0);
} else {
    start = Math.min(start, len);
}

if (end == null) {
    end = len;
} else if (end < 0) {
...
```

#### <a name="apidoc.element.mout.collection.min"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>min ()](#apidoc.element.mout.collection.min)
- description and source-code
```javascript
min = function (){
    var args = slice(arguments);
    if (args[0] == null) {
        return defaultReturn;
    }
    // array-like is treated as array
    return (typeof args[0].length === 'number')? arrMethod.apply(null, args) : objMethod.apply(null, args);
}
```
- example usage
```shell
...
var len = arr.length;

if (start == null) {
    start = 0;
} else if (start < 0) {
    start = Math.max(len + start, 0);
} else {
    start = Math.min(start, len);
}

if (end == null) {
    end = len;
} else if (end < 0) {
    end = Math.max(len + end, 0);
} else {
...
```

#### <a name="apidoc.element.mout.collection.pluck"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>pluck (list, key)](#apidoc.element.mout.collection.pluck)
- description and source-code
```javascript
function pluck(list, key) {
    return map(list, function(value) {
        return value[key];
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.collection.reduce"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>reduce ()](#apidoc.element.mout.collection.reduce)
- description and source-code
```javascript
reduce = function (){
    var args = slice(arguments);
    if (args[0] == null) {
        return defaultReturn;
    }
    // array-like is treated as array
    return (typeof args[0].length === 'number')? arrMethod.apply(null, args) : objMethod.apply(null, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.collection.reject"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>reject (list, iterator, thisObj)](#apidoc.element.mout.collection.reject)
- description and source-code
```javascript
function reject(list, iterator, thisObj) {
    iterator = makeIterator(iterator, thisObj);
    return filter(list, function(value, index, list) {
        return !iterator(value, index, list);
    }, thisObj);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.collection.size"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>size (list)](#apidoc.element.mout.collection.size)
- description and source-code
```javascript
function size(list) {
    if (!list) {
        return 0;
    }
    if (isArray(list)) {
        return list.length;
    }
    return objSize(list);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.collection.some"></a>[function <span class="apidocSignatureSpan">mout.collection.</span>some ()](#apidoc.element.mout.collection.some)
- description and source-code
```javascript
some = function (){
    var args = slice(arguments);
    if (args[0] == null) {
        return defaultReturn;
    }
    // array-like is treated as array
    return (typeof args[0].length === 'number')? arrMethod.apply(null, args) : objMethod.apply(null, args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.date"></a>[module mout.date](#apidoc.module.mout.date)

#### <a name="apidoc.element.mout.date.dayOfTheYear"></a>[function <span class="apidocSignatureSpan">mout.date.</span>dayOfTheYear (date)](#apidoc.element.mout.date.dayOfTheYear)
- description and source-code
```javascript
function dayOfTheYear(date){
    return (Date.UTC(date.getFullYear(), date.getMonth(), date.getDate()) -
            Date.UTC(date.getFullYear(), 0, 1)) / 86400000 + 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.date.diff"></a>[function <span class="apidocSignatureSpan">mout.date.</span>diff (start, end, unitName)](#apidoc.element.mout.date.diff)
- description and source-code
```javascript
function diff(start, end, unitName){
    // sort the dates to make it easier to process (specially year/month)
    if (start > end) {
        var swap = start;
        start = end;
        end = swap;
    }

    var output;

    if (unitName === 'month') {
        output = getMonthsDiff(start, end);
    } else if (unitName === 'year'){
        output = getYearsDiff(start, end);
    } else if (unitName != null) {
        if (unitName === 'day') {
            // ignore timezone difference because of daylight savings time
            start = toUtc(start);
            end = toUtc(end);
        }
        output = convert(end - start, 'ms', unitName);
    } else {
        output = end - start;
    }

    return output;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.date.isLeapYear"></a>[function <span class="apidocSignatureSpan">mout.date.</span>isLeapYear (fullYear)](#apidoc.element.mout.date.isLeapYear)
- description and source-code
```javascript
function isLeapYear(fullYear){
    if (isDate(fullYear)) {
        fullYear = fullYear.getFullYear();
    }
    return fullYear % 400 === 0 || (fullYear % 100 !== 0 && fullYear % 4 === 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.date.isSame"></a>[function <span class="apidocSignatureSpan">mout.date.</span>isSame (date1, date2, period)](#apidoc.element.mout.date.isSame)
- description and source-code
```javascript
function isSame(date1, date2, period){
    if (period) {
        date1 = startOf(date1, period);
        date2 = startOf(date2, period);
    }
    return Number(date1) === Number(date2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.date.parseIso"></a>[function <span class="apidocSignatureSpan">mout.date.</span>parseIso (str)](#apidoc.element.mout.date.parseIso)
- description and source-code
```javascript
function parseISO8601(str){
    var match = DATE_TIME.exec(str);
    if (!match) {
        // No time specified
        return parseDate(str);
    }

    return parseDate(match[1]) + parseTime(match[2]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.date.quarter"></a>[function <span class="apidocSignatureSpan">mout.date.</span>quarter (date)](#apidoc.element.mout.date.quarter)
- description and source-code
```javascript
function quarter(date){
    var month = date.getMonth();
    if (month < 3) return 1;
    if (month < 6) return 2;
    if (month < 9) return 3;
    return 4;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.date.startOf"></a>[function <span class="apidocSignatureSpan">mout.date.</span>startOf (date, period)](#apidoc.element.mout.date.startOf)
- description and source-code
```javascript
function startOf(date, period){
    date = clone(date);

    // intentionally removed "break" from switch since start of
    // month/year/etc should also reset the following periods
    switch (period) {
        case 'year':
            date.setMonth(0);
<span class="apidocCodeCommentSpan">        /* falls through */
</span>        case 'month':
            date.setDate(1);
        /* falls through */
        case 'week':
        case 'day':
            date.setHours(0);
        /* falls through */
        case 'hour':
            date.setMinutes(0);
        /* falls through */
        case 'minute':
            date.setSeconds(0);
        /* falls through */
        case 'second':
            date.setMilliseconds(0);
            break;
        default:
            throw new Error('"'+ period +'" is not a valid period');
    }

    // week is the only case that should reset the weekDay and maybe even
    // overflow to previous month
    if (period === 'week') {
        var weekDay = date.getDay();
        var baseDate = date.getDate();
        if (weekDay) {
            if (weekDay >= baseDate) {
                //start of the week is on previous month
                date.setDate(0);
            }
            date.setDate(date.getDate() - date.getDay());
        }
    }

    return date;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.date.strftime"></a>[function <span class="apidocSignatureSpan">mout.date.</span>strftime (date, format, localeData)](#apidoc.element.mout.date.strftime)
- description and source-code
```javascript
function strftime(date, format, localeData){
    localeData = localeData  || i18n;
    var reToken = /%([a-z%])/gi;

    function makeIterator(fn) {
        return function(match, token){
            return fn(date, token, localeData);
        };
    }

    return format
        .replace(reToken, makeIterator(expandCombinations))
        .replace(reToken, makeIterator(convertToken));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.date.timezoneAbbr"></a>[function <span class="apidocSignatureSpan">mout.date.</span>timezoneAbbr (date)](#apidoc.element.mout.date.timezoneAbbr)
- description and source-code
```javascript
function timezoneAbbr(date){
    // Date.toString gives different results depending on the
    // browser/system so we fallback to timezone offset
    // chrome: 'Mon Apr 08 2013 09:02:04 GMT-0300 (BRT)'
    // IE: 'Mon Apr 8 09:02:04 UTC-0300 2013'
    var tz = /\(([A-Z]{3,4})\)/.exec(date.toString());
    return tz? tz[1] : timezoneOffset(date);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.date.timezoneOffset"></a>[function <span class="apidocSignatureSpan">mout.date.</span>timezoneOffset (date)](#apidoc.element.mout.date.timezoneOffset)
- description and source-code
```javascript
function timezoneOffset(date){
    var offset = date.getTimezoneOffset();
    var abs = Math.abs(offset);
    var h = pad(Math.floor(abs / 60), 2);
    var m = pad(abs % 60, 2);
    return (offset > 0? '-' : '+') + h + m;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.date.totalDaysInMonth"></a>[function <span class="apidocSignatureSpan">mout.date.</span>totalDaysInMonth (fullYear, monthIndex)](#apidoc.element.mout.date.totalDaysInMonth)
- description and source-code
```javascript
function totalDaysInMonth(fullYear, monthIndex){
    if (isDate(fullYear)) {
        monthIndex = fullYear.getMonth();
    }

    if (monthIndex === 1 && isLeapYear(fullYear)) {
        return 29;
    } else {
        return DAYS_IN_MONTH[monthIndex];
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.date.totalDaysInYear"></a>[function <span class="apidocSignatureSpan">mout.date.</span>totalDaysInYear (fullYear)](#apidoc.element.mout.date.totalDaysInYear)
- description and source-code
```javascript
function totalDaysInYear(fullYear){
    return isLeapYear(fullYear)? 366 : 365;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.date.weekOfTheYear"></a>[function <span class="apidocSignatureSpan">mout.date.</span>weekOfTheYear (date, firstDayOfWeek)](#apidoc.element.mout.date.weekOfTheYear)
- description and source-code
```javascript
function weekOfTheYear(date, firstDayOfWeek){
    firstDayOfWeek = firstDayOfWeek == null? 0 : firstDayOfWeek;
    var doy = dayOfTheYear(date);
    var dow = (7 + date.getDay() - firstDayOfWeek) % 7;
    var relativeWeekDay = 6 - firstDayOfWeek - dow;
    return Math.floor((doy + relativeWeekDay) / 7);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.date.i18n_"></a>[module mout.date.i18n_](#apidoc.module.mout.date.i18n_)

#### <a name="apidoc.element.mout.date.i18n_.set"></a>[function <span class="apidocSignatureSpan">mout.date.i18n_.</span>set (localeData)](#apidoc.element.mout.date.i18n_.set)
- description and source-code
```javascript
set = function (localeData){
    mixIn(activeLocale, localeData);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.function"></a>[module mout.function](#apidoc.module.mout.function)

#### <a name="apidoc.element.mout.function.after"></a>[function <span class="apidocSignatureSpan">mout.function.</span>after (closure, times)](#apidoc.element.mout.function.after)
- description and source-code
```javascript
function after(closure, times){
    return function () {
        if (--times <= 0) closure();
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.awaitDelay"></a>[function <span class="apidocSignatureSpan">mout.function.</span>awaitDelay ( callback, delay )](#apidoc.element.mout.function.awaitDelay)
- description and source-code
```javascript
function awaitDelay( callback, delay ){
    var baseTime = now() + delay;
    return function() {
        // ensure all browsers will execute it asynchronously (avoid hard
        // to catch errors) not using "0" because of old browsers and also
        // since new browsers increase the value to be at least "4"
        // http://www.whatwg.org/specs/web-apps/current-work/multipage/timers.html#dom-windowtimers-settimeout
        var ms = Math.max(baseTime - now(), 4);
        return timeout.apply(this, append([callback, ms, this], arguments));
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.bind"></a>[function <span class="apidocSignatureSpan">mout.function.</span>bind (fn, context, args)](#apidoc.element.mout.function.bind)
- description and source-code
```javascript
function bind(fn, context, args){
    var argsArr = slice(arguments, 2); //curried args
    return function(){
        return fn.apply(context, argsArr.concat(slice(arguments)));
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.compose"></a>[function <span class="apidocSignatureSpan">mout.function.</span>compose ()](#apidoc.element.mout.function.compose)
- description and source-code
```javascript
function compose() {
   var fns = arguments;
   return function(arg){
       // only cares about the first argument since the chain can only
       // deal with a single return value anyway. It should start from
       // the last fn.
       var n = fns.length;
       while (n--) {
           arg = fns[n].call(this, arg);
       }
       return arg;
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.constant"></a>[function <span class="apidocSignatureSpan">mout.function.</span>constant (value)](#apidoc.element.mout.function.constant)
- description and source-code
```javascript
function constant(value){
    return function() {
        return value;
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.debounce"></a>[function <span class="apidocSignatureSpan">mout.function.</span>debounce (fn, threshold, isAsap)](#apidoc.element.mout.function.debounce)
- description and source-code
```javascript
function debounce(fn, threshold, isAsap){
    var timeout, result;
    function debounced(){
        var args = arguments, context = this;
        function delayed(){
            if (! isAsap) {
                result = fn.apply(context, args);
            }
            timeout = null;
        }
        if (timeout) {
            clearTimeout(timeout);
        } else if (isAsap) {
            result = fn.apply(context, args);
        }
        timeout = setTimeout(delayed, threshold);
        return result;
    }
    debounced.cancel = function(){
        clearTimeout(timeout);
    };
    return debounced;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.func"></a>[function <span class="apidocSignatureSpan">mout.function.</span>func (name)](#apidoc.element.mout.function.func)
- description and source-code
```javascript
function func(name){
    return function(obj){
        return obj[name]();
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.identity"></a>[function <span class="apidocSignatureSpan">mout.function.</span>identity (val)](#apidoc.element.mout.function.identity)
- description and source-code
```javascript
function identity(val){
    return val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.makeIterator_"></a>[function <span class="apidocSignatureSpan">mout.function.</span>makeIterator_ (src, thisObj)](#apidoc.element.mout.function.makeIterator_)
- description and source-code
```javascript
function makeIterator(src, thisObj){
    if (src == null) {
        return identity;
    }
    switch(typeof src) {
        case 'function':
            // function is the first to improve perf (most common case)
            // also avoid using 'Function#call' if not needed, which boosts
            // perf a lot in some cases
            return (typeof thisObj !== 'undefined')? function(val, i, arr){
                return src.call(thisObj, val, i, arr);
            } : src;
        case 'object':
            return function(val){
                return deepMatches(val, src);
            };
        case 'string':
        case 'number':
            return prop(src);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.memoize"></a>[function <span class="apidocSignatureSpan">mout.function.</span>memoize (fn, resolver)](#apidoc.element.mout.function.memoize)
- description and source-code
```javascript
function memoize(fn, resolver) {
    if (!isFunction(fn) || (resolver && !isFunction(resolver))) {
        throw new TypeError('Expected a function');
    }

    var memoized = function() {
        var cache = memoized.cache,
            key = resolver ? resolver.apply(this, arguments) : arguments[0];

        if (hasOwn(cache, key)) {
            return cache[key];
        }
        var result = fn.apply(this, arguments);
        cache[key] = result;
        return result;
    };

    memoized.cache = {};

    return memoized;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.partial"></a>[function <span class="apidocSignatureSpan">mout.function.</span>partial (f)](#apidoc.element.mout.function.partial)
- description and source-code
```javascript
function partial(f) {
    var as = slice(arguments, 1);
    var has_ = indexOf(as, _) !== -1;

    return function() {
        var rest = slice(arguments);

        // Don't waste time checking for placeholders if there aren't any.
        var args = has_ ? take(as.length, function(i) {
            var a = as[i];
            return a === _ ? rest.shift() : a;
        }) : as;

        return f.apply(this, rest.length ? args.concat(rest) : args);
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.prop"></a>[function <span class="apidocSignatureSpan">mout.function.</span>prop (name)](#apidoc.element.mout.function.prop)
- description and source-code
```javascript
function prop(name){
    return function(obj){
        return obj[name];
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.series"></a>[function <span class="apidocSignatureSpan">mout.function.</span>series ()](#apidoc.element.mout.function.series)
- description and source-code
```javascript
function series(){
    var fns = arguments;
    return function(){
        var i = 0,
            n = fns.length;
        while (i < n) {
            fns[i].apply(this, arguments);
            i += 1;
        }
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.throttle"></a>[function <span class="apidocSignatureSpan">mout.function.</span>throttle (fn, delay)](#apidoc.element.mout.function.throttle)
- description and source-code
```javascript
function throttle(fn, delay){
    var context, timeout, result, args,
        diff, prevCall = 0;
    function delayed(){
        prevCall = now();
        timeout = null;
        result = fn.apply(context, args);
    }
    function throttled(){
        context = this;
        args = arguments;
        diff = delay - (now() - prevCall);
        if (diff <= 0) {
            clearTimeout(timeout);
            delayed();
        } else if (! timeout) {
            timeout = setTimeout(delayed, diff);
        }
        return result;
    }
    throttled.cancel = function(){
        clearTimeout(timeout);
    };
    return throttled;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.timeout"></a>[function <span class="apidocSignatureSpan">mout.function.</span>timeout (fn, millis, context)](#apidoc.element.mout.function.timeout)
- description and source-code
```javascript
function timeout(fn, millis, context){

    var args = slice(arguments, 3);

    return setTimeout(function() {
        fn.apply(context, args);
    }, millis);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.times"></a>[function <span class="apidocSignatureSpan">mout.function.</span>times (n, callback, thisObj)](#apidoc.element.mout.function.times)
- description and source-code
```javascript
function times(n, callback, thisObj){
    var i = -1;
    while (++i < n) {
        if ( callback.call(thisObj, i) === false ) {
            break;
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.function.wrap"></a>[function <span class="apidocSignatureSpan">mout.function.</span>wrap (fn, wrapper)](#apidoc.element.mout.function.wrap)
- description and source-code
```javascript
function wrap(fn, wrapper){
    return partial(wrapper, fn);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.lang"></a>[module mout.lang](#apidoc.module.mout.lang)

#### <a name="apidoc.element.mout.lang.clone"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>clone (val)](#apidoc.element.mout.lang.clone)
- description and source-code
```javascript
function clone(val){
    switch (kindOf(val)) {
        case 'Object':
            return cloneObject(val);
        case 'Array':
            return cloneArray(val);
        case 'RegExp':
            return cloneRegExp(val);
        case 'Date':
            return cloneDate(val);
        default:
            return val;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.createObject"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>createObject (parent, props)](#apidoc.element.mout.lang.createObject)
- description and source-code
```javascript
function createObject(parent, props){
    function F(){}
    F.prototype = parent;
    return mixIn(new F(), props);

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.ctorApply"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>ctorApply (ctor, args)](#apidoc.element.mout.lang.ctorApply)
- description and source-code
```javascript
function ctorApply(ctor, args) {
    F.prototype = ctor.prototype;
    var instance = new F();
    ctor.apply(instance, args);
    return instance;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.deepClone"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>deepClone (val, instanceClone)](#apidoc.element.mout.lang.deepClone)
- description and source-code
```javascript
function deepClone(val, instanceClone) {
    switch ( kindOf(val) ) {
        case 'Object':
            return cloneObject(val, instanceClone);
        case 'Array':
            return cloneArray(val, instanceClone);
        default:
            return clone(val);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.deepEquals"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>deepEquals (a, b, callback)](#apidoc.element.mout.lang.deepEquals)
- description and source-code
```javascript
function deepEquals(a, b, callback){
    callback = callback || is;

    var bothObjects = isObject(a) && isObject(b);
    var bothArrays = !bothObjects && isArray(a) && isArray(b);

    if (!bothObjects && !bothArrays) {
        return callback(a, b);
    }

    function compare(a, b){
        return deepEquals(a, b, callback);
    }

    var method = bothObjects ? objEquals : arrEquals;
    return method(a, b, compare);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.defaults"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>defaults (var_args)](#apidoc.element.mout.lang.defaults)
- description and source-code
```javascript
function defaults(var_args){
    return find(toArray(arguments), nonVoid);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.inheritPrototype"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>inheritPrototype (child, parent)](#apidoc.element.mout.lang.inheritPrototype)
- description and source-code
```javascript
function inheritPrototype(child, parent){
    var p = createObject(parent.prototype);
    p.constructor = child;
    child.prototype = p;
    child.super_ = parent;
    return p;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.is"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>is (x, y)](#apidoc.element.mout.lang.is)
- description and source-code
```javascript
function is(x, y){
    // implementation borrowed from harmony:egal spec
    if (x === y) {
      // 0 === -0, but they are not identical
      return x !== 0 || 1 / x === 1 / y;
    }

    // NaN !== NaN, but they are identical.
    // NaNs are the only non-reflexive value, i.e., if x !== x,
    // then x is a NaN.
    // isNaN is broken: it converts its argument to number, so
    // isNaN("foo") => true
    return x !== x && y !== y;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isArguments"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isArguments (val)](#apidoc.element.mout.lang.isArguments)
- description and source-code
```javascript
isArguments = function (val){
    return isKind(val, 'Arguments');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isArray"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isArray ()](#apidoc.element.mout.lang.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isBoolean"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isBoolean (val)](#apidoc.element.mout.lang.isBoolean)
- description and source-code
```javascript
function isBoolean(val) {
    return isKind(val, 'Boolean');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isDate"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isDate (val)](#apidoc.element.mout.lang.isDate)
- description and source-code
```javascript
function isDate(val) {
    return isKind(val, 'Date');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isEmpty"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isEmpty (val)](#apidoc.element.mout.lang.isEmpty)
- description and source-code
```javascript
function isEmpty(val){
    if (val == null) {
        // typeof null == 'object' so we check it first
        return true;
    } else if ( typeof val === 'string' || isArray(val) ) {
        return !val.length;
    } else if ( typeof val === 'object' ) {
        var result = true;
        forOwn(val, function(){
            result = false;
            return false; // break loop
        });
        return result;
    } else {
        return true;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isFinite"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isFinite (val)](#apidoc.element.mout.lang.isFinite)
- description and source-code
```javascript
function isFinite(val){
    var is = false;
    if (typeof val === 'string' && val !== '') {
        is = GLOBAL.isFinite( parseFloat(val) );
    } else if (isNumber(val)){
        // need to use isNumber because of Number constructor
        is = GLOBAL.isFinite( val );
    }
    return is;
}
```
- example usage
```shell
...

/**
 * Check if value is finite
 */
function isFinite(val){
    var is = false;
    if (typeof val === 'string' && val !== '') {
        is = GLOBAL.isFinite( parseFloat(val) );
    } else if (isNumber(val)){
        // need to use isNumber because of Number constructor
        is = GLOBAL.isFinite( val );
    }
    return is;
}
...
```

#### <a name="apidoc.element.mout.lang.isFunction"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isFunction (val)](#apidoc.element.mout.lang.isFunction)
- description and source-code
```javascript
function isFunction(val) {
    return isKind(val, 'Function');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isInteger"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isInteger (val)](#apidoc.element.mout.lang.isInteger)
- description and source-code
```javascript
function isInteger(val){
    return isNumber(val) && (val % 1 === 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isKind"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isKind (val, kind)](#apidoc.element.mout.lang.isKind)
- description and source-code
```javascript
function isKind(val, kind){
    return kindOf(val) === kind;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isNaN"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isNaN (val)](#apidoc.element.mout.lang.isNaN)
- description and source-code
```javascript
function isNaN(val){
    // based on the fact that NaN !== NaN
    // need to check if it's a number to avoid conflicts with host objects
    // also need to coerce ToNumber to avoid edge case 'new Number(NaN)'
    return !isNumber(val) || $isNaN(Number(val));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isNull"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isNull (val)](#apidoc.element.mout.lang.isNull)
- description and source-code
```javascript
function isNull(val){
    return val === null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isNumber"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isNumber (val)](#apidoc.element.mout.lang.isNumber)
- description and source-code
```javascript
function isNumber(val) {
    return isKind(val, 'Number');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isObject"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isObject (val)](#apidoc.element.mout.lang.isObject)
- description and source-code
```javascript
function isObject(val) {
    return isKind(val, 'Object');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isPlainObject"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isPlainObject (value)](#apidoc.element.mout.lang.isPlainObject)
- description and source-code
```javascript
function isPlainObject(value) {
    return (!!value && typeof value === 'object' &&
        value.constructor === Object);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isPrimitive"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isPrimitive (value)](#apidoc.element.mout.lang.isPrimitive)
- description and source-code
```javascript
function isPrimitive(value) {
    // Using switch fallthrough because it's simple to read and is
    // generally fast: http://jsperf.com/testing-value-is-primitive/5
    switch (typeof value) {
        case "string":
        case "number":
        case "boolean":
            return true;
    }

    return value == null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isRegExp"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isRegExp (val)](#apidoc.element.mout.lang.isRegExp)
- description and source-code
```javascript
function isRegExp(val) {
    return isKind(val, 'RegExp');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isString"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isString (val)](#apidoc.element.mout.lang.isString)
- description and source-code
```javascript
function isString(val) {
    return isKind(val, 'String');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isUndefined"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isUndefined (val)](#apidoc.element.mout.lang.isUndefined)
- description and source-code
```javascript
function isUndef(val){
    return val === UNDEF;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.isnt"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>isnt (x, y)](#apidoc.element.mout.lang.isnt)
- description and source-code
```javascript
function isnt(x, y){
    return !is(x, y);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.kindOf"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>kindOf (val)](#apidoc.element.mout.lang.kindOf)
- description and source-code
```javascript
function kindOf(val) {
    if (val === null) {
        return 'Null';
    } else if (val === UNDEF) {
        return 'Undefined';
    } else {
        return _rKind.exec( _toString.call(val) )[1];
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.toArray"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>toArray (val)](#apidoc.element.mout.lang.toArray)
- description and source-code
```javascript
function toArray(val){
    var ret = [],
        kind = kindOf(val),
        n;

    if (val != null) {
        if ( val.length == null || kind === 'String' || kind === 'Function' || kind === 'RegExp' || val === GLOBAL ) {
            //string, regexp, function have .length but user probably just want
            //to wrap value into an array..
            ret[ret.length] = val;
        } else {
            //window returns true on isObject in IE7 and may have length
            //property. 'typeof NodeList' returns 'function' on Safari so
            //we can't use it (#58)
            n = val.length;
            while (n--) {
                ret[n] = val[n];
            }
        }
    }
    return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.toNumber"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>toNumber (val)](#apidoc.element.mout.lang.toNumber)
- description and source-code
```javascript
function toNumber(val){
    // numberic values should come first because of -0
    if (typeof val === 'number') return val;
    // we want all falsy values (besides -0) to return zero to avoid
    // headaches
    if (!val) return 0;
    if (typeof val === 'string') return parseFloat(val);
    // arrays are edge cases. 'Number([4]) === 4'
    if (isArray(val)) return NaN;
    return Number(val);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.lang.toString"></a>[function <span class="apidocSignatureSpan">mout.lang.</span>toString (val)](#apidoc.element.mout.lang.toString)
- description and source-code
```javascript
function toString(val){
    return val == null ? '' : val.toString();
}
```
- example usage
```shell
...
 * Abbreviated time zone name or similar information.
 */
function timezoneAbbr(date){
    // Date.toString gives different results depending on the
    // browser/system so we fallback to timezone offset
    // chrome: 'Mon Apr 08 2013 09:02:04 GMT-0300 (BRT)'
    // IE: 'Mon Apr 8 09:02:04 UTC-0300 2013'
    var tz = /\(([A-Z]{3,4})\)/.exec(date.toString());
    return tz? tz[1] : timezoneOffset(date);
}

module.exports = timezoneAbbr;
...
```



# <a name="apidoc.module.mout.math"></a>[module mout.math](#apidoc.module.mout.math)

#### <a name="apidoc.element.mout.math.ceil"></a>[function <span class="apidocSignatureSpan">mout.math.</span>ceil (val, step)](#apidoc.element.mout.math.ceil)
- description and source-code
```javascript
function ceil(val, step){
    step = Math.abs(step || 1);
    return Math.ceil(val / step) * step;
}
```
- example usage
```shell
...


/**
 * Round value up with a custom radix.
 */
function ceil(val, step){
    step = Math.abs(step || 1);
    return Math.ceil(val / step) * step;
}

module.exports = ceil;
...
```

#### <a name="apidoc.element.mout.math.clamp"></a>[function <span class="apidocSignatureSpan">mout.math.</span>clamp (val, min, max)](#apidoc.element.mout.math.clamp)
- description and source-code
```javascript
function clamp(val, min, max){
    return val < min? min : (val > max? max : val);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.math.countSteps"></a>[function <span class="apidocSignatureSpan">mout.math.</span>countSteps (val, step, overflow)](#apidoc.element.mout.math.countSteps)
- description and source-code
```javascript
function countSteps(val, step, overflow){
    val = Math.floor(val / step);

    if (overflow) {
        return val % overflow;
    }

    return val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.math.floor"></a>[function <span class="apidocSignatureSpan">mout.math.</span>floor (val, step)](#apidoc.element.mout.math.floor)
- description and source-code
```javascript
function floor(val, step){
    step = Math.abs(step || 1);
    return Math.floor(val / step) * step;
}
```
- example usage
```shell
...
    function split(array, segments) {
segments = segments || 2;
var results = [];
if (array == null) {
    return results;
}

var minLength = Math.floor(array.length / segments),
    remainder = array.length % segments,
    i = 0,
    len = array.length,
    segmentIndex = 0,
    segmentLength;

while (i < len) {
...
```

#### <a name="apidoc.element.mout.math.inRange"></a>[function <span class="apidocSignatureSpan">mout.math.</span>inRange (val, min, max, threshold)](#apidoc.element.mout.math.inRange)
- description and source-code
```javascript
function inRange(val, min, max, threshold){
    threshold = threshold || 0;
    return (val + threshold >= min && val - threshold <= max);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.math.isNear"></a>[function <span class="apidocSignatureSpan">mout.math.</span>isNear (val, target, threshold)](#apidoc.element.mout.math.isNear)
- description and source-code
```javascript
function isNear(val, target, threshold){
    return (Math.abs(val - target) <= threshold);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.math.lerp"></a>[function <span class="apidocSignatureSpan">mout.math.</span>lerp (ratio, start, end)](#apidoc.element.mout.math.lerp)
- description and source-code
```javascript
function lerp(ratio, start, end){
    return start + (end - start) * ratio;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.math.loop"></a>[function <span class="apidocSignatureSpan">mout.math.</span>loop (val, min, max)](#apidoc.element.mout.math.loop)
- description and source-code
```javascript
function loop(val, min, max){
    return val < min? max : (val > max? min : val);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.math.map"></a>[function <span class="apidocSignatureSpan">mout.math.</span>map (val, min1, max1, min2, max2)](#apidoc.element.mout.math.map)
- description and source-code
```javascript
function map(val, min1, max1, min2, max2){
    return lerp( norm(val, min1, max1), min2, max2 );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.math.norm"></a>[function <span class="apidocSignatureSpan">mout.math.</span>norm (val, min, max)](#apidoc.element.mout.math.norm)
- description and source-code
```javascript
function norm(val, min, max){
    if (val < min || val > max) {
        throw new RangeError('value (' + val + ') must be between ' + min + ' and ' + max);
    }

    return val === max ? 1 : (val - min) / (max - min);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.math.overflow"></a>[function <span class="apidocSignatureSpan">mout.math.</span>overflow (number, min, max)](#apidoc.element.mout.math.overflow)
- description and source-code
```javascript
function overflow(number, min, max){
    if ( max === undefined ) {
        max = min;
        min = 0;
    }

    var difference = max - min;

    if ( number < min ) {
        number += difference * ( ~~( ( min - number ) / difference ) + 1 );
    }

    return min + ( number - min ) % difference;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.math.round"></a>[function <span class="apidocSignatureSpan">mout.math.</span>round (value, radix)](#apidoc.element.mout.math.round)
- description and source-code
```javascript
function round(value, radix){
    radix = radix || 1; // default round 1
    return Math.round(value / radix) * radix;
}
```
- example usage
```shell
...


/**
 * Round number to a specific radix
 */
function round(value, radix){
    radix = radix || 1; // default round 1
    return Math.round(value / radix) * radix;
}

module.exports = round;
...
```



# <a name="apidoc.module.mout.number"></a>[module mout.number](#apidoc.module.mout.number)

#### <a name="apidoc.element.mout.number.abbreviate"></a>[function <span class="apidocSignatureSpan">mout.number.</span>abbreviate (val, nDecimals, dict)](#apidoc.element.mout.number.abbreviate)
- description and source-code
```javascript
function abbreviateNumber(val, nDecimals, dict){
    nDecimals = nDecimals != null? nDecimals : 1;
    dict = dict || _defaultDict;
    val = enforcePrecision(val, nDecimals);

    var str, mod;

    if (val < 1000000) {
        mod = enforcePrecision(val / 1000, nDecimals);
        // might overflow to next scale during rounding
        str = mod < 1000? mod + dict.thousand : 1 + dict.million;
    } else if (val < 1000000000) {
        mod = enforcePrecision(val / 1000000, nDecimals);
        str = mod < 1000? mod + dict.million : 1 + dict.billion;
    } else {
        str = enforcePrecision(val / 1000000000, nDecimals) + dict.billion;
    }

    return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.number.currencyFormat"></a>[function <span class="apidocSignatureSpan">mout.number.</span>currencyFormat (val, nDecimalDigits, decimalSeparator, thousandsSeparator)](#apidoc.element.mout.number.currencyFormat)
- description and source-code
```javascript
function currencyFormat(val, nDecimalDigits, decimalSeparator, thousandsSeparator) {
    val = toNumber(val);
    nDecimalDigits = nDecimalDigits == null? 2 : nDecimalDigits;
    decimalSeparator = decimalSeparator == null? '.' : decimalSeparator;
    thousandsSeparator = thousandsSeparator == null? ',' : thousandsSeparator;

    //can't use enforce precision since it returns a number and we are
    //doing a RegExp over the string
    var fixed = val.toFixed(nDecimalDigits),
        //separate begin [$1], middle [$2] and decimal digits [$4]
        parts = new RegExp('^(-?\\d{1,3})((?:\\d{3})+)(\\.(\\d{'+ nDecimalDigits +'}))?$').exec( fixed );

    if(parts){ //val >= 1000 || val <= -1000
        return parts[1] + parts[2].replace(/\d{3}/g, thousandsSeparator + '$&') + (parts[4] ? decimalSeparator + parts[4] : '');
    }else{
        return fixed.replace('.', decimalSeparator);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.number.enforcePrecision"></a>[function <span class="apidocSignatureSpan">mout.number.</span>enforcePrecision (val, nDecimalDigits)](#apidoc.element.mout.number.enforcePrecision)
- description and source-code
```javascript
function enforcePrecision(val, nDecimalDigits){
    val = toNumber(val);
    var pow = Math.pow(10, nDecimalDigits);
    return +(Math.round(val * pow) / pow).toFixed(nDecimalDigits);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.number.isNaN"></a>[function <span class="apidocSignatureSpan">mout.number.</span>isNaN (val)](#apidoc.element.mout.number.isNaN)
- description and source-code
```javascript
function isNaN(val){
    // jshint eqeqeq:false
    return typeof val === 'number' && val != val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.number.nth"></a>[function <span class="apidocSignatureSpan">mout.number.</span>nth (i)](#apidoc.element.mout.number.nth)
- description and source-code
```javascript
function nth(i) {
    var t = (i % 100);
    if (t >= 10 && t <= 20) {
        return 'th';
    }
    switch(i % 10) {
        case 1:
            return 'st';
        case 2:
            return 'nd';
        case 3:
            return 'rd';
        default:
            return 'th';
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.number.ordinal"></a>[function <span class="apidocSignatureSpan">mout.number.</span>ordinal (n)](#apidoc.element.mout.number.ordinal)
- description and source-code
```javascript
function ordinal(n){
   n = toInt(n);
   return n + nth(n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.number.pad"></a>[function <span class="apidocSignatureSpan">mout.number.</span>pad (n, minLength, char)](#apidoc.element.mout.number.pad)
- description and source-code
```javascript
function pad(n, minLength, char){
    n = toNumber(n);
    return lpad(''+ n, minLength, char || '0');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.number.rol"></a>[function <span class="apidocSignatureSpan">mout.number.</span>rol (val, shift)](#apidoc.element.mout.number.rol)
- description and source-code
```javascript
function rol(val, shift){
    return (val << shift) | (val >> (32 - shift));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.number.ror"></a>[function <span class="apidocSignatureSpan">mout.number.</span>ror (val, shift)](#apidoc.element.mout.number.ror)
- description and source-code
```javascript
function ror(val, shift){
    return (val >> shift) | (val << (32 - shift));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.number.sign"></a>[function <span class="apidocSignatureSpan">mout.number.</span>sign (val)](#apidoc.element.mout.number.sign)
- description and source-code
```javascript
function sign(val) {
    var num = toNumber(val);
    if (num === 0) return num; // +0 and +0 === 0
    if (isNaN(num)) return num; // NaN
    return num < 0? -1 : 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.number.toInt"></a>[function <span class="apidocSignatureSpan">mout.number.</span>toInt (val)](#apidoc.element.mout.number.toInt)
- description and source-code
```javascript
function toInt(val){
    // we do not use lang/toNumber because of perf and also because it
    // doesn't break the functionality
    return ~~val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.number.toUInt"></a>[function <span class="apidocSignatureSpan">mout.number.</span>toUInt (val)](#apidoc.element.mout.number.toUInt)
- description and source-code
```javascript
function toUInt(val){
    // we do not use lang/toNumber because of perf and also because it
    // doesn't break the functionality
    return val >>> 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.number.toUInt31"></a>[function <span class="apidocSignatureSpan">mout.number.</span>toUInt31 (val)](#apidoc.element.mout.number.toUInt31)
- description and source-code
```javascript
function toUInt31(val){
    // we do not use lang/toNumber because of perf and also because it
    // doesn't break the functionality
    return (val <= 0)? 0 : (val > MAX_INT? ~~(val % (MAX_INT + 1)) : ~~val);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.object"></a>[module mout.object](#apidoc.module.mout.object)

#### <a name="apidoc.element.mout.object.bindAll"></a>[function <span class="apidocSignatureSpan">mout.object.</span>bindAll (obj, rest_methodNames)](#apidoc.element.mout.object.bindAll)
- description and source-code
```javascript
function bindAll(obj, rest_methodNames){
    var keys = arguments.length > 1?
                slice(arguments, 1) : functions(obj);
    forEach(keys, function(key){
        obj[key] = bind(obj[key], obj);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.contains"></a>[function <span class="apidocSignatureSpan">mout.object.</span>contains (obj, needle)](#apidoc.element.mout.object.contains)
- description and source-code
```javascript
function contains(obj, needle) {
    return some(obj, function(val) {
        return (val === needle);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.deepFillIn"></a>[function <span class="apidocSignatureSpan">mout.object.</span>deepFillIn (target, defaults)](#apidoc.element.mout.object.deepFillIn)
- description and source-code
```javascript
function deepFillIn(target, defaults){
    var i = 0,
        n = arguments.length,
        obj;

    while(++i < n) {
        obj = arguments[i];
        if (obj) {
            // jshint loopfunc: true
            forOwn(obj, function(newValue, key) {
                var curValue = target[key];
                if (curValue == null) {
                    target[key] = newValue;
                } else if (isPlainObject(curValue) &&
                           isPlainObject(newValue)) {
                    deepFillIn(curValue, newValue);
                }
            });
        }
    }

    return target;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.deepMatches"></a>[function <span class="apidocSignatureSpan">mout.object.</span>deepMatches (target, pattern)](#apidoc.element.mout.object.deepMatches)
- description and source-code
```javascript
function deepMatches(target, pattern){
    if (target && typeof target === 'object' &&
        pattern && typeof pattern === 'object') {
        if (isArray(target) && isArray(pattern)) {
            return matchArray(target, pattern);
        } else {
            return matchObject(target, pattern);
        }
    } else {
        return target === pattern;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.deepMixIn"></a>[function <span class="apidocSignatureSpan">mout.object.</span>deepMixIn (target, objects)](#apidoc.element.mout.object.deepMixIn)
- description and source-code
```javascript
function deepMixIn(target, objects) {
    var i = 0,
        n = arguments.length,
        obj;

    while(++i < n){
        obj = arguments[i];
        if (obj) {
            forOwn(obj, copyProp, target);
        }
    }

    return target;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.equals"></a>[function <span class="apidocSignatureSpan">mout.object.</span>equals (a, b, callback)](#apidoc.element.mout.object.equals)
- description and source-code
```javascript
function equals(a, b, callback) {
    callback = callback || is;

    if (!isObject(a) || !isObject(b)) {
        return callback(a, b);
    }

    return (every(a, makeCompare(callback), b) &&
            every(b, checkProperties, a));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.every"></a>[function <span class="apidocSignatureSpan">mout.object.</span>every (obj, callback, thisObj)](#apidoc.element.mout.object.every)
- description and source-code
```javascript
function every(obj, callback, thisObj) {
    callback = makeIterator(callback, thisObj);
    var result = true;
    forOwn(obj, function(val, key) {
        // we consider any falsy values as "false" on purpose so shorthand
        // syntax can be used to check property existence
        if (!callback(val, key, obj)) {
            result = false;
            return false; // break
        }
    });
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.fillIn"></a>[function <span class="apidocSignatureSpan">mout.object.</span>fillIn (obj, var_defaults)](#apidoc.element.mout.object.fillIn)
- description and source-code
```javascript
function fillIn(obj, var_defaults){
    forEach(slice(arguments, 1), function(base){
        forOwn(base, function(val, key){
            if (obj[key] == null) {
                obj[key] = val;
            }
        });
    });
    return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.filter"></a>[function <span class="apidocSignatureSpan">mout.object.</span>filter (obj, callback, thisObj)](#apidoc.element.mout.object.filter)
- description and source-code
```javascript
function filterValues(obj, callback, thisObj) {
    callback = makeIterator(callback, thisObj);
    var output = {};
    forOwn(obj, function(value, key, obj) {
        if (callback(value, key, obj)) {
            output[key] = value;
        }
    });

    return output;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.find"></a>[function <span class="apidocSignatureSpan">mout.object.</span>find (obj, callback, thisObj)](#apidoc.element.mout.object.find)
- description and source-code
```javascript
function find(obj, callback, thisObj) {
    callback = makeIterator(callback, thisObj);
    var result;
    some(obj, function(value, key, obj) {
        if (callback(value, key, obj)) {
            result = value;
            return true; //break
        }
    });
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.flatten"></a>[function <span class="apidocSignatureSpan">mout.object.</span>flatten (obj, level)](#apidoc.element.mout.object.flatten)
- description and source-code
```javascript
function flatten(obj, level) {
    if (obj == null) {
        return {};
    }

    level = level == null ? -1 : level;
    return flattenTo(obj, {}, '', level);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.forIn"></a>[function <span class="apidocSignatureSpan">mout.object.</span>forIn (obj, fn, thisObj)](#apidoc.element.mout.object.forIn)
- description and source-code
```javascript
function forIn(obj, fn, thisObj){
    var key, i = 0;
    // no need to check if argument is a real object that way we can use
    // it for arrays, functions, date, etc.

    //post-pone check till needed
    if (_hasDontEnumBug == null) checkDontEnum();

    for (key in obj) {
        if (exec(fn, obj, key, thisObj) === false) {
            break;
        }
    }


    if (_hasDontEnumBug) {
        var ctor = obj.constructor,
            isProto = !!ctor && obj === ctor.prototype;

        while (key = _dontEnums[i++]) {
            // For constructor, if it is a prototype object the constructor
            // is always non-enumerable unless defined otherwise (and
            // enumerated above).  For non-prototype objects, it will have
            // to be defined on this object, since it cannot be defined on
            // any prototype objects.
            //
            // For other [[DontEnum]] properties, check if the value is
            // different than Object prototype value.
            if (
                (key !== 'constructor' ||
                    (!isProto && hasOwn(obj, key))) &&
                obj[key] !== Object.prototype[key]
            ) {
                if (exec(fn, obj, key, thisObj) === false) {
                    break;
                }
            }
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.forOwn"></a>[function <span class="apidocSignatureSpan">mout.object.</span>forOwn (obj, fn, thisObj)](#apidoc.element.mout.object.forOwn)
- description and source-code
```javascript
function forOwn(obj, fn, thisObj){
    forIn(obj, function(val, key){
        if (hasOwn(obj, key)) {
            return fn.call(thisObj, obj[key], key, obj);
        }
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.functions"></a>[function <span class="apidocSignatureSpan">mout.object.</span>functions (obj)](#apidoc.element.mout.object.functions)
- description and source-code
```javascript
function functions(obj){
    var keys = [];
    forIn(obj, function(val, key){
        if (typeof val === 'function'){
            keys.push(key);
        }
    });
    return keys.sort();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.get"></a>[function <span class="apidocSignatureSpan">mout.object.</span>get (obj, prop)](#apidoc.element.mout.object.get)
- description and source-code
```javascript
function get(obj, prop){
    var parts = prop.split('.'),
        last = parts.pop();

    while (prop = parts.shift()) {
        obj = obj[prop];
        if (obj == null) return;
    }

    return obj[last];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.has"></a>[function <span class="apidocSignatureSpan">mout.object.</span>has (obj, prop)](#apidoc.element.mout.object.has)
- description and source-code
```javascript
function has(obj, prop){
    return get(obj, prop) !== UNDEF;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.hasOwn"></a>[function <span class="apidocSignatureSpan">mout.object.</span>hasOwn (obj, prop)](#apidoc.element.mout.object.hasOwn)
- description and source-code
```javascript
function hasOwn(obj, prop){
    return Object.prototype.hasOwnProperty.call(obj, prop);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.keys"></a>[function <span class="apidocSignatureSpan">mout.object.</span>keys ()](#apidoc.element.mout.object.keys)
- description and source-code
```javascript
function keys() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.map"></a>[function <span class="apidocSignatureSpan">mout.object.</span>map (obj, callback, thisObj)](#apidoc.element.mout.object.map)
- description and source-code
```javascript
function mapValues(obj, callback, thisObj) {
    callback = makeIterator(callback, thisObj);
    var output = {};
    forOwn(obj, function(val, key, obj) {
        output[key] = callback(val, key, obj);
    });

    return output;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.matches"></a>[function <span class="apidocSignatureSpan">mout.object.</span>matches (target, props)](#apidoc.element.mout.object.matches)
- description and source-code
```javascript
function matches(target, props){
    // can't use "object/every" because of circular dependency
    var result = true;
    forOwn(props, function(val, key){
        if (target[key] !== val) {
            // break loop at first difference
            return (result = false);
        }
    });
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.max"></a>[function <span class="apidocSignatureSpan">mout.object.</span>max (obj, compareFn)](#apidoc.element.mout.object.max)
- description and source-code
```javascript
function max(obj, compareFn) {
    return arrMax(values(obj), compareFn);
}
```
- example usage
```shell
...
     */
    function slice(arr, start, end){
var len = arr.length;

if (start == null) {
    start = 0;
} else if (start < 0) {
    start = Math.max(len + start, 0);
} else {
    start = Math.min(start, len);
}

if (end == null) {
    end = len;
} else if (end < 0) {
...
```

#### <a name="apidoc.element.mout.object.merge"></a>[function <span class="apidocSignatureSpan">mout.object.</span>merge ()](#apidoc.element.mout.object.merge)
- description and source-code
```javascript
function merge() {
    var i = 1,
        key, val, obj, target;

    // make sure we don't modify source element and it's properties
    // objects are passed by reference
    target = deepClone( arguments[0] );

    while (obj = arguments[i++]) {
        for (key in obj) {
            if ( ! hasOwn(obj, key) ) {
                continue;
            }

            val = obj[key];

            if ( isObject(val) && isObject(target[key]) ){
                // inception, deep merge objects
                target[key] = merge(target[key], val);
            } else {
                // make sure arrays, regexp, date, objects are cloned
                target[key] = deepClone(val);
            }

        }
    }

    return target;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.min"></a>[function <span class="apidocSignatureSpan">mout.object.</span>min (obj, iterator)](#apidoc.element.mout.object.min)
- description and source-code
```javascript
function min(obj, iterator) {
    return arrMin(values(obj), iterator);
}
```
- example usage
```shell
...
var len = arr.length;

if (start == null) {
    start = 0;
} else if (start < 0) {
    start = Math.max(len + start, 0);
} else {
    start = Math.min(start, len);
}

if (end == null) {
    end = len;
} else if (end < 0) {
    end = Math.max(len + end, 0);
} else {
...
```

#### <a name="apidoc.element.mout.object.mixIn"></a>[function <span class="apidocSignatureSpan">mout.object.</span>mixIn (target, objects)](#apidoc.element.mout.object.mixIn)
- description and source-code
```javascript
function mixIn(target, objects){
    var i = 0,
        n = arguments.length,
        obj;
    while(++i < n){
        obj = arguments[i];
        if (obj != null) {
            forOwn(obj, copyProp, target);
        }
    }
    return target;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.namespace"></a>[function <span class="apidocSignatureSpan">mout.object.</span>namespace (obj, path)](#apidoc.element.mout.object.namespace)
- description and source-code
```javascript
function namespace(obj, path){
    if (!path) return obj;
    forEach(path.split('.'), function(key){
        if (!obj[key]) {
            obj[key] = {};
        }
        obj = obj[key];
    });
    return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.omit"></a>[function <span class="apidocSignatureSpan">mout.object.</span>omit (obj, var_keys)](#apidoc.element.mout.object.omit)
- description and source-code
```javascript
function omit(obj, var_keys){
    var keys = typeof arguments[1] !== 'string'? arguments[1] : slice(arguments, 1),
        out = {};

    for (var property in obj) {
        if (obj.hasOwnProperty(property) && !contains(keys, property)) {
            out[property] = obj[property];
        }
    }
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.pick"></a>[function <span class="apidocSignatureSpan">mout.object.</span>pick (obj, var_keys)](#apidoc.element.mout.object.pick)
- description and source-code
```javascript
function pick(obj, var_keys){
    var keys = typeof arguments[1] !== 'string'? arguments[1] : slice(arguments, 1),
        out = {},
        i = 0, key;
    while (key = keys[i++]) {
        out[key] = obj[key];
    }
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.pluck"></a>[function <span class="apidocSignatureSpan">mout.object.</span>pluck (obj, propName)](#apidoc.element.mout.object.pluck)
- description and source-code
```javascript
function pluck(obj, propName){
    return map(obj, prop(propName));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.reduce"></a>[function <span class="apidocSignatureSpan">mout.object.</span>reduce (obj, callback, memo, thisObj)](#apidoc.element.mout.object.reduce)
- description and source-code
```javascript
function reduce(obj, callback, memo, thisObj) {
    var initial = arguments.length > 2;

    if (!size(obj) && !initial) {
        throw new Error('reduce of empty object with no initial value');
    }

    forOwn(obj, function(value, key, list) {
        if (!initial) {
            memo = value;
            initial = true;
        }
        else {
            memo = callback.call(thisObj, memo, value, key, list);
        }
    });

    return memo;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.reject"></a>[function <span class="apidocSignatureSpan">mout.object.</span>reject (obj, callback, thisObj)](#apidoc.element.mout.object.reject)
- description and source-code
```javascript
function reject(obj, callback, thisObj) {
    callback = makeIterator(callback, thisObj);
    return filter(obj, function(value, index, obj) {
        return !callback(value, index, obj);
    }, thisObj);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.result"></a>[function <span class="apidocSignatureSpan">mout.object.</span>result (obj, prop)](#apidoc.element.mout.object.result)
- description and source-code
```javascript
function result(obj, prop) {
    var property = obj[prop];

    if(property === undefined) {
        return;
    }

    return isFunction(property) ? property.call(obj) : property;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.set"></a>[function <span class="apidocSignatureSpan">mout.object.</span>set (obj, prop, val)](#apidoc.element.mout.object.set)
- description and source-code
```javascript
function set(obj, prop, val){
    var parts = (/^(.+)\.(.+)$/).exec(prop);
    if (parts){
        namespace(obj, parts[1])[parts[2]] = val;
    } else {
        obj[prop] = val;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.size"></a>[function <span class="apidocSignatureSpan">mout.object.</span>size (obj)](#apidoc.element.mout.object.size)
- description and source-code
```javascript
function size(obj) {
    var count = 0;
    forOwn(obj, function(){
        count++;
    });
    return count;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.some"></a>[function <span class="apidocSignatureSpan">mout.object.</span>some (obj, callback, thisObj)](#apidoc.element.mout.object.some)
- description and source-code
```javascript
function some(obj, callback, thisObj) {
    callback = makeIterator(callback, thisObj);
    var result = false;
    forOwn(obj, function(val, key) {
        if (callback(val, key, obj)) {
            result = true;
            return false; // break
        }
    });
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.unset"></a>[function <span class="apidocSignatureSpan">mout.object.</span>unset (obj, prop)](#apidoc.element.mout.object.unset)
- description and source-code
```javascript
function unset(obj, prop){
    if (has(obj, prop)) {
        var parts = prop.split('.'),
            last = parts.pop();
        while (prop = parts.shift()) {
            obj = obj[prop];
        }
        return (delete obj[last]);

    } else {
        // if property doesn't exist treat as deleted
        return true;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.object.values"></a>[function <span class="apidocSignatureSpan">mout.object.</span>values (obj)](#apidoc.element.mout.object.values)
- description and source-code
```javascript
function values(obj) {
    var vals = [];
    forOwn(obj, function(val, key){
        vals.push(val);
    });
    return vals;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.queryString"></a>[module mout.queryString](#apidoc.module.mout.queryString)

#### <a name="apidoc.element.mout.queryString.contains"></a>[function <span class="apidocSignatureSpan">mout.queryString.</span>contains (url, paramName)](#apidoc.element.mout.queryString.contains)
- description and source-code
```javascript
function contains(url, paramName) {
    var regex = new RegExp('(\\?|&)'+ paramName +'=', 'g'); //matches '?param=' or '&param='
    return regex.test(getQuery(url));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.queryString.decode"></a>[function <span class="apidocSignatureSpan">mout.queryString.</span>decode (queryStr, shouldTypecast)](#apidoc.element.mout.queryString.decode)
- description and source-code
```javascript
function decode(queryStr, shouldTypecast) {
    var queryArr = (queryStr || '').replace('?', '').split('&'),
        reg = /([^=]+)=(.+)/,
        i = -1,
        obj = {},
        equalIndex, cur, pValue, pName;

    while ((cur = queryArr[++i])) {
        equalIndex = cur.indexOf('=');
        pName = cur.substring(0, equalIndex);
        pValue = decodeURIComponent(cur.substring(equalIndex + 1));
        if (shouldTypecast !== false) {
            pValue = typecast(pValue);
        }
        if (hasOwn(obj, pName)){
            if(isArray(obj[pName])){
                obj[pName].push(pValue);
            } else {
                obj[pName] = [obj[pName], pValue];
            }
        } else {
            obj[pName] = pValue;
       }
    }
    return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.queryString.encode"></a>[function <span class="apidocSignatureSpan">mout.queryString.</span>encode (obj)](#apidoc.element.mout.queryString.encode)
- description and source-code
```javascript
function encode(obj){
    var query = [],
        arrValues, reg;
    forOwn(obj, function (val, key) {
        if (isArray(val)) {
            arrValues = key + '=';
            reg = new RegExp('&'+key+'+=$');
            forEach(val, function (aValue) {
                arrValues += encodeURIComponent(aValue) + '&' + key + '=';
            });
            query.push(arrValues.replace(reg, ''));
        } else {
           query.push(key + '=' + encodeURIComponent(val));
        }
    });
    return (query.length) ? '?' + query.join('&') : '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.queryString.getParam"></a>[function <span class="apidocSignatureSpan">mout.queryString.</span>getParam (url, param, shouldTypecast)](#apidoc.element.mout.queryString.getParam)
- description and source-code
```javascript
function getParam(url, param, shouldTypecast){
    var regexp = new RegExp('(\\?|&)'+ param + '=([^&]*)'), //matches '?param=value' or '&param=value', value = $2
        result = regexp.exec( getQuery(url) ),
        val = (result && result[2])? result[2] : null;
    return shouldTypecast === false? val : typecast(val);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.queryString.getQuery"></a>[function <span class="apidocSignatureSpan">mout.queryString.</span>getQuery (url)](#apidoc.element.mout.queryString.getQuery)
- description and source-code
```javascript
function getQuery(url) {
    // url = url.replace(/#.*\?/, '?'); //removes hash (to avoid getting hash query)
    var queryString = /\?[a-zA-Z0-9\=\&\%\$\-\_\.\+\!\*\'\(\)\,]+/.exec(url); //valid chars according to: http://www.ietf.org/rfc
/rfc1738.txt
    return (queryString)? decodeURIComponent(queryString[0].replace(/\+/g,' ')) : '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.queryString.parse"></a>[function <span class="apidocSignatureSpan">mout.queryString.</span>parse (url, shouldTypecast)](#apidoc.element.mout.queryString.parse)
- description and source-code
```javascript
function parse(url, shouldTypecast) {
    return decode(getQuery(url), shouldTypecast);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.queryString.setParam"></a>[function <span class="apidocSignatureSpan">mout.queryString.</span>setParam (url, paramName, value)](#apidoc.element.mout.queryString.setParam)
- description and source-code
```javascript
function setParam(url, paramName, value){
    url = url || '';

    var re = new RegExp('(\\?|&)'+ paramName +'=[^&]*' );
    var param = paramName +'='+ encodeURIComponent( value );

    if ( re.test(url) ) {
        return url.replace(re, '$1'+ param);
    } else {
        if (url.indexOf('?') === -1) {
            url += '?';
        }
        if (url.indexOf('=') !== -1) {
            url += '&';
        }
        return url + param;
    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.random"></a>[module mout.random](#apidoc.module.mout.random)

#### <a name="apidoc.element.mout.random.random"></a>[function <span class="apidocSignatureSpan">mout.</span>random ()](#apidoc.element.mout.random.random)
- description and source-code
```javascript
function random(){
    return random.get();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.random.choice"></a>[function <span class="apidocSignatureSpan">mout.random.</span>choice (items)](#apidoc.element.mout.random.choice)
- description and source-code
```javascript
function choice(items) {
    var target = (arguments.length === 1 && isArray(items))? items : arguments;
    return target[ randInt(0, target.length - 1) ];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.random.guid"></a>[function <span class="apidocSignatureSpan">mout.random.</span>guid ()](#apidoc.element.mout.random.guid)
- description and source-code
```javascript
function guid() {
  return (
      randHex(8)+'-'+
      randHex(4)+'-'+
      // v4 UUID always contain "4" at this position to specify it was
      // randomly generated
      '4' + randHex(3) +'-'+
      // v4 UUID always contain chars [a,b,8,9] at this position
      choice(8, 9, 'a', 'b') + randHex(3)+'-'+
      randHex(12)
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.random.rand"></a>[function <span class="apidocSignatureSpan">mout.random.</span>rand (min, max)](#apidoc.element.mout.random.rand)
- description and source-code
```javascript
function rand(min, max){
    min = min == null? MIN_INT : min;
    max = max == null? MAX_INT : max;
    return min + (max - min) * random();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.random.randBit"></a>[function <span class="apidocSignatureSpan">mout.random.</span>randBit ()](#apidoc.element.mout.random.randBit)
- description and source-code
```javascript
function randomBit() {
    return randBool()? 1 : 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.random.randBool"></a>[function <span class="apidocSignatureSpan">mout.random.</span>randBool ()](#apidoc.element.mout.random.randBool)
- description and source-code
```javascript
function randBool(){
    return random() >= 0.5;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.random.randHex"></a>[function <span class="apidocSignatureSpan">mout.random.</span>randHex (size)](#apidoc.element.mout.random.randHex)
- description and source-code
```javascript
function randHex(size){
    size = size && size > 0? size : 6;
    var str = '';
    while (size--) {
        str += choice(_chars);
    }
    return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.random.randInt"></a>[function <span class="apidocSignatureSpan">mout.random.</span>randInt (min, max)](#apidoc.element.mout.random.randInt)
- description and source-code
```javascript
function randInt(min, max){
    min = min == null? MIN_INT : ~~min;
    max = max == null? MAX_INT : ~~max;
    // can't be max + 0.5 otherwise it will round up if 'rand'
    // returns 'max' causing it to overflow range.
    // -0.5 and + 0.49 are required to avoid bias caused by rounding
    return Math.round( rand(min - 0.5, max + 0.499999999999) );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.random.randSign"></a>[function <span class="apidocSignatureSpan">mout.random.</span>randSign ()](#apidoc.element.mout.random.randSign)
- description and source-code
```javascript
function randomSign() {
    return randBool()? 1 : -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.random.randString"></a>[function <span class="apidocSignatureSpan">mout.random.</span>randString (length, dictionary)](#apidoc.element.mout.random.randString)
- description and source-code
```javascript
function randomString(length, dictionary) {
    if(!isNumber(length) || length <= 0) {
      length = 8;
    }

    if(!isString(dictionary) || dictionary.length < 1) {
      dictionary = defaultDictionary;
    }

    var result = '',
        domain = dictionary.length - 1;

    while(length--) {
      result += dictionary[randInt(0, domain)];
    }

    return result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.random.random"></a>[module mout.random.random](#apidoc.module.mout.random.random)

#### <a name="apidoc.element.mout.random.random.random"></a>[function <span class="apidocSignatureSpan">mout.random.</span>random ()](#apidoc.element.mout.random.random.random)
- description and source-code
```javascript
function random(){
    return random.get();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.random.random.get"></a>[function <span class="apidocSignatureSpan">mout.random.random.</span>get ()](#apidoc.element.mout.random.random.get)
- description and source-code
```javascript
function random() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.string"></a>[module mout.string](#apidoc.module.mout.string)

#### <a name="apidoc.element.mout.string.camelCase"></a>[function <span class="apidocSignatureSpan">mout.string.</span>camelCase (str)](#apidoc.element.mout.string.camelCase)
- description and source-code
```javascript
function camelCase(str){
    str = toString(str);
    str = replaceAccents(str);
    str = removeNonWord(str)
        .replace(/[\-_]/g, ' ') //convert all hyphens and underscores to spaces
        .replace(/\s[a-z]/g, upperCase) //convert first char of each word to UPPERCASE
        .replace(/\s+/g, '') //remove spaces
        .replace(/^[A-Z]/g, lowerCase); //convert first char to lowercase
    return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.contains"></a>[function <span class="apidocSignatureSpan">mout.string.</span>contains (str, substring, fromIndex)](#apidoc.element.mout.string.contains)
- description and source-code
```javascript
function contains(str, substring, fromIndex){
    str = toString(str);
    substring = toString(substring);
    return str.indexOf(substring, fromIndex) !== -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.crop"></a>[function <span class="apidocSignatureSpan">mout.string.</span>crop (str, maxChars, append)](#apidoc.element.mout.string.crop)
- description and source-code
```javascript
function crop(str, maxChars, append) {
    str = toString(str);
    return truncate(str, maxChars, append, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.endsWith"></a>[function <span class="apidocSignatureSpan">mout.string.</span>endsWith (str, suffix)](#apidoc.element.mout.string.endsWith)
- description and source-code
```javascript
function endsWith(str, suffix) {
    str = toString(str);
    suffix = toString(suffix);

    return str.indexOf(suffix, str.length - suffix.length) !== -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.escapeHtml"></a>[function <span class="apidocSignatureSpan">mout.string.</span>escapeHtml (str)](#apidoc.element.mout.string.escapeHtml)
- description and source-code
```javascript
function escapeHtml(str){
    str = toString(str)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/'/g, '&#39;')
        .replace(/"/g, '&quot;');
    return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.escapeRegExp"></a>[function <span class="apidocSignatureSpan">mout.string.</span>escapeRegExp (str)](#apidoc.element.mout.string.escapeRegExp)
- description and source-code
```javascript
function escapeRegExp(str) {
    return toString(str).replace(/\W/g,'\\$&');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.escapeUnicode"></a>[function <span class="apidocSignatureSpan">mout.string.</span>escapeUnicode (str, shouldEscapePrintable)](#apidoc.element.mout.string.escapeUnicode)
- description and source-code
```javascript
function escapeUnicode(str, shouldEscapePrintable){
    str = toString(str);
    return str.replace(/[\s\S]/g, function(ch){
        // skip printable ASCII chars if we should not escape them
        if (!shouldEscapePrintable && (/[\x20-\x7E]/).test(ch)) {
            return ch;
        }
        // we use "000" and slice(-4) for brevity, need to pad zeros,
        // unicode escape always have 4 chars after "\u"
        return '\\u'+ ('000'+ ch.charCodeAt(0).toString(16)).slice(-4);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.hyphenate"></a>[function <span class="apidocSignatureSpan">mout.string.</span>hyphenate (str)](#apidoc.element.mout.string.hyphenate)
- description and source-code
```javascript
function hyphenate(str){
    str = toString(str);
    str = unCamelCase(str);
    return slugify(str, "-");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.insert"></a>[function <span class="apidocSignatureSpan">mout.string.</span>insert (string, index, partial)](#apidoc.element.mout.string.insert)
- description and source-code
```javascript
function insert(string, index, partial){
    string = toString(string);

    if (index < 0) {
        index = string.length + index;
    }

    index = clamp(index, 0, string.length);

    return string.substr(0, index) + partial + string.substr(index);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.interpolate"></a>[function <span class="apidocSignatureSpan">mout.string.</span>interpolate (template, replacements, syntax)](#apidoc.element.mout.string.interpolate)
- description and source-code
```javascript
function interpolate(template, replacements, syntax){
    template = toString(template);
    var replaceFn = function(match, prop){
        return toString( get(replacements, prop) );
    };
    return template.replace(syntax || stache, replaceFn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.lowerCase"></a>[function <span class="apidocSignatureSpan">mout.string.</span>lowerCase (str)](#apidoc.element.mout.string.lowerCase)
- description and source-code
```javascript
function lowerCase(str){
    str = toString(str);
    return str.toLowerCase();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.lpad"></a>[function <span class="apidocSignatureSpan">mout.string.</span>lpad (str, minLen, ch)](#apidoc.element.mout.string.lpad)
- description and source-code
```javascript
function lpad(str, minLen, ch) {
    str = toString(str);
    ch = ch || ' ';

    return (str.length < minLen) ?
        repeat(ch, minLen - str.length) + str : str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.ltrim"></a>[function <span class="apidocSignatureSpan">mout.string.</span>ltrim (str, chars)](#apidoc.element.mout.string.ltrim)
- description and source-code
```javascript
function ltrim(str, chars) {
    str = toString(str);
    chars = chars || WHITE_SPACES;

    var start = 0,
        len = str.length,
        charLen = chars.length,
        found = true,
        i, c;

    while (found && start < len) {
        found = false;
        i = -1;
        c = str.charAt(start);

        while (++i < charLen) {
            if (c === chars[i]) {
                found = true;
                start++;
                break;
            }
        }
    }

    return (start >= len) ? '' : str.substr(start, len);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.makePath"></a>[function <span class="apidocSignatureSpan">mout.string.</span>makePath (var_args)](#apidoc.element.mout.string.makePath)
- description and source-code
```javascript
function makePath(var_args){
    var result = join(slice(arguments), '/');
    // need to disconsider duplicate '/' after protocol (eg: 'http://')
    return result.replace(/([^:\/]|^)\/{2,}/g, '$1/');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.normalizeLineBreaks"></a>[function <span class="apidocSignatureSpan">mout.string.</span>normalizeLineBreaks (str, lineEnd)](#apidoc.element.mout.string.normalizeLineBreaks)
- description and source-code
```javascript
function normalizeLineBreaks(str, lineEnd) {
    str = toString(str);
    lineEnd = lineEnd || '\n';

    return str
        .replace(/\r\n/g, lineEnd) // DOS
        .replace(/\r/g, lineEnd)   // Mac
        .replace(/\n/g, lineEnd);  // Unix
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.pascalCase"></a>[function <span class="apidocSignatureSpan">mout.string.</span>pascalCase (str)](#apidoc.element.mout.string.pascalCase)
- description and source-code
```javascript
function pascalCase(str){
    str = toString(str);
    return camelCase(str).replace(/^[a-z]/, upperCase);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.properCase"></a>[function <span class="apidocSignatureSpan">mout.string.</span>properCase (str)](#apidoc.element.mout.string.properCase)
- description and source-code
```javascript
function properCase(str){
    str = toString(str);
    return lowerCase(str).replace(/^\w|\s\w/g, upperCase);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.removeNonASCII"></a>[function <span class="apidocSignatureSpan">mout.string.</span>removeNonASCII (str)](#apidoc.element.mout.string.removeNonASCII)
- description and source-code
```javascript
function removeNonASCII(str){
    str = toString(str);

    // Matches non-printable ASCII chars -
    // http://en.wikipedia.org/wiki/ASCII#ASCII_printable_characters
    return str.replace(/[^\x20-\x7E]/g, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.removeNonWord"></a>[function <span class="apidocSignatureSpan">mout.string.</span>removeNonWord (str)](#apidoc.element.mout.string.removeNonWord)
- description and source-code
```javascript
function removeNonWord(str){
    str = toString(str);
    return str.replace(PATTERN, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.repeat"></a>[function <span class="apidocSignatureSpan">mout.string.</span>repeat (str, n)](#apidoc.element.mout.string.repeat)
- description and source-code
```javascript
function repeat(str, n){
    var result = '';
    str = toString(str);
    n = toInt(n);
   if (n < 1) {
       return '';
   }
   while (n > 0) {
       if (n % 2) {
           result += str;
       }
       n = Math.floor(n / 2);
       str += str;
   }
   return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.replace"></a>[function <span class="apidocSignatureSpan">mout.string.</span>replace (str, search, replacements)](#apidoc.element.mout.string.replace)
- description and source-code
```javascript
function replace(str, search, replacements) {
    str = toString(str);
    search = toArray(search);
    replacements = toArray(replacements);

    var searchLength = search.length,
        replacementsLength = replacements.length;

    if (replacementsLength !== 1 && searchLength !== replacementsLength) {
        throw new Error('Unequal number of searches and replacements');
    }

    var i = -1;
    while (++i < searchLength) {
        // Use the first replacement for all searches if only one
        // replacement is provided
        str = str.replace(
            search[i],
            replacements[(replacementsLength === 1) ? 0 : i]);
    }

    return str;
}
```
- example usage
```shell
...
    function makeIterator(fn) {
        return function(match, token){
            return fn(date, token, localeData);
        };
    }

    return format
        .replace(reToken, makeIterator(expandCombinations))
        .replace(reToken, makeIterator(convertToken));
}


function expandCombinations(date, token, l10n){
    if (token in _combinations) {
        var expanded = _combinations[token];
...
```

#### <a name="apidoc.element.mout.string.replaceAccents"></a>[function <span class="apidocSignatureSpan">mout.string.</span>replaceAccents (str)](#apidoc.element.mout.string.replaceAccents)
- description and source-code
```javascript
function replaceAccents(str){
    str = toString(str);

    // verifies if the String has accents and replace them
    if (str.search(/[\xC0-\xFF]/g) > -1) {
        str = str
                .replace(/[\xC0-\xC5]/g, "A")
                .replace(/[\xC6]/g, "AE")
                .replace(/[\xC7]/g, "C")
                .replace(/[\xC8-\xCB]/g, "E")
                .replace(/[\xCC-\xCF]/g, "I")
                .replace(/[\xD0]/g, "D")
                .replace(/[\xD1]/g, "N")
                .replace(/[\xD2-\xD6\xD8]/g, "O")
                .replace(/[\xD9-\xDC]/g, "U")
                .replace(/[\xDD]/g, "Y")
                .replace(/[\xDE]/g, "P")
                .replace(/[\xE0-\xE5]/g, "a")
                .replace(/[\xE6]/g, "ae")
                .replace(/[\xE7]/g, "c")
                .replace(/[\xE8-\xEB]/g, "e")
                .replace(/[\xEC-\xEF]/g, "i")
                .replace(/[\xF1]/g, "n")
                .replace(/[\xF2-\xF6\xF8]/g, "o")
                .replace(/[\xF9-\xFC]/g, "u")
                .replace(/[\xFE]/g, "p")
                .replace(/[\xFD\xFF]/g, "y");
    }
    return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.rpad"></a>[function <span class="apidocSignatureSpan">mout.string.</span>rpad (str, minLen, ch)](#apidoc.element.mout.string.rpad)
- description and source-code
```javascript
function rpad(str, minLen, ch) {
    str = toString(str);
    ch = ch || ' ';
    return (str.length < minLen)? str + repeat(ch, minLen - str.length) : str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.rtrim"></a>[function <span class="apidocSignatureSpan">mout.string.</span>rtrim (str, chars)](#apidoc.element.mout.string.rtrim)
- description and source-code
```javascript
function rtrim(str, chars) {
    str = toString(str);
    chars = chars || WHITE_SPACES;

    var end = str.length - 1,
        charLen = chars.length,
        found = true,
        i, c;

    while (found && end >= 0) {
        found = false;
        i = -1;
        c = str.charAt(end);

        while (++i < charLen) {
            if (c === chars[i]) {
                found = true;
                end--;
                break;
            }
        }
    }

    return (end >= 0) ? str.substring(0, end + 1) : '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.sentenceCase"></a>[function <span class="apidocSignatureSpan">mout.string.</span>sentenceCase (str)](#apidoc.element.mout.string.sentenceCase)
- description and source-code
```javascript
function sentenceCase(str){
    str = toString(str);

    // Replace first char of each sentence (new line or after '.\s+') to
    // UPPERCASE
    return lowerCase(str).replace(/(^\w)|\.\s+(\w)/gm, upperCase);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.slugify"></a>[function <span class="apidocSignatureSpan">mout.string.</span>slugify (str, delimeter)](#apidoc.element.mout.string.slugify)
- description and source-code
```javascript
function slugify(str, delimeter){
    str = toString(str);

    if (delimeter == null) {
        delimeter = "-";
    }
    str = replaceAccents(str);
    str = removeNonWord(str);
    str = trim(str) //should come after removeNonWord
            .replace(/ +/g, delimeter) //replace spaces with delimeter
            .toLowerCase();
    return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.startsWith"></a>[function <span class="apidocSignatureSpan">mout.string.</span>startsWith (str, prefix)](#apidoc.element.mout.string.startsWith)
- description and source-code
```javascript
function startsWith(str, prefix) {
    str = toString(str);
    prefix = toString(prefix);

    return str.indexOf(prefix) === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.stripHtmlTags"></a>[function <span class="apidocSignatureSpan">mout.string.</span>stripHtmlTags (str)](#apidoc.element.mout.string.stripHtmlTags)
- description and source-code
```javascript
function stripHtmlTags(str){
    str = toString(str);

    return str.replace(/<[^>]*>/g, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.trim"></a>[function <span class="apidocSignatureSpan">mout.string.</span>trim (str, chars)](#apidoc.element.mout.string.trim)
- description and source-code
```javascript
function trim(str, chars) {
    str = toString(str);
    chars = chars || WHITE_SPACES;
    return ltrim(rtrim(str, chars), chars);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.truncate"></a>[function <span class="apidocSignatureSpan">mout.string.</span>truncate (str, maxChars, append, onlyFullWords)](#apidoc.element.mout.string.truncate)
- description and source-code
```javascript
function truncate(str, maxChars, append, onlyFullWords){
    str = toString(str);
    append = append || '...';
    maxChars = onlyFullWords? maxChars + 1 : maxChars;

    str = trim(str);
    if(str.length <= maxChars){
        return str;
    }
    str = str.substr(0, maxChars - append.length);
    //crop at last space or remove trailing whitespace
    str = onlyFullWords? str.substr(0, str.lastIndexOf(' ')) : trim(str);
    return str + append;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.typecast"></a>[function <span class="apidocSignatureSpan">mout.string.</span>typecast (val)](#apidoc.element.mout.string.typecast)
- description and source-code
```javascript
function typecast(val) {
    var r;
    if ( val === null || val === 'null' ) {
        r = null;
    } else if ( val === 'true' ) {
        r = true;
    } else if ( val === 'false' ) {
        r = false;
    } else if ( val === UNDEF || val === 'undefined' ) {
        r = UNDEF;
    } else if ( val === '' || isNaN(val) ) {
        //isNaN('') returns false
        r = val;
    } else {
        //parseFloat(null || '') returns NaN
        r = parseFloat(val);
    }
    return r;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.unCamelCase"></a>[function <span class="apidocSignatureSpan">mout.string.</span>unCamelCase (str, delimiter)](#apidoc.element.mout.string.unCamelCase)
- description and source-code
```javascript
function unCamelCase(str, delimiter){
    if (delimiter == null) {
        delimiter = ' ';
    }

    function join(str, c1, c2) {
        return c1 + delimiter + c2;
    }

    str = toString(str);
    str = str.replace(CAMEL_CASE_BORDER, join);
    str = str.toLowerCase(); //add space between camelCase text
    return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.underscore"></a>[function <span class="apidocSignatureSpan">mout.string.</span>underscore (str)](#apidoc.element.mout.string.underscore)
- description and source-code
```javascript
function underscore(str){
    str = toString(str);
    str = unCamelCase(str);
    return slugify(str, "_");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.unescapeHtml"></a>[function <span class="apidocSignatureSpan">mout.string.</span>unescapeHtml (str)](#apidoc.element.mout.string.unescapeHtml)
- description and source-code
```javascript
function unescapeHtml(str){
    str = toString(str)
        .replace(/&amp;/g , '&')
        .replace(/&lt;/g  , '<')
        .replace(/&gt;/g  , '>')
        .replace(/&#0*39;/g , "'")
        .replace(/&quot;/g, '"');
    return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.unescapeUnicode"></a>[function <span class="apidocSignatureSpan">mout.string.</span>unescapeUnicode (str)](#apidoc.element.mout.string.unescapeUnicode)
- description and source-code
```javascript
function unescapeUnicode(str){
    str = toString(str);
    return str.replace(/\\u[0-9a-f]{4}/g, function(ch){
        var code = parseInt(ch.slice(2), 16);
        return String.fromCharCode(code);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.unhyphenate"></a>[function <span class="apidocSignatureSpan">mout.string.</span>unhyphenate (str)](#apidoc.element.mout.string.unhyphenate)
- description and source-code
```javascript
function unhyphenate(str){
    str = toString(str);
    return str.replace(/(\w)(-)(\w)/g, '$1 $3');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.string.upperCase"></a>[function <span class="apidocSignatureSpan">mout.string.</span>upperCase (str)](#apidoc.element.mout.string.upperCase)
- description and source-code
```javascript
function upperCase(str){
    str = toString(str);
    return str.toUpperCase();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.time"></a>[module mout.time](#apidoc.module.mout.time)

#### <a name="apidoc.element.mout.time.convert"></a>[function <span class="apidocSignatureSpan">mout.time.</span>convert (val, sourceUnitName, destinationUnitName)](#apidoc.element.mout.time.convert)
- description and source-code
```javascript
function convert(val, sourceUnitName, destinationUnitName){
    destinationUnitName = destinationUnitName || 'ms';
    return (val * getUnit(sourceUnitName)) / getUnit(destinationUnitName);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.time.now"></a>[function <span class="apidocSignatureSpan">mout.time.</span>now ()](#apidoc.element.mout.time.now)
- description and source-code
```javascript
function now(){
    // yes, we defer the work to another function to allow mocking it
    // during the tests
    return now.get();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.time.parseMs"></a>[function <span class="apidocSignatureSpan">mout.time.</span>parseMs (ms)](#apidoc.element.mout.time.parseMs)
- description and source-code
```javascript
function parseMs(ms){
    return {
        milliseconds : countSteps(ms, 1, 1000),
        seconds      : countSteps(ms, 1000, 60),
        minutes      : countSteps(ms, 60000, 60),
        hours        : countSteps(ms, 3600000, 24),
        days         : countSteps(ms, 86400000)
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.time.toTimeString"></a>[function <span class="apidocSignatureSpan">mout.time.</span>toTimeString (ms)](#apidoc.element.mout.time.toTimeString)
- description and source-code
```javascript
function toTimeString(ms){
    var h = ms < HOUR   ? 0 : countSteps(ms, HOUR),
        m = ms < MINUTE ? 0 : countSteps(ms, MINUTE, 60),
        s = ms < SECOND ? 0 : countSteps(ms, SECOND, 60),
        str = '';

    str += h? h + ':' : '';
    str += pad(m, 2) + ':';
    str += pad(s, 2);

    return str;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mout.time.now"></a>[module mout.time.now](#apidoc.module.mout.time.now)

#### <a name="apidoc.element.mout.time.now.now"></a>[function <span class="apidocSignatureSpan">mout.time.</span>now ()](#apidoc.element.mout.time.now.now)
- description and source-code
```javascript
function now(){
    // yes, we defer the work to another function to allow mocking it
    // during the tests
    return now.get();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mout.time.now.get"></a>[function <span class="apidocSignatureSpan">mout.time.now.</span>get ()](#apidoc.element.mout.time.now.get)
- description and source-code
```javascript
function now() { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
