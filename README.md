[![npm version](https://badge.fury.io/js/rnbv.svg)](https://badge.fury.io/js/rnbv)

# react-native-bump-version (rnbv)

Bump version in both Android / iOS project

![image](./demo.gif)

# Install

```
npm install --save-dev rnbv
```

Or if you use Yarn:

```
yarn add -D rnbv
```

# Usage

**CLI Usage**

Run `rnbv` and answer prompts.

**Script Usage**

```javascript
const { getAndroidVersion, getIOSVersion } = require('rnbv')

getAndroidVersion() // => e.g.) 1.0.2
```

# Configuration

You can specify path to build files. The following is the default config:

```javascript
// rnbv.config.js

module.exports = {
  androidPath: './android/app/build.gradle',
  iosPath: './ios/MyApp/Info.plist',
}
```
