---
title: Article Layout
---

export const Highlight = ({children, color}) => (
<span
style={{
      color: color,
      padding: '0.2rem',
    }}>
{children}
</span>
);

This page will help you to know the exact layout that is needed to be followed for writing articles for <Highlight color="#1877F2">NeoAlgo</Highlight>

## Author

Info of author should be written in this format at the start of the article page

```md
---
slug: javascript
title: JavaScript It
author: Gao Wei
author_title: Docusaurus Core Team
author_url: https://github.com/wgao19
author_image_url: https://avatars1.githubusercontent.com/u/2055384?v=4
tags: [JavaScript, Algorithms, ES6]
---
```

Welcome info regarding the topic of the article should be written after the info of the author.

Ex., A very warm welcome to you, the Reader of my article. I am writing this to introduce you to one of the coolest things that have had happened in this tech world. Yes, the world of JavaScript!

## Prerequisite

This should be the very first head section where the required library or any other knowledge will be written.

### Library

If you have used any Node Packages then that should be listed here with the info regarding the installation

To get the colors in your console using NodeJS will require installing the Node Package -

```JavaScript
npm install colors
```

### Covers

Or if your program or article highlights certain specific parts of technology such as abstraction, ES6, etc., then they should be listed here in this format -

This article covers the brain-storming topics including -

1. Abstraction
2. ES6
3. Encapsulation

<hr />

## Main Idea

Your awesome idea goes here. The subtopics of the same section should go line by line

You can display images in this way -

![Docusaurus logo](../static/img/js.png)

### Sub Topic01

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque elementum dignissim ultricies. Fusce rhoncus ipsum tempor eros aliquam consequat. Lorem ipsum dolor sit amet

If you want to provide any alarming info then it should be used as -

:::tip Something

Watch out for that semicolon. That can ruin your day

:::

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque elementum dignissim ultricies. Fusce rhoncus ipsum tempor eros aliquam consequat. Lorem ipsum dolor sit amet.

For underlying any dangerous pattern or something that, then you can have it as -

:::danger Something

KISS - Keep it Simple Silly

:::

Don't misuse it. Only use it whenever it is needed.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque elementum dignissim ultricies. Fusce rhoncus ipsum tempor eros aliquam consequat. Lorem ipsum dolor sit amet

### Sub Topic02

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque elementum dignissim ultricies. Fusce rhoncus ipsum tempor eros aliquam consequat. Lorem ipsum dolor sit amet

You can insert your code snippet with syntax highlighting -

```jsx
export const Highlight = ({ children, color }) => (
  <span
    style={{
      color: color,
      padding: "0.2rem",
    }}
  >
    {children}
  </span>
);
```

### Sub Topic03

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque elementum dignissim ultricies. Fusce rhoncus ipsum tempor eros aliquam consequat. Lorem ipsum dolor sit amet

A note should be inserted as -

<blockquote><p> Pellentesque elementum dignissim ultricies. Fusce rhoncus ipsum tempor eros aliquam consequat. Lorem ipsum dolor sit amet</p></blockquote>

Note with link -

<blockquote><h4><a href="https://github.com/facebook/docusaurus">[RFC] Know more </a></h4><p>Fusce rhoncus ipsum tempor eros aliquam consequat. Lorem ipsum dolor sit amet</p></blockquote>

<hr />

## Test Cases

If you are explaining any code or program then the Input/Output of the program should go into this section as -

> Every example should be unique & max 3 examples should be provided

### Example01

Example where element is found

```javaScript

Enter array length - 5
Enter 1 element - 23
Enter 2 element - 45
Enter 3 element - 87
Enter 4 element - 12
Enter 5 element - 54
Your array -  [ 23, 45, 87, 12, 54 ]
Enter number to search - 54
Found 54

```

### Example02

Example where element is not found

```javaScript

Enter array length - 5
Enter 1 element - 23
Enter 2 element - 45
Enter 3 element - 87
Enter 4 element - 12
Enter 5 element - 54
Your array -  [ 23, 45, 87, 12, 54 ]

Enter number to search - 14
Not Found

```

<hr />

## End Note

Here, the summary of the article will go. Rewind the necessary things.

You should provide the code link of the file that you or someone who has written for NeoAlgo ( If you are explaining any code from the NeoAlgo )

### Resources

List all the resources you had to go through to create this beautiful article.

1. Articles from [MDN](https://developer.mozilla.org/en-US/)
2. [JavaScript](https://www.javascript.com/) Website
3. Code snippets from [W3School](https://www.w3schools.com/)
