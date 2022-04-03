<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-m ">
	<div class="container-fluid">
		<img src="../assets/img/logo.png"   class="logo">
	<a class="navbar-brand" >Pasteles</a>
	<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
 <span class="navbar-toggler-icon"></span>
 </button>
<div class="collapse navbar-collapse" id="navbarNavAltMarkup">
<div class="navbar-nav">

 <a class="nav-link" >Comprar</a>
 <a class="nav-link" >Administrador</a>
 </div>
</div>
	</div>
      </nav>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({
  props: {

  }
})
export default class menu extends Vue {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.bg-m {
	background-color: #fff;
}


.logo{
	width: 120px;
	height: 90px;
	margin-top:0px;

}
</style>
