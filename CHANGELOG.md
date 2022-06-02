
<a name="EdgeX REST Device Service (found in device-rest-go) Changelog"></a>
## EdgeX REST Device Service
[Github repository](https://github.com/edgexfoundry/device-rest-go)

## Change Logs for EdgeX Dependencies

- [device-sdk-go](https://github.com/edgexfoundry/device-sdk-go/blob/jakarta/CHANGELOG.md)

## [v2.1.1] - Jakarta - 2021-06-08 (Only compatible with the 2.x releases)

### Bug Fixes 🐛

- see SDK changelog link above

## [v2.0.0] Ireland - 2021-06-30  (Not Compatible with 1.x releases)
### Change Logs for EdgeX Dependencies
- [device-sdk-go](https://github.com/edgexfoundry/device-sdk-go/blob/v2.0.0/CHANGELOG.md)
- [go-mod-core-contracts](https://github.com/edgexfoundry/go-mod-core-contracts/blob/v2.0.0/CHANGELOG.md)

### Features ✨
- Enable using MessageBus as the default ([#01c2e73](https://github.com/edgexfoundry/device-rest-go/commits/01c2e73))
- Add Registry/Config Access token capability ([#03a48d5](https://github.com/edgexfoundry/device-rest-go/commits/03a48d5))
- Remove Logging configuration ([#c973575](https://github.com/edgexfoundry/device-rest-go/commits/c973575))
### Bug Fixes 🐛
- use correct service key in SecretStore paths ([#23b2ca7](https://github.com/edgexfoundry/device-rest-go/commits/23b2ca7))
- Add Type='vault' to [SecretStore] config ([#99e6da9](https://github.com/edgexfoundry/device-rest-go/commits/99e6da9))
### Code Refactoring ♻
- remove unimplemented InitCmd/RemoveCmd configuration ([#d82b524](https://github.com/edgexfoundry/device-rest-go/commits/d82b524))
- Change PublishTopicPrefix value to be 'edgex/events/device' ([#13945f3](https://github.com/edgexfoundry/device-rest-go/commits/13945f3))
- Update configuration for change to common ServiceInfo struct Moved non-common settings under [Device] section ([#7571376](https://github.com/edgexfoundry/device-rest-go/commits/7571376))
    ```
    BREAKING CHANGE:
    Service configuration has changed
    ```
- Update to assign and uses new Port Assignments ([#2f1c2cc](https://github.com/edgexfoundry/device-rest-go/commits/2f1c2cc))
    ```
    BREAKING CHANGE:
    Device Rest default port number has changed to 59986
    ```
- Added go mod tidy under test target ([#dd01544](https://github.com/edgexfoundry/device-rest-go/commits/dd01544))
- Update for new service key names and overrides for hyphen to underscore ([#2ecd16f](https://github.com/edgexfoundry/device-rest-go/commits/2ecd16f))
    ```
    BREAKING CHANGE:
    Service key names used in configuration have changed.
    ```
- use v2 device-sdk ([#8b511d7](https://github.com/edgexfoundry/device-rest-go/commits/8b511d7))
### Documentation 📖
- update README for v2 ([#f51f5ca](https://github.com/edgexfoundry/device-rest-go/commits/f51f5ca))
- Add badges to readme ([#972f9a5](https://github.com/edgexfoundry/device-rest-go/commits/972f9a5))
### Build 👷
- update build files for v2 ([#a01389d](https://github.com/edgexfoundry/device-rest-go/commits/a01389d))
- **snap:** set release name to 'ireland' ([#903fe29](https://github.com/edgexfoundry/device-rest-go/commits/903fe29))
- update go.mod to go 1.16 ([#0dd2d84](https://github.com/edgexfoundry/device-rest-go/commits/0dd2d84))
- update Dockerfiles to use go 1.16 ([#2544f5c](https://github.com/edgexfoundry/device-rest-go/commits/2544f5c))
- **snap:** update snap v2 support ([#b99a89d](https://github.com/edgexfoundry/device-rest-go/commits/b99a89d))
- **snap:** update environment overrides for device and profile dir ([#5707fd0](https://github.com/edgexfoundry/device-rest-go/commits/5707fd0))
- **snap:** update epoch for Ireland release ([#629973d](https://github.com/edgexfoundry/device-rest-go/commits/629973d))
- **snap:** fix regression due to v2 build changes ([#a2ffdda](https://github.com/edgexfoundry/device-rest-go/commits/a2ffdda))
- **snap:** update go to 1.16 ([#fc4971f](https://github.com/edgexfoundry/device-rest-go/commits/fc4971f))
- **snap:** '-go' suffix removed from device name ([#8b5b60a](https://github.com/edgexfoundry/device-rest-go/commits/8b5b60a))
- **snap:** run 'go mod tidy' ([#e393ce8](https://github.com/edgexfoundry/device-rest-go/commits/e393ce8))
### Continuous Integration 🔄
- update local docker image names ([#2c710f7](https://github.com/edgexfoundry/device-rest-go/commits/2c710f7))

<a name="v1.2.1"></a>
## [v1.2.1] - 2021-02-02
### Features ✨
- **snap:** add startup-duration and startup-interval configure options ([#4b44503](https://github.com/edgexfoundry/device-rest-go/commits/4b44503))
### Build 👷
- **deps:** Bump github.com/edgexfoundry/device-sdk-go ([#70](https://github.com/edgexfoundry/device-rest-go/issues/70)) ([#abd24f1](https://github.com/edgexfoundry/device-rest-go/commits/abd24f1))
### Continuous Integration 🔄
- add semantic.yml for commit linting, update PR template to latest ([#c3aa815](https://github.com/edgexfoundry/device-rest-go/commits/c3aa815))
- standardize dockerfiles ([#998a81b](https://github.com/edgexfoundry/device-rest-go/commits/998a81b))

<a name="v1.2.0"></a>
## [v1.2.0] - 2020-11-18
### Doc
- correct build instructions ([#36](https://github.com/edgexfoundry/device-rest-go/issues/36)) ([#a96498e](https://github.com/edgexfoundry/device-rest-go/commits/a96498e))
### Bug Fixes 🐛
- **snap:** Update snap versioning logic ([#ad0a8ed](https://github.com/edgexfoundry/device-rest-go/commits/ad0a8ed))
### Code Refactoring ♻
- Upgrade SDK to v1.2.4-dev.34 ([#54](https://github.com/edgexfoundry/device-rest-go/issues/54)) ([#4f6fe4f](https://github.com/edgexfoundry/device-rest-go/commits/4f6fe4f))
- update dockerfile to appropriately use ENTRYPOINT and CMD, closes[#34](https://github.com/edgexfoundry/device-rest-go/issues/34) ([#46301eb](https://github.com/edgexfoundry/device-rest-go/commits/46301eb))
### Build 👷
- upgrade device-sdk-go ([#42](https://github.com/edgexfoundry/device-rest-go/issues/42)) ([#0a79c20](https://github.com/edgexfoundry/device-rest-go/commits/0a79c20))
- Upgrade to Go1.15 ([#069cb69](https://github.com/edgexfoundry/device-rest-go/commits/069cb69))
- **all:** Enable use of DependaBot to maintain Go dependencies ([#755b338](https://github.com/edgexfoundry/device-rest-go/commits/755b338))
- **deps:** Bump github.com/edgexfoundry/device-sdk-go ([#5430346](https://github.com/edgexfoundry/device-rest-go/commits/5430346))
- **deps:** Bump github.com/spf13/cast from 1.3.0 to 1.3.1 ([#72307df](https://github.com/edgexfoundry/device-rest-go/commits/72307df))

<a name="v1.1.2"></a>
## [v1.1.2] - 2020-08-19
### Features ✨
- **device-rest:** Add snap directory for device-rest ([#6a789b2](https://github.com/edgexfoundry/device-rest-go/commits/6a789b2))
### Documentation 📖
- Add standard PR template ([#d097784](https://github.com/edgexfoundry/device-rest-go/commits/d097784))

<a name="v1.1.1"></a>
## [v1.1.1] - 2020-06-15
### Bug Fixes 🐛
- Update package name in main.go to match the one in version.go ([#fb37ef4](https://github.com/edgexfoundry/device-rest-go/commits/fb37ef4))

<a name="v1.1.0"></a>
## [v1.1.0] - 2020-05-13
### Code Refactoring ♻
- Set default logging level to INFO ([#d5d9203](https://github.com/edgexfoundry/device-rest-go/commits/d5d9203))
- upgrade SDK to v1.2.0 ([#32a9f9d](https://github.com/edgexfoundry/device-rest-go/commits/32a9f9d))
### Build 👷
- Switch to Go 1.13 ([#2cc5958](https://github.com/edgexfoundry/device-rest-go/commits/2cc5958))

<a name="v1.0.0"></a>
## v1.0.0 - 2020-02-18
### Features ✨
- **rest ds:** Implement new REST Device service ([#5c6b288](https://github.com/edgexfoundry/device-rest-go/commits/5c6b288))
### Bug Fixes 🐛
- Update to latest release of SDK V1.1.2 for mediaType fix ([#49bf546](https://github.com/edgexfoundry/device-rest-go/commits/49bf546))
