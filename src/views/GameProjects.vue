<template>
  <div>
    <h1>Games</h1>

    <div style="margin-bottom: 30px;">
      The projects I am currently working.
    </div>

    <ProjectsList v-bind:projects="projects" />

    <div style="margin-top: 30px;">
      <a href="https://github.com/F1R3015?tab=repositories"> And more.</a>
    </div>
    
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import ProjectsList from "@/components/ProjectsList.vue";
import gameProjectsData from "@/data/GameProjectsData.ts";

export default Vue.extend({
  name: "GameProjects",
  components: {
    ProjectsList,
  },
  data: function () {
    return {
      projects: gameProjectsData,
    };
  },
});
</script>
