<template>
  <article>
    <h3>The <code>body</code> Element</h3>
    <p>All of the content of a webpage goes inside the HTML document's body.</p>
    <p>Contrast this to the head, where we put information that describes the content, but is not the content itself.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="semantic">Next: Semantic Elements</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "The <body> Element" } },
data() { return { code: 
`<!DOCTYPE html>
<html lang="en">

  <head>
    <title>Avery's Cool Website</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="/css/custom.css">
  </head>
  
  <body></body>
</html>`
} } } </script>
