![image](./demo.gif)

# react-native-bump-version (rnbv)

Bump version in both Android / iOS project

# Install

```
npm install --save-dev rnbv
```

Or if you use Yarn:

```
yarn add -D rnbv
```

# Usage

Run `rnbv` and answer prompts.

# Configuration

You can specify path to build files. The following is the default config:

```javascript
// rnbv.config.js

module.exports = {
  androidPath: './android/app/build.gradle',
  iosPath: './ios/MyApp/Info.plist',
}
```
