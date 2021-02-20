<template>
  <article>
    <h3>Add CSS to a Webpage using the <code>link</code> Element</h3>
    <p>The best way to add CSS to a webpage is to use the <code>link</code> element.</p>
    <p>We set the <code>rel</code> attribute to <code>"stylesheet"</code> and set <code>href</code> to the URL of a separate CSS file.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="body">Next: The <code>body</code> Element</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "How to Add CSS to a Webpage" } },
data() { return { code: 
`<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Avery's Cool Website</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="/css/custom.css">
  </head>
</html>`
} } } </script>
