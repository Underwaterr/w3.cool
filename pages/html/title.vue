<template>
  <article>
    <h3>The <code>title</code> Element</h3>
    <p>Every webpage has a title. This title is used by browsers, bookmarks, search engines and more to help users identify the page.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="link">Next: adding CSS with <code>link</code></NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "The <title> Element" } },
data() { return { code: 
`<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Avery's Cool Website</title>
  </head>
</html>`
} } } </script>
