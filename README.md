# Unhandled JSON Key Access in Dart

This repository demonstrates a common error in Dart applications when handling JSON responses: attempting to access a key that does not exist in the JSON data.  The code throws an exception if the expected key is missing.

The `bug.dart` file contains the buggy code, and `bugSolution.dart` provides a corrected version.

## Problem

The `fetchData` function in `bug.dart` makes a network request and parses a JSON response. It then tries to access the `nonExistentKey`, leading to an exception if that key isn't present.