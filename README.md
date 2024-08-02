---

# Markdown Tutorial

## What is Markdown?

Markdown is a lightweight markup language with plain-text formatting syntax. It's often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

## Basic Syntax

### Headings

You can create headings by starting a line with one or more `#` symbols, followed by a space. The number of `#` symbols corresponds to the heading level.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

### Emphasis

You can emphasize text by making it bold or italic.

- **Bold**: Use `**` or `__` to enclose the text.
- *Italic*: Use `*` or `_` to enclose the text.
- ***Bold and Italic***: Use a combination of both.

```markdown
**This is bold text**
__This is also bold text__

*This is italic text*
_This is also italic text_

***This is bold and italic text***
___This is also bold and italic text___
```

### Lists

#### Unordered List

Use `-`, `+`, or `*` followed by a space.

```markdown
- Item 1
- Item 2
  - Subitem 1
  - Subitem 2
```

#### Ordered List

Use numbers followed by a period and a space.

```markdown
1. Item 1
2. Item 2
   1. Subitem 1
   2. Subitem 2
```

### Links

Create links by placing the link text in brackets `[]`, followed by the URL in parentheses `()`.

```markdown
[OpenAI](https://www.openai.com)
```

### Images

Similar to links, but with an exclamation mark `!` at the beginning.

```markdown
![Alt text](https://www.example.com/image.jpg)
```

### Blockquotes

Use the `>` symbol followed by a space.

```markdown
> This is a blockquote.
```

### Code

#### Inline Code

Use backticks `` ` `` to enclose inline code.

```markdown
Here is some `inline code`.
```

#### Code Blocks

Use triple backticks ``` ``` ``` or indent lines with four spaces.

<pre>
```python
def hello_world():
    print("Hello, World!")
```
</pre>

### Horizontal Rules

Create horizontal rules with three or more `-`, `*`, or `_` symbols.

```markdown
---
***
___
```

### Tables

Tables are created using pipes `|` and dashes `-`. The colons `:` can be used to align columns.

```markdown
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

| Left-aligned | Center-aligned | Right-aligned |
|:-------------|:--------------:|--------------:|
| col 1 is     | some text      | right aligned |
| col 2 is     | centered       | $10           |
| zebra stripes| are neat       | $20           |
```

---

That's a basic overview of Markdown. It covers most of what you'll need for everyday writing and formatting. If you have any specific questions or need more advanced features, feel free to ask!