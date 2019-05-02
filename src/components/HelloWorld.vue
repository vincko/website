<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Feel free to contact me at
      <a href="mailto:jeltsch.vincent@gmail.com" target="_blank" rel="noopener">jeltsch.vincent@gmail.com</a>.
    </p>
    <h3>Projects I am involved in:</h3>
    <ul>
      <li><a href="https://klecksx.de" target="_blank" rel="noopener">KlecksX</a></li>
      <li><a href="https://studystuff.org" target="_blank" rel="noopener">StudyStuff</a></li>
      <li><a href="https://teg-ev.de" target="_blank" rel="noopener">TEG e.V.</a></li>
    </ul>
    <h3>My social media:</h3>
    <ul>
      <li><a href="https://github.com/vincko" target="_blank" rel="noopener">GitHub</a></li>
      <li><a href="https://www.linkedin.com/in/vincent-jeltsch-3185b8102" target="_blank" rel="noopener">LinkedIn</a></li>
      <li><a href="https://www.facebook.com/vincent.jeltsch" target="_blank" rel="noopener">Facebook</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
