<template>
  <article>
    <h3>The <code>footer</code> Element</h3>
    <p>The <code>foooter</code> element is for footers: sections of information about another piece of content. Examples include details about the author, citations, copyright information, etc. This can be for an article or for the whole webpage.</p>
    <p>While footers are typically after the content they refer to, this doesn't necessarily have to be the case.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="nav">Next: The <code>nav</code> Element</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "The <footer> Element" } },
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
    <header>Here's where my website header content will go</header>
    <main>
      <article>
        <header>Here's where my article's header content will go</header>
        Here's where the rest of my article content will go
        <footer>Here's where my article's footer content will go</footer>
      </article>
    </main>
    <footer>Here's where my website's footer content will go</footer>
  </body>
</html>`
} } } </script>
