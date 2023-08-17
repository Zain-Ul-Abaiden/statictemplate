<template>
<Navbar />
<HeroComponent />
<FootBar />
</template>

<script>

import FootBar from '@/components/FootBar.vue';
import HeroComponent from '@/components/HeroComponent.vue';
import Navbar from '@/components/NavBar.vue'

export default {
  name: 'HomeView',

  components: {
    Navbar,
    HeroComponent,
    FootBar
}
}
</script>
