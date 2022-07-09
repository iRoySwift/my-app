# NativeBase TypeScript Expo Template

The official NativeBase TypeScript template for [Expo](https://docs.expo.io/)

## Usage

1. init

```sh
expo init my-app --template @native-base/expo-template-typescript
```

2. tsconfig.json

```json
{
  "extends": "expo/tsconfig.base",
  "compilerOptions": {
    "strict": true,
    "allowSyntheticDefaultImports": true,
    "jsx": "react-native",
    "lib": ["DOM", "ESNext"],
    "moduleResolution": "node",
    "noEmit": true,
    "skipLibCheck": true,
    "resolveJsonModule": true
  }
}
```

3. prettier.config.js

```js
const options = {
  arrowParens: 'avoid',
  singleQuote: true,
  backetSpace: true,
  endOfLine: 'lf',
  semi: false,
  tabWidth: 2,
  trailingComma: 'none'
}

module.exports = options
```

4. install

```sh
yarn add @react-navigation/native @react-navigation/drawer react-native-screens
```

```sh
yarn add styled-system styled-components
```

```sh
yarn add moti react-native-reanimated
```

```sh
yarn add nanoid  expo-linking
```
