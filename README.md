# Dart: Handling Non-Existent Keys in JSON Response

This repository demonstrates a common error in Dart when handling JSON responses: attempting to access a key that does not exist.  The `bug.dart` file shows the erroneous code, while `bugSolution.dart` provides a corrected version.

The issue arises when the JSON response doesn't contain the expected key, leading to an exception.  The solution involves checking for the key's existence before accessing its value.

## How to run

1. Clone the repository.
2. Ensure you have Dart SDK installed.
3. Run the code using `dart run bug.dart` and `dart run bugSolution.dart`.

## License

MIT