<template>
  <article>
    <h3>Paragraphs with the <code>p</code> Element</h3>
    <p>Wrap each paragraph with <code>&lt;p&gt;</code> tags.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" :data-line="5" />
    <NuxtLink to="headline">Next: Headlines</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "The <p> Element" } },
data() { return { code: 
`<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="utf-8">
    <title>Avery's Cool Website</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="/css/custom.css">
  </head>
  
  <body>
    <p>Hello, world!</p>
    <p>My name is Avery. I like to make websites.</p>
    <p>Here is another paragraph for my website. Paragraphs are made of multiple sentences.</p>
  </body>
</html>`
} } } </script>
