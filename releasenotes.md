### v1.5.5
- updated client
- detectLng from route: detectLngFromPath index of route path, eg. 0 -> /en-US/myPage.html, 1 -> /cms/en-US/myPage.html
- addRoutes, eg. /en/introduction, /de/einfuehrung,..

### v1.5.0
- remove route added
- optional arg authenticated for postmissing, change, remove routes
- integrated i18next-webtranslate
- couchDb Backend

### v1.4.1
- post processing for translation
- updated client

### v1.4.0
- preload multiple languages
- translate key to other language than current
- updated client to 1.4.0
- added missing tests
- new documentation

### v1.3.4
- updated client
- fixed bug in update route

### v1.3.3

- fixed response type of post routes to json
- updated client

### v1.3.1

- debugging / logging
- updated client
- easier override for backend implementation

### v1.2.5

- added function to grap current language from template (i18n.lng())
- merged [pull request #15](https://github.com/jamuhl/i18next-node/pull/15) for express.js v3 support
- updated client

### v1.2.3 & v1.2.4

- updated client

### v1.2.0

- keep version in sync with clientside version
- better support to override default sync
- support for translation contexts
- fixed init without options, callback

### v0.5.0

- options saveMissing
- multiple plurals
- bug fix

### v0.0.1

- tests with mocha
- multi-namespace support
- loading files from filesystem
- clientscript support
- graceful fallback en-US -> en -> fallbackLng
- support for pluralized strings
- insertion of variables into translations
- translation nestingto translations