# [Flutter](https://flutter.dev/) Best Practices

### Naming convention
Classes, enums, typedefs, and extensions name should in ```UpperCamelCase```.
```
class TabView { ... }
enum TabItem { .. }
typedef Predicate<T> = bool Function(T value);
extension MyTabItems<T> on List<T> { ... }
```
Libraries, packages, directories, and source files name should be in ```snake_case(lowercase_with_underscores)```.
```
library global_constants;
import 'tabs/tab_view.dart';
```
Variables, constants, parameters, and named parameters should be in ```lowerCamelCase```.
```
var car;
const carPrice = 33333.14;
void sum(int horsePower) {
  // ...
}
```
