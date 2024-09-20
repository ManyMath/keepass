# `keepass`
KeePass in Dart.  A command-line interface and library.

## Getting started
Run the command-line interface:
```sh
dart pub activate keepass
keepass
```

or use the library as in:
```dart
dart pub add keepass
```
<!--
```dart
import 'package:keepass/keepass.dart';

void main() {
    final keepass = KeePass();
    final database = keepass.open('path/to/database.kdbx', 'password');
    final entries = database.entries;
}
```