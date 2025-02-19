<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated class="bg-primary text-white">
      <q-toolbar>
        <q-toolbar-title>My Portfolio</q-toolbar-title>
        <q-btn flat to="/" label="Home" />
        <q-btn flat to="/projects" label="Projects" />
        <q-btn flat to="/work-experience" label="Work Experience" />
        <q-btn flat to="/contact" label="Contact" />
      </q-toolbar>
    </q-header>

    <q-page-container>
      <q-page class="q-pa-md">
        <div class="text-center">
          <h1 class="text-h2">Hi, I'm Kamalia Farhana</h1>
          <p class="text-subtitle1">
            Fullstack Developer | Laravel & Vue.js Enthusiast
          </p>
          <q-btn color="primary" label="View My Work" to="/projects" />
        </div>
      </q-page>
    </q-page-container>
  </q-layout>
</template>

<script setup>
// Add any JS or Nuxt composables here if needed
</script>

<style scoped>
h1 {
  color: #027be3;
}
p {
  color: #555;
}
</style>
