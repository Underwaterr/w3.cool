<template>
  <article>
    <h3>The <code>aside</code> Element</h3>
    <p>For content that is tangentially related to the main content, such as pull-quotes or sidebars.</p> 
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="footer">Next: The <code>footer</code> Element</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "The <aside> Element" } },
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
        <aside>Here's where a pull-quote could go!</aside>
        <footer>Here's where my article's footer content will go</footer>
      </article>
    </main>
    <footer>Here's where my website's footer content will go</footer>
  </body>
</html>`
} } } </script>
