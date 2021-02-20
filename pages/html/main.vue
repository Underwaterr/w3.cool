<template>
  <article>
    <h3>The <code>main</code> Element</h3>
    <p>The <code>main</code> element contains the "dominant contents of the document".</p>
    <p>Because the <code>main</code> element is semantic, the exact use case is subjective. Don't over-think it!</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="article">Next: The <code>article</code> Element</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "The <main> Element" } },
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
    <main></main>
  </body>
</html>`
} } } </script>
