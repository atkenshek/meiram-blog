---
title: "Markdown Syntax"
date: 2022-10-14T13:48:20+06:00
draft: false
toc: false
images:
tags: ["markdown", "css", "html"]
---

This article offers a sample of basic Markdown syntax that can be used in Hugo content files, also it shows whether basic HTML elements are decorated with CSS in a Hugo theme.
<!--more-->

# Headings

The following HTML `<h1>`—`<h6>` elements represent six levels of section headings. `<h1>` is the highest section level while `<h6>` is the lowest.

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Paragraph

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras vel nisi libero. Maecenas vel dui et leo fermentum commodo vel et erat. In purus eros, sollicitudin id justo eu, mattis feugiat nibh. Donec eros dui, posuere sed egestas eu, vehicula eget purus. Maecenas vulputate, nulla sit amet luctus dictum, ipsum justo porttitor leo, ultricies porta leo enim nec nunc. Sed in tincidunt augue. Donec facilisis id neque quis cursus. Suspendisse egestas placerat ipsum, eu iaculis quam iaculis ac. 

Praesent molestie bibendum sagittis. Donec tristique lorem eget diam pharetra finibus. Aliquam erat volutpat. Nam sit amet velit eleifend leo fermentum ullamcorper eu sed nibh. Nullam vestibulum scelerisque sodales. Morbi vel quam vel erat mattis elementum a nec elit.

## Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

#### Blockquote without attribution

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Note** that you can use *Markdown syntax* within a blockquote.

#### Blockquote with attribution

> Don't communicate by sharing memory, share memory by communicating.<br>
> — <cite>Rob Pike</cite>


## Tables

Tables aren't part of the core Markdown spec, but Hugo supports them out-of-the-box.

   Name | Age
--------|------
    Bob | 27
  Alice | 23

#### Inline Markdown within tables

| Italics   | Bold     | Code   |
| --------  | -------- | ------ |
| *italics* | **bold** | `code` |

## Code Blocks

#### Code block with backticks

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

#### Code block indented with four spaces

    <!doctype html>
    <html lang="en">
    <head>
      <meta charset="utf-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

#### Code block with Hugo's internal highlight shortcode
{{< highlight html >}}
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

## List Types

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

* List item
* Another item
* And another item

#### Nested list

* Fruit
  * Apple
  * Orange
  * Banana
* Dairy
  * Milk
  * Cheese