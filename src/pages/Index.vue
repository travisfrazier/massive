<template>
  <Layout>
    <Hero />
    <Section-1 />
    <Section-2 />
    <Section-3 />
    <Section-4 />
  </Layout>
</template>

<script>
import Hero from '../components/Hero';
import Section1 from '../components/Section1.vue';
import Section2 from '../components/Section2.vue';
import Section3 from '../components/Section3.vue';
import Section4 from '../components/Section4.vue';


export default {
  metaInfo: {
    title: 'Massive'
  },
  components: {
    Hero,
    Section1,
    Section2,
    Section3,
    Section4
  }
}
</script>

<style lang="scss">
.home-links a {
  margin-right: 1rem;
}
</style>
