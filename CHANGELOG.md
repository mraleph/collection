## 1.6.0

* Add a `UnionSet` class that provides a view of the union of a set of sets.

* Add a `UnionSetController` class that provides a convenient way to manage the
  contents of a `UnionSet`.

* Fix another incorrectly-declared generic type.

## 1.5.1

* Fix an incorrectly-declared generic type.

## 1.5.0

* Add `DelegatingIterable.typed()`, `DelegatingList.typed()`,
  `DelegatingSet.typed()`, `DelegatingMap.typed()`, and
  `DelegatingQueue.typed()` static methods. These wrap untyped instances of
  these classes with the correct type parameter, and assert the types of values
  as they're accessed.

* Fix the types for `binarySearch()` and `lowerBound()` so they no longer
  require all arguments to be comparable.

* Add generic annotations to `insertionSort()` and `mergeSort()`.

## 1.4.1

* Fix all strong mode warnings.

## 1.4.0

* Add a `new PriorityQueue()` constructor that forwards to `new
  HeapPriorityQueue()`.

* Deprecate top-level libraries other than `package:collection/collection.dart`,
  which exports these libraries' interfaces.

## 1.3.0

* Add `lowerBound` to binary search for values that might not be present.

* Verify that the is valid for `CanonicalMap.[]`.

## 1.2.0

* Add string comparators that ignore ASCII case and sort numbers numerically.

## 1.1.3

* Fix type inconsistencies with `Map` and `Set`.

## 1.1.2

* Export `UnmodifiableMapView` from the Dart core libraries.

## 1.1.1

* Bug-fix for signatures of `isValidKey` arguments of `CanonicalizedMap`.

## 1.1.0

* Add a `QueueList` class that implements both `Queue` and `List`.

## 0.9.4

* Add a `CanonicalizedMap` class that canonicalizes its keys to provide a custom
  equality relation.

## 0.9.3+1

* Fix all analyzer hints.

## 0.9.3

* Add a `MapKeySet` class that exposes an unmodifiable `Set` view of a `Map`'s
  keys.

* Add a `MapValueSet` class that takes a function from values to keys and uses
  it to expose a `Set` view of a `Map`'s values.