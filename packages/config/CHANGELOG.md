# v0.1.6 (Wed Dec 02 2020)

#### 🐛 Bug Fix

- Fix loading of custom config files [#71](https://github.com/intuit/proof/pull/71) ([@adierkens](https://github.com/adierkens))
- Fix loading of custom config files ([@adierkens](https://github.com/adierkens))

#### Authors: 1

- Adam Dierkens ([@adierkens](https://github.com/adierkens))

---

# v0.1.3 (Tue Aug 11 2020)

#### 🐛 Bug Fix

- Update applitools version in the plugin [#52](https://github.com/intuit/proof/pull/52) ([@adierkens](https://github.com/adierkens))
- Update applitools to latest ([@adierkens](https://github.com/adierkens))

#### Authors: 1

- Adam Dierkens ([@adierkens](https://github.com/adierkens))

---

# v0.1.0 (Wed Jul 01 2020)

### Release Notes

_From #36_

**🔥 Breaking 🔥**
* Upgrades webdriverio to version 6 (up from 4). This includes changing the API for the `browser` object passed to tests. See https://v6.webdriver.io/ for API changes. 
* Removes the `@proof-ui/storybook` package and the configuration step. Stories are now gathered using storybook directly; and no changes or registration code is required from clients to run tests.
* Removes the inclusion of `power-assert` in favor of users providing their own assertion library. 

**Features**

* Add ability to change the name of the tests using the `test()` API. 


#### Internal Changes

- Updates all dependencies to latest versions
- Swap `xo` to `eslint`

Fixes #26 
Fixes #27

**Canary Release** - `0.0.21-canary.b590b95.0`

---

#### 🔨 Breaking Minor Change

- webdriverio upgrade [#36](https://github.com/intuit/proof/pull/36) ([@adierkens](https://github.com/adierkens))

#### 🐛 Bug Fix

- Add port to config ([@adierkens](https://github.com/adierkens))
- Get applitools plugin working ([@adierkens](https://github.com/adierkens))
- Swap to eslint. run prettier on everything ([@adierkens](https://github.com/adierkens))

#### Authors: 1

- Adam Dierkens ([@adierkens](https://github.com/adierkens))
