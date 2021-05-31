<template>
  <section class="section1">
    <div class="container section1__content">
      <p class="section1__content--title">
        Find &#38; compare your local<br> plans and prividers fast
      </p>
      <p class="section1__content--text">
        Let us help you find the right Medicare Supplement Coverage plan for
        you. In less than 1 minute you could be saving your deductables, co-pays
        and Medicare bills.
      </p>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.section1 {
  padding: 100px 0px;
  background: url('../assets/bg-1.jpg');
  background-size: cover;
  background-position: center;
  display: flex;
  align-items: center;
}
.section1__content--title {
  color: $color-dark;
  font-size: $font-l;
  font-weight: 700;
  margin: 0 0 16px 0;
  text-transform: capitalize;
}
.section1__content--text {
  font-size: $font-s;
  width: 65%;
  line-height: 1.5;
  color: $color-font-one;
  margin-bottom: 0px;
}
</style>
