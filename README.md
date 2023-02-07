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

## MiniappExercise Miniapp

Miniapp that compose of two orientation 'horizontal' , 'vertical' and uses the same props and types

## MiniappExercise DataIn Props

| Prop                     | Required | Type        | Description                                                           |
| :----------------------- | :------- | :---------- | :-------------------------------------------------------------------- | -------------------------------- |
| **`type`**               | Yes      | `string`    | Choose between 'horizontal' or 'vertical' orientation for this screen |
| **`points`**             | No       | `string     | number`                                                               | use to set points on this screen |
| **`text`**               | No       | `string`    | use to set title on this screen                                       |
| **`listContainerStyle`** | No       | `ViewStyle` | View style for list component                                         |
| **`overlayStyle`**       | No       | `ViewStyle` | View style for overlay                                                |
| **`textStyle`**          | No       | `TextStyle` | Text style for item description                                       |

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

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT

---

Made with [create-react-native-library](https://github.com/callstack/react-native-builder-bob)
