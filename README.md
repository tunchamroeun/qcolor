# qcolor

[Quasar Color palette](https://quasar.dev/style/color-palette) in flutter

## Usage

```dart
void main() {
  Color colorRed = QColors.red;
  Color colorRed14 = QColors.red14;
  Color parseString = QColors.parseColor('red-14'); // can parse "red-14 or red14, error fallback QColors.teal"
}
```