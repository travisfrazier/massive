<template>
  <section id="section5" class="section5">
    <div class="section5__content container">
      <div class="section5__content--left">
        <img class="section5__content--image" src="../assets/image-3.svg" />
      </div>
      <div class="section5__content--right">
        <h3 class="section5__content--title">Perscription Plans</h3>
        <p class="section5__content--text">
          It is administered by the federal government. The plan has two parts:
          A and B. Part A is referred to as hospital insurance and covers care
          at hospitals (inpatient) and skilled nursing facilities as well as
          hospice care and some home health care. Part B is medical insurance
          and covers doctors’ services (at their offices and at hospitals),
          preventive care, and medical supplies.
        </p>
        <button class="section5__content--button">Find Plans</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.section5 {
  background: $color-bg-three;
  padding: 80px 0px;
}
.section5__content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 85px;
  align-items: center;
  height: 100%;
  @media only screen and (max-width: 900px) {
    grid-template-columns: 1fr;
    gap: 20px;
  }
}
.section5__content--image {
  width: 100%;
}
.section5__content--title {
  color: $color-light;
  font-weight: 700;
  font-size: $font-xl;
  margin-bottom: 40px;
}
.section5__content--text {
  color: $color-font-one;
  font-size: $font-m;
  margin-bottom: 40px;
  margin-top: 0px;
  line-height: 1.5;
}
.section5__content--button {
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
