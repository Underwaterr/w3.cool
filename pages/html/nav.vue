<template>
  <article>
    <h3>The <code>nav</code> Element</h3>
    <p>For a section of a webpage that has a group of links that navigate either to other webpages or to different sections within a webpage.</p>
    <p>Navigation can be site-wide or relative to an article or section.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="aside ">Next: The <code>aside</code> Element</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "The <nav> Element" } },
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
    <nav>Here's where my website's navigation will go</nav>
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
