# miniappexercise

test

## Installation

```sh
npm install miniappexercise
```

## Usage

```js
import { multiply } from 'miniappexercise';

// ...
```

## Changelogs

```Changes per version
v0.1.2 - edit ReadMe file
v0.1.1 - Changes in container style
v0.1.0 - initial publish


```

## MiniappExercise Miniapp

Miniapp that compose of two orientation 'horizontal' , 'vertical' and uses the same props and types

## MiniappExercise DataIn Props

| Prop                     | Required | Type               | Description                                                           |
| :----------------------- | :------- | :----------------- | :-------------------------------------------------------------------- |
| **`type`**               | Yes      | `string`           | Choose between 'horizontal' or 'vertical' orientation for this screen |
| **`points`**             | No       | `string or number` | use to set points on this screen                                      |
| **`text`**               | No       | `string`           | use to set title on this screen                                       |
| **`listContainerStyle`** | No       | `ViewStyle`        | View style for list component                                         |
| **`overlayStyle`**       | No       | `ViewStyle`        | View style for overlay                                                |
| **`textStyle`**          | No       | `TextStyle`        | Text style for item description                                       |

## MiniappExercise DataLoad Props

| Prop        | Type   |
| :---------- | :----- |
| **`id`**    | number |
| **`image`** | string |
| **`text`**  | string |

## MiniappExercise DataOut Props

| Prop              | Required | Type         | Description          |
| :---------------- | :------- | :----------- | :------------------- |
| **`TestDataOut`** | Yes      | `() => void` | Button onClick event |

## Example

Run the following commands

`npm run boostrap`:setup project by installing all dependencies and pods.
`npm run example run start`: start the Metro server for the example app.
`npm run example run android`: run the example app on Android.
`npm run example run ios`: run the example app on iOS.

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT

---

Made with [create-react-native-library](https://github.com/callstack/react-native-builder-bob)
