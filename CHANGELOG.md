## 0.0.1 - Initial Release

<details>
<summary>Release Notes</summary>

### Overview

This is the initial release of the `get_storage_pro` package, aimed at simplifying the process of storing and retrieving objects in Flutter applications using the `get_storage` package.

### Key Features

- Provides utility methods for storing and retrieving objects directly to/from storage.
- Supports storing single objects, lists of objects, and fetching single or multiple objects from storage.
- Automatically handles object serialization and deserialization, eliminating the need for manual conversion to/from maps.
- Introduces the `CommonDataClass` base class for model classes, making it easier to define and manage data models.

### Future Plans

In future releases, we plan to add additional features and improvements, including:

- Enhanced error handling and error reporting.
- Support for more advanced data manipulation operations.
- Optimization and performance enhancements.
- Expanded documentation and examples to make usage even easier.

### Contributions

This package is open-source, and contributions are welcome! Feel free to fork the repository and contribute improvements, bug fixes, or new features. Pull requests will be actively reviewed and accepted after verification.

Thank you for using `get_storage_pro`!

</details>

## 0.0.8

<details>
<summary>Release Notes</summary>

- Added Example main.dart
- Added `deleteById` function to remove a specific object of type [T] from storage.
- Implemented `deleteAllObjects` function to remove all objects of type [T] from storage.

</details>

## 0.1.1

<details>
<summary>Release Notes</summary>

### Overview

This release introduces several new functionalities and improvements to the `get_storage_pro`
package.

### New Features

- Introduced `listenForObjectChanges` function to listen for changes to a specific object of type [T].
- Added `eraseAll` with an optional bool parameter [eraseMainGetStorage] (true by default) to erase complete `GetStoragePro` and `GetStorage` default data.
- Added `listenAllObjects` function to listen for changes to all objects of type [T].

### Changes and Enhancements

- Improved documentation comments for better clarity and understanding.
- Enhanced error handling and error reporting.

### Future Plans

In future releases, we plan to continue improving existing functionalities and adding more features,
including:

- Support for advanced data manipulation operations.
- Performance optimizations.
- Expanded documentation with more examples and tutorials.

### Contributions

Contributions to this package are welcome! Feel free to fork the repository and contribute
improvements, bug fixes, or new features. Pull requests will be actively reviewed and accepted after
verification.

Thank you for using `get_storage_pro`!

</details>

## 0.1.2
<details>
<summary>Release Notes</summary>

### Changes and Enhancements
- Improved & optimised performance

### Contributions

Contributions to this package are always welcome! Feel free to fork the repository and contribute
improvements, bug fixes, or new features. Pull requests will be actively reviewed and accepted after
verification.

Thank you for using `get_storage_pro`!
</details>

## 0.1.4
<details>
<summary>Release Notes</summary>

### Changes and Enhancements
- Fixed containers bug

### Contributions

Contributions to this package are always welcome! Feel free to fork the repository and contribute
improvements, bug fixes, or new features. Pull requests will be actively reviewed and accepted after
verification.

Thank you for using `get_storage_pro`!
</details>

## 0.1.9
<details>
<summary>Release Notes</summary>

### Changes and Enhancements
- Major Upgrade [Shifted to Reflectable to overcome the unnecessary fromMap issue]
- Updated lints and annotations

### Changes:
- Now annotate your model class with `@gsp` as well as extend with `CommonDataClass`
- After annotating run `dart pub run build_runner build` in your terminal. (This will create a new file `main.reflectable.dart` in root folder of your project, don't change anything in that file)
- Now just call `initializeReflectable();` in `main.dart` main function.

### Contributions

Contributions to this package are always welcome! Feel free to fork the repository and contribute
improvements, bug fixes, or new features. Pull requests will be actively reviewed and accepted after
verification.

Thank you for using `get_storage_pro`!
</details>