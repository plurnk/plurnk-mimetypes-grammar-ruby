# @plurnk/plurnk-mimetypes-grammar-ruby

Pre-built `tree-sitter-ruby` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-ruby
```

## what's in here

- **`ruby.wasm`** — pre-built from the pinned upstream [tree-sitter-ruby](https://github.com/tree-sitter/tree-sitter-ruby) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `ruby.wasm` is built from the upstream tree-sitter-ruby grammar; see the pinned commit for that project's attribution.
