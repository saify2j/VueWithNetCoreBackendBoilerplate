<template>
    <div class="hello">
        <h1>{{ msg }}</h1>
        <img src="../assets/logo.png" />
        <p>
            Template for Vue JS 3.0 and .NET 5 applications developed by <b>Alexandre Malavasi.</b><br />
            In order to get more content on Vue JS and .NET platform, please follow on my social media profiles:
        </p>
    </div>
</template>

<script>
export default {
  name: 'Home',
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
