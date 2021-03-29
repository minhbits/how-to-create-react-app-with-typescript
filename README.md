#### 1. Create React App project with TypeScript
```js
npx create-react-app <app-name> --template typescript
```
#### 2. Setup: ESLint

1. Install ESLint
```js
npm install eslint eslint-plugin-jest --save-dev
```
2. Setup a configuration file
```js
npx eslint --init
```
3. Add script to lint all files
```js
// package.json

 "scripts": {
    ...
    "lint": "eslint . --ext .ts,.tsx"
  },
```
4. Or lint single files
```js
npx eslint <file>>
```

**Resources:**
- [create-react-app](https://create-react-app.dev/docs/adding-typescript)
- [ESLint](https://eslint.org/docs/user-guide/getting-started)
