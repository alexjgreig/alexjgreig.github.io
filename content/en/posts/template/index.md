---
title: Useful Markdown Commands
date: 2024-02-13
author: Alex Greig
description: Markdown Uses
---

## Paragraph

The below are some useful commands to use when creating markdown files for web content.

## Image

The following syntax includes an image.

```markdown
![Landscape](1.jpg)
```

![Landscape](1.jpg)

## Tables

Tables aren't part of the core Markdown specification, but Hugo supports them:

   Name | Age
--------|------
   Alice | 33
   Bob | 38
   Charlie | 20

## Code Blocks

### Code block with backticks

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title> HTML5 Document</title>
</head>
<body>
  <p>Testing</p>
</body>
</html>
```

### Code block with Hugo's internal highlight shortcode

{{< highlight html >}}
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>HTML5 Document</title>
</head>
<body>
  <p>Testing</p>
</body>
</html>
{{< /highlight >}}

## List Types

### Ordered List

1. 1st item
2. 2nd item with some `code` in it
3. 3rd item

### Nested list

* Sports
  * Football
  * Tennis
  * Golf
* Car Brands
  * Porsche
  * Toyota
