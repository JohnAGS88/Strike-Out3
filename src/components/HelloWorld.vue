<template>
  <div class="hello">
    <nav class="navbar  bg-dark">
      <a class="navbar-brand" href="#"></a>
    </nav>
    <h1>{{ msg }}</h1>
    <h3>Tabla de Empleados</h3>
    <table class="table table-hover table-bordered">
  <thead class="table-dark">
    <tr>
      <th scope="col">Nombre Empleado</th>
      <th scope="col">Fecha</th>
      <th scope="col">Tipo</th>
      <th scope="col">Hora</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">Jacob James</th>
      <td>22/05/2021</td>
      <td>Seguridad</td>
      <td>07:05 am</td>
    </tr>
    <tr>
      <th scope="row">Sofia Reyes</th>
      <td>02/05/2021</td>
      <td>Gerente</td>
      <td>08:35 am</td>
    </tr>
     <tr>
      <th scope="row">Milki Gomez</th>
      <td>09/04/2021</td>
      <td>Ayudante</td>
      <td>08:00 am</td>
    </tr>
  </tbody>
</table>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>


<style scoped>
.table{ 
  margin-left: 34.5%;
  margin-top: 60px;
  width: 30%;
 
}
</style>
