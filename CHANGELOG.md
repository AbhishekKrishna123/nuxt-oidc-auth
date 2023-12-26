# Changelog


## v0.2.0

[compare changes](https://github.com/itpropro/nuxt-oidc-auth/compare/6b924f7ea7037a3af861cbba82244892ff5e61f6...v0.2.0)

### 🚀 Enhancements

- **jwt:** ✨   Added optional token validation ([39fea17](https://github.com/itpropro/nuxt-oidc-auth/commit/39fea17))
- **validation:** ✨   Integrated token validation ([8481892](https://github.com/itpropro/nuxt-oidc-auth/commit/8481892))
- **session:** ✨   Implemented expiration check and automatic token refresh ([a039eec](https://github.com/itpropro/nuxt-oidc-auth/commit/a039eec))
- **config:** ✨   Improved typings, added providers, improved claim features ([7d0d9c2](https://github.com/itpropro/nuxt-oidc-auth/commit/7d0d9c2))
- **composables:** ✨   Added login, logout and renamed composable import ([37f38c3](https://github.com/itpropro/nuxt-oidc-auth/commit/37f38c3))
- **playground:** ✨   Updated playground, removed knitwork dep, type improvements ([5ea5845](https://github.com/itpropro/nuxt-oidc-auth/commit/5ea5845))
- **middleware:** ✨   Added optional global auth middleware ([35a6e54](https://github.com/itpropro/nuxt-oidc-auth/commit/35a6e54))

### 🩹 Fixes

- **build:** 💚   Fixed type imports that prevented a successful build ([9201cc3](https://github.com/itpropro/nuxt-oidc-auth/commit/9201cc3))

### 💅 Refactors

- **structure:** ♻️   Improved structure and type references ([5c11215](https://github.com/itpropro/nuxt-oidc-auth/commit/5c11215))
- **types:** 🏷️   Improved typings ([71e7fa2](https://github.com/itpropro/nuxt-oidc-auth/commit/71e7fa2))

### 📖 Documentation

- **readme:** ✏️   Updated README ([34c7bb3](https://github.com/itpropro/nuxt-oidc-auth/commit/34c7bb3))
- **readme:** ✏️   Updated README with secret and session information ([a89f655](https://github.com/itpropro/nuxt-oidc-auth/commit/a89f655))
- **readme:** ✏️   Added hint to not overwrite internal session properties ([c3c9daf](https://github.com/itpropro/nuxt-oidc-auth/commit/c3c9daf))

### ❤️ Contributors

- Jan-Henrik Damaschke ([@itpropro](http://github.com/itpropro))
- Itpropro ([@itpropro](http://github.com/itpropro))

## v0.0.13

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.12...v0.0.13)

### 🏡 Chore

- Rename session from verify to fetch ([10694e9](https://github.com/Atinux/nuxt-auth-utils/commit/10694e9))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.12

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.11...v0.0.12)

### 🩹 Fixes

- Correct arguments for hooks ([6e0193e](https://github.com/Atinux/nuxt-auth-utils/commit/6e0193e))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.11

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.10...v0.0.11)

### 🚀 Enhancements

- Add sessionHooks to extend user sessions ([c470319](https://github.com/Atinux/nuxt-auth-utils/commit/c470319))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.10

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.9...v0.0.10)

### 🚀 Enhancements

- Added linkedIn auth provider ([#13](https://github.com/Atinux/nuxt-auth-utils/pull/13))

### 🩹 Fixes

- Add audience to auth0 runtime config types ([#27](https://github.com/Atinux/nuxt-auth-utils/pull/27))

### 📖 Documentation

- Add LinkedIn in providers ([c9b9925](https://github.com/Atinux/nuxt-auth-utils/commit/c9b9925))

### 🏡 Chore

- Update deps ([bb3a510](https://github.com/Atinux/nuxt-auth-utils/commit/bb3a510))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- José Manuel Madriaza Caravia 
- H+ <serdar@justserdar.dev>

## v0.0.9

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.8...v0.0.9)

### 🚀 Enhancements

- Add max_age param for auth0 ([#26](https://github.com/Atinux/nuxt-auth-utils/pull/26))
- Added Microsoft as oauth provider ([#8](https://github.com/Atinux/nuxt-auth-utils/pull/8))

### ❤️ Contributors

- Jakub Frelik <j.frelik.it@outlook.com>
- Uģis ([@BerzinsU](http://github.com/BerzinsU))

## v0.0.8

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.7...v0.0.8)

### 🩹 Fixes

- Avoid infinite loop with latest Nuxt ([93b949d](https://github.com/Atinux/nuxt-auth-utils/commit/93b949d))

### 🏡 Chore

- **playground:** Better with right title ([97a3ad3](https://github.com/Atinux/nuxt-auth-utils/commit/97a3ad3))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.7

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.6...v0.0.7)

### 🩹 Fixes

- **oauth:** Add generic OAuthConfig type ([#18](https://github.com/Atinux/nuxt-auth-utils/pull/18))

### 📖 Documentation

- Use consistent reference to module ([13daa78](https://github.com/Atinux/nuxt-auth-utils/commit/13daa78))

### 🏡 Chore

- Add SameSite=lax ([1b296e2](https://github.com/Atinux/nuxt-auth-utils/commit/1b296e2))

### ❤️ Contributors

- Sigve Hansen ([@sifferhans](http://github.com/sifferhans))
- Daniel Roe <daniel@roe.dev>
- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.6

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.5...v0.0.6)

### 🚀 Enhancements

- Added discord auth provider ([#7](https://github.com/Atinux/nuxt-auth-utils/pull/7))
- Added oauth battle.net ([#11](https://github.com/Atinux/nuxt-auth-utils/pull/11))
- Refactor login buttons to use dropdown ([#14](https://github.com/Atinux/nuxt-auth-utils/pull/14))

### 🏡 Chore

- Update deps ([05f4a9c](https://github.com/Atinux/nuxt-auth-utils/commit/05f4a9c))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- Arash 
- Samuel LEFEVRE 
- H+ <serdar@darweb.nl>

## v0.0.5

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.4...v0.0.5)

### 🚀 Enhancements

- Added google as oauth provider ([#3](https://github.com/Atinux/nuxt-auth-utils/pull/3))
- Added twitch as supported oauth provider ([#5](https://github.com/Atinux/nuxt-auth-utils/pull/5))
- Added auth0 as oauth provider ([#6](https://github.com/Atinux/nuxt-auth-utils/pull/6))

### 💅 Refactors

- Use `useSession` generic rather than assertion ([#4](https://github.com/Atinux/nuxt-auth-utils/pull/4))

### 📖 Documentation

- Add demo ([cbc8b7a](https://github.com/Atinux/nuxt-auth-utils/commit/cbc8b7a))

### 🏡 Chore

- **release:** V0.0.4 ([2bc6f9a](https://github.com/Atinux/nuxt-auth-utils/commit/2bc6f9a))

### ❤️ Contributors

- Antoine Lassier <toinousp@gmail.com>
- Gerben Mulder ([@Gerbuuun](http://github.com/Gerbuuun))
- Ahmed Rangel ([@ahmedrangel](http://github.com/ahmedrangel))
- Akshara Hegde <akshara.dt@gmail.com>
- Sébastien Chopin ([@Atinux](http://github.com/Atinux))
- Daniel Roe ([@danielroe](http://github.com/danielroe))

## v0.0.4

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.3...v0.0.4)

### 🩹 Fixes

- Use import presets ([f16ebc9](https://github.com/Atinux/nuxt-auth-utils/commit/f16ebc9))

### 🏡 Chore

- **release:** V0.0.3 ([9d1342c](https://github.com/Atinux/nuxt-auth-utils/commit/9d1342c))
- Add comment ([1923dcc](https://github.com/Atinux/nuxt-auth-utils/commit/1923dcc))

### ❤️ Contributors

- Daniel Roe ([@danielroe](http://github.com/danielroe))
- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.3

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.2...v0.0.3)

### 🚀 Enhancements

- Allow users to define custom session factory + types ([#2](https://github.com/Atinux/nuxt-auth-utils/pull/2))

### 🩹 Fixes

- Don't log warning about password when preparing types ([804057b](https://github.com/Atinux/nuxt-auth-utils/commit/804057b))
- Import useRuntimeConfig ([bdbb4b8](https://github.com/Atinux/nuxt-auth-utils/commit/bdbb4b8))

### 🏡 Chore

- Remove `.nuxtrc` ([3f96e97](https://github.com/Atinux/nuxt-auth-utils/commit/3f96e97))
- Add type testing script ([e9ffa5e](https://github.com/Atinux/nuxt-auth-utils/commit/e9ffa5e))
- Move playground into workspace ([bd8108c](https://github.com/Atinux/nuxt-auth-utils/commit/bd8108c))
- Add playground type test ([74f452c](https://github.com/Atinux/nuxt-auth-utils/commit/74f452c))

### 🤖 CI

- Run lint + test actions in ci ([f50c1b5](https://github.com/Atinux/nuxt-auth-utils/commit/f50c1b5))

### ❤️ Contributors

- Daniel Roe ([@danielroe](http://github.com/danielroe))
- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

## v0.0.2

[compare changes](https://github.com/Atinux/nuxt-auth-utils/compare/v0.0.1...v0.0.2)

## v0.0.1


### 🩹 Fixes

- Workaround for addServerImportsDir not working ([5a189df](https://github.com/Atinux/nuxt-auth-utils/commit/5a189df))

### 📖 Documentation

- Update readme ([06f1504](https://github.com/Atinux/nuxt-auth-utils/commit/06f1504))

### 🏡 Chore

- Init ([19caed2](https://github.com/Atinux/nuxt-auth-utils/commit/19caed2))
- Add runtime config ([9013484](https://github.com/Atinux/nuxt-auth-utils/commit/9013484))
- V0 ([18ea43a](https://github.com/Atinux/nuxt-auth-utils/commit/18ea43a))
- Init ([9b75953](https://github.com/Atinux/nuxt-auth-utils/commit/9b75953))

### ❤️ Contributors

- Sébastien Chopin ([@Atinux](http://github.com/Atinux))

