# jackdaw-template-game

A [cargo-generate](https://cargo-generate.github.io/cargo-generate/)
template for creating a [jackdaw](https://github.com/jbuehler23/jackdaw)
game project.

## Usage

Via Bevy CLI (preferred):

```sh
bevy new my_game -t https://github.com/jbuehler23/jackdaw_template_game
```

Via cargo-generate directly:

```sh
cargo generate --git https://github.com/jbuehler23/jackdaw_template_game --name my_game
```

Either command produces a new directory `my_game/` containing a
minimal jackdaw game project ready to build.

## Status

Play-in-Editor (PIE) support is under active construction in
jackdaw. Until PIE lands, this template scaffolds a project that
loads as an editor extension so you can start prototyping against
the editor's scene. Migration to PIE semantics will be a one-line
change once the runtime ships; the generated project is
structured to make that cheap.

See the [jackdaw docs](https://github.com/jbuehler23/jackdaw/tree/main/book/src/developer-guide/extending-the-editor.md)
for the current authoring workflow.

## License

Dual-licensed under MIT and Apache-2.0 to match jackdaw's own
licensing. Scaffolded projects are yours — pick any license you
like.
