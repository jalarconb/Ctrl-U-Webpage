<template>
  <div class="transactions">
    
    <div class="title">
      Últimas Transacciones Registradas
    </div>
    
    <table>
      <tr>
        <th>Fecha Transacción</th>
        <th>Remitente</th>
        <th>Destinatario</th>
        <th>Valor</th>
        <th>Concepto</th>
        <th>Código de Verificación</th>
      </tr>
      <tr>
        <td>Hoy xd</td>
        <td>Rem1</td>
        <td>Rem2</td>
        <td>$1.000</td>
        <td>Pan xd</td>
        <td>1234567890</td>
      </tr>
    </table>
  </div>

</template>

<!-- -------------------------------------------------------------------------------------------------- -->

<script>
export default {

}
</script>

<!-- -------------------------------------------------------------------------------------------------- -->

<style scoped>

.transactions {
  background: white;
  
  margin-top: 30px;
  padding: 30px;
  margin-inline: 10% 10%;
}

.title {
  font-size: 5vh;
  font-style: italic;
  font-weight: 500;

  padding-bottom: 30px;
}

table {
  margin-inline: auto;
  text-align: center;

  font-size: 2.4vh;

  background: lightgray;
}

tr {
  background: white;
}

th {
  font-style: italic;
  
  background: darkgray;

  padding-inline: 20px;
  padding-top: 5px;
  padding-bottom: 5px;
}

td {
  padding-top: 2px;
  padding-bottom: 2px;
}

</style>
