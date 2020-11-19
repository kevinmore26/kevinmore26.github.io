<!DOCTYPE html>
<html lang="es">
  <!-- PARA HACERLE A LA PÁGINA QUE ESTARÁ EN ESPAÑOL -->
  <head>
    <meta charset="UTF-8" />
    <title>Kevin More</title>
    <link rel="icon" type="image/png" href="images/Kev.png" />
    <link rel="stylesheet" href ="portafolio/estilos.css"/>
    <!-- HREF PARA TRAER IMAGENES DE UNA CARPETA, IMAGES PORQUE SABES QUE TU ARCHIVO HTML ESTÁ AHÍ.PONES IMAGES PORQUE ESTÁ EN LA MISMA CARPETA QUE EL HTML Y EL / ES PARA ENTRAR A UNA CARPETA  -->
  </head>
  <body>
    <header class="header">
      <!-- ES PARA LA CABECERA Y SE LE RECOMIENDA QUE LLEVE DE CLASE HEADER PARA SER MÁS ORDENADO :) -->
        <figure>
          <img src="images/uwu.png" height="60px" alt="Logo de http://leonidasesteban.com" class="logo1"/>
          <!-- EL IMG SIEMPRE SE CIERRA EN SÍ MISMO -->
          <!-- EL ALT ES POR SI LA PÁGINA NO LLEGA A CARGAR COMPLETAMENTE, ENTONCES TE CARGA UN MENSAJE OPCIONAL -->
          <!-- SRC ES PARA LA RUTA :) -->
        </figure>
        <nav class="menu" >
          <ol>
            <!-- OL para clasificar en orden :D el ul, no.  -->
            <li>
            
              <!-- para enlaces internos y externos USANDO EL <a></a>-->
              <a class = "link" href="#Portafolio">Portafolio</a>
              <!-- el # es para unirlo luego con un id y poder modificarlo -->
            </li>
            <li>
              <a class = "link" href="#experiencia">Experiencia</a>
            </li>
            <li>
              <a class = "link" href="#trabajemosjuntos">Trabajemos juntos</a>
            </li>
          </ol>
        </nav>
    </header>
    <section class="hero">  
      <!-- secciones y le pone hero porque normalmente es el principal o cabecera principal :) -->
      <h1 >
        Hola! Soy <strong>Kevin More</strong> Futuro <strong>Desarrollador Web</strong> y <br/> <strong>Frontend</strong> con <br> pasión por la <strong>programación</strong>
        <!-- br es como un enter pero en html y se cierra en sí misma  -->
      </h1>    
    </section>
    <section id ="Portafolio" class="port">
      <!-- Acá llamas los href y le pones un class con cualquier nombre para posteriormente modificarlo en un archivo css -->
      <h2>Portafolio (Proyectos Destacados)</h2>
      <article class="project">
        <h3 class="project-title">Platzi_Video</h3>
        <p class="project-description">Platzi Video fue el resultado de 3 meses de trabajo
            para crear la mejor app para enseñar el funcionamiento
            de React y React Native. Desde crear un vista-detalle, hasta patrones avanzados de nevegación, este proyecto ha sido el ejemplo de futuros creadores de aplicaciones multiplataforma</p>
            <figure class="project-imageContainer">
              <img class="project-image" height="350" src="images/platzi-video-react-native.png" alt="proyecto del curso de React Native">
              <!-- acuerdate que cuando vas a insertar una imagen debes ponerlo dentro de un <figure></figure> -->
            </figure>
      </article>
      <article class="project">
        <h3 class="project-title">Platzi_Video</h3>
        <p class="project-description">Platzi Video fue el resultado de 3 meses de trabajo
            para crear la mejor app para enseñar el funcionamiento
            de React y React Native. Desde crear un vista-detalle, hasta patrones avanzados de nevegación, este proyecto ha sido el ejemplo de futuros creadores de aplicaciones multiplataforma</p>
            <figure class="project-imageContainer">
              <img class="project-image" height="350" src="images/platzi-video-react-native.png" alt="proyecto del curso de React Native">
              <!-- acuerdate que cuando vas a insertar una imagen debes ponerlo dentro de un <figure></figure> -->
            </figure>
      </article>
    </section>
    <section id ="experiencia" class="event-list">
      <h2 class="experience">Más sobre su experiencia</h2>
      
      
      <article class="event">
        <figure class="event-imageContainer">
          <img  class="event-image" src="images/tomy.jpg" width="250" />
        </figure>
        <div>
        <h3 class="event-title">PlatziConf México 2018</h3>
        <p class="event-description">El evento más grande sobre gente que quiere aprender más de internet. En esté evento te comparto como tener una vida de constante aprendizaje.</p>
        <a class="event-url" href="https://www.youtube.com/watch?v=XP_EHQxu4OI&ab_channel=ESPA%C3%91A" target="_blank">Ver Plática</a>
        </div>
      </article>
    
    </section>
    <section class="scxd">¿Quieres contactar a mi mishi?</section>
    <section id ="trabajemosjuntos" class="contact">
      <form action = "/suscripcion/" class="form-email"></form>
      <input type="datetime" placeholder="Dejanos tu email :)">
      <button>enviar</button>
      <div class="social">
        <a href="https://www.facebook.com/kevinmore1401/" target="_blank" class="social-link facebook"></a>
        <a href="https://www.instagram.com/kevinmore26/" target="_blank" class="social-link instagram"></a>
        <a href="https://github.com/kevinmore26" target="_blank" class="social-link github"></a>
      </div>
    </section>
    <footer class="footer">
      <div>
        <p class="cdw">Estudiante en platzi 2020 :D <img src="images/platzi.png" width="70" alt="Hola"></p>
      </div>
    </footer>
  </body>
</html>
