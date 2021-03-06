# Changelog

## 0.11.0

* Ignore typescript test files

## 0.10.4

* Bump lodash because vulnerability

## 0.10.3

* Added a before each hook to the tests

## 0.10.2

* Added `coverage/*` to `.npmignore`
* Added `.eslintignore` to `.npmignore`
* Added `.eslintrc.js` to `.npmignore`
* Added `.vscode/settings.json` to `.npmignore`

## 0.10.1

* Added `test/*` to `.npmignore`

## 0.10.0

* Added typescript files to the walker whitelist `.ts` and `.tsx`

## 0.9.0

* Array of objects now work correctly
* Array of strings now work correctly

## 0.8.0

* Fixed crash for JSX in ternary operators
* Ignoring dangerouslySetInnerHtml and src attributes

## 0.7.1

* Added to JSXAttributes to blacklist `className`, `color`, `href`, `as`
* Only traverse the source dir

## 0.7.0

* Babel generator now tries to maintain lines (`retainLines`)
* Babel generator now retains function parenthesis. (`retainFunctionParens`)
* Ignore things in react router (path, from, to)
* Ignore things inside any an object or JSX named style
* Added test for nested identifiers
* Added array of objects in aspirational testing
* Added change log

## 0.6.1

* Dont replace ternaries outside JSX
* Added another troubleshooting tip

## 0.6.0

* Support for ternary operators
* Ignore `<style jsx>{'.some-class{background:'white';}'}</style>`

## 0.5.0

* Added trouble shooting advice in README.md
* Now accepting src dir in process argv
* A dry run support (Babel parses and generates the code again without changing anything)
* Added support for multiline values
* Added more aspirational test cases

## 0.4.0

* Fixed template literal in regression testing

## 0.3.1

* Added keywords in package.json

## 0.3.0

* Overhauled identifier filtering
* Support let assignments
* Fixed key extractor regex
* Add some aspirational test cases

## 0.2.0

* Ignore file if unable to parse
* Added support for experimental class properties
* Some inline documentation

## 0.1.0 (Initial public release)

* Added fixtures testing
* Replace all JSXText with i18n bindings
* All Identifiers used inside JSX elements should be translated
* Idempotence
* Dont import i18n if there is nothing to translate
* Dont import i18n if nothing changed (idempotence)
* Support for interpolated strings