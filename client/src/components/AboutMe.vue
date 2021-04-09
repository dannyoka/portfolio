<template>
  <div id="about-row">
    <div class="about-col" style="order: 0;">
      <q-card flat>
        <q-card-section>
          <p>About me</p>
        </q-card-section>
        <q-card-section>
          I'm a self-taught developer
        </q-card-section>
      </q-card>
    </div>
    <div class="about-col" style="order: 1;">
      <img
        src="../assets/OkaFamily-73.jpg"
        alt=""
        style="width: 50%;"
        id="headshot"
      />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#about-row {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  align-items: center;
  width: 100%;
}
#headshot {
  background-image: linear-gradient(
    to right bottom,
    rgba(255, 255, 255, 0.7),
    rgba(255, 255, 255, 0.7),
    url("../assets/OkaFamily-73.jpg")
  );
}
.about-col {
  display: flex;
  width: 50%;
  flex-direction: row;
  justify-content: center;
}
</style>
