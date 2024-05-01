<template>
  <div>
    <H1>{{name}}</H1>
    <ul>
      <li v-for="project in projects" :key="project.name"></li>
    </ul>
  </div>
</template>

<script setup>
  const name = "Harindu Hadithya"
  const projects = [
    {name: "Project 1"},
    {name: "Project 2"}
  ]
</script>