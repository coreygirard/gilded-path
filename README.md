# gilded-path

A list of software engineering projects of gradually increasing complexity, useful for building foundational CS skills in a hopefully realistic way

## General Guidance

-

## Projects

### LISP parser

Lisps are programming languages that generally use paired parentheses to specify structure. You are to write a program to convert a string into a data structure. For example, provided the string

```
(aaa (bbb ccc) (ddd (eee fff)))
```

you should return a structure similar to

```
[
    "aaa",
    [
        "bbb",
        "ccc"
    ],
    [
        "ddd",
        [
            "eee",
            "fff"
        ]
    ]
]
```

Returned data structure may be slightly different depending on language used, etc, but it should be functionally identical to this result
