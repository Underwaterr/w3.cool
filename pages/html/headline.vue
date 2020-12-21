<template>
  <article>
    <h3>Headlines</h3>
    <p>We use headlines in writing to introduce and label different sections of content.<p>
    <p>Remember that headline elements don't determine how elements visually appear. The one and only use for HTML is to label what content is; any and all styling to elements come from CSS.</p>
    <h4>Example</h4>
    <Prism language="html" :code="code" />
    <NuxtLink to="hyperlink">Next: Hyperlinks with Anchor Tags</NuxtLink>
  </article>
</template>

<script>
export default { data() { return { code: 
`<!DOCTYPE html>
<html lang="en">

  <head>
    <title>Avery's Cool Website</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="/css/custom.css">
  </head>
  
  <body>
    <h1>Avery's Cool Website</h1>
    <h2>About Avery</h2>
    <p>Avery likes computers and listens to jazz.</p>
    <h2>Avery's Musical Talents</h2>
    <p>Avery can't play the bass but they think people who can are awesome!</p>
  </body>
</html>`
} } } </script>
