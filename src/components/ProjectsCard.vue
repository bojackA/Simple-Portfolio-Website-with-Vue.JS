<template>
  <div class="main-container">
    <div
      class="project-card"
      v-for="(item, index) in projectData.projectsArray"
      v-bind:key="item"
    >
      <h2>{{ projectData.projectsArray[index].Title }}</h2>
      <img :src="projectData.projectsArray[index].image" alt="" />
      <p>{{ projectData.projectsArray[index].About }}</p>
    </div>
  </div>
</template>
<script>
import jsonData from "/projects.json";
export default {
  data() {
    return {
      projectData: jsonData,
    };
  },
};
</script>
<style>
.project-card {
  width: 100vw; /* Set width to fill the entire viewport width */
}
.project-card-img {
  height: 10rem;
}
</style>
