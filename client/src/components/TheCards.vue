<template>
  <div id="cardsRow" class="q-pa-md">
    <q-card v-for="(project, i) in projects" :key="i">
      <q-card-section>
        {{ project.title }}
      </q-card-section>
      <q-card-section>
        {{ project.description }}
      </q-card-section>
      <q-card-section>
        Technologies used:
        <q-separator inset></q-separator>
        <div v-for="(technology, idx) in project.technologies" :key="idx">
          {{ technology }}
        </div>
      </q-card-section>
    </q-card>
  </div>
</template>

<script>
export default {
  data() {
    return {
      projects: [
        {
          title: "First Project",
          description: "This was my first ptoject",
          technologies: ["Quasar", "Vue", "Express"]
        },
        {
          title: "Second Project",
          description: "This was my second project",
          technologies: ["Python", "Socket.io"]
        }
      ]
    };
  }
};
</script>

<style>
#cardsRow {
  display: flex;
  justify-content: space-evenly;
}
</style>
