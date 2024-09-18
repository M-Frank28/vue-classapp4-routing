<template>
<div>

  <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <router-Link class="navbar-brand" to="#">ClassApp routing</router-Link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <router-Link class="nav-link active" aria-current="page" to="/home">Home</router-Link>
        </li>
        <li class="nav-item">
          <router-Link class="nav-link" to="/services">services</router-Link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/contact">Contact</router-link>
        </li>
       
      </ul>
    </div>
  </div>
</nav>

</div>

<router-view/>

</template>


<script>

export default{

  name:'App'

}

</script>


<style scoped>

</style>