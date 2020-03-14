<template>
  <main>
    <section class="intro">
      <div class="intro_text">
        <p>Hey, I'm Joel and i'm a frontend developer from Melbourne, Australia.</p>
        <p>I work at <a href="https://raak.com.au" target="_blank">raak creative</a> building beautiful headless sites with nuxt.js</p>
      </div>
    </section>
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
main{
    padding: 2rem;
    @media (min-width:1280px){
        max-width: 60vw;
    }
}
.intro{
  line-height: 1.5;
  a{
    color: currentColor;
  }
}
</style>