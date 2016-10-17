# SublimeLinter Settings

[Website](http://www.sublimelinter.com/en/latest/)

The settings for SublimeLinter get built automatically, but for each linter that is installed, there are specific steps to get up and running for each respective linter.

## Installed Linters

### [SublimeLinter-csslint](https://github.com/SublimeLinter/SublimeLinter-csslint)

- Install `csslint` via `npm install -g csslint`.
- Ensure that it is available in the default $PATH.

### [SublimeLinter-contrib-eslint](https://packagecontrol.io/packages/SublimeLinter-contrib-eslint)

- install `eslint` via `npm install -g eslint`
- run `eslint --init` in your code folder or in your `~` folder.

> **Note**: I have included a default [`.eslintrc`](/packages/SublimeLinter/.eslintrc) file which I keep in `~` so that I am not "required" to init eslint on every project, but I still can if it is necessary.

### [SublimeLinter-php](https://github.com/SublimeLinter/SublimeLinter-php)

- Make sure that `php` is installed and available in the default $PATH.
