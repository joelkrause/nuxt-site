<template>
  <main>
    <section class="intro">
      <div class="intro_text">
        <p>Hey, I'm Joel and i'm a frontend developer from Melbourne, Australia.</p>
        <p>I work at raak creative building beautiful headless sites with wordpess and nuxt.js</p>
      </div>
    </section>
    <Social />
  </main>
</template>

<script>
import Header from '~/components/Header.vue'
import Social from '~/components/Social.vue'

export default {
  components: {
    Header,
    Social
  }
}
</script>

<style lang="scss" scoped>
.intro{}
</style>