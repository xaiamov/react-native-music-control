## [0.12.0](https://github.com/tanguyantoine/react-native-music-control/compare/release-2020-02-16...release-2020-06-12) (2020-06-12)

- Fix: non initialised notification variable ([#334](https://github.com/tanguyantoine/react-native-music-control/issues/334) from rborn/bugfix/code_errors)
- Fix: Start foreground service ([#329](https://github.com/tanguyantoine/react-native-music-control/issues/329) from bunmiedee/startForegroundService)
- Readme Overhaul May 2020 ([#325](https://github.com/tanguyantoine/react-native-music-control/issues/325))
- Fixes android 7 api 24 compatibility issues

## [0.11.0](https://github.com/tanguyantoine/react-native-music-control/compare/release-2019-12-10...release-2020-02-16) (2020-02-16)

- Add Fast Forward and Rewind actions in compact view ([#318](https://github.com/tanguyantoine/react-native-music-control/issues/318))
- Stopping Foreground Service directly instead of starting the service and then stopping in onStartCommand ([#316](https://github.com/tanguyantoine/react-native-music-control/issues/316))

## [0.10.8](https://github.com/tanguyantoine/react-native-music-control/compare/v0.10.6...release-2019-12-10) (2019-12-09)

- feat: handle Audio onFocusChanged if paused ([#308](https://github.com/tanguyantoine/react-native-music-control/issues/308))
- Fix the app crash when run on android api level <= 23 ([#311](https://github.com/tanguyantoine/react-native-music-control/issues/311))
- Handled edge case NPE
- Added null check when abandoning audio focus
- Remove prepack
- Added JS compiled files
- Fix TSC script command
- addTarget:action: should return MPRemoteCommandHandlerStatus
- Temporary workaround for [#297](https://github.com/tanguyantoine/react-native-music-control/issues/297)
- Ignoring react native import
- Disable implicit any rule

## [0.10.6](https://github.com/tanguyantoine/react-native-music-control/compare/v0.10.5...v0.10.6) (2019-08-26)

### Bug Fixes

* **java:** Move stopForegroundService() to onStop event ([#294](https://github.com/tanguyantoine/react-native-music-control/issues/294)) ([e9b4679](https://github.com/tanguyantoine/react-native-music-control/commit/e9b4679))

## [0.10.5](https://github.com/tanguyantoine/react-native-music-control/compare/v0.10.4...v0.10.5) (2019-07-10)

### Bug Fixes

* **android:** error can't find symbol Notification ([b572320](https://github.com/tanguyantoine/react-native-music-control/commit/b572320))
* **android:** migrate support libraries to androidx ([260f720](https://github.com/tanguyantoine/react-native-music-control/commit/260f720)), closes [#280](https://github.com/tanguyantoine/react-native-music-control/issues/280)
* **package.json:** remove unused rnpm object to fix warning in RN 0.60 ([fc48d40](https://github.com/tanguyantoine/react-native-music-control/commit/fc48d40))
* bump version ([9e6991a](https://github.com/tanguyantoine/react-native-music-control/commit/9e6991a))
* bump version ([3fccd12](https://github.com/tanguyantoine/react-native-music-control/commit/3fccd12))

## [0.10.4](https://github.com/tanguyantoine/react-native-music-control/compare/v0.10.3...v0.10.4) (2019-05-24)

### Bug Fixes

* Illegal null AudioFocusRequest exception  ([#261](https://github.com/tanguyantoine/react-native-music-control/issues/261)) ([351a1ab](https://github.com/tanguyantoine/react-native-music-control/commit/351a1ab)), closes [#260](https://github.com/tanguyantoine/react-native-music-control/issues/260)

## [0.10.3](https://github.com/tanguyantoine/react-native-music-control/compare/v0.10.2...v0.10.3) (2019-05-23)

### Bug Fixes

* move variables around and trigger deploy ([6703bf7](https://github.com/tanguyantoine/react-native-music-control/commit/6703bf7))

## [0.10.2](https://github.com/tanguyantoine/react-native-music-control/compare/v0.10.1...v0.10.2) (2019-04-26)

### Bug Fixes

* **ios:** call beginReceivingRemoteControlEvents ([442b77b](https://github.com/tanguyantoine/react-native-music-control/commit/442b77b))
* **ios:** update playback state using :setPlaybackState in iOS 11+ ([b2b1acc](https://github.com/tanguyantoine/react-native-music-control/commit/b2b1acc)), closes [#242](https://github.com/tanguyantoine/react-native-music-control/issues/242)

## [0.10.1](https://github.com/tanguyantoine/react-native-music-control/compare/v0.10.0...v0.10.1) (2019-04-26)

### Bug Fixes

* do no skip prepack script ([51a2532](https://github.com/tanguyantoine/react-native-music-control/commit/51a2532))

# [0.10.0](https://github.com/tanguyantoine/react-native-music-control/compare/v0.9.9...v0.10.0) (2019-04-25)

### Features

* Android interuption ([#240](https://github.com/tanguyantoine/react-native-music-control/issues/240)) ([7c5fe92](https://github.com/tanguyantoine/react-native-music-control/commit/7c5fe92))

## [0.9.9](https://github.com/tanguyantoine/react-native-music-control/compare/v0.9.8...v0.9.9) (2019-02-09)

### Bug Fixes

* bump version ([c0c7754](https://github.com/tanguyantoine/react-native-music-control/commit/c0c7754))

## [0.9.8](https://github.com/tanguyantoine/react-native-music-control/compare/v0.9.7...v0.9.8) (2019-02-01)

### Bug Fixes

* controls not showing on Android lock screen ([#227](https://github.com/tanguyantoine/react-native-music-control/issues/227)) ([51a6fc2](https://github.com/tanguyantoine/react-native-music-control/commit/51a6fc2))
* remove extra pause event related to app suspension in IOS10+ ([6ee2a86](https://github.com/tanguyantoine/react-native-music-control/commit/6ee2a86))

## [0.9.7](https://github.com/tanguyantoine/react-native-music-control/compare/v0.9.6...v0.9.7) (2019-01-11)

### Bug Fixes

* stopForeground service ([36b1922](https://github.com/tanguyantoine/react-native-music-control/commit/36b1922))

## [0.9.6](https://github.com/tanguyantoine/react-native-music-control/compare/v0.9.5...v0.9.6) (2019-01-05)

### Bug Fixes

* release ([6efc1ad](https://github.com/tanguyantoine/react-native-music-control/commit/6efc1ad))
