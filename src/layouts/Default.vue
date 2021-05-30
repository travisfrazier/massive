<template>
  <div>
    <Header />
    <slot />
    <Footer />
  </div>
</template>

<script>
import Header from '~/components/Header.vue';
import Footer from '~/components/Footer.vue';

export default {
  components: {
    Header,
    Footer
  }
};
</script>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style lang="scss">
body {
  font-family: $font-style-main;
  margin: 0;
  padding: 0;
  line-height: 1;
  box-sizing: border-box;
}
.container {
  max-width: 1250px;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
}
</style>
