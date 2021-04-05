<template>
  <div>
    <hero-box></hero-box>
    <the-cards></the-cards>
    <q-dialog v-model="welcomeDialog">
      <q-card style="width: 50%">
        <q-card-section>
          To subscribe to my newsletter:
          <q-form>
            <q-input v-model="form.email" label="Enter Email"> </q-input>
          </q-form>
        </q-card-section>

        <q-card-actions align="right">
          <q-btn
            @click="cancelEmail"
            label="No, Thanks"
            color="negative"
          ></q-btn>
          <q-btn @click="submitEmail" label="Submit" color="primary"></q-btn>
        </q-card-actions>
      </q-card>
    </q-dialog>
  </div>
</template>

<script>
import TheCards from "../components/TheCards";
import HeroBox from "../components/HeroBox";
export default {
  name: "PageIndex",
  mounted() {
    this.welcomeDialog = true;
  },
  components: {
    TheCards,
    HeroBox
  },
  data() {
    return {
      welcomeDialog: false,
      form: {
        email: ""
      }
    };
  },
  methods: {
    closeDialog() {
      this.welcomeDialog = false;
    },
    submitEmail() {
      this.closeDialog();
    },
    cancelEmail() {
      this.closeDialog();
    }
  }
};
</script>

<style scoped></style>
