<!-- Los comentarios a lo largo del codigo son muy importantes nos ayudan  -->

<!DOCTYPE html>
<html>
<head>
<title>Moda</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Oswald">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open Sans">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
h1,h2,h3,h4,h5,h6 {font-family: "Oswald"}
body {font-family: "Open Sans"}
</style>
</head>

<body class="w3-light-grey">

<!-- Navigation bar with social media icons --> 


<div class="w3-bar w3-blue w3-hide-small">
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-facebook-official"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-instagram"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-snapchat"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-flickr"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-twitter"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-linkedin"></i></a>
  <a href="#" class="w3-bar-item w3-button w3-right"><i class="fa fa-search"></i></a>
</div>
  
<!-- w3-content defines a container for fixed size centered content, 
and is wrapped around the whole page content, except for the footer in this example -->
<div class="w3-content" style="max-width:1600px">

  <!-- Header -->
  <header class="w3-container w3-center w3-padding-48 w3-white">
    <h1 class="w3-xxxlarge"><b>Moda  </b></h1>
    <h6>Bienvenidos a <span class="w3-tag">Moda para jóvenes </span></h6>
  </header>

  <!-- Image header -->
  <header id="home">
    <img class="w3-image" src="img/lol7.jfif" alt="Fashion Blog" width="1600" height="1060">
    <div class="w3-display-left w3-padding-large">
      <h1 class="w3-text-white">Y</h1>
      <h1 class="w3-jumbo w3-text-white w3-hide-small"><b>Moda para jóvenes </b></h1>
      <h6><button class="w3-button w3-white w3-padding-large w3-large w3-opacity w3-hover-opacity-off" onclick="document.getElementById('subscribe').style.display='block'">INCRESAR</button></h6>
    </div>
  </header>

  <!-- Grid -->
  <div class="w3-row w3-padding w3-border">

    <!-- Blog entries -->
    <div class="w3-col l8 s12">
    
      <!-- Blog entry -->
      <div class="w3-container w3-white w3-margin w3-padding-large">
        <div class="w3-center">
          <h3>En este sitio web vamos hablar de los tipos de moda y de alguna manera para que puedas lucir hermos@ 

          </h5>
        </div>

        <div class="w3-justify">
          <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
          <p><strong>1 clásico</strong> algo de moda</p>
          <p> Apostar por el clásico siempre es un valor seguro, aunque para encontrar
             ese punto de sofisticación y glamour también hay que desarrollar criterio. ¡Es cuestión de práctica!</p>
          <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
          <p class="w3-right"><button class="w3-button w3-pink" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
          <p class="w3-clear"></p>

          <img src="img/lol0.webp" style="width:100px;">
          <img src="img/lol.jpg" style="width:100px;">

            <div class="w3-justify">
              <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
              <p><strong>2. Romántico</strong> algo de moda</p>
              <p>el estilo romántico es muy royal. Es el que elegirían las princesas Disney clásicas, pero con cuidado de no ir demasiado recargadas.
                 Y es que las prendas destacan por su alta ornamentación y por los cortes tridimensionales.</p>
              <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
              <p class="w3-right"><button class="w3-button w3-purple" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
              <p class="w3-clear"></p>

              <img src="img/lol2.jpg" style="width:100px;">
              <img src="img/lol3.png" style="width:100px;">
              <img src="img/lol4.png" style="width:100px;">

              <div class="w3-justify">
                <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
                <p><strong>3. Boho  </strong> algo de moda</p>
                <p>Entre los diferentes estilos de vestir, los inicios de este se suelen ubicar a principios del año 2000. Aúna lo hippy y lo bohemio, así que es un estilo con mucha personalidad que no resulta fácil clavar.
                   Lo bueno es que no tienes que imitarlo, sino adaptarlo a lo que te guste.</p>
                <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
                <p class="w3-right"><button class="w3-button w3-pink" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
                <p class="w3-clear"></p>

                <img src="img/lol5.png" style="width:100px;">
                <img src="img/lol6.jpg" style="width:100px;">

                  <div class="w3-justify">
                    <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
                    <p><strong>4. Deportivo</strong> algo de moda</p>
                    <p>Hace ya unos años que conocimos el concepto de athleisure , que promueve el uso de prendas deportivas en el día a día sin renunciar al glamour. Se puede ir chic con outfits tradicionalmente reservados al ejercicio físico, lo que tiene su dificultad.
                       Quienes lo consiguen trasladan mucha personalidad. </p>
                    <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
                    <p class="w3-right"><button class="w3-button w3-purple" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
                    <p class="w3-clear"></p>
      
                    <img src="img/lol8.jpg" style="width:100px;">
                    <img src="img/lol9.png" style="width:100px;">
                    <img src="img/lol10.png" style="width:100px;">

                   <div class="w3-justify">
                      <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
                      <p><strong>5. Fashion </strong> algo de moda</p>
                      <p>también se le llama trendy. No es un estilo en sí mismo, sino que define una práctica: la de seguir siempre las tendencias en moda. Quienes se adhieren a él se ponen lo que se lleva, 
                        pero no se trata de asumir cualquier corriente sin criterio, sino de adaptarla a un estilo personal.</p>
                      <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
                      <p class="w3-right"><button class="w3-button w3-pink" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
                      <p class="w3-clear"></p>
          
                      <img src="img/lol11.png" style="width:100px;">
                      <img src="img/lol12.jpg" style="width:100px;">
                      <img src="img/lol13.jpg" style="width:100px;">
                      
          <p class="w3-clear"></p>
          <div class="w3-row w3-margin-bottom" id="demo1" style="display:none">
            <hr>
              <div class="w3-col l2 m3">
                <img src="img/MLR_Freya.webp" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>lisa <span class="w3-opacity w3-medium">May 3, 2006, 6:32 PM</span></h4>
                <p>la mejor moda</p>
              </div>
          </div>
        </div>
      </div>
      <hr>


        <div class="w3-justify">
          <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
          <p><strong>6. Hipster</strong> Un poco de la moda</p>
          <p>Es el estilo de las mujeres inconformistas y que rehúsan encorsetarse. Por eso mezclan el grunge, 
            el boho y el hippie para configurar looks originales con algún toque gótico. Con criterio, eso sí, para no parecer un collage.</p>
          <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
          <p class="w3-right"><button class="w3-button w3-blue" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
          <p class="w3-clear"></p>
          
          <img src="img/lol14.jpg" style="width:100px;">
          <img src="img/lol15.png" style="width:100px;">
          <img src="img/lol16.jpg" style="width:100px;">
          
          <div class="w3-justify">
            <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
            <p><strong>7. Grunge</strong> Un poco de la moda</p>
            <p>el grunge es un estilo parecido al anterior, con la diferencia de que es más rígido. Nos referimos a que,
               si bien el hipster es más ecléctico y admite más mezcla, el grunge se ciñe a lo rebelde y desenfadado</p>
            <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
            <p class="w3-right"><button class="w3-button w3-red" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
            <p class="w3-clear"></p>

            <img src="img/lol17.jpg" style="width:100px;">
            <img src="img/lol19.png" style="width:100px;">

            <div class="w3-justify">
              <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
              <p><strong>8. Minimalista</strong> Un poco de la moda</p>
              <p>el minimalismo arrasa entre los estilos decorativos para el hogar y también en la moda. Se basa en la máxima de que menos es más, luego se ubica en una línea opuesta a la del estilo romántico, por ejemplo.
                 Es más parecido al clásico, con el que comparte ventajas como la atemporalidad</p>
              <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
              <p class="w3-right"><button class="w3-button w3-blue" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
              <p class="w3-clear"></p>

              <img src="img/lol20.png" style="width:100px;">
              <img src="img/lol21.jpg" style="width:100px;">
              <img src="img/lol22.jpg" style="width:100px;">

              <div class="w3-justify">
                <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
                <p><strong>9. Preppy</strong> Un poco de la moda</p>
                <p>Quizás el término se te asemeje a repipi, pero no. O sí, depende de cómo lo veas. Toma como referencia la forma de vestir de las estudiantes estadounidenses de clase alta, 
                  así que es uno de los estilos de moda femenina más juveniles. Y más posh</p>
                <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
                <p class="w3-right"><button class="w3-button w3-red" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
                <p class="w3-clear"></p>

                <img src="img/lol23.jpg" style="width:100px;">
                <img src="img/lol24.jpg" style="width:100px;">
                <img src="img/lol25.jpg" style="width:100px;">
              
                <div class="w3-justify">
                  <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
                  <p><strong>10. Urban-chic</strong> Un poco de la moda</p>
                  <p>Se le llama también streetwear. Es un estilo libre, incluso diríamos que funciona a modo de cajón de sastre. Sigue las tendencias,
                     pero adaptándolas a las preferencias para ganar en comodidad y seguridad en una misma</p>
                  <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
                  <p class="w3-right"><button class="w3-button w3-blue" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
                  <p class="w3-clear"></p>

                  <img src="img/lol26.png" style="width:100px;">
                  <img src="img/lol27.jpg" style="width:100px;">
          
                  <div class="w3-justify">
                    <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
                    <p><strong>11. Emos</strong> Un poco de la moda</p>
                    <p>Los Emos consta de prendas negras, pantalones, camisas y chaquetas ajustadas; los ojos maquillados, el mechón largo de cabello que les tapa medio rostro, 
                      a veces usan correas o cinturones con taches, y tienden a tener el aspecto de su piel muy blanco.</p>
                    <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
                    <p class="w3-right"><button class="w3-button w3-red" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
                    <p class="w3-clear"></p>

                    <img src="img/lol29.jpg" style="width:100px;">
                    <img src="img/lol30.png" style="width:100px;">
                    <img src="img/lol31.jpg" style="width:100px;">
                    

                    <div class="w3-justify">
                      <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
                      <p><strong>12. Dark</strong> Un poco de la moda</p>
                      <p>El Dark es una forma de vida, expresada en la forma de vestir, en los gustos por la música y la literatura, 
                        temas recurrentes de la subcultura oscura como las novelas de terror, vampirismo</p>
                      <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
                      <p class="w3-right"><button class="w3-button w3-blue" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
                      <p class="w3-clear"></p>

                      <img src="img/lol32.png" style="width:100px;">
                      <img src="img/lol33.jpg" style="width:100px;">
                      <img src="img/lol34.jpg" style="width:100px;">

                      <div class="w3-justify">
                        <img src="img/MLR_Ryusuke_Yamino.webp" alt="Runway" style="width:100%" class="w3-padding-16">
                        <p><strong>13. cottagecore</strong> Un poco de la moda</p>
                        <p>se refiere no sólo a una estética
                           y estilo de vestir sino a una forma de vida estrechamente vinculada al campo y a la vida rural</p>
                        <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
                        <p class="w3-right"><button class="w3-button w3-red" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
                        <p class="w3-clear"></p>
                       <img src="img/lol35.png" style="width:100px;">
                       <img src="img/lol36.png" style="width:100px;">
                       <img src="img/lol37.jpg" style="width:100px;">

          <!-- Example of comment field -->
          <div id="demo3" style="display:none">
            <hr>
            <div class="w3-row w3-margin-bottom">
              <div class="w3-col l2 m3">
                <img src="img/lol009.jfif" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>mary<span class="w3-opacity w3-medium">April 10, 2015, 7:22 PM</span></h4>
                <p>hermoso.</p>
              </div>
            </div>
            <div class="w3-row w3-margin-bottom">
              <div class="w3-col l2 m3">
                <img src="img/lol0010.jfif" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>brayan<span class="w3-opacity w3-medium">April 8, 2015, 10:32 PM</span></h4>
                <p>lindos estilos.</p>
              </div>
            </div>
            <div class="w3-row w3-margin-bottom">
              <div class="w3-col l2 m3">
                <img src="img/lol008.jfif" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>linda<span class="w3-opacity w3-medium">April 7, 2015, 9:12 PM</span></h4>
                <p>bellicimos!</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      
    <!-- END BLOG ENTRIES -->
    </div>

    <!-- About/Information menu -->
    <div class="w3-col l4">
      <!-- About Card -->
      <div class="w3-white w3-margin">
        <img src="img/lol008.jfif" alt="Jane" style="width:100%" class="w3-grayscale">
        <div class="w3-container w3-black">
          <h4>linda</h4>
          <p>lo mejor</p>
        </div>
      </div>
      <hr>

      <!-- Posts -->
      <div class="w3-white w3-margin">

          <li class="w3-padding-16">
            <img src="img/lol0011.jfif" alt="Image" class="w3-left w3-margin-right" style="width:50px">
            <span class="w3-large">Ana</span>
            <br>
            <span>yo quiero esos stilos</span>
          </li>
          <li class="w3-padding-16">
            <img src="img/lol0012.jfif" alt="Image" class="w3-left w3-margin-right" style="width:50px">
            <span class="w3-large">lili</span>
            <br>
            <span>donde los puedo conseguir </span>
          </li>
          <li class="w3-padding-16">
            <img src="img/lol0013.jfif" alt="Image" class="w3-left w3-margin-right w3-sepia" style="width:50px">
            <span class="w3-large">jesika</span>
            <br>

          <h4>bellisimos</h4>
        </div>
        <div class="w3-container w3-white">
          <p>
            <span class="w3-tag w3-black-w3-margin-bottom">Moda</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Hipster</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Grunge</span>
            <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">romántico</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Minimalista</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">clasico</span>
            <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Boho</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Preppy</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Emos</span>
            <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Deportivo</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Urban-chic</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Dark</span>
            <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">fashion</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom"> cottagecore</span>
          </p>
        </div>
      </div>
      <hr>

      <!-- Inspiration -->
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-pink">
          <h4>Inspiration</h4>
        </div>
        <div class="w3-row-padding w3-white">
          <div class="w3-col s6">
            <p><img src="img/ño.jfif" alt="moda" style="width:100%"></p>
            <p><img src="img/mñ.jfif" alt="moda" style="width:100%"></p>
          </div>
          <div class="w3-col s6">
            <p><img src="img/ño2.jfif" alt="moda" style="width:100%" class="w3-grayscale"></p>
            <p><img src="img/ñp3.jfif" alt="lili" style="width:100%"></p>
         </div>
        </div>
      </div>
      <hr>

      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>Follow Me</h4>
        </div>
        <div class="w3-container w3-xlarge w3-padding">
          <i class="fa fa-facebook-official w3-hover-opacity"></i>
          <i class="fa fa-instagram w3-hover-opacity"></i>
          <i class="fa fa-snapchat w3-hover-opacity"></i>
          <i class="fa fa-pinterest-p w3-hover-opacity"></i>
          <i class="fa fa-twitter w3-hover-opacity"></i>
          <i class="fa fa-linkedin w3-hover-opacity"></i>
        </div>
      </div>
      <hr>
      
      <!-- Subscribe -->
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>Subscribe</h4>
        </div>
        <div class="w3-container w3-white">
          <p>Enter your e-mail below and get notified on the latest blog posts.</p>
          <p><input class="w3-input w3-border" type="text" placeholder="Enter e-mail" style="width:100%"></p>
          <p><button type="button" onclick="document.getElementById('subscribe').style.display='block'" class="w3-button w3-block w3-red">Subscribe</button></p>
        </div>
      </div>

    <!-- END About/Intro Menu -->
    </div>

  <!-- END GRID -->
  </div>

<!-- END w3-content -->
</div>

<!-- Subscribe Modal -->
<div id="subscribe" class="w3-modal w3-animate-opacity">
  <div class="w3-modal-content" style="padding:32px">
    <div class="w3-container w3-white">
      <i onclick="document.getElementById('subscribe').style.display='none'" class="fa fa-remove w3-transparent w3-button w3-xlarge w3-right"></i>
      <h2 class="w3-wide">SUBSCRIBE</h2>
      <p>Join my mailing list to receive updates on the latest blog posts and other things.</p>
      <p><input class="w3-input w3-border" type="text" placeholder="Enter e-mail"></p>
      <button type="button" class="w3-button w3-block w3-padding-large w3-red w3-margin-bottom" onclick="document.getElementById('subscribe').style.display='none'">Subscribe</button>
    </div>
  </div>
</div>

<!-- Footer -->
