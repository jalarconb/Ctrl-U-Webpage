<template>
  <div class="home">

    <div class="menu">
      <div class="menu-item">
        Inicio
      </div>
      <div class="menu-item">
        Transacciones
      </div>

      <div class="logo">
        <img src="../assets/ctrlu-logo.png">
      </div>

      <div class="menu-item">
        Transacciones
      </div>
      <div class="menu-item">
        About
      </div>
    </div>

  </div>

</template>

<!-- -------------------------------------------------------------------------------------------------- -->

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- -------------------------------------------------------------------------------------------------- -->

<style scoped>

.menu {
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-top: 30px;
}

.menu-item {
  /* border: 3px solid blue; */
  flex: 1;
  text-align: center;
  cursor: pointer;

  font-size: 30px;
  color: var(--text-color);

  padding: 10px;
  border-bottom: 3px solid white;
}

.menu-item:hover {
  border-bottom: 3px solid blue;
}

.logo {
  border: 3px solid red;
  display: flex;
  align-content: center;
  justify-content: center;
  vertical-align: middle;
}

</style>
