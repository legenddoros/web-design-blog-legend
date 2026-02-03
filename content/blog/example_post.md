---
title: How to Write a Blog
description: How to use 11ty and Markdown
date: 2026-02-03
tags: ["starter", "these are tags for your posts"]
---

We can write our blogs using the [Markdown framework](https://www.markdownguide.org/). Markdown, similar to HTML, is a markup language. 

## Using `#` Makes Headers, Useful to Section Content

### More `##` Creates Subheadings

#### 11ty allows us to link from these headings too

We can embed links, or we can also use regular HTML.

<a href="https://www.google.com/">Regular `<a>` tag </a>

[Markdown linking](https://www.google.com/)

I can also link to [another section of the page](#now-i-am-at-the-bottom).

You can write code in code blocks, using ```

```js
// this is a command
function myCommand() {
	let counter = 0;
	counter++;
}

// Test with a line break above this line.
console.log('Test');
```

Or you can write inline code `like this`

## Running Locally

To run our blog for local testing:

1. Open terminal in VS Code
2. Type `npm run start`
3. Open the localhost link in your browser. It should look something like `http://localhost:8080/`
4. It will live update, so every time you press save on your blog post it will be uploaded!

## Publishing to the Web

## Now I am at the bottom!