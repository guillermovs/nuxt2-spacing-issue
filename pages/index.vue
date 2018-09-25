<template>
  <section class="container">

  <!-- START: These elements should be displayed inline, but a space appears in between them, breaking them into two lines -->
    <section class="inline-block">
      Inline-block left
    </section>

    <section class="inline-block">
      Inline-block right
    </section>
    <!-- END -->

  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>

.inline-block{
  display:inline-block;
  width: 50%;
}

.container{
  width:100%;
}

</style>
