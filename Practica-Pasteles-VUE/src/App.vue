<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-m ">
	<div class="container-fluid">
		<img src="../src/assets/img/logo.png"   class="logo">
	<a class="navbar-brand" >Pasteles</a>
	<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
 <span class="navbar-toggler-icon"></span>
 </button>
<div class="collapse navbar-collapse" id="navbarNavAltMarkup">
<div class="navbar-nav">

    <router-link to="/" class="mx-4">Home</router-link>
    <router-link to="/about" class="mx-4">Comprar</router-link>
    <router-link to="/about" class="mx-4">Administrar</router-link>
 </div>
</div>
	</div>
      </nav>
  <nav>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #FFB6C1;
}

.bg-m {
	background-color: #fff;
}


.logo{
	width: 120px;
	height: 90px;
	margin-top:0px;

}
</style>
