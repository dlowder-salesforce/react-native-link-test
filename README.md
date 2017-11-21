# Example to test react-native link tvOS bug

- Clone this repo
- Change to the top level directory
- Execute `yarn` or `npm install`
- Execute `react-native link react-native-svg`
- Open `ios/EndToEndTest.xcodeproj`


If bug is still present, the EndToEndTest iOS target will include both the iOS and tvOS react-native-svg libraries.
