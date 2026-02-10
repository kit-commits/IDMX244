# Learn Markdown

Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. This guide will teach you the basics of Markdown syntax.

## Headings

You can create headings by using the `#` symbol. The number of `#` symbols indicates the heading level:

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

## Emphasis

You can add emphasis to text using asterisks or underscores:

- *Italic text* using `*italic*` or `_italic_`
- **Bold text** using `**bold**` or `__bold__`
- ***Bold and italic*** using `***bold and italic***`
- ~~Strikethrough~~ using `~~strikethrough~~`

## Lists

### Unordered Lists

Create unordered lists using `-`, `*`, or `+`:

```markdown
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
- Item 3
```

Result:
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
- Item 3

### Ordered Lists

Create ordered lists using numbers:

```markdown
1. First item
2. Second item
3. Third item
```

Result:
1. First item
2. Second item
3. Third item

## Links

Create links using `[link text](URL)`:

```markdown
[GitHub](https://github.com)
```

Result: [GitHub](https://github.com)

## Images

Add images using `![alt text](image URL)`:

```markdown
![Markdown Logo](https://markdown-here.com/img/icon256.png)
```

## Code

### Inline Code

Use backticks for inline code: `` `code` ``

Example: Use the `console.log()` function to print to the console.

### Code Blocks

Use triple backticks for code blocks:

````markdown
```
code block
```
````

You can specify a language for syntax highlighting:

````markdown
```javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
}
```
````

Result:
```javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
}
```

## Blockquotes

Create blockquotes using `>`:

```markdown
> This is a blockquote.
> It can span multiple lines.
```

Result:
> This is a blockquote.
> It can span multiple lines.

## Horizontal Rules

Create horizontal rules using three or more dashes, asterisks, or underscores:

```markdown
---
```

Result:

---

## Tables

Create tables using pipes and dashes:

```markdown
| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |
```

Result:

| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |

## Task Lists

Create task lists using `- [ ]` for unchecked and `- [x]` for checked items:

```markdown
- [x] Completed task
- [ ] Incomplete task
- [ ] Another incomplete task
```

Result:
- [x] Completed task
- [ ] Incomplete task
- [ ] Another incomplete task

## Paragraphs and Line Breaks

To create paragraphs, leave a blank line between blocks of text.

To create a line break, end a line with two or more spaces, or use a `<br>` tag.

## Escaping Characters

Use a backslash `\` to escape Markdown characters:

```markdown
\* This is not italic \*
```

Result: \* This is not italic \*

## Additional Resources

- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Flavored Markdown](https://github.github.com/gfm/)
- [Markdown Tutorial](https://www.markdowntutorial.com/)

---

*Happy Markdown writing!*
