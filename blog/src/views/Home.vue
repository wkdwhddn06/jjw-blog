<template>
  <div class="home">
    <Profile msg="PROFILE"/>
    <Develop/>
    <Design/>
  </div>
</template>

<script>
// @ is an alias to /src
import Profile from '@/components/Profile.vue'
import Develop from '@/components/Develop.vue'
import Design from '@/components/Design.vue'

export default {
  name: 'home',
  components: {
    Profile,
    Develop,
    Design
  }
}
</script>
