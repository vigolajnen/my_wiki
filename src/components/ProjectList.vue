<template>
  <ul class="project-list">
    <li v-for='item in projectList' :key='item.id'>{{ item.title }}</li>
  </ul>
</template>

<script>
export default {
  name: 'ProjectList',
  data () {
    return {
      projectList: [
        {
          id: 1,
          title: 'Новый ЛК'
        },
        {
          id: 2,
          title: 'FHR'
        },
        {
          id: 3,
          title: 'Trade'
        },
        {
          id: 4,
          title: 'FH админка'
        }
      ]
    }
  }
}
</script>
