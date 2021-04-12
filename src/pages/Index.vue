<template>
  <Layout>

    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <!-- <g-image alt="Example image" src="~/logo_monoflow-studio.png" width="400" /> -->

  <Stage />


  </Layout>
</template>

<script>
import Stage from '~/components/Stage.vue'

export default {
    metaInfo: {
        title: 'monoflow.studio | Home'
    },
    components: {
        Stage
    }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
