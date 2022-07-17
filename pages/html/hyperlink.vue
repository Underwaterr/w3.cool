<template>
  <article>
    <h3>Hyperlinks</h3>
    <p>Hyperlinks are the most important feature of the internet. They let webpages link to other webpages!</p>
    <p>Hyperlinks use the <code>&lt;a&gt;</code> tag for some reason. Be sure not to confuse it with the <code>&lt;link&gt;</code> element, which is how we add CSS and JavaScript to a webpage.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="hyperlink">Next: Hyperlinks with Anchor Tags</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "Hyperlinks with the <a> Element" } },
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
    <h1>Avery's Cool Website</h1>
    <h2>About Avery</h2>
    <p>Avery likes computers and listens to <a href="https://en.wikipedia.org/wiki/Jazz">jazz</a>.</p>
  </body>
</html>`
} } } </script>
