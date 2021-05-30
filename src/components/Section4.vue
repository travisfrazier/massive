<template>
  <section class="section4">
    <div class="section4__content container">
      <div class="section4__content--left">
        <h3 class="section4__content--title">Medicare Supplements</h3>
        <p class="section4__content--text">
          Recipients of Traditional Medicare can purchase Medicare supplements
          (also known as Medigap) from private companies. It is Used for health
          care costs not covered by Traditional Medicare (copayments,
          deductibles, etc.) Supplements correspond with different levels of
          coverage and work with with your original Part A and B benefits. You
          will pay an additional monthly premium for Medigap. (at their offices
          and at hospitals), preventive care, and medical supplies.
        </p>
        <button class="section4__content--button">Find Plans</button>
      </div>
      <div class="section4__content--right">
        <img class="section4__content--image" src="../assets/image-2.svg" />
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.section4 {
  background: $color-neutral;
  height: 750px;
}
.section4__content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 85px;
  align-items: center;
  height: 100%;
}
.section4__content--title {
  color: $color-light;
  font-weight: 700;
  font-size: $font-xl;
  margin-bottom: 40px;
}
.section4__content--text {
  color: $color-font-one;
  font-size: $font-m;
  margin-bottom: 40px;
  margin-top: 0px;
  line-height: 1.5;
}
.section4__content--button {
  background: $color-action;
  text-transform: uppercase;
  font-size: $font-btn;
  color: $color-neutral;
  border: none;
  border-radius: 5px;
  padding: 8px 34px;
  font-weight: 700;
  cursor: pointer;
}
</style>
