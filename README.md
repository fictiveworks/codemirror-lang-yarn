# Yarn Grammar for CodeMirror

This is a [CodeMirror](https://codemirror.net/6/) language support package for the dialog format used by [YarnSpinner](http://yarnspinner.dev/).

## Specification

Yarn has a [language specification for V2](https://github.com/YarnSpinnerTool/YarnSpinner/blob/e600560302b33d955e33b981d51f8d8c75ebaa81/Documentation/Yarn-Spec.md) of the text format.

## ~~Compile the Grammar~~

```
npm run prepare
```

## ~~Tests~~

Tests are bootstrapped from the CodeMirror 6 utilities using a text-file format for declaring test fixtures. Each fixture is an example syntax fragment followed by the expected syntax tree for the fragment.

Run all tests with the following command:

```
npm test
```

## License

MIT. See the license file included with this software distribution.
