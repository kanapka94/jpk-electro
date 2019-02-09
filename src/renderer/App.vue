<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'jpk-client'
}
</script>

<style>
  @font-face {
    font-family: "Nunito";
    src: url('assets/scss/fonts/Nunito-Light.ttf') format('truetype');
    font-weight: 300;
  }

  @font-face {
    font-family: "Nunito";
    src: url('assets/scss/fonts/Nunito-Regular.ttf') format('truetype');
    font-weight: normal;
  }

  @font-face {
    font-family: "Nunito";
    src: url('assets/scss/fonts/Nunito-Bold.ttf') format('truetype');
    font-weight: bold;
  }

	* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
	}

  body {
	  font-family: 'Nunito', sans-serif;
	}
</style>