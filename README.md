# NoSelf Minimal Dark

A minimalistic, mobile-friendly Hugo theme

## Features

- Dark
- Minimalistic
- Responsive/mobile-first layout
- Minimal CSS and no JavaScript (except KaTeX for LaTeX formulas)
- Monospace font
- Responsive code blocks and tables

## Installation

Copy this directory into `themes/noself-minimal-dark`, then set:

```toml
theme = "noself-minimal-dark"
```

Enable math globally:

```toml
[params]
math = true
```

Or enable it for an individual page:

```yaml
---
title: "A post with math"
math: true
---
```

Math examples:

Inline: `\(E = mc^2\)`

Display:

```text
$$
\int_0^\infty e^{-x^2}\,dx = \frac{\sqrt{\pi}}{2}
$$
```

## Example config

See `exampleSite/config.toml`.
