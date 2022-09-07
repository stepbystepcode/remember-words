<template>
  <div class="home">
    <MyWords />
  </div>
</template>

<script>
// @ is an alias to /src
import MyWords from '@/components/MyWords.vue'

export default {
  name: 'HomeView',
  components: {
    MyWords
  }
}
</script>
