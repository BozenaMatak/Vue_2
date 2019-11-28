<template>
<div class="container">
  <div class="row">
    <div class="col-1"></div>

    <div class="col-7">

      <InstagramCard/> 
    </div>
    <div class="col-3">
      <Suggestions/>
      <Stories/>
    </div>
  </div>
  </div>
</template>

<script>
import InstagramCard from '@/components/InstagramCard.vue'
import Suggestions from '@/components/Suggestions.vue'
import Stories from '@/components/Stories.vue'
export default {
  name: 'home',
  components: {
    InstagramCard,
    Suggestions,
    Stories
  }
}
</script>

<style lang="scss">
.card{
  margin-bottom: 20px;

  .card-body{
    padding:0;
  }
}
</style>