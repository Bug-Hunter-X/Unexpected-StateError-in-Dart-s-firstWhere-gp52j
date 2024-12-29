# Dart firstWhere StateError Bug

This repository demonstrates an unexpected `StateError` that can occur when using the `firstWhere` method in Dart.  The `firstWhere` method throws a `StateError` if no element in the list satisfies the provided predicate.  This behavior can lead to unexpected crashes if not properly handled.

The solution demonstrates a safer way to use `firstWhere` by utilizing the `orElse` parameter to provide a default value when no matching element is found.
