# Changelog

### 0.2.0

- Add `hlsl`, `asm` (x86 Assembly), `m` (Matlab), `sas`, `d`, `dart`, `plsql`, `logo`, , `pas` (Object Pascal/Delphi), `cobol`, `kt` (Kotlin), `scala`, `abap`, `julia`, `scheme`, `prolog`, `ada`, `lisp`, `apex`, `fortran`, `haskell`, `hcl`, `hack`, `awk`, `as` (ActionScript), `tcl`, `ocaml`, `viml`, `puppet`, `jsonnet`, `smalltalk`, `cr` (Crystal), `wat` (WASM), `nix`, `elm`, `purescript`, `svelte`.
- Add `pug` language and make `jade` an alias of it.
- Use GitHub workflow to update grammars periodically. [#72](https://github.com/shikijs/shiki/issues/72).
- Use GitHub workflow to update themes periodically. [#71](https://github.com/shikijs/shiki/issues/71).
- Use theme foreground color when color of token is `undefined`. [#27](https://github.com/shikijs/shiki/issues/27).
- SVG Renderer. [#2](https://github.com/shikijs/shiki/issues/2).
- Fix HTML escaping. [#26](https://github.com/octref/shiki/issues/26) and [#28](https://github.com/octref/shiki/pull/28). Thanks to contribution from [@jackens](https://github.com/jackens).
- 🙌 Add an option to skip generating the explanation text. [#52](https://github.com/shikijs/shiki/pull/52). Thanks to contribution from [Gerrit Birkeland](https://github.com/Gerrit0).
- 🙌 Improve performance by avoiding some unnecessary string copies. [#51](https://github.com/shikijs/shiki/pull/51). Thanks to contribution from [Gerrit Birkeland](https://github.com/Gerrit0).
- 🙌 Allow loading custom `tmLanguage`. [#10](https://github.com/octref/shiki/issues/10) and [#49](https://github.com/octref/shiki/pull/49). Thanks to contribution from [Orta Therox](https://github.com/orta) and [@pngwn](https://github.com/pngwn).
- 🙌 Update Java grammar. [#36](https://github.com/octref/shiki/issues/36) and [#37](https://github.com/octref/shiki/issues/37). Thanks to contribution from [@0xflotus](https://github.com/0xflotus).

### 0.1.7 | 2020-04-28

- Update to latest Dark+/Light+ theme from VS Code.

### 0.1.6 | 2019-09-19

- Add `toml` language from https://github.com/bungcip/better-toml. [#20](https://github.com/octref/shiki/issues/20).

### 0.1.5 | 2019-09-09

- Begin to keep a changelog. [#7](https://github.com/octref/shiki/issues/7).
- Accept `plaintext`, `text` and `txt` as `lang`. Will return `code` as it is. [#16](https://github.com/octref/shiki/issues/16).
- Add `jsonc` language. [#18](https://github.com/octref/shiki/issues/18).
- Add `csharp` language. [#14](https://github.com/octref/shiki/issues/14).
- Add `md` as an alias for `markdown`.
- Add `zsh` as an alias for `bash`.
- Add `yml` as an alias for `yaml`.
- 🙌 Use json5 for parsing theme as JSONC. [#11](https://github.com/octref/shiki/issues/11). Thanks to contribution from [Wes Bos](https://github.com/wesbos).