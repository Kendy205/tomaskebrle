---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
title: Hello world!
publishDate: 12 Sep 2021
name: Nate Moore
value: 128
description: Just a Hello World Post!
---

This is so cool!

Do variables work {frontmatter.value \* 2}?

````javascript
```javascript
// Example JavaScript
const x = 7;
function returnSeven() {
  return x;
}
````