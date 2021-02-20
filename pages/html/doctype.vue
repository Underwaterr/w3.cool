<template>
  <article>
    <h3>Doctype</h3>
    <p>The first line of every HTML5 file is the Doctype. It tells the web browser that this is an HTML5 file.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="html-element">Next: the HTML element</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "HTML Doctype" } },
data() { return { code: 
`<!DOCTYPE html>`
} } } </script>
