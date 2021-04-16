<template>
  <div class="row footer">
    <div class="col-lg-3 col-md-6 col-sm-6 col-xs-12">
      <p><strong>monoflow.</strong>studio</p>
    </div>
    <div class="col-lg-3 col-md-6 col-sm-6 col-xs-12">
      <p>Leverkusenstraße 8</p>
      <p>22761 Hamburg</p>
      <p>Deutschland</p>
    </div>
    <div class="col-lg-3 col-md-6 col-sm-6 col-xs-12">  
      <p><a href="">hello@monoflow.studio</a></p>
    </div>
    <div class="col-lg-3 col-md-6 col-sm-6 col-xs-12">
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

<style lang="scss" scoped>
    @import "~/assets/colors.scss";

    .footer {
      font-size: 1.25rem;

      a, p {
          margin-block-start: .5em;
          margin-block-end: .5em;
          margin-inline-start: 0px;
          margin-inline-end: 0px;
          color: $Dark;
      }

      a {
        transition: all 300ms ease-in-out;

        &:hover {
          color: $Blue-50;
        }
      }
    }

</style>