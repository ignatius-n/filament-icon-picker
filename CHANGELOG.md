# Changelog

## [6.0.0](https://github.com/ignatius-n/filament-icon-picker/compare/5.0.0...6.0.0) (2026-09-24)


### ⚠ BREAKING CHANGES

* fuse.js is replaced by @leeoniya/ufuzzy.
* getSetJs(), getIconsJs() and getIconSvgJs() are removed; the package now registers two routes under the _icon-picker prefix.
* getIcon() now returns null for ids with no file, and icon labels drop the set prefix ("O academic cap", not "Heroicon o academic cap").
* CanBeCacheable is removed and cache config moved from icon-picker.cache.* to filament-icon-picker.cache.*.
* add support for filament v5
* filament v4 support
* Support for filament v3 added (dropped support for v2)

### Features

* add laravel 11 support ([a5531db](https://github.com/ignatius-n/filament-icon-picker/commit/a5531dbf5c63f0e3b3f7c9be6c2e56c4575de494))
* add laravel 11 support ([a5531db](https://github.com/ignatius-n/filament-icon-picker/commit/a5531dbf5c63f0e3b3f7c9be6c2e56c4575de494))
* add support for filament v5 ([5a8eb99](https://github.com/ignatius-n/filament-icon-picker/commit/5a8eb991ea64917311e3e7382fa5de966f39bdbf))
* add the possibility to limit sets that should be shown ([06f335f](https://github.com/ignatius-n/filament-icon-picker/commit/06f335f2bc3e70e5d878747c0d423c8090b8d5c8))
* Added configuration file for global defaults ([4a9bd1b](https://github.com/ignatius-n/filament-icon-picker/commit/4a9bd1b35f01c511d080b3285bdd121b9da570dc))
* Added icon column ([275a7ea](https://github.com/ignatius-n/filament-icon-picker/commit/275a7ea67411ee29960060bac6e36efde35337d7))
* added icon picker with two different layouts ([7197b70](https://github.com/ignatius-n/filament-icon-picker/commit/7197b701331111a42f3322dbd54e3d671dd58fc2))
* added service provider ([6a478c5](https://github.com/ignatius-n/filament-icon-picker/commit/6a478c5c6336ce2006df4645b1aa88f8c0625787))
* added support for placeholders in icon column ([5b87e53](https://github.com/ignatius-n/filament-icon-picker/commit/5b87e53e73ec8510986ab96b2e1c90fdf7a6a740))
* automatically refresh cache on sets / icons change ([db899b4](https://github.com/ignatius-n/filament-icon-picker/commit/db899b45137c936f5c064f9f130c7026e9bcf83a))
* cache icon listings server-side and rename the config namespace ([233c742](https://github.com/ignatius-n/filament-icon-picker/commit/233c742acf0410e732db1866045bee7fee933d20))
* caching search results ([babbe3b](https://github.com/ignatius-n/filament-icon-picker/commit/babbe3b7919fd3b51f2464b829cf202c9e2d0f8f))
* changes to support filament v3 ([777cdd4](https://github.com/ignatius-n/filament-icon-picker/commit/777cdd406ff09dd53f20169284b14ab5b99c2db9))
* filament v4 support ([2863a29](https://github.com/ignatius-n/filament-icon-picker/commit/2863a29b7ae1eba3ca4873494f6ada19f08b6408))
* **icons:** improve icon fetching logic in IconManager ([9b8efd2](https://github.com/ignatius-n/filament-icon-picker/commit/9b8efd2aace7431d607868cc74ec78f32b947224))
* minor changes ([a824e49](https://github.com/ignatius-n/filament-icon-picker/commit/a824e49eed23f56fc8b47d18a2d084a74f915e43))
* minor fixes and changes ([988c029](https://github.com/ignatius-n/filament-icon-picker/commit/988c029ff6af79600cf6c9776509eba5f8ff5961))
* prepare for release ([f3633dc](https://github.com/ignatius-n/filament-icon-picker/commit/f3633dcbd8ca1c6ab44082be9147a62f9200fad2))
* remove display name when icon removed ([6ffe4b0](https://github.com/ignatius-n/filament-icon-picker/commit/6ffe4b0860c46902d4110576cef50b8706b7b56e))
* remove laravel dependency to support all versions ([123543b](https://github.com/ignatius-n/filament-icon-picker/commit/123543b4d62653180fed47c11fce7caa0f00a5e9))
* remove laravel dependency to support all versions ([123543b](https://github.com/ignatius-n/filament-icon-picker/commit/123543b4d62653180fed47c11fce7caa0f00a5e9))
* sanitize uploaded svg icons and restrict icon labels ([dff53e0](https://github.com/ignatius-n/filament-icon-picker/commit/dff53e068846027c1802afced83f571ba4e5fb60))
* scopes ([b25569c](https://github.com/ignatius-n/filament-icon-picker/commit/b25569c18c90a95afb896bec3e3162375d669622))
* scopes ([0e43a10](https://github.com/ignatius-n/filament-icon-picker/commit/0e43a1011f76880d01f8a7fb5115eeb7ca171670))
* scopes ([636eb8d](https://github.com/ignatius-n/filament-icon-picker/commit/636eb8d7a7026f70b72a90464eeec0e3c6c59a93))
* serve icons over token-authorized endpoints instead of Livewire ([4beaf26](https://github.com/ignatius-n/filament-icon-picker/commit/4beaf260b66275aa15fe96f12024ded086ca616f))
* swap fuse.js for uFuzzy and batch svg fetching on the client ([953904c](https://github.com/ignatius-n/filament-icon-picker/commit/953904c75c2ba50c574af79283f1402bcf975d30))
* translations ([67d4bdc](https://github.com/ignatius-n/filament-icon-picker/commit/67d4bdc288dcc4aa4446ea0f89f2c593941ed7a1))
* upload icons update JS after upload ([bc68e1e](https://github.com/ignatius-n/filament-icon-picker/commit/bc68e1e0bdf1654ee88119c823f41c552c3279c2))
* validation ([acdc80d](https://github.com/ignatius-n/filament-icon-picker/commit/acdc80d298a0fe2efcae3e56873e624fe8672a9f))
* validation ([c32bd61](https://github.com/ignatius-n/filament-icon-picker/commit/c32bd61096958b4fe3021c1e33041793b1f2f01a))
* version 1 wip ([b585a89](https://github.com/ignatius-n/filament-icon-picker/commit/b585a896d581f9344abd9b7af9266fd79020847c))
* version 1 wip ([35dbc0b](https://github.com/ignatius-n/filament-icon-picker/commit/35dbc0b888f3eeceb6072454e191bf3e701e0d8a))


### Bug Fixes

* bump filament dependency to stable version ([2953a4e](https://github.com/ignatius-n/filament-icon-picker/commit/2953a4ea77aa729a0ce6a09fbacdd3af7fa11e6f))
* check that custom icons exist instead of matching the set prefix ([3269661](https://github.com/ignatius-n/filament-icon-picker/commit/3269661fca68996b1195de0010b39fb9fb384f62))
* correct PSR-4 violation in CanBeCacheable and tighten icon manager types ([76a9dd9](https://github.com/ignatius-n/filament-icon-picker/commit/76a9dd9fd3d00621f5c84cc23710aee11f5ee445))
* Disabled multiple() method ([ec332a8](https://github.com/ignatius-n/filament-icon-picker/commit/ec332a8a287e60d464423643dab8e3f0c647c0d2))
* enforce scope and allowed sets when resolving icons ([e8c4e51](https://github.com/ignatius-n/filament-icon-picker/commit/e8c4e51920aa70ca005ea32ed7310efd53425e56))
* fixed mismatched method signature ([8cd76ce](https://github.com/ignatius-n/filament-icon-picker/commit/8cd76cedbc05462948befd419f6d0d5383299806))
* icon column for nullable icons ([e2b6cd1](https://github.com/ignatius-n/filament-icon-picker/commit/e2b6cd143718e2ffac3e0f8f82e89342fafddc46))
* icon column null if icon does not exist anymore ([5489f2d](https://github.com/ignatius-n/filament-icon-picker/commit/5489f2deece8e4d8d0e9067f7a0b5465661cc181))
* layout on_top wouldn't render correctly ([c7b3cd9](https://github.com/ignatius-n/filament-icon-picker/commit/c7b3cd97345dbe33b67c20dc1078789b0f113e1a))
* Method mismatch causing exception thrown on empty search query ([5667fd6](https://github.com/ignatius-n/filament-icon-picker/commit/5667fd6d3880bc322c3b80873212ac579ca134ef))
* Method mismatch causing exception thrown on empty search query ([4793fd0](https://github.com/ignatius-n/filament-icon-picker/commit/4793fd0435d66dd77b9576c589c639548b78ab1a))
* namespace ([05e6e6d](https://github.com/ignatius-n/filament-icon-picker/commit/05e6e6d28ab44e4dd71b83386aa3dd6216014bbd))
* parameters of createOptionUsing method ([e2aa51c](https://github.com/ignatius-n/filament-icon-picker/commit/e2aa51cbeef5ad7af4e7b4e91ab82600b4deae5a))
* parameters of createOptionUsing method ([e2aa51c](https://github.com/ignatius-n/filament-icon-picker/commit/e2aa51cbeef5ad7af4e7b4e91ab82600b4deae5a))
* README.md ([ed309fe](https://github.com/ignatius-n/filament-icon-picker/commit/ed309fee35e9566356d67635176af2f312fa687b))
* README.md ([ed309fe](https://github.com/ignatius-n/filament-icon-picker/commit/ed309fee35e9566356d67635176af2f312fa687b))
* relationship Declaration ([1aab5f2](https://github.com/ignatius-n/filament-icon-picker/commit/1aab5f292e8e813e3c20cf7e4bf1ffc0c2caff8d))
* relationship signature ([3c97ef5](https://github.com/ignatius-n/filament-icon-picker/commit/3c97ef50c4af26fed94bdf89fc7054306dc7e23c))
* relationship signature ([3c97ef5](https://github.com/ignatius-n/filament-icon-picker/commit/3c97ef50c4af26fed94bdf89fc7054306dc7e23c))
* Removed enums to support PHP 8.0 ([4a8bf11](https://github.com/ignatius-n/filament-icon-picker/commit/4a8bf113b7b90126e21678e841227e6c9d36e18b))
* support nested directories ([22220c4](https://github.com/ignatius-n/filament-icon-picker/commit/22220c4aa17f411d5e7cd36a6dac2bfe4e26ce2e))
* support nested directories ([22220c4](https://github.com/ignatius-n/filament-icon-picker/commit/22220c4aa17f411d5e7cd36a6dac2bfe4e26ce2e))
* update readme ([c040a72](https://github.com/ignatius-n/filament-icon-picker/commit/c040a725af934d84c1cbb908eceab73a7ea15a3a))
* update readme about new set installation ([c040a72](https://github.com/ignatius-n/filament-icon-picker/commit/c040a725af934d84c1cbb908eceab73a7ea15a3a))
* upgrade deps to match Laravel 10 compatibility ([9241cd5](https://github.com/ignatius-n/filament-icon-picker/commit/9241cd5731c89788014d9f3a51fbadfe7e1831dd))
* use one source of truth for the custom icon set id ([bc4be45](https://github.com/ignatius-n/filament-icon-picker/commit/bc4be452b297e4e94c1b732752292a16bc7ee4ed))


### Performance

* minified the css stylesheets ([fdc0228](https://github.com/ignatius-n/filament-icon-picker/commit/fdc0228385fa12ee968644a2855d0915b831b223))
* resolve single icons by file lookup instead of listing the set ([4904607](https://github.com/ignatius-n/filament-icon-picker/commit/4904607b995fafbe75838986f1b65193b8a7a0ea))


### Refactor

* centralize custom icon scope ids in IconScope ([e8d8e44](https://github.com/ignatius-n/filament-icon-picker/commit/e8d8e44d6ce4919e87623885db7098e1456e4200))
* cleanup Icon ([ffd261e](https://github.com/ignatius-n/filament-icon-picker/commit/ffd261e7cfa78e9f88e1ede3b889a9e4702bc47b))
* cleanup Icon ([01f67d1](https://github.com/ignatius-n/filament-icon-picker/commit/01f67d1f965eb49ca5c0e92c4c2b6a21a007ddbf))
* no results found and searching cards to own component ([edd8b87](https://github.com/ignatius-n/filament-icon-picker/commit/edd8b87983f08622ac3fe22c3cf49d544261754d))


### Style

* fix code styling ([a55c3cb](https://github.com/ignatius-n/filament-icon-picker/commit/a55c3cb8efe35ae5925c1dd4bd45500089a69da7))
* removed commented out code ([a46df31](https://github.com/ignatius-n/filament-icon-picker/commit/a46df31bc944733fa8b786682146a49520cb1cf9))
* removed unused css ([156c0ab](https://github.com/ignatius-n/filament-icon-picker/commit/156c0abc26ace202b08f42a51d7eb622f72407e8))

## [5.0.0](https://github.com/GuavaCZ/filament-icon-picker/compare/4.0.0...5.0.0) (2026-08-04)


### ⚠ BREAKING CHANGES

* fuse.js is replaced by @leeoniya/ufuzzy.
* getSetJs(), getIconsJs() and getIconSvgJs() are removed; the package now registers two routes under the _icon-picker prefix.
* getIcon() now returns null for ids with no file, and icon labels drop the set prefix ("O academic cap", not "Heroicon o academic cap").
* CanBeCacheable is removed and cache config moved from icon-picker.cache.* to filament-icon-picker.cache.*.

### Features

* cache icon listings server-side and rename the config namespace ([233c742](https://github.com/GuavaCZ/filament-icon-picker/commit/233c742acf0410e732db1866045bee7fee933d20))
* sanitize uploaded svg icons and restrict icon labels ([dff53e0](https://github.com/GuavaCZ/filament-icon-picker/commit/dff53e068846027c1802afced83f571ba4e5fb60))
* serve icons over token-authorized endpoints instead of Livewire ([4beaf26](https://github.com/GuavaCZ/filament-icon-picker/commit/4beaf260b66275aa15fe96f12024ded086ca616f))
* swap fuse.js for uFuzzy and batch svg fetching on the client ([953904c](https://github.com/GuavaCZ/filament-icon-picker/commit/953904c75c2ba50c574af79283f1402bcf975d30))


### Bug Fixes

* check that custom icons exist instead of matching the set prefix ([3269661](https://github.com/GuavaCZ/filament-icon-picker/commit/3269661fca68996b1195de0010b39fb9fb384f62))
* correct PSR-4 violation in CanBeCacheable and tighten icon manager types ([76a9dd9](https://github.com/GuavaCZ/filament-icon-picker/commit/76a9dd9fd3d00621f5c84cc23710aee11f5ee445))
* enforce scope and allowed sets when resolving icons ([e8c4e51](https://github.com/GuavaCZ/filament-icon-picker/commit/e8c4e51920aa70ca005ea32ed7310efd53425e56))
* use one source of truth for the custom icon set id ([bc4be45](https://github.com/GuavaCZ/filament-icon-picker/commit/bc4be452b297e4e94c1b732752292a16bc7ee4ed))


### Performance

* resolve single icons by file lookup instead of listing the set ([4904607](https://github.com/GuavaCZ/filament-icon-picker/commit/4904607b995fafbe75838986f1b65193b8a7a0ea))


### Refactor

* centralize custom icon scope ids in IconScope ([e8d8e44](https://github.com/GuavaCZ/filament-icon-picker/commit/e8d8e44d6ce4919e87623885db7098e1456e4200))
