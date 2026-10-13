# A Beginner's Guide to Markdown

**Author:** Kashif Sharma
**Student ID:** 991857768

Markdown is a lightweight markup language that adds formatting to plain text documents. You write normal text and add a few simple symbols to show which words should look different. Markdown is platform independent, so it works on any device and operating system. Websites like **GitHub** and **Reddit** support it, which is why it is used for `README.md` files.

This article explains the basic Markdown syntax. Each section shows the syntax first and then the result.

## 1. Headings

Headings are made with the `#` symbol. One `#` is the biggest heading, and each extra `#` makes the heading one level smaller.

```
# Heading Level 1
## Heading Level 2
### Heading Level 3
```

### This is a Level 3 heading

Every section title in this article is a heading.

## 2. Paragraphs

To create a paragraph, leave a blank line between lines of text.

This is the first paragraph.

This is the second paragraph.

## 3. Emphasis

### Bold

To make text bold, put two asterisks on each side: `**Hello World!**`

Result: **Hello World!**

### Italic

To make text italic, put one asterisk on each side: `*Hello World!*`

Result: *Hello World!*

### Bold and italic together

You can also use both in one sentence: `**Markdown** is *easy* to learn.`

Result: **Markdown** is *easy* to learn.

## 4. Block Quotes

To create a block quote, start the line with `>`. To have more than one paragraph inside the quote, put a `>` on the blank line between them.

```
> Hello World!
>
> World is a beautiful place!
```

Result:

> Hello World!
>
> World is a beautiful place!

## 5. Lists

### Ordered lists

Ordered lists use numbers followed by a period. To indent an item, add four spaces in front of it.

```
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item
```

Result:

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

### Unordered lists

Unordered lists use a dash `-` in front of each item. Indenting works the same way.

```
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
```

Result:

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

## 6. Code

To show a word or phrase as code, put backticks around it: `` `This is a code` ``

Result: `This is a code`

Code formatting is useful for commands, file names and keyboard keys, for example `git status`, `README.md` or `Ctrl + S`.

## 7. Links

To create a link, put the link text in square brackets, then the URL in parentheses right after it, with no space in between.

```
[Link to Markdown Guide](https://github.com/httpskashif07/Lab4-Working-With-Excel/edit/main/MarkdownArticle.md)
```

Result: [Link to MarkdownArticle]([https://www.markdownguide.org/basic-syntax/](https://github.com/httpskashif07/Lab4-Working-With-Excel/edit/main/MarkdownArticle.md))

## 7. Adding Image

To add an image, put an exclamation mark (!) before the square brackets, then write the image name inside the square brackets, followed by the image path in parentheses with no space in between.

```
![Link to Adding Image]("screenshots\01-install-module.png")
```

Result: ![Link to Adding Image](screenshots\01-install-module.png)


## 8. Tables

To create a table, use pipes `|` to separate the columns and three or more hyphens `---` under the header row. Colons in the hyphen row set the alignment:

- `:---` aligns the column to the left
- `:---:` centres the column
- `---:` aligns the column to the right

```
| Subnet | Network Address | Broadcast Address | Default Gateway |
|:-------|:---------------:|:-----------------:|----------------:|
| SN1    | 192.168.1.0     | 192.168.1.127     | 192.168.1.1     |
| SN2    | 192.168.1.128   | 192.168.1.255     | 192.168.1.129   |
```

Result:

| Subnet | Network Address | Broadcast Address | Default Gateway |
|:-------|:---------------:|:-----------------:|----------------:|
| SN1    | 192.168.1.0     | 192.168.1.127     | 192.168.1.1     |
| SN2    | 192.168.1.128   | 192.168.1.255     | 192.168.1.129   |

## 9. Task Lists

To create a task list, add a dash and square brackets with a space `- [ ]` in front of each item. Put an `x` inside the brackets `- [x]` to mark the task as done.

```
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

Result:

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## Summary

| Syntax | What it does | Example |
|:-------|:------------:|--------:|
| `#` | Heading | `## Title` |
| Blank line | New paragraph | (empty line) |
| `**text**` | Bold | **bold** |
| `*text*` | Italic | *italic* |
| `>` | Block quote | `> Quote` |
| `1.` | Ordered list | `1. Item` |
| `-` | Unordered list | `- Item` |
| `` ` `` | Code | `code` |
| `[text](url)` | Link | `[Guide](url)` |
| `\|` and `---` | Table | `\| A \| B \|` |
| `- [ ]` | Task list | `- [x] Done` |
