# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="1.0.0"></a>
# [1.0.0](https://github.com/paulgv/nuxt-i18n/compare/v0.1.0...v1.0.0) (2017-12-05)


### Features

* **refactor:** refactor module's code ([e4186dc](https://github.com/paulgv/nuxt-i18n/commit/e4186dc))


### BREAKING CHANGES

* **refactor:** Route generation utils have been renamed & the module doesn't register a vuex module anymore

- Replace all calls to getLocalizedRoute() with localePath()
- Replace all calls to getSwitchLocaleRoute() with switchLocalePath()
- Configured locales are now accessible in any component via `$i18n.locales`
- Similarly, default app locale can be accessed via `i18n.defaultLocale`
