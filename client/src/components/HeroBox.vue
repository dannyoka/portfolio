<template>
  <div id="heroBox">
    <div id="textCol">
      <h3>
        Hi, I'm Danny Oka
      </h3>
      <h5>
        I'm a full-stack developer
      </h5>
      <q-btn label="Contact Me"> </q-btn>
    </div>
    <div class="imageCol">
      <!-- <img src="../assets/OkaFamily-73.jpg" alt="" style="width: 50%;" /> -->
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
      to right,
      rgba(8, 40, 83, 0.8),
      rgba(80, 87, 94, 0.8)
    ),
    url("https://images.unsplash.com/photo-1531685250784-7569952593d2?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=967&q=80");
  background-repeat: no-repeat;
  background-size: cover;
  height: 75vh;
  width: 100%;
  padding-top: 0;
  display: flex;
  justify-content: space-around;
  flex-direction: row;
  align-items: center;
  clip-path: polygon(0 0, 100% 0, 100% 80%, 0 100%);
}
#textCol {
  width: 25%;
}
.imageCol {
  height: 100%;
}
</style>
