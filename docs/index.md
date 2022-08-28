---
title: Github Pages Demo (Index)
---

# Table of Contents

Works with kramdown, but not with GFM:

* TOC
{:toc}

# Code Blocks

Code block with syntax highlighting:

~~~js
console.log("code block");
~~~

```js
console.log("code block");
```

Code block inside "details" tag. Works with GFM, but not with kramdown:

<details>
<summary>summary here</summary>

``` js
console.log("details here");
```

~~~ js
console.log("details here");
~~~

~~~
console.log("details here, without highlighting");
~~~

</details>

# Links

Relative link to an internal page: [Link2](/linkme.md)
