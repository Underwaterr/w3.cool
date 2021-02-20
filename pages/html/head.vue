<template>
  <article>
    <h3>The <code>head</code> Element</h3>
    <p>This element groups together all of the elements that describe the content of the webpage.</p>
    <p>Contrast this to the <code>body</code> element that will contain the content itself.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="encoding">Next: Encoding with the <code>meta</code> element</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "The <head> Element" } },
data() { return { code: 
`<!DOCTYPE html>
<html lang="en">
  <head></head>
</html>`
} } } </script>
