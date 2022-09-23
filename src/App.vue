<script setup>

</script>

<template>
<div class="container-fluid">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
      <img src="./img/Logo.png" alt="LogoCocina" width="125" height="125">
      <a class="navbar-brand" href="#">La Cocina</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="#">Desayunos</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Comida</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Cena</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Especialidades</a>
          </li>
        </ul>
      </div>
      </div>
    </nav>
</div>
<br>
<div class="card-deck">
<div class="row row-cols-1 row-cols-md-3 g-4 card-deck">

  <div class="card">
    <img class="card-img-top" src="./img/comida1.jpg" alt="...">
    <div class="card-body">
      <h5 class="card-title">spaghetti</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
    </div>
    <div class="card-footer">
      <small class="text-muted">$100</small>
    </div>
  </div>
  <div class="card">
    <img class="card-img-top" src="./img/comida2.png" alt="...">
    <div class="card-body">
      <h5 class="card-title">Tacos al pator</h5>
      <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
    </div>
    <div class="card-footer">
      <small class="text-muted">$50</small>
    </div>
  </div>
  <div class="card">
    <img class="card-img-top" src="./img/comida3.jpg" alt="...">
    <div class="card-body">
      <h5 class="card-title">Mole con arroz</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
    </div>
    <div class="card-footer">
      <small class="text-muted">$200</small>
    </div>
  </div>
  <div class="card">
    <img class="card-img-top" src="./img/comida4.jpg" alt="...">
    <div class="card-body">
      <h5 class="card-title">chile relleno</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
    </div>
    <div class="card-footer">
      <small class="text-muted">$50</small>
    </div>
  </div>
  <div class="card">
    <img class="card-img-top" src="./img/comida5.jpg" alt="...">
    <div class="card-body">
      <h5 class="card-title">Enchiladas</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
    </div>
    <div class="card-footer">
      <small class="text-muted">$50</small>
    </div>
  </div>
  <div class="card">
    <img class="card-img-top" src="./img/comida6.jpg" alt="...">
    <div class="card-body">
      <h5 class="card-title">Desayuno</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
    </div>
    <div class="card-footer">
      <small class="text-muted">$60</small>
    </div>
  </div>
</div>
</div>
<br><br><br><br><br>

  <footer class="footer-distributed">


    <div class="footer-left">

      <img src="./img/Logo.png" width="100px" alt="">

      <p class="footer-links">
        <a href="#" class="link-1">LaCocina</a>
      </p>

      <p class="footer-company-name">La Cocina © </p>
    </div>

    <div class="footer-center">

      <div>
        <i class="fa fa-map-marker"></i>
        <p><span>4 calle</span> México</p>
      </div>

      <div>
        <i class="fa fa-phone"></i>
        <p>+21312423543</p>
      </div>

    </div>

    <div class="footer-right">

      <p class="footer-company-about">
        <span>acerca de la compania</span>
        <br>
        Lorem ipsum dolor sit amet, consectateur adispicing elit. Fusce euismod convallis velit, eu auctor lacus
        vehicula sit amet.
      </p>

    </div>

  </footer>
</template>

<style scoped>
li{
  cursor: pointer;
}
h5{
  color: black;
}
p{
  color: gray;
}
img{
  display: block;
  max-width: 100%;
  height: auto;
}
</style>
