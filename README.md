# react-native-block

## Getting started

`$ npm install react-native-block --save`

### Mostly automatic installation

`$ react-native link react-native-block`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-block` and add `Block.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libBlock.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.BlockPackage;` to the imports at the top of the file
  - Add `new BlockPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-block'
  	project(':react-native-block').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-block/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-block')
  	```


## Usage
```javascript
import Block from 'react-native-block';

// TODO: What to do with the module?
Block;
```
