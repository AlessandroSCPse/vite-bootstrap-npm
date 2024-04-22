<script>
import AppHeader from './components/AppHeader.vue';

export default {
  components: {
    AppHeader
  }
}
</script>

<template>
  <AppHeader></AppHeader>

  <div class="container">
    <div class="row row-cols-2">
      <div class="col">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sint obcaecati, delectus officiis magnam ipsum minima perspiciatis soluta, at, nesciunt possimus quam iure harum tempora sequi itaque id hic impedit earum.
      </div>
      <div class="col">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sint obcaecati, delectus officiis magnam ipsum minima perspiciatis soluta, at, nesciunt possimus quam iure harum tempora sequi itaque id hic impedit earum.
      </div>
    </div>
  </div>
</template>

<style lang="scss">
@use './style/generic';
</style>