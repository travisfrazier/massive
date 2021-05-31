<template>
  <section class="section6">
    <div class="section6__content container">
      <div class="section6__content--left">
        <h3 class="section6__content--title">Medicare Supplements</h3>
        <p class="section6__content--text">
          Recipients of Traditional Medicare can purchase Medicare supplements
          (also known as Medigap) from private companies. It is Used for health
          care costs not covered by Traditional Medicare (copayments,
          deductibles, etc.) Supplements correspond with different levels of
          coverage and work with with your original Part A and B benefits. You
          will pay an additional monthly premium for Medigap. (at their offices
          and at hospitals), preventive care, and medical supplies.
        </p>
      </div>
      <div class="section6__content--right"></div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.section6 {
  background: $color-bg-one;
  position: relative;
  padding-top: 100px;
  padding-bottom: 190px;
}
.section6__content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 85px;
  align-items: center;
  height: 100%;
  @media only screen and (max-width: 768px) {
    grid-template-columns: 1fr;
  }
}

.section6__content--title {
  color: $color-neutral;
  font-weight: 700;
  font-size: $font-xl;
  margin-bottom: 40px;
  margin-top: 0px;
}
.section6__content--image {
  object-fit: cover;
}
.section6__content--right {
  background: url('../assets/person-3.jpg');
  width: 100%;
  height: 100%;
  background-size: cover;
  background-position: right 10%;
  width: 100%;
  height: 100%;
  background-size: cover;
  left: 50%;
  bottom: 0;
  position: absolute;
  width: 50vw;
  @media only screen and (max-width: 768px) {
    grid-template-columns: 1fr;
  }
}
.section6__content--text {
  color: $color-neutral;
  font-size: $font-m;
  margin-bottom: 0px;
  margin-top: 0px;
  line-height: 1.5;
}
</style>
