<template>
  <div class="home">
    <LandingPage msg="Ohvitseride Park"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import LandingPage from '@/components/LandingPage.vue' // @ is an alias to /src

export default defineComponent({
  name: 'HomeView',
  components: {
    LandingPage
  }
})
</script>
