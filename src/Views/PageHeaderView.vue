<template>
  <header class="page-header p-4">
    <project-list />

    
  </header>
</template>

<script>
import ProjectList from "@/components/ProjectList.vue";
export default {
  name: "PageHeaderView",
  data() {
    return {
      projectList: [],
    };
  },
  components: {
    ProjectList,
  },
};
</script>

<style lang=""></style>
