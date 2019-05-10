
# react-native-camera-utils

## Getting started

`$ npm install react-native-camera-utils --save`

### Mostly automatic installation

`$ react-native link react-native-camera-utils`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-camera-utils` and add `RNCameraUtils.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNCameraUtils.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNCameraUtilsPackage;` to the imports at the top of the file
  - Add `new RNCameraUtilsPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-camera-utils'
  	project(':react-native-camera-utils').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-camera-utils/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-camera-utils')
  	```


## Usage
```javascript
import RNCameraUtils from 'react-native-camera-utils';

// TODO: What to do with the module?
RNCameraUtils;
```
  