<template>
  <g-link class="logo" to="/">
    <g-image
      class="logo_image"
      alt="Logo image"
      src="~/assets/images/ace_ohio.png"
      height="70"
      width="70"
    />
  </g-link>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style lang="scss">
.logo {
  text-decoration: none;
  color: var(--body-color) !important;
  font-size: 0.9em;
  margin-top: 0.4rem;
  &__image {
    vertical-align: middle;
    border-radius: 99px;
    height: 40px;
    width: 40px;
    margin-right: 0.5em;
  }
}
</style>
