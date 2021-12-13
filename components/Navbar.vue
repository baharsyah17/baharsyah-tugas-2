<template>
  <div id="app">
    <nav>
      <ul>
        <li class="px-80">Tugas Bahar</li>
        <li><a href="/">Home</a></li>
        <li><a href="https://www.facebook.com/">Facebook</a></li>
        <li><a href="https://twitter.com/?lang=en">Twitter</a></li>
        <li><a href="https://www.youtube.com/">Youtube</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
ul {
  margin: 0;
  overflow: hidden;
  background-color: black;
  color: white;
  padding: 20px;
}
li {
  float: left;
}
li a {
  display: block;
  text-align: center;
  border-radius: 5px;
  padding-left: 25px;
  padding-right: 25px;
}
li a:hover:not(.active) {
  background-color: blue;
}
</style>
