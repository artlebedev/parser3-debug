Debug
=====

Installation
------------

Add to your parsekit.json file new dependency:
```json
{
  "require": {
    ...
    "artlebedev/parser3-debug": "~1.0"
  }
}
```

Update your project dependencies:

```shell
$ parsekit update
```


And just add use statement
```parser
@USE
artlebedev/parser3-debug/Debug.p
# or
^use[artlebedev/parser3-debug/Debug.p]
```


Usage
-----

```parser
^dstop[$anyVariable]
```
