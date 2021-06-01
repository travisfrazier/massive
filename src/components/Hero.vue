<template>
  <section class="hero">
    <div class="container">
      <div class="hero__content--wrapper">
        <div class="hero__content">
          <div class="hero__content--top">
            <h2 class="hero__content--titleOne">Find Medicare Coverage</h2>
          </div>
          <div class="hero__content--bottom">
            <h3 class="hero__content--titleTwo">
              Compare <strong>Medicare Plans</strong><br> in one minute!
            </h3>
            <form class="hero__form">
              <label class="hero__form--label">Enter Your Zip Code</label>
              <input required class="hero__form--input" id="zip" name="zip" type="text" pattern="[0-9]*">
              <button class="hero__form--button" type="submit">Get Started</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.hero {
  height: 540px;
  background: url('../assets/hero-massive.jpg');
  background-size: cover;
  background-position: left;
  position: relative;
  @media only screen and (max-width: 900px) {
    height: 700px;
    display: flex;
    align-items: center;
  }
}
.hero__content--wrapper {
  display: flex;
  justify-content: flex-end;
  align-items: flex-end;
}
.hero__content {
  position: absolute;
  bottom: -30px;
  width: 600px;
  @media only screen and (max-width: 900px) {
    bottom: 20px;
    width: 100%;
    position: static;
    opacity: .85;
  }
}
.hero__content--top {
  background: $color-light;
  padding: 44px 0px;
  text-align: center;
  border-radius: 10px 10px 0px 0px;
  @media only screen and (max-width: 900px) {
    padding: 30px 0px;
  }
}
.hero__content--titleOne {
  color: $color-neutral;
  font-size: $font-xl;
  font-weight: 800;
  text-transform: capitalize;
  margin: 0;
  @media only screen and (max-width: 900px) {
    font-size: $font-l;
  }
}
.hero__content--titleTwo {
  margin: 0;
  color: $color-font-two;
  font-size: $font-l;
  text-align: center;
  margin: 0 0 30px 0;
  font-weight: 400;
  @media only screen and (max-width: 900px) {
    font-size: $font-m;
  }
}
.hero__content--bottom {
  background: $color-dark;
  border-radius: 0px 0px 10px 10px;
  padding: 24px 48px 48px 48px;
  @media only screen and (max-width: 900px) {
    padding: 16px 30px 30px 30px;
  }
}
.hero__form {
  display: flex;
  background: $color-neutral;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 38px 38px 19px 38px;
  border-radius: 5px;
}
.hero__form--input {
  padding: 18px;
  margin-bottom: 12px;
  width: 100%;
  border-color: $color-action-two;
  border-radius: 4px;
  &:focus {
    outline: none;
  }
}
.hero__form--label {
  margin-bottom: 12px;
  color: $color-dark;
  font-size: $font-m;
}
.hero__form--button {
  background: $color-action;
  text-transform: uppercase;
  font-size: $font-btn;
  color: $color-neutral;
  border: none;
  border-radius: 5px;
  padding: 8px 34px;
  font-weight: 700;
  cursor: pointer;
  @media only screen and (max-width: 900px) {
    font-size: $font-s;
  }
}
</style>
