
# react-native-thermal-state

## Getting started

`$ npm install react-native-thermal-state --save`

### Mostly automatic installation

`$ react-native link react-native-thermal-state`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-thermal-state` and add `RNThermalState.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNThermalState.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
	- Add `import com.reactlibrary.RNThermalStatePackage;` to the imports at the top of the file
	- Add `new RNThermalStatePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
		```
		include ':react-native-thermal-state'
		project(':react-native-thermal-state').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-thermal-state/android')
		```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
		```
			compile project(':react-native-thermal-state')
		```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNThermalState.sln` in `node_modules/react-native-thermal-state/windows/RNThermalState.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
	- Add `using Thermal.State.RNThermalState;` to the usings at the top of the file
	- Add `new RNThermalStatePackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNThermalState from 'react-native-thermal-state';

// TODO: What to do with the module?
RNThermalState;
```
