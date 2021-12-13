<template>
  <div class="row">
    <div class="side">
      <h1 class="p-10 font-bold">Popular Title</h1>
      <img src="bmw.jpeg" alt="bmw1" />
      <br />
      <img src="bmw-2.jpeg" alt="bmw2" />
      <br />
      <img src="jhonson.jpeg" alt="jhonsom" />
    </div>
    <div class="main">
      <h2 class="font-bold">TITLE HEADING</h2>
      <h3>Title Description</h3>
      <br />
      <div class="fakeimg" style="height: 200px">Image</div>
      <p class="py-6">Some text..</p>
      <p>
        Sunt in culpa qui officia deserunt mollit anim id est laborum
        consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore
        et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
        exercitation ullamco.
      </p>
      <p class="py-6">Some order list:</p>
      <ol class="list-decimal">
        <li>Tipe 1</li>
        <br />
        <li>Tipe 2</li>
        <br />
        <li>Tipe 3</li>
        <br />
        <li>Tipe 4</li>
      </ol>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.row {
  display: flex;
  flex-wrap: wrap;
}
.side {
  flex: 30%;
  background-color: red;
  padding: 20px;
  text-align: center;
  font-size: 30px;
}
.main {
  flex: 70%;
  background-color: white;
  padding: 20px;
}
img {
  height: 250px;
  width: 550px;
  padding-left: 20%;
  padding-right: 5%;
}
.fakeimg {
  background-color: gray;
  width: 100%;
  padding: 20px;
}

h2 {
  font-size: 40px;
  padding-top: 20px;
}
h3 {
  font-size: 28px;
  padding-top: 15px;
  padding-bottom: 15px;
}
ol {
  padding-left: 40px;
}
</style>
