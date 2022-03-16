<template>
  <article>
    <h3>Character Encoding with the <code>meta</code> Element</h3>
    <p>We need to specify what encoding the webpage uses. Almost always, the encoding is UTF-8.</p>
    <p>To do this, we will set the <code>charset</code> attribute of a <code>meta</code> element inside of the <code>head</code> element.</p>
    <h4>Example</h4>
    <Prism language="html" :code="charset" />
    <NuxtLink to="title">Next: <code>title</code></NuxtLink>
    <h3>Setting the Viewport with <code>meta</code></h3>
    <p>We have to specify the viewport for the webpage to look good on devices of different sizes (such as phones, tablets and laptops).</p>
    <p>We'll add <code>&lt;meta name="viewport" content="width=device-width, initial-scale=1"&gt;</code> inside the head. Rarely will we need to deviate from these values.</p>
    <h4>Example</h4>
    <Prism language="html" :code="viewport" />
    <NuxtLink to="title">Next: Setting the title</NuxtLink>
  </article>
</template>

<script>
export default {
head() { return { title: "Character Encoding with the <meta> Element" } },
data() { return { 
charset: 
`<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  </head>
</html>`,
viewport:
`<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
  </head>
</html>`
} } } </script>
