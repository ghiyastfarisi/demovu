<template>
  <section class="container is-fullhd">
    <topbar/>
    <leftbar/>
  </section>
</template>

<script>
import topbar from '~/components/topbar';
import leftbar from '~/components/leftbar';

export default {
  components: {
    topbar,
    leftbar
  }
}
</script>

<style scoped>
</style>
