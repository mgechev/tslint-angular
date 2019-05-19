# Angular TSLint Preset

A preset with TSLint rules for development of Angular applications. The preset contains both, tslint core rules, and [codelyzer](https://github.com/mgechev/codelyzer) rules, which are going to perform Angular specific linting.

This package is based on the tslint configuration of [Angular CLI](https://github.com/angular/angular-cli) and aligns with the [Angular style guide](https://angular.io/guide/styleguide).

**Note:** there are few more rules added on top of the Angular CLI configuration.

## How to use?

```bash
npm i tslint-angular --save-dev
```

After that configure `tslint.json` to use the preset:

```json
{
  "extends": ["tslint-angular"],
  "rules": {
    "directive-selector": [true, "attribute", "foo", "camelCase"],
    "component-selector": [true, "element", "foo", "kebab-case"]
  }
}
```

**Notice** that `directive-selector` and `component-selector` are configurable so you need to add them manually in the `rules` section of `tslint.json`.

## License

MIT

