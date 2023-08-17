<template>
<Navbar />
<HeroComponent />
</template>

<script>

import HeroComponent from '@/components/HeroComponent.vue';
import Navbar from '@/components/Nav.vue'

export default {
  name: 'HomeView',

  components: {
    Navbar,
    HeroComponent
}
}
</script>
