<template>
  <section class="section2">
    <div class="section2__box">
      <p class="section2__title">Medicare Part A</p>
      <a class="section2__link">Learn more</a>
    </div>
    <div class="section2__box">
      <p class="section2__title">Medicare Supplements</p>
      <a class="section2__link">Learn more</a>
    </div>
    <div class="section2__box">
      <p class="section2__title">Perscription Plans</p>
      <a class="section2__link">Learn more</a>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.section2 {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
}
.section2__box {
  text-align: center;
  background: $color-light;
  padding: 24px 0px;
  border-right: 2px solid $color-neutral;
  &:last-of-type {
    border-right: none;
  }
}
.section2__title {
  font-size: $font-l;
  font-weight: 700;
  color: $color-neutral;
  margin-bottom: 16px;
  margin-top: 0px;
}
.section2__link {
  color: $color-neutral;
  font-size: $font-m;
  text-decoration: underline;
  cursor: pointer;
}
</style>
