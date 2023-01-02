## [1.5.1](https://github.com/swrlab/react-native-music-control/compare/v1.5.0...v1.5.1) (2022-07-26)

- wrap forceForeground in try-catch block
- update dev-dependencies
- simplify xcodebuild command

## [1.5.0](https://github.com/swrlab/react-native-music-control/compare/v.1.4.0...v1.5.0) (2022-07-19)

- update project and readme
- add command line build for ios
- add foreground service type to startForeground()
- increase target and compile sdk to 30
- fix pod warning of inherited flags
- fix ios build by adding podfile
- update dependencies
- fix android build and add npm-script
- update spacing of java files and package.json
- update gradle and android deps
- Add foregroundServiceType to Android Manifest ([#402](https://github.com/tanguyantoine/react-native-music-control/issues/402) from tanguyantoine/bradleyflood-patch-1)
- Fix Android Apps crashing when targeting v12 / SDK31 ([#397](https://github.com/tanguyantoine/react-native-music-control/issues/397) from rafaelmaeuer/dev/fix-android-12-pending-intent-mutability)

## [1.4.0](https://github.com/swrlab/react-native-music-control/releases/tag/v.1.4.0) (2021-05-21)

- feat: upgrade dependencies
- update readme
  - [#385](https://github.com/tanguyantoine/react-native-music-control/issues/385) from srobbin/chore/fix-readme-parenthesis
  - [#386](https://github.com/tanguyantoine/react-native-music-control/issues/386) from dayze/patch-1
- Add singleTask Activity instructions to Readme ([#383](https://github.com/tanguyantoine/react-native-music-control/issues/383) from tanguyantoine/feature/ReadmeUpdateActivity)
- exception handling added and crash fixed ([#381](https://github.com/tanguyantoine/react-native-music-control/issues/381) from krunalbad/patch-1)
- Adding mavenCentral() as jcenter() is shutting ([#382](https://github.com/tanguyantoine/react-native-music-control/issues/382) from maheshwarimrinal/patch-1)
- Patch 2 - missing setNotificationId() added for android ([#368](https://github.com/tanguyantoine/react-native-music-control/issues/368))
- change order of Sections in readme ([#370](https://github.com/tanguyantoine/react-native-music-control/issues/370))

## [1.3.0](https://github.com/tanguyantoine/react-native-music-control/tree/f6ef12b9cdd858baff903c1433b56b0975208d2b) (2020-11-30)

- docs: update readme
- Exports MusicControl.Command ([#361](https://github.com/tanguyantoine/react-native-music-control/issues/361))
- fixed hide method to work with older SDKs ([#354](https://github.com/tanguyantoine/react-native-music-control/issues/354) from frknnay/fix/android-hide-for-older-sdks)
- Fix Xcode 12 build errors ([#363](https://github.com/tanguyantoine/react-native-music-control/issues/363))
- iOS Live Stream Indicator ([#353](https://github.com/tanguyantoine/react-native-music-control/issues/353))

## [1.2.1](https://github.com/tanguyantoine/react-native-music-control/tree/99a623fd918565f03a3f4e061547e57427ad97a0) (2020-10-12)

- ci: fix versioning
- fix: push version commit
- fix: set author
- ci: fix typo
- chore: remove github registry for now
- ci: add workflow dispatch
- fix: dependencies

## [1.0.0](https://github.com/tanguyantoine/react-native-music-control/compare/release-2020-02-16...release-2020-06-12) (2020-06-12)

- Fixes for [#266](https://github.com/tanguyantoine/react-native-music-control/issues/266) ([#344](https://github.com/tanguyantoine/react-native-music-control/issues/344) from rborn/master)
  - Fix for session not always present when checking if active
  - fix merge error for undefined NOTIFICATION_ID
  - fix double definition
  - Update MusicControlNotification.java
  - modified to prevent crash
  - Solve MusicControlModule exception issue
  - replace prepack with prepublish script
  - add lib dir back to the repo
  - add react-native to dev dependencies
  - try to bind service first
  - add local binder instance
  - Fixes crash android 9
- Adjust playback speed while playing ([#336](https://github.com/tanguyantoine/react-native-music-control/issues/336) from SBShane/master)
- Add setNotificationIds to Android ([#337](https://github.com/tanguyantoine/react-native-music-control/issues/337) from mixcloud/change-android-notification-ids)

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
