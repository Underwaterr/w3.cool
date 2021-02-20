<template>
  <article>
    <h3>Setting the Viewport with <code>meta</code></h3>
    <p>We have to specify the viewport for the webpage to look good on devices of different sizes (such as phones, tablets and laptops).</p>
    <p>We'll add <code>&lt;meta name="viewport" content="width=device-width, initial-scale=1"&gt;</code> inside the head. Rarely will we need to deviate from these values.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="css">Next: including CSS</NuxtLink>
  </article>
</template>

<script>
export default { 
head() { return { title: "Setting the Viewport with the <meta> Element" } },
data() { return { code: 
`<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Avery's Cool Website</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
  </head>
</html>`
} } } </script>
