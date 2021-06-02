<template>
  <header class="header">
    <div class="container header__content">
      <div class="header__logo">
        <img class="header__logo--img" src="../assets/logo.svg" />
      </div>
      <div class="header__contact">
        <img class="header__contact--img" src="../assets/phone.svg" />
        <div class="header__contact--num">
          <a class="header__contact--tel" href="tel:+18663687202"
            >866-768-7202</a
          >
          <div class="header__contact--box">
            <img class="header__contact--ellipse" src="../assets/ellipse.svg" />
            <span class="header__contact--text">Live agents available now</span>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.header {
  padding-top: 16px;
  padding-bottom: 16px;
}
.header__logo {
  display: flex;
}
.header__logo--img {
  width: 300px;
  align-self: center;
  @media only screen and (max-width: 900px) {
    width: 100%;
    width: 200px;
  }
  @media only screen and (max-width: 500px) {
    width: 150px;
  }
}
.header__content {
  display: flex;
  justify-content: space-between;
  @media only screen and (max-width: 900px) {
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 24px;
  }
  @media only screen and (max-width: 500px) {
    gap: 10px;
  }
}
.header__contact--img {
  width: 45px;
  margin-right: 12px;
  @media only screen and (max-width: 900px) {
    width: 25px;
  }
  @media only screen and (max-width: 500px) {
    width: 20px;
    align-self: center;
  }
}
.header__contact {
  display: flex;
  align-items: center;
  @media only screen and (max-width: 900px) {
    justify-self: end;
  }
}
.header__contact--num {
  display: flex;
  flex-direction: column;
  white-space: nowrap;
  @media only screen and (max-width: 500px) {
    white-space: normal;
  }
}
.header__contact--tel {
  text-decoration: none;
  color: $color-action-two;
  font-weight: 700;
  font-size: $font-l;
  letter-spacing: 1.2px;
  @media only screen and (max-width: 900px) {
    font-size: $font-m;
  }
  @media only screen and (max-width: 500px) {
    font-size: $font-s;
  }
}
.header__contact--text {
  text-transform: capitalize;
  color: $color-action-two;
  font-weight: 700;
  font-size: $font-s;
   @media only screen and (max-width: 900px) {
    font-size: $font-xs;
  }
}
.header__contact--box {
  display: flex;
  align-items: center;
}
.header__contact--ellipse {
  width: 10px;
  margin-right: 4px;
  @media only screen and (max-width: 500px) {
    display: none;
  }
}
</style>
