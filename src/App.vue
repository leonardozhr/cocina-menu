
<template>
  <div class="alert alert-primary" role="alert">
  Leonardo Zacateco Hernández Leonardo --- 10° "A" 
  </div>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Fonda don Cheto </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Postres</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">No hay </a>
      </li>
    </ul>
  </div>
</nav>

<hr/>
<h1>Menu</h1>
<hr/>

  <card url="https://img.freepik.com/foto-gratis/tacos-mexicanos-carne-res-salsa-tomate-salsa_2829-14218.jpg?w=1380&t=st=1663893580~exp=1663894180~hmac=5984a70402dc67c6a25704a5ab6392cebec8c886a241f805a1872172b6ee0d31" 
    nombre="Tacos" descripcion="3 tacos de carne de cerdo" costo="25 mxn"/>
  <card url="https://img.freepik.com/fotos-premium/mole-enchiladas-comida-mexicana-salsas-chile_79295-18553.jpg?w=1380" nombre="Enchiladas" descripcion="Enchiladas de mole con pollo" costo="45 mxn"/>
  <card url="https://img.freepik.com/fotos-premium/chiles-nogada-cocina-tradicional-mexicana-puebla-mexico_137422-3.jpg?w=1380" nombre="Chile en nogada" descripcion="Chile poblano en nogada" costo="80 mxn"/>
  <card url="https://img.freepik.com/fotos-premium/pozole-mote-guiso-maiz-grande-mexico_79295-5184.jpg?w=1380" nombre="Pozole" descripcion="Pozole rojo con pollo" costo="60 mxn"/>
  <card url="https://img.freepik.com/foto-gratis/arroz-tradicional-mexicano-servido-guisantes-verdes-mesa-madera_123827-20472.jpg?w=1380&t=st=1663893594~exp=1663894194~hmac=12edcaf85d4f2d11c651525c21a57f619a4017ddeefe26a4c83e4137f85eb81a" 
   nombre="Arroz" descripcion="Arroz rojo con verduras" costo="20 mxn"/>
  <card url="https://img.freepik.com/foto-gratis/burritos-envueltos-carne-picada-verduras-sobre-superficie-madera_2829-8275.jpg?w=1060&t=st=1663893595~exp=1663894195~hmac=e986d0abbb387eb4decf25ff37d5c859498d355ca661853ee43d96e25e2e78eb" 
   nombre="Burrito" descripcion="Burrito de carne asada" costo="60 mxn"/>

<hr/>
<div class="card text-center">
  <div class="card-header">
    Menu del dia
  </div>
  <div class="card-body">
    <h5 class="card-title">Atendemos de lunes a viernes </h5>
    <p class="card-text">Cualquier sugerencia o queja al siguente numero 324875913485</p>
    
  </div>
  <div class="card-footer text-muted">
    de 8 hrs a 15 hrs
  </div>
</div>

</template>

<script>
  import Card from "./components/Card.vue";

  export default{
    components:{Card},
  };
</script>