<h1>
Simple Markdown Cheat Sheet
</h1>
<br/>

> Please refer to the official documentation on [GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) to learn more about the formatting syntax.

Markdown is a method for writing formatted text using a simple plain text format. This document only cover the base markdown syntax to enahncing your Github README.

- [Headings](#headings)
- [Text styles](#text-styles)
# Headings

<!-- omit in toc -->
# Heading 1
<!-- omit in toc -->
## Heading 2
<!-- omit in toc -->
### Heading 3
<!-- omit in toc -->
#### Heading 4
<!-- omit in toc -->
##### Heading 5
```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
OR
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
```

# Text styles
### Bold
**The quick brown fox jumps over the lazy dog.**
<br>
__The quick brown fox jumps over the lazy dog.__

```markdown
**The quick brown fox jumps over the lazy dog.**
__The quick brown fox jumps over the lazy dog.__
```

### Italic
*The quick brown fox jumps over the lazy dog.*
<br>
_The quick brown fox jumps over the lazy dog._

```markdown
*The quick brown fox jumps over the lazy dog.*
_The quick brown fox jumps over the lazy dog._
```
### Bold and Italic
**_The quick brown fox jumps over the lazy dog._**

```markdown
**_The quick brown fox jumps over the lazy dog._**
```
### Blockquotes
> The quick brown fox jumps over the lazy dog.

> The quick brown fox jumps over the lazy dog.
>
> The quick brown fox jumps over the lazy dog.
>
> The quick brown fox jumps over the lazy dog.

> The quick brown fox jumps over the lazy dog.
>> The quick brown fox jumps over the lazy dog.
>>> The quick brown fox jumps over the lazy dog.

> **The quick brown fox** *jumps over the lazy dog.*

```markdown
> The quick brown fox jumps over the lazy dog.
> The quick brown fox jumps over the lazy dog.
>
> The quick brown fox jumps over the lazy dog.
>
> The quick brown fox jumps over the lazy dog.
> The quick brown fox jumps over the lazy dog.
>> The quick brown fox jumps over the lazy dog.
>>> The quick brown fox jumps over the lazy dog.
> **The quick brown fox** *jumps over the lazy dog.*
```
### Monospaced
<samp>The quick brown fox jumps over the lazy dog.</samp>
```markdown
<samp>The quick brown fox jumps over the lazy dog.</samp>
```
### Underlined
<ins>The quick brown fox jumps over the lazy dog.</ins>
```markdown
<ins>The quick brown fox jumps over the lazy dog.</ins>
```
### Strike-through
~~The quick brown fox jumps over the lazy dog.~~
``` markdown
~~The quick brown fox jumps over the lazy dog.~~
```
### Boxed
<table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>
```markdown
<table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>
```

Subscript <sub>The quick brown fox jumps over the lazy dog.</sub>

Superscript <sup>The quick brown fox jumps over the lazy dog.</sup>

```markdown
Subscript <sub>The quick brown fox jumps over the lazy dog.</sub>
Superscript <sup>The quick brown fox jumps over the lazy dog.</sup>
```

<!-- omit in toc -->
<h3 align="center"> My latest Medium posts </h3>
```markdown
<h3 align="center"> My latest Medium posts </h3>
```

# Tables

<table>
<tr>
<td width="33%"">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
</tr>
</table>

```markdown
<table>
<tr>
<td width="33%"">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
</tr>
</table>
```

| Default    | Left align | Center align | Right align |
| ---------- | :--------- | :----------: | ----------: |
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |
| 999999999  | 999999999  | 999999999    | 999999999   |
| 99999999   | 99999999   | 99999999     | 99999999    |
| 9999999    | 9999999    | 9999999      | 9999999     |

```markdown
| Default    | Left align | Center align | Right align |
| ---------- | :--------- | :----------: | ----------: |
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |
| 999999999  | 999999999  | 999999999    | 999999999   |
| 99999999   | 99999999   | 99999999     | 99999999    |
| 9999999    | 9999999    | 9999999      | 9999999     |

```
