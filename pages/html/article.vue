<template>
  <article>
    <h3>The <code>article</code> Element</h3>
    <p>The <code>article</code> element is for content that forms an independent, self-contained part of a document. For example, a webpage might have multiple blog posts, each within their own <code>article</code> element.</p> 
    <p>The key idea is <em>independence</em>. Would this section of content still make sense without the rest of the webpage?</p>
    <h4>External Links</h4>
    <p><ul>
      <li><a href="https://html.spec.whatwg.org/multipage/sections.html#the-article-element">The HTML Standard</a></li>
      <li><a href="https://www.smashingmagazine.com/2020/01/html5-article-section/">Why You Should Choose HTML5 <code>article</code> Over <code>section</code></a></li>
    </ul></p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="header">Next: The <code>header</code> Element</NuxtLink>
  </article>
</template>

<script>
export default { 
//head() { return { title: "The Article Element" } },
data() { return { code: 
`<!DOCTYPE html>
<html lang="en">

  <head>
    <title>Avery's Cool Website</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="/css/custom.css">
  </head>
  
  <body>
    <main>
      <article>Here's where my first article will go!</article>
      <article>Here's where my second article will go!</article>
    </main>
  </body>
</html>`
} } } </script>
