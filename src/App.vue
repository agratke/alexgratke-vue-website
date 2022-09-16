<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
import AlexGratke from './components/AlexGratke.vue'
</script>

<template>
  <!-- <q-layout view="hHh lpR fFf"> -->
    <div class="q-pb-md">
      <q-toolbar class="bg-secondary">
        <q-toolbar-title>
          Alex Gratke
        </q-toolbar-title>
        <q-tabs v-model="tab" inline-label class="" >
          <q-tab name="about" icon="person" label="About" />
          <q-tab name="projects" icon="construction" label="Projects" />
          <q-tab name="musicCollage" icon="audiotrack" label="What Am I Listening To" />
        </q-tabs>
      </q-toolbar>
    </div>

    <div class='row'>
      <div class='col-sm-2'></div>
      <div class='col-sm-8 main-content'>
        <AlexGratke msg="Alex Gratke"/>
      </div>
      <div class='col-sm-2'></div>
    </div>
  <!-- </q-layout> -->
  
</template>

<style scoped>

</style>
