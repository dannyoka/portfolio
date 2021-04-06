<template>
  <div id="heroBox">
    <div id="textCol">
      <h3>
        Hi, I'm Daniel Oka
      </h3>
      <h4>
        I'm a web developer specializing in Node and Vue.
      </h4>
    </div>
    <div class="imageCol">
      <img src="../assets/OkaFamily-73.jpg" alt="" style="width: 50%;" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#heroBox {
  color: white;
  background-image: linear-gradient(
      to right bottom,
      rgba(243, 150, 150, 0.8),
      rgba(194, 48, 48, 0.8)
    ),
    url("https://images.unsplash.com/photo-1531685250784-7569952593d2?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=967&q=80");
  background-repeat: no-repeat;
  background-size: cover;
  height: 75vh;
  width: 100%;
  padding-top: 0;
  display: flex;
  justify-content: space-evenly;
  flex-direction: row;
  align-items: center;
}
#textCol {
  width: 25%;
}
.imageCol {
  width: 25%;
}
</style>
