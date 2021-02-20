<template>
  <article>
    <h3>Character Encoding with the <code>meta</code> Element</h3>
    <p>We need to specify what encoding the webpage uses. Almost always, the encoding is UTF-8.</p>
    <p>To do this, we will set the <code>charset</code> attribute of a <code>meta</code> element inside of the <code>head</code> element.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="title">Next: <code>title</code></NuxtLink>
  </article>
</template>

<script>
export default {
head() { return { title: "Character Encoding with the <meta> Element" } },
data() { return { code: 
`<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  </head>
</html>`
} } } </script>
