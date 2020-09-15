<template>
  <div id="app">
    <div class="container">
      <section class="image">Image</section>
      <section class="text">
        <h1>¡Ay no!</h1>
        <p class="message">Has llegado a la cara "oculta" de la luna ¿Qué haces aquí?. En este lugar no existen webs <em>por ahora</em>, así que puedes:</p>
        <div class="buttons">
          <button>Ojo</button>
          <button>Volver a casa</button>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
* {
  box-sizing: border-box;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  margin: 0;
  padding: 0;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
}

.container {
  background-color: plum;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}
</style>
