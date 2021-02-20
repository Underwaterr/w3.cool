<template>
  <article>

    <h3>The <code>html</code> Element</h3>
    <p>Everything besides the <NuxtLink to="doctype">doctype</NuxtLink> will go inside the HTML element.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code[0]" />

    <h3>The <code>lang</code> Attribute</h3>
    <p>We specify the language of the webpage by setting the "lang" attribute.</p>
    <p>The values are based on the <a href="https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry">IANA Language Subtag Registry</a>.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code[1]" />
    <NuxtLink to="head">Next: <code>head</code></NuxtLink>

  </article>
</template>

<script>
export default { 
head() { return { title: "The <html> Element" } },
data() { return { code: [
`<!DOCTYPE html>
<html></html>`,
`<!DOCTYPE html>
<html lang="en">
</html>`]
} } } </script>
