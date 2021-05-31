<template>
  <footer class="footer">
    <div class="container footer__content">
      <p class="footer__text">
        Copyright © 2021 SimpleMedicareCoverage. All rights reserved
      </p>
      <ul class="footer__list">
        <li class="footer__list--item">
          <g-link class="footer__list--link" to="/">Disclaimer</g-link>
        </li>
        <li class="footer__list--item">
          <g-link class="footer__list--link" to="/"
            >Terms &#38; Conditions</g-link
          >
        </li>
        <li class="footer__list--item">
          <g-link class="footer__list--link" to="/">Contact us</g-link>
        </li>
        <li class="footer__list--item">
          <g-link class="footer__list--link" to="/">Privacy Policy</g-link>
        </li>
      </ul>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.footer {
  background: $color-bg-two;
  padding: 30px 0px;
}
.footer__content {
  display: flex;
  justify-content: space-between;
  align-items: center;
  @media only screen and (max-width: 768px) {
    flex-direction: column;
    text-align: center;
    justify-content: center;
  }
}
.footer__text {
  color: $color-neutral;
  font-weight: 600;
  font-size: $font-s;
}
.footer__list {
  display: flex;
  list-style-type: none;
}
.footer__list--item {
  border-right: 2px solid $color-neutral;
  padding: 0px 6px;
  &:last-of-type {
    border-right: none;
  }
}
.footer__list--link {
  color: $color-neutral;
  font-weight: 600;
  font-size: $font-s;
  text-decoration: none;
}
</style>
