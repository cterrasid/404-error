<template>
  <div id="app">
    <div class="container">
      <h1 class="title">404 Not Found</h1>
      <div class="content">
        <section class="image">
          <img src="./assets/moon.png" alt="Far side of the moon" />
        </section>
        <section class="text">
          <h2>¡Ay no! ¿Qué haces aquí?</h2>
          <p class="message">
            Has llegado a la cara
            <strong>oculta</strong> de la luna. En este lugar no existen páginas
            <em>por ahora</em>, así que puedes:
          </p>
          <div class="buttons">
            <button>Ojo</button>
            <button>Volver a casa</button>
            <button>¡Avísame!</button>
          </div>
        </section>
      </div>
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

.title {
  align-self: flex-start;
  font-family: monospace;
  font-size: 12px;
  text-transform: uppercase;
  width: 100%;
}

.container {
  align-items: center;
  background-color: black;
  color: beige;
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: space-evenly;
  padding: 20px;
}

.content {
  align-items: center;
  display: flex;
  flex-direction: column;
  height: 100%;
  justify-content: center;
}

.image img {
  height: 100px;
}

.text h2 {
  text-align: center;
}

.buttons {
  display: flex;
  justify-content: space-evenly;
  margin: 20px;
}

@media screen and (min-width: 768px) {
  .content {
    flex-direction: row;
  }

  .text h2 {
    text-align: start;
  }

  .buttons {
    justify-content: space-between;
    margin: 15px 0;
    width: 200px;
  }
}
</style>
