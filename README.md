# Projeto_Netflix
Projeto clone Netflix

Para o carrosel :secret:

Cria uma pasta no JS e CSS com nome owl

- Foi pego o Arquivo do Owl Carrousel 

  + docs > assets > vendors = jquery.mim poe no " js > owl"
  + docs > assets > owlcarousel = owl.carousel.min poe no "js > owl"
  + 
  + dist > assets = owl.carousel.min poe no "css > owl"
  + dist > assets = owl.theme.default.min poe no "css > owl"

- 

  <div class="carrosel_filmes">
      <div class="owl-carousel owl-theme">
          <div class="box_filme"><img src="imagens/1.jpg" alt=""></div>
          <div class="box_filme"><img src="imagens/2.jpg" alt=""></div>
          <div class="box_filme"><img src="imagens/3.jpg" alt=""></div>
          <div class="box_filme"><img src="imagens/4.jpg" alt=""></div>
          <div class="box_filme"><img src="imagens/5.jpg" alt=""></div>
          <div class="box_filme"><img src="imagens/6.jpg" alt=""></div>
          <div class="box_filme"><img src="imagens/7.jpg" alt=""></div>
          <div class="box_filme"><img src="imagens/8.jpg" alt=""></div>
          <div class="box_filme"><img src="imagens/9.jpg" alt=""></div>
          <div class="box_filme"><img src="imagens/10.jpg" alt=""></div>
      </div>
  </div>
  
  Ainda no html linka os arquivos
  
  <script src="https://kit.fontawesome.com/2c36e9b7b1.js"></script>
  <script src="js/olw/jquery.min.js"></script>
  <script src="js/olw/owl.carousel.min.js"></script>
  <script src="js/main.js"></script>
  
  e cola isso no main.js sem os script abaixo
  <script>
  $('.owl-carousel').owlCarousel({
      loop:true,
      margin:10,
      nav:true,
      responsive:{
          0:{
              items:2
          },
          600:{
              items:3
          },
          1000:{
              items:7
          }
      }
  })
  </script>
  
  e no css seta a altura e largura de cada capa do carrosel
  <style>
  /*Carrosel*/
  .box_filme {
      height: 100%;
      width: 100%;
      display: block;
      cursor: pointer;
  }
  </style>

  

