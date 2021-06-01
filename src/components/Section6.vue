<template>
  <section class="section6">
    <div class="section6__content container">
      <div class="section6__content--left">
        <h3 class="section6__content--title">
          Talk directly to a licensed insurance agency in your area!
        </h3>
        <p class="section6__content--text">
          We're dedicated to helping you find the right Medicare Supplement
          Insurance. If you're looking to lower your out-of-pocket expenses or
          expand your current Medicare coverage, we have Licensed Insurance
          Agents available to provide expert advice and guidance. Let us walk
          you through the process!
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
  overflow: hidden;
  @media only screen and (max-width: 900px) {
    padding-bottom: 100px;
  }
}
.section6__content {
  display: grid;
  grid-template-columns: 1.5fr 1fr;
  gap: 85px;
  align-items: center;
  height: 100%;
  @media only screen and (max-width: 900px) {
    grid-template-columns: 1fr;
    gap: 60px;
  }
}

.section6__content--title {
  color: $color-neutral;
  font-weight: 700;
  font-size: $font-xl;
  margin-bottom: 40px;
  margin-top: 0px;
}
.section6__content--right {
  background: url('../assets/person-3.jpg');
  height: 100%;
  background-size: cover;
  left: 60%;
  bottom: 0;
  position: absolute;
  width: 40vw;
  background-position: right center;
  @media only screen and (max-width: 900px) {
    position: static;
    background-position: 75% center;
    height: 500px;
    width: 100%;
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
