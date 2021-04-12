<template>
  <div class="footer">
    <div class="column large-4 medium-6 small-12">
        <p><strong>monoflow.</strong>studio</p>
    </div>
    <div class="column large-4 medium-6 small-12">
        <p>Leverkusenstraße 8</p>
        <p>22761 Hamburg</p>
        <p>Deutschland</p>
    </div>
    <div class="column large-4 medium-6 small-12">
        <p><a href="">hello@monoflow.studio</a></p>
    </div>
    <div class="column large-4 medium-6 small-12 social-media">
        <p><a href="" target="_blank" rel="noopener">Twitter</a></p>
        <p><a href="" target="_blank" rel="noopener">LinkedIn</a></p>
        <p><a href="" target="_blank" rel="noopener">Dribbble</a></p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style>
    .footer {
        position: absolute;
        bottom: 0;
        width: 100%;
        height: 160px;
        display: flex;
        /* padding: 80px 0; */
        font-family: 'Poppins', sans-serif;
        font-size: 1.25rem;

    }
    .column {
      flex-grow: 1;
    }

    a, p {
        margin-block-start: .5em;
        margin-block-end: .5em;
        margin-inline-start: 0px;
        margin-inline-end: 0px;
        color: #29303D;
    }

    a:hover {
        color: #0055FF;
    }
</style>