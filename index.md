# Markdown CSS Preview Test

This page is a small visual test fixture for the Markdown preview styles.
The numbers below help verify the body font's tabular numerals: `0123456789`, `12.50`, and `2026-09-01`.

## Heading Levels

H2 text.

### Heading level 3

H3 text.

#### Heading level 4

H4 text.

##### Heading level 5

H5 text.

###### Heading level 6

The headings above should have distinct theme colors and regular or medium font weights.
The first `h1` should also have less top margin than later headings.

## Inline Typography

Inline `code` should use a monospace font, a smaller size, and a light background.
Use <kbd>Cmd</kbd> + <kbd>K</kbd> to test keyboard markup.

This sentence contains **bold Markdown**, __strong Markdown__, <b>an HTML b element</b>, and <strong>an HTML strong element</strong>.
These elements should use the reduced bold weight from the stylesheet.

## Code Block

```css
body {
    font-size: 14px;
    font-variant-numeric: tabular-nums;
}

code, kbd, pre {
    font-family: JetBrains Mono, Fira Code, monospace;
}
```

The fenced block should use the same monospace font family as inline code.

## Common Markdown Elements

- Unordered list item with `inline code`
- Another item with **emphasis**
- Final item with a number: 42

1. First ordered item
2. Second ordered item
3. Third ordered item

> This blockquote provides surrounding content for checking contrast and spacing.

[A sample link](https://example.com)

| Property | Value |
| --- | ---: |
| Font size | 14px |
| Line count | 27 |
| Test score | 100.00 |

---

End of the Markdown CSS preview test.
