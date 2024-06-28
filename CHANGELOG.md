## v4.1.4 (2024-06-28)

#### :bug: Bug Fix
* [#400](https://github.com/yapplabs/ember-modal-dialog/pull/400) Avoid Fastboot crash when accessing `navigator` global ([@gilest](https://github.com/gilest))

#### Committers: 1
- Giles Thompson ([@gilest](https://github.com/gilest))

## v4.1.3 (2024-01-04)

## v4.1.2 (2023-05-08)

#### :bug: Bug Fix
* [#395](https://github.com/yapplabs/ember-modal-dialog/pull/395) ember-tether version change was missing in peerDependencies declaration ([@lukemelia](https://github.com/lukemelia))

#### Committers: 1
- Luke Melia ([@lukemelia](https://github.com/lukemelia))

## v4.1.1 (2023-05-05)

## v4.1.0 (2023-02-23)

#### :rocket: Enhancement
* [#389](https://github.com/yapplabs/ember-modal-dialog/pull/389) Add splattibutes support and fix containerClassNames for rendered in place modals ([@ratierd](https://github.com/ratierd))

#### :bug: Bug Fix
* [#389](https://github.com/yapplabs/ember-modal-dialog/pull/389) Add splattibutes support and fix containerClassNames for rendered in place modals ([@ratierd](https://github.com/ratierd))

#### :house: Internal
* [#390](https://github.com/yapplabs/ember-modal-dialog/pull/390) Run tests with node 16 ([@lukemelia](https://github.com/lukemelia))

#### Committers: 2
- David Ratier ([@ratierd](https://github.com/ratierd))
- Luke Melia ([@lukemelia](https://github.com/lukemelia))

## v4.0.1 (2022-04-10)

#### :bug: Bug Fix
* [#378](https://github.com/yapplabs/ember-modal-dialog/pull/378) Fix error attempting to join class names when they are a string ([@lukemelia](https://github.com/lukemelia))

#### Committers: 2
- Luke Melia ([@lukemelia](https://github.com/lukemelia))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))

## v4.0.0 (2022-02-09)

#### :boom: Breaking Change

Drops support for Ember 3.19 and below

#### :rocket: Enhancement

Ember 4 compatibility and Embroider support

## v4.0.0-beta.0 (2022-01-24)

#### :rocket: Enhancement
* [#358](https://github.com/yapplabs/ember-modal-dialog/pull/358) Start on embroider support ([@rwwagner90](https://github.com/rwwagner90))

#### :house: Internal
* [#370](https://github.com/yapplabs/ember-modal-dialog/pull/370) Embroider support ([@rwwagner90](https://github.com/rwwagner90))
* [#369](https://github.com/yapplabs/ember-modal-dialog/pull/369) Bump deps, yarn upgrade ([@rwwagner90](https://github.com/rwwagner90))
* [#365](https://github.com/yapplabs/ember-modal-dialog/pull/365) ember-cli 4 ([@rwwagner90](https://github.com/rwwagner90))
* [#361](https://github.com/yapplabs/ember-modal-dialog/pull/361) Remove ember-classic-decorator ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 1
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))

## v4.0.0-alpha.1 (2021-09-09)

#### :boom: Breaking Change
* [#350](https://github.com/yapplabs/ember-modal-dialog/pull/350) Stop delegating targetAttachmentClass argument ([@lukemelia](https://github.com/lukemelia))

#### :house: Internal
* [#351](https://github.com/yapplabs/ember-modal-dialog/pull/351) Avoid global `Ember` deprecation in add-modals-container initializer ([@lukemelia](https://github.com/lukemelia))
* [#346](https://github.com/yapplabs/ember-modal-dialog/pull/346) Update lint commands ([@rwwagner90](https://github.com/rwwagner90))
* [#345](https://github.com/yapplabs/ember-modal-dialog/pull/345) Use GitHub Actions instead of Travis ([@rwwagner90](https://github.com/rwwagner90))
* [#344](https://github.com/yapplabs/ember-modal-dialog/pull/344) Update to angle bracket components ([@rwwagner90](https://github.com/rwwagner90))
* [#341](https://github.com/yapplabs/ember-modal-dialog/pull/341) Update to ember-cli 3.16 ([@rwwagner90](https://github.com/rwwagner90))
* [#338](https://github.com/yapplabs/ember-modal-dialog/pull/338) Adopt ember-ignore-children-helper ([@bjornharrtell](https://github.com/bjornharrtell))

#### Committers: 3
- Björn Harrtell ([@bjornharrtell](https://github.com/bjornharrtell))
- Luke Melia ([@lukemelia](https://github.com/lukemelia))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))

## v4.0.0-alpha.0 (2021-05-25)

#### :boom: Breaking Change
* [#332](https://github.com/yapplabs/ember-modal-dialog/pull/332) Drop support for Ember 3.19 and below ([@Turbo87](https://github.com/Turbo87))

#### :house: Internal
* [#333](https://github.com/yapplabs/ember-modal-dialog/pull/333) Add volta config ([@lukemelia](https://github.com/lukemelia))
* [#324](https://github.com/yapplabs/ember-modal-dialog/pull/324) Upgrade `ember-wormhole` to v0.6.0 ([@legallai](https://github.com/legallai))
* [#331](https://github.com/yapplabs/ember-modal-dialog/pull/331) Remove obsolete `this.get(...)` calls ([@Turbo87](https://github.com/Turbo87))
* [#330](https://github.com/yapplabs/ember-modal-dialog/pull/330) dummy: Remove obsolete `register-subclassed-modals` initializer ([@Turbo87](https://github.com/Turbo87))
* [#329](https://github.com/yapplabs/ember-modal-dialog/pull/329) Add missing `this.` prefixes to the templates ([@Turbo87](https://github.com/Turbo87))

#### Committers: 3
- Luke Melia ([@lukemelia](https://github.com/lukemelia))
- Tobias Bieniek ([@Turbo87](https://github.com/Turbo87))
- [@legallai](https://github.com/legallai)

## v3.0.3 (2021-05-17)

#### :bug: Bug Fix
* [#326](https://github.com/yapplabs/ember-modal-dialog/pull/326) initializers/add-modals-container: Work around string injection bug ([@Turbo87](https://github.com/Turbo87))

#### :house: Internal
* [#327](https://github.com/yapplabs/ember-modal-dialog/pull/327) Silence deprecation warnings ([@Turbo87](https://github.com/Turbo87))

#### Committers: 1
- Tobias Bieniek ([@Turbo87](https://github.com/Turbo87))

## v3.0.2 (2021-02-18)

#### :bug: Bug Fix
* [#315](https://github.com/yapplabs/ember-modal-dialog/pull/315) fix: support `ember-engines` ([@buschtoens](https://github.com/buschtoens))

#### Committers: 1
- Jan Buschtöns ([@buschtoens](https://github.com/buschtoens))

## v3.0.1 (2020-07-24)

#### :bug: Bug Fix
* [#300](https://github.com/yapplabs/ember-modal-dialog/pull/300) Fix dummy app css and two actions ([@lukemelia](https://github.com/lukemelia))
* [#295](https://github.com/yapplabs/ember-modal-dialog/pull/295) fixes my previous change to the css installation instructions ([@christophermlne](https://github.com/christophermlne))
* [#294](https://github.com/yapplabs/ember-modal-dialog/pull/294) fixes bad css import snippet in README installation instructions ([@christophermlne](https://github.com/christophermlne))

#### :memo: Documentation
* [#295](https://github.com/yapplabs/ember-modal-dialog/pull/295) fixes my previous change to the css installation instructions ([@christophermlne](https://github.com/christophermlne))
* [#294](https://github.com/yapplabs/ember-modal-dialog/pull/294) fixes bad css import snippet in README installation instructions ([@christophermlne](https://github.com/christophermlne))
* [#281](https://github.com/yapplabs/ember-modal-dialog/pull/281) Update README.md ([@newyork-anthonyng](https://github.com/newyork-anthonyng))

#### :house: Internal
* [#307](https://github.com/yapplabs/ember-modal-dialog/pull/307) Switch to release-it ([@lukemelia](https://github.com/lukemelia))
* [#305](https://github.com/yapplabs/ember-modal-dialog/pull/305) Bump websocket-extensions from 0.1.3 to 0.1.4 ([@dependabot[bot]](https://github.com/apps/dependabot))
* [#304](https://github.com/yapplabs/ember-modal-dialog/pull/304) Bump jquery from 3.4.1 to 3.5.0 ([@dependabot[bot]](https://github.com/apps/dependabot))
* [#306](https://github.com/yapplabs/ember-modal-dialog/pull/306) Bump lodash from 4.17.11 to 4.17.19 ([@dependabot[bot]](https://github.com/apps/dependabot))

#### Committers: 5
- Anthony Ng ([@newyork-anthonyng](https://github.com/newyork-anthonyng))
- Ben Kiefer ([@benkiefer](https://github.com/benkiefer))
- Christopher Milne ([@christophermlne](https://github.com/christophermlne))
- Luke Melia ([@lukemelia](https://github.com/lukemelia))
- [@mum-never-proud](https://github.com/mum-never-proud)

# Change Log

## [3.0.0-beta.4](https://github.com/yapplabs/ember-modal-dialog/tree/3.0.0-beta.4) (2019-06-18)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v3.0.0-beta.3...3.0.0-beta.4)

**Merged pull requests:**

- Pure CSS [\#278](https://github.com/yapplabs/ember-modal-dialog/pull/278) ([chrism](https://github.com/chrism))
- Upgrading dependencies [\#277](https://github.com/yapplabs/ember-modal-dialog/pull/277) ([chrism](https://github.com/chrism))
- Move contribution guide to CONTRIBUTING.md [\#274](https://github.com/yapplabs/ember-modal-dialog/pull/274) ([hakilebara](https://github.com/hakilebara))
- Add a table of contents to README.md [\#272](https://github.com/yapplabs/ember-modal-dialog/pull/272) ([hakilebara](https://github.com/hakilebara))

## [v3.0.0-beta.3](https://github.com/yapplabs/ember-modal-dialog/tree/v3.0.0-beta.3) (2018-11-23)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v3.0.0-beta.2...v3.0.0-beta.3)

**Merged pull requests:**

- Only try to invoke onClose action if it has been provided [\#271](https://github.com/yapplabs/ember-modal-dialog/pull/271) ([lukemelia](https://github.com/lukemelia))

## [v3.0.0-beta.2](https://github.com/yapplabs/ember-modal-dialog/tree/v3.0.0-beta.2) (2018-11-12)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v3.0.0-beta.1...v3.0.0-beta.2)

**Merged pull requests:**

- \[BREAKING\] Update to ember-cli-babel@7. \(Drops support for ember-cli \< 2.13\) [\#266](https://github.com/yapplabs/ember-modal-dialog/pull/266) ([rwjblue](https://github.com/rwjblue))

## [v3.0.0-beta.1](https://github.com/yapplabs/ember-modal-dialog/tree/v3.0.0-beta.1) (2018-11-12)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v2.4.4...v3.0.0-beta.1)

**Merged pull requests:**

- \[BREAKING\] Update ember to 3.5, drop support for Ember 2.4  [\#265](https://github.com/yapplabs/ember-modal-dialog/pull/265) ([lukemelia](https://github.com/lukemelia))
- use closure actions [\#264](https://github.com/yapplabs/ember-modal-dialog/pull/264) ([mcfiredrill](https://github.com/mcfiredrill))
- Handle when App.rootElement can be a node, rather than an id [\#263](https://github.com/yapplabs/ember-modal-dialog/pull/263) ([averydev](https://github.com/averydev))
- update README.md Custom Modals section [\#259](https://github.com/yapplabs/ember-modal-dialog/pull/259) ([hakilebara](https://github.com/hakilebara))
- Update .travis.yml [\#258](https://github.com/yapplabs/ember-modal-dialog/pull/258) ([samselikoff](https://github.com/samselikoff))
- Don't sendAction in click handler when component isDestroying or isDestroyed [\#255](https://github.com/yapplabs/ember-modal-dialog/pull/255) ([oscarni](https://github.com/oscarni))

## [v2.4.4](https://github.com/yapplabs/ember-modal-dialog/tree/v2.4.4) (2018-05-14)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v3.0.0-beta.0...v2.4.4)

## [v3.0.0-beta.0](https://github.com/yapplabs/ember-modal-dialog/tree/v3.0.0-beta.0) (2018-03-03)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v2.4.3...v3.0.0-beta.0)

**Merged pull requests:**

- Update dependencies [\#247](https://github.com/yapplabs/ember-modal-dialog/pull/247) ([lukemelia](https://github.com/lukemelia))
- \[BREAKING\] Remove deprecations in anticipation of 3.0.0 [\#246](https://github.com/yapplabs/ember-modal-dialog/pull/246) ([lukemelia](https://github.com/lukemelia))

## [v2.4.3](https://github.com/yapplabs/ember-modal-dialog/tree/v2.4.3) (2018-03-03)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v2.4.2...v2.4.3)

**Merged pull requests:**

- Fix bug in specifying incorrect overlay selector on iOS [\#245](https://github.com/yapplabs/ember-modal-dialog/pull/245) ([lukemelia](https://github.com/lukemelia))

## [v2.4.2](https://github.com/yapplabs/ember-modal-dialog/tree/v2.4.2) (2018-02-22)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v2.4.1...v2.4.2)

**Merged pull requests:**

- Update version compatibility \(which controls ember:try version targets\) [\#243](https://github.com/yapplabs/ember-modal-dialog/pull/243) ([lukemelia](https://github.com/lukemelia))
- Fix bug with clickOutsideToClose when specifying a stack [\#242](https://github.com/yapplabs/ember-modal-dialog/pull/242) ([andrewhavens](https://github.com/andrewhavens))
- ember-cli-update to 2.17 [\#235](https://github.com/yapplabs/ember-modal-dialog/pull/235) ([Dhaulagiri](https://github.com/Dhaulagiri))
- Removing jQuery [\#234](https://github.com/yapplabs/ember-modal-dialog/pull/234) ([gmurphey](https://github.com/gmurphey))
- Confusing sentence [\#223](https://github.com/yapplabs/ember-modal-dialog/pull/223) ([dan-ste](https://github.com/dan-ste))

## [v2.4.1](https://github.com/yapplabs/ember-modal-dialog/tree/v2.4.1) (2017-12-05)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v2.4.0...v2.4.1)

**Merged pull requests:**

- Revert modules update to file in app directory [\#232](https://github.com/yapplabs/ember-modal-dialog/pull/232) ([Dhaulagiri](https://github.com/Dhaulagiri))
- handle global document being undefined [\#230](https://github.com/yapplabs/ember-modal-dialog/pull/230) ([BryanCrotaz](https://github.com/BryanCrotaz))

## [v2.4.0](https://github.com/yapplabs/ember-modal-dialog/tree/v2.4.0) (2017-11-21)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v2.3.0...v2.4.0)

**Merged pull requests:**

- Add ember-cli-version-checker as a dep [\#222](https://github.com/yapplabs/ember-modal-dialog/pull/222) ([samselikoff](https://github.com/samselikoff))
- Make optional dependencies section easier to read [\#220](https://github.com/yapplabs/ember-modal-dialog/pull/220) ([chrisvdp](https://github.com/chrisvdp))
- fix\(\#195\): provide default values for concatenatedProperties [\#217](https://github.com/yapplabs/ember-modal-dialog/pull/217) ([RustyToms](https://github.com/RustyToms))
- use new modules api [\#215](https://github.com/yapplabs/ember-modal-dialog/pull/215) ([Dhaulagiri](https://github.com/Dhaulagiri))
- Fixed formatting on `ember install ember-tether` [\#209](https://github.com/yapplabs/ember-modal-dialog/pull/209) ([djones](https://github.com/djones))
- keyboard example - use Ember best practice form instead of .on\(\) [\#208](https://github.com/yapplabs/ember-modal-dialog/pull/208) ([caseywatts](https://github.com/caseywatts))
- Update imports for newer Ember-cli [\#204](https://github.com/yapplabs/ember-modal-dialog/pull/204) ([mazondo](https://github.com/mazondo))

## [v2.3.0](https://github.com/yapplabs/ember-modal-dialog/tree/v2.3.0) (2017-06-23)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v2.2.0...v2.3.0)

**Merged pull requests:**

- Don't fail if ENV\['ember-modal-dialog'\] is not defined [\#202](https://github.com/yapplabs/ember-modal-dialog/pull/202) ([lukemelia](https://github.com/lukemelia))
- Pass `stack` and `value` properties through to liquid-wormhole/liquid-tether [\#201](https://github.com/yapplabs/ember-modal-dialog/pull/201) ([lukemelia](https://github.com/lukemelia))
- Fix modals in FastBoot [\#200](https://github.com/yapplabs/ember-modal-dialog/pull/200) ([sandydoo](https://github.com/sandydoo))
- Typo: missing comma [\#197](https://github.com/yapplabs/ember-modal-dialog/pull/197) ([jacobq](https://github.com/jacobq))

## [v2.2.0](https://github.com/yapplabs/ember-modal-dialog/tree/v2.2.0) (2017-05-15)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v2.1.0...v2.2.0)

**Merged pull requests:**

- Make modal-dialog component animatable via liquid-fire [\#193](https://github.com/yapplabs/ember-modal-dialog/pull/193) ([lukemelia](https://github.com/lukemelia))
- Add support for an `overlayPosition` property which supports values of `'parent'` or `'sibling'` [\#192](https://github.com/yapplabs/ember-modal-dialog/pull/192) ([lukemelia](https://github.com/lukemelia))
- Allow specifying `hasOverlay=false` to suppress output of the overlay div. [\#191](https://github.com/yapplabs/ember-modal-dialog/pull/191) ([lukemelia](https://github.com/lukemelia))
- Minor README cleanup [\#190](https://github.com/yapplabs/ember-modal-dialog/pull/190) ([lukemelia](https://github.com/lukemelia))

## [v2.1.0](https://github.com/yapplabs/ember-modal-dialog/tree/v2.1.0) (2017-05-14)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v2.0.0...v2.1.0)

**Merged pull requests:**

- Detect ember-tether and throw an error early if not present and tetherTarget is passed. [\#189](https://github.com/yapplabs/ember-modal-dialog/pull/189) ([lukemelia](https://github.com/lukemelia))
- Make tests more robust with waitUntil [\#188](https://github.com/yapplabs/ember-modal-dialog/pull/188) ([lukemelia](https://github.com/lukemelia))
- Simplify dummy app a bit [\#187](https://github.com/yapplabs/ember-modal-dialog/pull/187) ([lukemelia](https://github.com/lukemelia))
- Unify `modal-dialog` and `tether-dialog` into one `modal-dialog` component [\#186](https://github.com/yapplabs/ember-modal-dialog/pull/186) ([lukemelia](https://github.com/lukemelia))
- Replace `modal-dialog-overlay` component with a div and deprecate it. [\#185](https://github.com/yapplabs/ember-modal-dialog/pull/185) ([lukemelia](https://github.com/lukemelia))
- Update title of dummy app [\#184](https://github.com/yapplabs/ember-modal-dialog/pull/184) ([lukemelia](https://github.com/lukemelia))
- Rename `close` action to `onClose` and deprecate `close`. [\#183](https://github.com/yapplabs/ember-modal-dialog/pull/183) ([lukemelia](https://github.com/lukemelia))
- Switch dummy app/tests to use routes instead of query params [\#182](https://github.com/yapplabs/ember-modal-dialog/pull/182) ([lukemelia](https://github.com/lukemelia))
- install was installed inadvertently, so let's uninstall the inadvertent install of install [\#181](https://github.com/yapplabs/ember-modal-dialog/pull/181) ([lukemelia](https://github.com/lukemelia))
- Use ember-native-dom-helpers and async/await [\#180](https://github.com/yapplabs/ember-modal-dialog/pull/180) ([lukemelia](https://github.com/lukemelia))
- Upgrade ember-cli, ember-cli-babel, and friends [\#179](https://github.com/yapplabs/ember-modal-dialog/pull/179) ([lukemelia](https://github.com/lukemelia))
- Use camelCase properties, deprecate public kebab case properties [\#178](https://github.com/yapplabs/ember-modal-dialog/pull/178) ([lukemelia](https://github.com/lukemelia))

## [v2.0.0](https://github.com/yapplabs/ember-modal-dialog/tree/v2.0.0) (2017-05-12)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v2.0.0-beta.0...v2.0.0)

**Merged pull requests:**

- Update to Babel 6. [\#175](https://github.com/yapplabs/ember-modal-dialog/pull/175) ([rwjblue](https://github.com/rwjblue))

## [v2.0.0-beta.0](https://github.com/yapplabs/ember-modal-dialog/tree/v2.0.0-beta.0) (2017-04-05)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v1.0.0...v2.0.0-beta.0)

**Merged pull requests:**

- Update ember-cli and other tooling dependencies. [\#174](https://github.com/yapplabs/ember-modal-dialog/pull/174) ([lukemelia](https://github.com/lukemelia))
- Update ember-wormhole dependency and ember-tether devDependency [\#173](https://github.com/yapplabs/ember-modal-dialog/pull/173) ([lukemelia](https://github.com/lukemelia))
- Drop support for Ember versions older than 2.4 [\#172](https://github.com/yapplabs/ember-modal-dialog/pull/172) ([lukemelia](https://github.com/lukemelia))

## [v1.0.0](https://github.com/yapplabs/ember-modal-dialog/tree/v1.0.0) (2017-04-05)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.9.1...v1.0.0)

**Merged pull requests:**

- Use Chrome in CI. [\#171](https://github.com/yapplabs/ember-modal-dialog/pull/171) ([lukemelia](https://github.com/lukemelia))
- \[BREAKING\] Change default scss to use static positioning for render in place. [\#169](https://github.com/yapplabs/ember-modal-dialog/pull/169) ([andrewhavens](https://github.com/andrewhavens))
- Use yarn for dependency management [\#168](https://github.com/yapplabs/ember-modal-dialog/pull/168) ([andrewhavens](https://github.com/andrewhavens))
- Add ability to specify a callback that is triggered when overlay is clicked. [\#167](https://github.com/yapplabs/ember-modal-dialog/pull/167) ([andrewhavens](https://github.com/andrewhavens))
- Check for Ember version with new ember-cli-version-checker API. [\#166](https://github.com/yapplabs/ember-modal-dialog/pull/166) ([dan-ste](https://github.com/dan-ste))

## [v0.9.1](https://github.com/yapplabs/ember-modal-dialog/tree/v0.9.1) (2017-02-14)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.9.0...v0.9.1)

**Merged pull requests:**

- Touch event handling on IOS for clickOutsideToClose [\#161](https://github.com/yapplabs/ember-modal-dialog/pull/161) ([Chee7ah](https://github.com/Chee7ah))
- Add element center to positioned container [\#144](https://github.com/yapplabs/ember-modal-dialog/pull/144) ([wandertosee](https://github.com/wandertosee))
- Register unique clickOutsideToClose click handlers [\#129](https://github.com/yapplabs/ember-modal-dialog/pull/129) ([oscarni](https://github.com/oscarni))

## [v0.9.0](https://github.com/yapplabs/ember-modal-dialog/tree/v0.9.0) (2016-08-19)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.8.8...v0.9.0)

**Merged pull requests:**

- Support unit and integration tests out of the box. [\#142](https://github.com/yapplabs/ember-modal-dialog/pull/142) ([blimmer](https://github.com/blimmer))
- Update README to change usage of `ember-key-responder` to `ember-keyboard` [\#141](https://github.com/yapplabs/ember-modal-dialog/pull/141) ([SaladFork](https://github.com/SaladFork))
- Update ember-cli and use ember try's versionCompatibility [\#136](https://github.com/yapplabs/ember-modal-dialog/pull/136) ([lukemelia](https://github.com/lukemelia))

## [v0.8.8](https://github.com/yapplabs/ember-modal-dialog/tree/v0.8.8) (2016-07-13)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.8.7...v0.8.8)

**Merged pull requests:**

- Move back to ember-wormhole 0.3.6 to retain support for older Ember versions [\#135](https://github.com/yapplabs/ember-modal-dialog/pull/135) ([lukemelia](https://github.com/lukemelia))

## [v0.8.7](https://github.com/yapplabs/ember-modal-dialog/tree/v0.8.7) (2016-07-12)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.8.6...v0.8.7)

**Merged pull requests:**

- Avoid deprecation warning by updating ember-cli-htmlbars [\#134](https://github.com/yapplabs/ember-modal-dialog/pull/134) ([mdentremont](https://github.com/mdentremont))

## [v0.8.6](https://github.com/yapplabs/ember-modal-dialog/tree/v0.8.6) (2016-07-05)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.8.5...v0.8.6)

**Merged pull requests:**

- Bump ember-cli-htmlbars to 1.0.3 [\#123](https://github.com/yapplabs/ember-modal-dialog/pull/123) ([sohara](https://github.com/sohara))

## [v0.8.5](https://github.com/yapplabs/ember-modal-dialog/tree/v0.8.5) (2016-06-22)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.8.4...v0.8.5)

**Merged pull requests:**

- Call `this.\_super.init` to avoid ember-cli deprecation [\#132](https://github.com/yapplabs/ember-modal-dialog/pull/132) ([ascot21](https://github.com/ascot21))

## [v0.8.4](https://github.com/yapplabs/ember-modal-dialog/tree/v0.8.4) (2016-05-11)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.8.3...v0.8.4)

**Merged pull requests:**

- Improve tether-dialog positioning [\#128](https://github.com/yapplabs/ember-modal-dialog/pull/128) ([chrislopresto](https://github.com/chrislopresto))
- Update ember-tether version [\#126](https://github.com/yapplabs/ember-modal-dialog/pull/126) ([chrislopresto](https://github.com/chrislopresto))
- Added link to introduction video [\#118](https://github.com/yapplabs/ember-modal-dialog/pull/118) ([taras](https://github.com/taras))
- Fixes ember-try dependency for ember 1.13.10 [\#117](https://github.com/yapplabs/ember-modal-dialog/pull/117) ([jeremywrowe](https://github.com/jeremywrowe))

## [v0.8.3](https://github.com/yapplabs/ember-modal-dialog/tree/v0.8.3) (2015-12-22)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.8.2...v0.8.3)

**Merged pull requests:**

- Perform a big JSCS suave cleanup [\#110](https://github.com/yapplabs/ember-modal-dialog/pull/110) ([chrislopresto](https://github.com/chrislopresto))
- Add tether-dialog `constraints` property [\#109](https://github.com/yapplabs/ember-modal-dialog/pull/109) ([chrislopresto](https://github.com/chrislopresto))
- update suave so tests pass on master [\#108](https://github.com/yapplabs/ember-modal-dialog/pull/108) ([hmcq6](https://github.com/hmcq6))
- Fixing a small typo. [\#91](https://github.com/yapplabs/ember-modal-dialog/pull/91) ([kiwiupover](https://github.com/kiwiupover))

## [v0.8.2](https://github.com/yapplabs/ember-modal-dialog/tree/v0.8.2) (2015-10-26)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.8.1...v0.8.2)

**Merged pull requests:**

- Update to Ember CLI 1.13.8 [\#90](https://github.com/yapplabs/ember-modal-dialog/pull/90) ([chrislopresto](https://github.com/chrislopresto))

## [v0.8.1](https://github.com/yapplabs/ember-modal-dialog/tree/v0.8.1) (2015-09-19)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.8.0...v0.8.1)

**Merged pull requests:**

- add additional learning resource [\#85](https://github.com/yapplabs/ember-modal-dialog/pull/85) ([jeffreybiles](https://github.com/jeffreybiles))
- Made the initializer ember 1.13/2.0/2.1 friendly [\#82](https://github.com/yapplabs/ember-modal-dialog/pull/82) ([toranb](https://github.com/toranb))

## [v0.8.0](https://github.com/yapplabs/ember-modal-dialog/tree/v0.8.0) (2015-09-10)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.7.7...v0.8.0)

**Merged pull requests:**

- Create separate modal-dialog and tether-dialog components [\#79](https://github.com/yapplabs/ember-modal-dialog/pull/79) ([chrislopresto](https://github.com/chrislopresto))
- Update css for center scrolling example [\#74](https://github.com/yapplabs/ember-modal-dialog/pull/74) ([samselikoff](https://github.com/samselikoff))
- Make centered scrolling example work [\#73](https://github.com/yapplabs/ember-modal-dialog/pull/73) ([sandstrom](https://github.com/sandstrom))
- introduce ember-suave [\#72](https://github.com/yapplabs/ember-modal-dialog/pull/72) ([raycohen](https://github.com/raycohen))

## [v0.7.7](https://github.com/yapplabs/ember-modal-dialog/tree/v0.7.7) (2015-08-04)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.7.6...v0.7.7)

**Merged pull requests:**

- refactor `updateAlignment` to make it clear what the different paths are [\#66](https://github.com/yapplabs/ember-modal-dialog/pull/66) ([raycohen](https://github.com/raycohen))
- assert that specified alignment target exists [\#65](https://github.com/yapplabs/ember-modal-dialog/pull/65) ([kagemusha](https://github.com/kagemusha))
- Adds the ability to close when clicking anywhere outside the modal without an overlay [\#59](https://github.com/yapplabs/ember-modal-dialog/pull/59) ([kellyselden](https://github.com/kellyselden))
- Add version check for minimum ember-cli version [\#56](https://github.com/yapplabs/ember-modal-dialog/pull/56) ([lukemelia](https://github.com/lukemelia))

## [v0.7.6](https://github.com/yapplabs/ember-modal-dialog/tree/v0.7.6) (2015-07-27)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.7.5...v0.7.6)

**Merged pull requests:**

- Upgrade to ember-cli 1.13.1 [\#63](https://github.com/yapplabs/ember-modal-dialog/pull/63) ([chrislopresto](https://github.com/chrislopresto))
- Respect MODAL\_DIALOG\_USE\_TETHER application property [\#62](https://github.com/yapplabs/ember-modal-dialog/pull/62) ([chrislopresto](https://github.com/chrislopresto))
- Generate a changelog [\#61](https://github.com/yapplabs/ember-modal-dialog/pull/61) ([mike-north](https://github.com/mike-north))
- Make overlay clicks work on iOS automatically by adding `cursor: pointer` to the overlay div. [\#60](https://github.com/yapplabs/ember-modal-dialog/pull/60) ([lukemelia](https://github.com/lukemelia))
- Add a changelog. [\#54](https://github.com/yapplabs/ember-modal-dialog/pull/54) ([blimmer](https://github.com/blimmer))

## [v0.7.5](https://github.com/yapplabs/ember-modal-dialog/tree/v0.7.5) (2015-06-25)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.7.4...v0.7.5)

**Merged pull requests:**

- Pass through additional ember-tether options [\#49](https://github.com/yapplabs/ember-modal-dialog/pull/49) ([chrislopresto](https://github.com/chrislopresto))

## [v0.7.4](https://github.com/yapplabs/ember-modal-dialog/tree/v0.7.4) (2015-06-19)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.7.3...v0.7.4)

**Merged pull requests:**

- Allow 2.0.0-beta's to use current templates. [\#44](https://github.com/yapplabs/ember-modal-dialog/pull/44) ([rwjblue](https://github.com/rwjblue))

## [v0.7.3](https://github.com/yapplabs/ember-modal-dialog/tree/v0.7.3) (2015-06-19)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.7.2...v0.7.3)

**Merged pull requests:**

- Swap the modal-dialog template based on Ember version. [\#43](https://github.com/yapplabs/ember-modal-dialog/pull/43) ([rwjblue](https://github.com/rwjblue))

## [v0.7.2](https://github.com/yapplabs/ember-modal-dialog/tree/v0.7.2) (2015-05-31)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.7.1...v0.7.2)

## [v0.7.1](https://github.com/yapplabs/ember-modal-dialog/tree/v0.7.1) (2015-05-24)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.7.0...v0.7.1)

**Merged pull requests:**

- When `renderInPlace` is true, do not use tether or do any positioning [\#36](https://github.com/yapplabs/ember-modal-dialog/pull/36) ([lukemelia](https://github.com/lukemelia))

## [v0.7.0](https://github.com/yapplabs/ember-modal-dialog/tree/v0.7.0) (2015-05-19)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.6.0...v0.7.0)

**Merged pull requests:**

- Use ember-tether for modal positioning [\#35](https://github.com/yapplabs/ember-modal-dialog/pull/35) ([chrislopresto](https://github.com/chrislopresto))
- Clarifies the close action's functionality in the documentation [\#32](https://github.com/yapplabs/ember-modal-dialog/pull/32) ([pzuraq](https://github.com/pzuraq))
- Guard against `document` being undefined. [\#31](https://github.com/yapplabs/ember-modal-dialog/pull/31) ([rwjblue](https://github.com/rwjblue))
- Remove public [\#30](https://github.com/yapplabs/ember-modal-dialog/pull/30) ([sandstrom](https://github.com/sandstrom))

## [v0.6.0](https://github.com/yapplabs/ember-modal-dialog/tree/v0.6.0) (2015-05-05)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.5.0...v0.6.0)

**Merged pull requests:**

- Add modal-dialog service with `destinationElementId` for easier subclassing [\#28](https://github.com/yapplabs/ember-modal-dialog/pull/28) ([rlivsey](https://github.com/rlivsey))
- Improve routable usage info. [\#27](https://github.com/yapplabs/ember-modal-dialog/pull/27) ([pedrokiefer](https://github.com/pedrokiefer))
- Component unit test example [\#20](https://github.com/yapplabs/ember-modal-dialog/pull/20) ([varblob](https://github.com/varblob))

## [v0.5.0](https://github.com/yapplabs/ember-modal-dialog/tree/v0.5.0) (2015-04-28)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.4.1...v0.5.0)

**Merged pull requests:**

- Wormhole-less Modals [\#26](https://github.com/yapplabs/ember-modal-dialog/pull/26) ([chrislopresto](https://github.com/chrislopresto))
- Add an alignment css class to the positioned div [\#25](https://github.com/yapplabs/ember-modal-dialog/pull/25) ([lukemelia](https://github.com/lukemelia))
- Fix typo: modals-overlay =\> modal-overlays [\#23](https://github.com/yapplabs/ember-modal-dialog/pull/23) ([balinterdi](https://github.com/balinterdi))
- Update install instructions for Ember CLI 0.2.3 [\#21](https://github.com/yapplabs/ember-modal-dialog/pull/21) ([balinterdi](https://github.com/balinterdi))

## [v0.4.1](https://github.com/yapplabs/ember-modal-dialog/tree/v0.4.1) (2015-04-25)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.4.0...v0.4.1)

## [v0.4.0](https://github.com/yapplabs/ember-modal-dialog/tree/v0.4.0) (2015-04-17)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.3.0...v0.4.0)

## [v0.3.0](https://github.com/yapplabs/ember-modal-dialog/tree/v0.3.0) (2015-04-13)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.2.2...v0.3.0)

**Merged pull requests:**

- Introduced overlay-class and container-class attributes. [\#18](https://github.com/yapplabs/ember-modal-dialog/pull/18) ([lukemelia](https://github.com/lukemelia))
- Allow alignmentTarget to be specified as a reference to an Ember View or a DOM element in addition to a selector. [\#16](https://github.com/yapplabs/ember-modal-dialog/pull/16) ([lukemelia](https://github.com/lukemelia))

## [v0.2.2](https://github.com/yapplabs/ember-modal-dialog/tree/v0.2.2) (2015-04-11)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/v0.2.1...v0.2.2)

## [v0.2.1](https://github.com/yapplabs/ember-modal-dialog/tree/v0.2.1) (2015-04-10)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/0.2.0...v0.2.1)

**Merged pull requests:**

- Remove orphan overlay component [\#13](https://github.com/yapplabs/ember-modal-dialog/pull/13) ([olivia](https://github.com/olivia))
- Updating ember-cli version to fix build errors on windows [\#12](https://github.com/yapplabs/ember-modal-dialog/pull/12) ([olivia](https://github.com/olivia))
- Clarify key-responder is about keyboard shortcuts [\#10](https://github.com/yapplabs/ember-modal-dialog/pull/10) ([samselikoff](https://github.com/samselikoff))

## [0.2.0](https://github.com/yapplabs/ember-modal-dialog/tree/0.2.0) (2015-04-05)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/0.1.0...0.2.0)

**Merged pull requests:**

- Test against 1.10 through beta [\#7](https://github.com/yapplabs/ember-modal-dialog/pull/7) ([ef4](https://github.com/ef4))
- Drop unused ember-data dependency [\#6](https://github.com/yapplabs/ember-modal-dialog/pull/6) ([ef4](https://github.com/ef4))
- Use Ember.observer and Ember.on instead of function prototype equivalents [\#4](https://github.com/yapplabs/ember-modal-dialog/pull/4) ([lukemelia](https://github.com/lukemelia))

## [0.1.0](https://github.com/yapplabs/ember-modal-dialog/tree/0.1.0) (2015-03-26)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/0.0.3...0.1.0)

**Merged pull requests:**

- Metal Modal Approach [\#2](https://github.com/yapplabs/ember-modal-dialog/pull/2) ([chrislopresto](https://github.com/chrislopresto))

## [0.0.3](https://github.com/yapplabs/ember-modal-dialog/tree/0.0.3) (2014-11-14)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/0.0.2...0.0.3)

## [0.0.2](https://github.com/yapplabs/ember-modal-dialog/tree/0.0.2) (2014-10-12)
[Full Changelog](https://github.com/yapplabs/ember-modal-dialog/compare/0.0.1...0.0.2)

## [0.0.1](https://github.com/yapplabs/ember-modal-dialog/tree/0.0.1) (2014-10-05)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*