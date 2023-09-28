## SLIM quarto extension

This is a simple SLIM font extension to quarto. This extension was inspired by the [critic markup extension](https://github.com/mloubout/critic-markup) for [ScholarlyMarkdown](http://scholarlymarkdown.com/) available under [MIT license](https://github.com/mloubout/critic-markup/blob/main/LICENSE).

## Installing

```bash
quarto add ziyiyin97/SLIM
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

To use this extension, simply add it to your header as a filter

```yaml
---
title: Markup example
filters:
  - SLIM
---
```

## Example

Here is a minimal example showing the critic markup syntax and its rendering: [example.qmd](example.qmd).
