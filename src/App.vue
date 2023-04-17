<template>

<nav class="navbar navbar-expand navbar-light bg-light">
    <div class="nav navbar-nav">
        <router-link to="/CrearView" class = "nav-link">Crear</router-link>
        <router-link to="/ListarView" class = "nav-link">Empleados</router-link>
    </div>
</nav>
  <router-view/>
</template>

