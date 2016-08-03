# Nodejs Snippets for [Atom](https://atom.io)

A collection of Nodejs, JavaScript snippets.

This package also support some of the ES6 syntax half-heartedly.

## Install
Go to `Settings > Install` & then search for `atom-nodejs-snippets` under Packages. After installation, restart Atom.

## Snippets
These snippets are for daily use to avoid writing as much as it could the boilerplate code. If you like, to add yours, feel free to contribute.

**Nodejs Commonly used entities:**
- `re` require
- `me` module.exports
- `exp` exports
- `cb` callback()

**path Module**
- `pjoin` path.join()
- `pdir` path.dirname()
- `pres` path.resolve()
- `pbase` path.basename()
- `pext` path.extname()

**fs Module**
- `fsread` fs.readFile()
- `fsreadstream` fs.createReadStream()
- `fswrite` fs.writeFile()

**event Module**
- `on` event handler | emitter.on('event', function(){})

**stream Module**
- `rstream` readable stream
- `wstream` writable stream
- `pipe`  rs.pipe(ws);

**Process & Global Variables**
- `process.env`
- `process.pid`
- `process.cwd`
- `process.stdin`
- `process.stdout`
- `process.stderr`
- `process.version`
- `process.argv`
- `process.exit`
- `process.kill`
- `process.uptime`
- `process.nextTick` process.nextTick()
- `dirn` dirname

**boilerplate code for requiring core modules**
- `util` const util = require('util');
- `http`
- `fs`
- `path`
- `zlib`
- `buffer`
- `stream`
- `qstring`
- `assert`

**Consoles Shorthand**
- `cl` console.log()
- `cw` console.warn()
- `cd` console.dir()
- `ci` console.info()
- `ce` console.error()

**assert Module**
- `assert.equal`
- `assert.notEqual`
- `assert.deepEqual`
- `assert.ok`
- `assert.ifError`

**Promise**
- `p` new Promise(function(resolve, reject) {});
- `pthen` promise.then(function (){});
- `catch` promise.catch(function (err) {});

**timer functions**
- `si` setInterval()
- `st` setTimeout()
- `sim` setImmediate()

**BDD Testing**
- `desc` describe
- `it`  it in synchronous
- `itasync` it in asynchronous
- `itpending` it pending
- `bef` before()
- `aft` after()
- `befe` beforeEach()
- `afte` afterEach()

**BDD Chai expect Library**
- `expect` const expect = chai.expect;
- `expecte` expect equal
- `expectde` expect deep equal
- `expectne` expect not equal
- `expectnde` expect not deep equal

**Common JS Syntax**
- `kv` key:value pair (object)
- `fnm` method (object)
- `fn` anonymous function
- `fnn` named function
- `fne` function expression
- `iife` immediately invoked function expression
- `use` strict mode
- `r` return
- `rt` return true
- `rf` return false
- `rp` return promise
- `al` alert

**ES6 Syntax**
- `im` import X from module
- `ar` arrow function with parameters
- `aro` arrow function without parameters
- `arn` named arrow function
- `cb6` Nodejs callback in ES6
- `meth` Method (object)
- `get` getter
- `set` setter
- `on6` event handler in ES6
- `process.nextTick6`
- `si6`, `st6`, `sim6` Timer functions in ES6
- `p6`, `pthen6`, `pcatch6`, `rp6` Promises in ES6

**JSON**
- `jparse` JSON.parse()
- `jstr` JSON.stringify()

---
## TODO
- Add more ES6 snippets
- Convert BDD & BDD Chai Library snippets to ES6

## Contribute

Pull requests for more snippets are welcome.

### License
MIT Copyright (c) 2016 Aman Mittal