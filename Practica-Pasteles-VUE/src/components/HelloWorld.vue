<template>
	<div class="text-center">
  <div id="carouselExampleCaptions" class="carousel slide " data-bs-ride="carousel">
	<div class="carousel-indicators">
	<button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
	<button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
	<button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
	</div>
	<div class="carousel-inner">
	<div class="carousel-item active">
	<img src="../assets/img/pastel-s.jpg" class="d-block  slid" alt="...">
	<div class="carousel-caption d-none d-md-block fondos ">
	<h5>Descuentos en compras onlyne</h5>
	<p>10% de descuento en todas tus compras onlyne en el mes de marzo.</p>
	</div>
	</div>
	<div class="carousel-item">
	<img src="../assets/img/pasteles-s2.jpg" class="d-block slid" alt="...">
	<div class="carousel-caption d-none d-md-block fondos">
	<h5>Presentes en tus eventos mas especiales</h5>
	<p>Estamos contigo en tus momentos mas memorables.</p>
	</div>
	</div>
<div class="carousel-item">
	<img src="../assets/img/pasteles-s3.jpg" class="d-block slid" alt="...">
<div class="carousel-caption d-none d-md-block fondos">
<h5>Personalisa a tu estilo</h5>
  <p>Diseña y crea tu propio estilo.</p>
	</div>
	</div>
	</div>
	<button class="carousel-control-prev clas2" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
	<span class="carousel-control-prev-icon" aria-hidden="true"></span>
	<span class="visually-hidden">Previous</span>
	</button>
	<button class="carousel-control-next clas1" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
	<span class="carousel-control-next-icon" aria-hidden="true"></span>
	<span class="visually-hidden">Next</span>
	</button>
      </div>
      </div>


      <h1 class="text-center my-4">Opiniones</h1>
<ul class="list-group">
    <li class="list-group-item">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-4">

                    </div>

                    <div class="col-5">
                        <div class="d-block">
                            <h3 class="h3">Edgar Bryan</h3>
                            <p>Me encanto sin duda el pastel hizo mas especial mi fiesta de cumple años.</p>
                        </div>
                    </div>

                    <div class="col-3">

                    </div>
                </div>
            </div>
    </li>


    <li class="list-group-item">
        <div class="container-fluid">
            <div class="row">
                <div class="col-4">

                </div>

                <div class="col-5">
                    <div class="d-block">
                        <h3 class="h3">Rigo Medrano</h3>
                        <p>Me encanto sin duda el pastel hizo mas especial mi fiesta de cumple años.</p>
                    </div>
                </div>

                <div class="col-3">

                </div>
            </div>
        </div>
</li>


<li class="list-group-item">
    <div class="container-fluid">
        <div class="row">
            <div class="col-4">

            </div>

            <div class="col-5">
                <div class="d-block">
                    <h3 class="h3">Estela Mora</h3>
                    <p>Me encanto sin duda el pastel hizo mas especial mi fiesta de cumple años.</p>
                </div>
            </div>

            <div class="col-3">

            </div>
        </div>
    </div>
</li>


<li class="list-group-item">
    <div class="container-fluid">
        <div class="row">
            <div class="col-4">

            </div>

            <div class="col-5">
                <div class="d-block">
                    <h3 class="h3">Alexander Lopez</h3>
                    <p>Me encanto sin duda el pastel hizo mas especial mi fiesta de cumple años.</p>
                </div>
            </div>

            <div class="col-3">


            </div>
        </div>
    </div>
</li>
</ul>



<h1 class="text-center my-4">Contacto</h1>


    <div class="container fondo ">


        <span class="p-float-label tma mx-4 mt-4">
            <input id="float-input tma" class="tma" type="text" >
            <label for="float-input">Correo</label>
        </span>


        <span class="p-float-label tma mx-4 mt-4">
            <input id="float-input " class="tma" type="text"  >
            <label for="float-input">Nombre</label>
        </span>

        <textarea  class="tma mx-4 mt-4" placeholder="Mensaje"></textarea>

        <button class="btn btn-lg colr float-center mx-4 mt-4">Enviar</button>

    </div>

    <div class="footer mt-4">
    <div class="container-fluid">
        <div class="row">
            <div class="col-4">
                <div class="d-block">
                    <h5>Telefono</h5>
                    <p>4451234556</p>
                </div>
            </div>
            <div class="col-4">
                <div class="d-block">
                    <h5>Direccion</h5>
                    <p>Calle Hidalgo #455 de moroleon GTO.</p>
                </div>
            </div>
            <div class="col-4">
                <div class="d-block">
                    <h5>Horarios</h5>
                    <p>De lunes a domingo de 09:00-16:00</p>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({
  props: {
    msg: String
  }
})
export default class HelloWorld extends Vue {
  msg!: string
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.slid{
	height: 550px;
	width: 70%;
	margin-left: 15%;
	margin-right: 15%;


}

.fondo{
    background-color: rgba(255, 255, 255, 0.322);
    border: 1px rgb(216, 62, 157) solid;
    width: 100%;
    height: 80%;
}

.tma{
    width:80%;
}
.footer{
    width: 100%;
    background-color:#fff;
}
.colr{
    background-color: rgba(216, 48, 238, 0.74);
}

.clas1{
margin-right: 15%;
}

.clas2{
	margin-left: 15%;
	}

	.fondo{
		background-image: url(../assets/img/fondo.jpg);
	}


</style>
