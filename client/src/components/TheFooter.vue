<template>
  <div id="footer" class="bg-blue-2">
    <div id="footer-title">
      <p>Contact Me</p>
    </div>
    <q-separator inset></q-separator>
    <div id="footer-body">
      <div class="footer-item">
        <p class="footer-text">
          Daniel Oka
        </p>
      </div>
      <div class="footer-item">
        <q-icon name="phone"></q-icon>
        <p class="footer-text">
          (602) 339-9657
        </p>
      </div>
      <div class="footer-item">
        <q-icon name="email"></q-icon>
        <a href="mailto:dannyoka@gmail.com">
          <p class="footer-text">
            dannyoka@gmail.com
          </p>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#footer {
}
#footer-title {
  display: flex;
  justify-content: center;
}
#footer-body {
  display: flex;
  justify-content: space-evenly;
  width: 100%;
  padding-top: 2vh;
}
.footer-text {
  color: orangered;
  padding-right: 10px;
}
.footer-item {
  display: flex;
  align-content: center;
}
</style>
