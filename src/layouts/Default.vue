<template>
  <div class="layout">
    <div class="content-wrap">
        <header class="header">
            <g-link to="/">
              <g-image alt="Example image" src="~/logo_monoflow-studio.svg" width="200" />
            </g-link>
            <Button />
            <!-- <g-link to="/">{{ $static.metadata.siteName }}</g-link> -->
          <!-- <nav class="nav">
            <g-link class="nav__link" to="/">Home</g-link>
            <g-link class="nav__link" to="/about/">About</g-link>
          </nav> -->
        </header>
        <slot/>
    </div>
    <Footer />
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<script>
  import Footer from '~/components/Footer.vue'
  import Button from '~/components/Button.vue'

  export default {
    components: {
      Footer,
      Button
    }
  }
</script>


<style>
  body {
    font-family: -apple-system,system-ui,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
    margin:0;
    padding:0;
    line-height: 1.5;
  }

  .layout {
    position: relative;
    max-width: 1200px;
    min-height: 100vh;
    margin: 0 auto;
    padding-left: 20px;
    padding-right: 20px;
  }

  .content-wrap {
    padding-bottom: 160px;
  }

  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
    height: 80px;
  }

  .nav__link {
    margin-left: 20px;
  }
</style>
