<template>
  <div class="flex min-h-screen">
    <Sidebar />
    <div class="flex-1 flex flex-col">
      <Header />
      <MainContent />
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Sidebar from './components/Sidebar.vue'
import MainContent from './components/MainContent.vue'

export default {
  name: 'App',
  components: {
    Header,
    Sidebar,
    MainContent,
  },
}
</script>

<style>
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>