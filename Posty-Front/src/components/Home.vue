<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <router-link v-bind:to="{ name: 'Posts' }">See All Posts</router-link>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'Welcome to Posty!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
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
  color: #4d7ef7;
  text-decoration: none;
}
</style>
