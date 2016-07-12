# Associative Arrays - WIP

One of the most reinvented concepts in programming is the [associative array](https://en.wikipedia.org/wiki/Associative_array).
It consists of a collection of [attribute-value pairs](https://en.wikipedia.org/wiki/Attribute%E2%80%93value_pair).
It's fundamentalness - yet obviousness - has led to it having dozens of names. Here are some of them.

## Anatomy of associative arrays

```
associative-array := [ attribute-value-pair* ]
attribute-value-pair := (attribute, value)
```

## Associative arrays as they are known

Language | Associative Array | Attribute-value pair | Attribute | Value
--- | --- | --- | --- | ---
JSON | object | member | name | value
JavaScript | object | property | property name | value 
Python | dict | key-value pair | key | value
PHP | array | key-value pair | key | value
Perl | hash | | key | value
C | struct | member | | |
C++ | std::map | | key | value
Excel | Sheet | row | column | cell
ADO | recordset | record| field | property
SQL | table | row | column | value
Lua | table | | key | value
NoSQL | key-value store | | key | value


Another source: [Wikipedia](https://en.wikipedia.org/wiki/Associative_array#Language_support) (wikipedia has everything, doesn't it?!)
