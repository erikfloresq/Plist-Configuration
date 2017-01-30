# Plist Configuration

Some configurations for different technologies

## For HandOff ##
```
<key>NSUserActivityTypes</key>
<array>
  <string>com.comercio.urbania.Favorites</string>
  <string>com.comercio.urbania.Search</string>
</array>
```
## For Location when in usage  ##
```
<key>NSLocationWhenInUseUsageDescription</key>
<string>Usaremos su localizacion para ubicar su nuevo hogar</string>
```
## For Location when always usage ##
```
<key>NSLocationAlwaysUsageDescription</key>
<string>My description about why I need this capability</string>
```
## For URL ##
```
<key>NSAppTransportSecurity</key>
<dict>
  <key>NSAllowsArbitraryLoads</key>
  <true/>
</dict>
```
## For Open Application with schemes ##
```
<key>LSApplicationQueriesSchemes</key>
<array>
  <string>itms-apps</string>
  <string>comgooglemaps</string>
  <string>comgooglemapsurl</string>
</array>
```
## For Photo Library ##
```
<key>NSPhotoLibraryUsageDescription</key>
<string>My description about why I need this capability</string>
```
## For Siri ##
```
<key>NSSiriUsageDescription</key>
<string>My description about why I need this capability</string>
```
## For Microphone ##
```
<key>NSMicrophoneUsageDescription</key>
<string>My description about why I need this capability</string>
```
## Camera ##
```
<key>NSCameraUsageDescription</key>
<string>My description about why I need this capability</string>
```
## Contacts ##
```
<key>NSContactsUsageDescription</key>
<string>My description about why I need this capability</string>
```
