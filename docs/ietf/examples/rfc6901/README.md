# TODO:
TODO:


# JSON String Representation

```
""           // the whole document
"/foo"       ["bar", "baz"]
"/foo/0"     "bar"
"/"          0
"/a~1b"      1
"/c%d"       2
"/e^f"       3
"/g|h"       4
"/i\\j"      5
"/k\"l"      6
"/ "         7
"/m~0n"      8
```

# URI Fragment Identifier Representation

```
#            // the whole document
#/foo        ["bar", "baz"]
#/foo/0      "bar"
#/           0
#/a~1b       1
#/c%25d      2
#/e%5Ef      3
#/g%7Ch      4
#/i%5Cj      5
#/k%22l      6
#/%20        7
#/m~0n       8
```
