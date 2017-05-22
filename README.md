
# react-native-geofire

## Getting started

`$ npm install react-native-geofire --save`

### Mostly automatic installation

`$ react-native link react-native-geofire`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-geofire` and add `RNGeofire.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNGeofire.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import br.com.ferreiraz.RNGeofirePackage;` to the imports at the top of the file
  - Add `new RNGeofirePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-geofire'
  	project(':react-native-geofire').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-geofire/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-geofire')
  	```


## Usage
```javascript
import RNGeofire from 'react-native-geofire';

// TODO: What to do with the module?
RNGeofire;
```
  