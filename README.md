# Plist Configuration
=================

Some configurations for different technologies

## For HandOff ##
```
<key>NSUserActivityTypes</key>
<array>
  <string>com.comercio.urbania.Favorites</string>
  <string>com.comercio.urbania.Search</string>
</array>
```
## For Geolocation ##
```
<key>NSLocationWhenInUseUsageDescription</key>
<string>Usaremos su localizacion para ubicar su nuevo hogar</string>
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
