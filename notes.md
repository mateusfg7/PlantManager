# Packages

To install a package with expo just type:

```
$ expo install [package]
```
## Used Packages/Components

- **react-native** (doesn't need installation)
  - **SafeAreaView**: _A view, but contain all the content in visible area of the phone. (just works on Iphone)_
  - **Platform**: _Get information about the running device._
  - **StatusBar**: _Get information and dimensions about the status bar of the phone._
  - **Dimensions**: _Get dimensions of the phone._
  - **KeyboardAvoidingView**: _A view that modify the elements position when the keyboard is open._
  - **FlatList**: _Component to create a list of items, something like `map()` of Javascript._
  - **react-native-iphone-x-helper** (need installation): _Misc help methods for Iphone X_
  - **ActivityIndicator**: _Component to show load circle_

- **expo**
  - **@expo/vector-icons**: _Use most common icons on expo, equivalent to react-icons package for React._
  - **expo-font**: _Use customized fonts on expo._
  - **@expo-google-fonts/[font]**: _Use a specific font from google fonts. package e.g.: @expo-google-fonts/inter_
  - **expo-app-loading**: _The splash screen as a component_
  - **lottie-react-native**: _Use animation on expo/react-native_

# Javascript/Typescript

## If/Else

The `if` conditional accepts a block without `{}`, like:
```typescript
if (condition)
  return "Hello Word"

if (condition) return "Hello Word"
```