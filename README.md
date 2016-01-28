# pnpm

> High **p**erformance **npm**

pnpm is a fast implementation of `npm install`.

![](https://raw.githubusercontent.com/rstacruz/pnpm/gh-pages/screencast.gif)

[![Status](https://travis-ci.org/rstacruz/pnpm.svg?branch=master)](https://travis-ci.org/rstacruz/pnpm "See test builds")

## Install

Install it via npm.

```
npm install -g pnpm.js
```

Use `pnpm` in place of `npm`. It overrides `pnpm i` and `pnpm install`—all other commands will passthru to `npm`.

```
pnpm install lodash
```

## Preview release

`pnpm` will stay in `<1.0.0` until it's achieved feature parity with `npm install`.

- [ ] `pnpm install`
  - [x] npm packages
  - [ ] GitHub packages
  - [ ] @scoped modules
  - [ ] tarball packages
  - [ ] file packages
  - [ ] bin executables
  - [ ] `--global` installs
  - [ ] `--save` et al
- [ ] `pnpm uninstall`
- [ ] `pnpm ls`

## Acknowledgements

[ied](https://www.npmjs.com/package/ied) is built on a very similar premise.

## Thanks

**pnpm** © 2016+, Rico Sta. Cruz. Released under the [MIT] License.<br>
Authored and maintained by Rico Sta. Cruz with help from contributors ([list][contributors]).

> [ricostacruz.com](http://ricostacruz.com) &nbsp;&middot;&nbsp;
> GitHub [@rstacruz](https://github.com/rstacruz) &nbsp;&middot;&nbsp;
> Twitter [@rstacruz](https://twitter.com/rstacruz)

[MIT]: http://mit-license.org/
[contributors]: http://github.com/rstacruz/pnpm/contributors
