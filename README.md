# Fn

Functional utility library for PHP.


## API

### partial


### compose


### identity


### constant


### always


### never


### cat


### moreThanOrEqualTo


### lessthan


### equalTo


### notEqualTo


### even


### odd


### both


### invoker


### invokeAll


### invoke


### negate


### conditional


### doWhen


### errorThrower


### conditionalThrower


### throwWhen


### throwError


### resolve


### resolver


### whenSetInvoker


### keySetChecker


### isKeySet


### accessor


### cb


### zip


### mapAssoc


### pick


### any

Returns true if any item in the array passes a predicate

#### Example:

```php
Fn\any([1, 3, 4, 5, 9], Fn\even()) // true
Fn\any([1, 3, 5, 9], Fn\even()) // false
```

### all

Returns true if every item in the array passes a predicate

#### Example:

```php
Fn\all([1, 3, 5, 9], Fn\odd()) // true
Fn\all([1, 3, 4, 5, 9], Fn\even()) // false
```

### joinOr


### joinAnd


### factoryMap


### factory


### caller


### countWhere


### reduceAssoc

