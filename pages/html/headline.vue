<template>
  <article>
    <h3>Headlines</h3>
    <p>We use headlines in writing to introduce and label different sections of content.<p>
    <p>Do not use headline elements to make text bigger or smaller. HTML is only for describing what kind of content something is. Use CSS to change how text appears.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="hyperlink">Next: Hyperlinks with Anchor Tags</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "The <h1> Element & More!" } },
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
    <p>Avery likes computers and listens to jazz.</p>
    <h2>Avery's Musical Talents</h2>
    <p>Avery can't play the bass but admires those who can!</p>
  </body>
</html>`
} } } </script>
