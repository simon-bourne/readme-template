# Handlebars CLI Ext

A really simple CLI wrapper around the [handlebars](https://crates.io/handlebars) crate with some extra helpers:

- `{{ include "my-file.txt" }}`: include the contents of `my-file.txt`
- `{{ shell "ls -l" }}`: Run `ls -l` and include the captured stdout

## Install

```bash
cargo install handlebars-cli-ext
```

## Run

```bash
handlebars-cli-ext < input.tmpl > output.txt
```
