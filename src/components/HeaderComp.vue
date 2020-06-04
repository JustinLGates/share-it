<template>
  <header class="bg-primary text-light container-fluid sticky-top shadow">
    <div class="row">
      <div class="col-md-8 col-12 text-md-left">
        <img class="smlogo" src="../assets/logo.png" alt />
        <h1 class>Hoy tatoo</h1>
      </div>

      <div class="col-md-4 col-12 text-md-right">
        <nav id="nav" class>
          <router-link class="btn btn-dark m-2" to="/">Home</router-link>
          <router-link class="btn btn-dark m-2" to="/about">About</router-link>
        </nav>
      </div>
    </div>
  </header>
</template>


<script>
export default {};
</script>

<style scoped>
.smlogo {
  padding: 0px;
  margin: 0px;
  display: inline;
  max-height: 45px;
  max-width: 45px;
}
h1 {
  display: inline;
}
</style>