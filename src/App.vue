<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
@import 'assets/styles/tailwind.postcss';

body, html {
  height: 100%;
}

#app {
  font-family: Inter var,ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Helvetica Neue,Arial,Noto Sans,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
}

.container {
  @apply mx-auto;
}

input,
textarea {
  color: #fff;
  background-color: transparent;
}

input:focus,
textarea:focus {
  outline: none;
}
</style>
