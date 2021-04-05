<template>
  <div>
    <q-toolbar class="bg-grey-3">
      <div id="footer">
        <q-card flat>
          <q-card-section>
            Contact Info:
          </q-card-section>
          <q-separator inset></q-separator>
          <q-card-section>
            Danny Oka <br />
            <a href="mailto:dannyoka@gmail.com">dannyoka@gmail.com</a> <br />
            (602) 339-9657
          </q-card-section>
        </q-card>
        <q-card flat></q-card>
      </div>
    </q-toolbar>
  </div>
</template>

<script>
export default {};
</script>

<style>
#footer {
  display: flex;
  justify-content: space-evenly;
  width: 100%;
}
</style>
