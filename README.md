# Dart Hello World

Hello World example using the [Dart](https://www.dartlang.org) language.

## Running

First [install Dart](https://www.dartlang.org/install). On Mac OS X:

```
brew tap dart-lang/dart
brew install dart --with-content-shell --with-dartium
```

Build the client-side JavaScript bundle with:

```
dart2js --minify src/main.dart
```

Open `index.html` in a browser.

## Bundle size

```
$ js-size out.js
┌─────────────────┬─────────┐
│ Minified (gzip) │ 10.4 kB │
└─────────────────┴─────────┘
```

