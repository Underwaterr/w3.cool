<template>
  <article>
    <h3>The <code>header</code> Element</h3>
    <p>Not to be confused with <NuxtLink to="heading">headings</NuxtLink>, headers are the more broad sections of a webpage that introduce other content, whether as part of an individual article or for the entire webpage.</p>
    <!-- https://html.spec.whatwg.org/multipage/sections.html#the-header-element -->
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="footer">Next: The <code>footer</code> Element</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "The Header Element" } },
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
      </article>
    </main>
  </body>
</html>`
} } } </script>
