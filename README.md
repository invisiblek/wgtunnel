<h1 align="center">
WG Tunnel
</h1>

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Discord Chat](https://img.shields.io/discord/1108285024631001111.svg)](https://discord.gg/rbRRNh6H7V)

</div>

<div align="center">


[![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.zaneschepke.wireguardautotunnel)
[![Fire TV](https://img.shields.io/badge/fire%20tv-fc3b2d?style=for-the-badge&logo=amazon%20fire%20tv&logoColor=white)](https://www.amazon.com/gp/product/B0CFGGL7WK)
[![F-Droid](https://img.shields.io/static/v1?style=for-the-badge&message=F-Droid&color=1976D2&logo=F-Droid&logoColor=FFFFFF&label=)](https://f-droid.org/packages/com.zaneschepke.wireguardautotunnel/)


</div>

<div align="center">

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/N4N8NMJN2)

</div>


<div align="left">

This is an alternative Android Application for [WireGuard](https://www.wireguard.com/) with added features. Built using the [wireguard-android](https://github.com/WireGuard/wireguard-android) library and [Jetpack Compose](https://developer.android.com/jetpack/compose), this application was inspired by the official [WireGuard Android](https://github.com/WireGuard/wireguard-android) app.

</div>

<div align="center">

## Screenshots

<p float="center">
  <img label="Main" style="padding-right:25px" src="fastlane/metadata/android/en-US/images/phoneScreenshots/main_screen.png" width="200" />
  <img label="Config" style="padding-left:25px" src="fastlane/metadata/android/en-US/images/phoneScreenshots/config_screen.png" width="200" />
  <img label="Settings" style="padding-left:25px" src="fastlane/metadata/android/en-US/images/phoneScreenshots/settings_screen.png" width="200" />
  <img label="Support" style="padding-left:25px" src="fastlane/metadata/android/en-US/images/phoneScreenshots/support_screen.png" width="200" />
</p>

<div align="left">

## Inspiration

The original inspiration for this app came from the inconvenience of having to manually turn VPN off and on while on different networks. This app was created to offer a free solution to this problem. 

## Features

* Add tunnels via .conf file, zip, manual entry, or QR code
* Auto connect to VPN based on Wi-Fi SSID, ethernet, or mobile data
* Split tunneling by application with search
* WireGuard support for kernel and userspace modes
* Always-On VPN support
* Export tunnels to zip
* Quick tile support for VPN toggling
* Static shortcuts support for primary tunnel for automation integration
* Intent automation support for all tunnels
* Automatic service restart after reboot
* Battery preservation measures


## Building
    
```
$ git clone https://github.com/zaneschepke/wgtunnel
$ cd wgtunnel
$ ./gradlew assembleDebug
```

</span>
