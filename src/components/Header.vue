<template>
  <h1 class="header">Butterfly Hunt</h1>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
/* pacifico-regular - latin */
@font-face {
  font-family: "Pacifico";
  font-style: normal;
  font-weight: 900;
  src: url("../fonts/pacifico-v16-latin-regular.eot"); /* IE9 Compat Modes */
  src: local("Pacifico Regular"), local("Pacifico-Regular"),
    url("../fonts/pacifico-v16-latin-regular.eot?#iefix")
      format("embedded-opentype"),
    /* IE6-IE8 */ url("../fonts/pacifico-v16-latin-regular.woff2")
      format("woff2"),
    /* Super Modern Browsers */ url("../fonts/pacifico-v16-latin-regular.woff")
      format("woff"),
    /* Modern Browsers */ url("../fonts/pacifico-v16-latin-regular.ttf")
      format("truetype"),
    /* Safari, Android, iOS */
      url("../fonts/pacifico-v16-latin-regular.svg#Pacifico") format("svg"); /* Legacy iOS */
}

.header {
  color: white;
  font-family: Pacifico;
  font-size: 4.2em;
  padding: 0em;
  margin-top: 0;
  margin-bottom: 0;
  text-shadow: 0 0 1px #011502, 0 0 5px #011502, 0 0 10px #01200f,
    0 0 20px #01200f, 0 0 25px #32746d, 0 0 30px #32746d;
}
</style>
