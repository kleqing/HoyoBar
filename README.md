<div align="center">
  <img src="Assets/logo.png" alt="logo" width="160" height="160" />
  <h3><code>PaimonMenuBar</code></h3>
  <p><em>Real-time tracking your Genshin Impact account status into your macOS menubar</em></p>

  <img src="https://img.shields.io/badge/uses-SwiftUI-f05138?labelColor=282c34&logo=swift" alt="Use Swift" />
  <img src="https://img.shields.io/badge/macOS-11.0+-f05138?labelColor=282c34&logo=apple" alt="macOS 10.13+" />
  <a href="https://github.com/kleqing/HoyoBar/releases/latest"><img src="https://img.shields.io/github/v/release/spencerwooo/PaimonMenuBar?labelColor=282c34&logo=GitHub" alt="GitHub Release" /></a>
</div>

## What's this?

![screenshot](Assets/scr.png)

> Paimon helps you track your Genshin Impact daily resin, expeditions, and more — straight in your macOS menu bar.

Paimon can help you —

* 🌙 Keep track of your daily resin.
* 💰 Monitor your daily expeditions and real-time realm currency.
* 🏁 Remind you about your daily commissions and weekly boss fights.
* 🍯 And notify you when your parametric transformer is ready to use.

Basically, `HoyoBar` lives in your macOS menu bar quietly, and offers you a nice way of monitoring your in-game real-time stats when you need to check them.

> **Note**
>
> `HoyoBar` is made with SwiftUI, designed for and native to macOS.
> Support both Intel (x86) and M1 (arm64)

## Download

[![GitHub Release](https://img.shields.io/github/v/release/kleqing/HoyoBar?labelColor=282c34&logo=GitHub&style=for-the-badge)](https://github.com/kleqing/HoyoBar/releases/latest)

## Installation

> Open `.dmg` file, copy `HoyoBar.app` to /Application
> Open `HoyoBar.app`

> https://paimon.swo.moe

## Things to know

1. HoyoBar uses the official Hoyoverse API found in either [米游社 (for CN players)](https://bbs.mihoyo.com/ys/) or [HoYoLAB (for Global players)](https://www.hoyolab.com/home).
2. Yes, HoyoBar needs your cookie. It is so that HoyoBar can request said API on your behalf, and fetch those in-game stats periodically. Rest assured that **the cookie is only stored locally.**

## Credits

* Credits to @spencerwoo for his original app. Check [here](https://github.com/spencerwooo/PaimonMenuBar) if you want to use original version instead of this one!

<details>
<summary>Development notes.</summary>

## Features

* [x] Start at login.
* [x] Complie using target 10.13 instead of 11.0+.
* [x] Supported both Intel and M1 Macs.
* [x] Support English, Chinese and Vietnamese.
* [x] Using HoyoLab icon instead of HuTao icon (I love original icon than HuTao icon although I got her at 2.2 because I want to make some people think that it's 'HoyoLab Lite')
* [x] Code-sign and publish as `.dmg`.
* [x] Auto-updates and check for update. (I didn't check yet)
* [x] Custom website and help for acquiring the cookie.
* [x] Support for cn and global genshin accounts (米游社 and hoyolab).

## Build

* Using Xcode 13, Swift 5.5 and SDK 10.13.
* App icon was built from Apple icon template for Adobe Photoshop.
* Using DropDMG to create `.dmg` file.

* Add appcast.xml with the version tag and build number.

</details>

## License

[MIT](LICENSE)

<div align="center">
  <img src="Assets/footer.png" />
  <em>Rebuilt by <a href="https://github.com/kleqing">kleqing</a><br>All credit are belongs to <a href="https://spencerwoo.com">spencerwoo</a>.
  </em>
  <h6>This is a forked version and I just built for mine. For the long term support, please using the <a href="https://github.com/spencerwooo/PaimonMenuBar">original</a> one.</h6>
</div>
