# Angular TSLint Preset

A preset with TSLint rules for development of Angular applications. The preset contains both, tslint core rules, and [codelyzer](https://github.com/mgechev/codelyzer) rules, which are going to lint the templates of your Angular components.

The same set of rules is used by [@angular/cli](https://github.com/angular/angular-cli) and aligns with the [Angular style guide](https://angular.io/styleguide).

# How to use?

```bash
npm i tslint-angular --save-dev
```

After that configure tslint to use the preset:

```json
{
  "extends": ["tslint-angular"]
}
```

# License

MIT
