<template>
  <div>
    <h1>Another page</h1>

    <h2>Code Example #1</h2>
    <Prism language="html">{{ code[0] }}</Prism>
    
    <h2>Code Example #2</h2>
    <Prism language="html">{{ code[1] }}</Prism>
  </div>
</template>

<script>
export default {
  data() {
    return {
      code: [
`<html>
  <p>Meow</p>
</html>`,

`<html>
  <p>Woof</p>
</html>`]
    }
  }
}
</script>
