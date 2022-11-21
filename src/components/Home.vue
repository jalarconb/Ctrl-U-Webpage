<template>
  <div class="home">
    <div class="menu">
      <div class="menu-item">
        Inicio
      </div>
      <div class="menu-item">
        Transacciones
      </div>
      <div class="menu-item">
        Info
      </div>
    </div>
    <div class="logo">
      <img src="../assets/ctrlu-logo.png">
      <!-- <img src="../assets/ctrlu-logo.png"> -->
    </div>

    <div class="hello">
      Hola xd
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
  margin-top: 10px;
}

.menu-item {
  border: 3px solid blue;
  flex: 1;
  text-align: center;
}

.logo {
  border: 3px solid red;
  display: flex;
  align-content: left;
  justify-content: left;
  vertical-align: middle;
  /* width: ; */
  /* height: 90vh; */
}

</style>
