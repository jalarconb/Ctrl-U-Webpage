<template>

  <div id="nav" class="menu">
    <router-link to="/" class="menu-item">
      Inicio
    </router-link>

    <div class="logo">
      <img src="@/assets/ctrlu-logo.png">
    </div>

    <router-link to="/transactions" class="menu-item">
      Transacciones
    </router-link>
  </div>

  <router-view/>

</template>

<!-- -------------------------------------------------------------------------------------------------- -->

<style>

:root {
  /* Paleta de Colores */
  --orange: #FF731D;
  --light-orange: #FFF7E9;
  --gold: #f8b02e;
  --dark-blue: #001d2f;
  --blue: #1746A2;
  --light-blue: #5F9DF7;
}

html {
  background: lightgray;
}

#app {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  text-align: center;
  
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  color: var(--dark-blue);
}

.menu {
  display: flex;
  align-items: center;
  justify-content: space-around;

  background: white;
  border-top: 8px solid var(--blue);
  border-bottom: 8px solid var(--gold);

  margin-top: 30px;
  padding-bottom: 10px;
}

/* .menu-item { */
#nav a.menu-item {
  /* border: 3px solid blue; */
  flex: 1;
  text-align: center;
  cursor: pointer;

  font-size: 30px;
  font-style: italic;
  font-weight: bold;
  text-decoration: inherit;
  color: var(--dark-blue);

  padding: 10px;
  margin-inline: 30px;
  border-bottom: 3px solid var(--orange);
}

#nav a.menu-item:hover {
  color: #3c7dff;
  border-bottom: 3px solid var(--blue);
}

#nav a.router-link-active {
  /* color: #3c7dff; */
  color: var(--dark-blue);
  background: linear-gradient(#f8b02e00, #ffca6980);
}

.logo {
  /* border: 3px solid red; */
  display: flex;
  align-content: center;
  justify-content: center;
  vertical-align: middle;
  height: 220px;
}

</style>