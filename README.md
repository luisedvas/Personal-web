# Personal-web
Web personal
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <title>Portfolio</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
  </head>
  <body>
    <header>
      <section class="boton-principal">
        <form action="url-where-you-want-to-submit-form-data">
          <input type="text" placeholder="Datos" required>
          <button type="submit">Submit</button>
        </form>
     </section>
      <a target="_blank" href="https://www.linkedin.com/in/luiseduardodiazv/"><img class="imagen-de-perfil" src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fpublic.notion-static.com%2F42bdc3e0-7c8f-48b8-ba88-8497dcc0b36b%2Fphoto_2020-12-05_14-51-59.jpg?width=180&userId=2df478bb-ed80-4268-838b-761757425b08&cache=v2" width="800px" height="800px" alt="imagen-de-perfil"  id="top"></a>
      <h1 class="encabezado-principal"><strong>Luis Eduardo Díaz</strong></h1>
      <side>
        <ul class="un-list">
          <li>Datos</li>
          <li>Edad: 28 años</li>
          <li>Dirección: Ciudad Ojeda, Venezuela.</li>
        </ul>
      </side>
    </header> 
      <!-- Mejorar mi presentación -->
    <main class="presentacion">
      <p><em>Hola!<br><br> Mi nombre es Luis Eduardo Díaz, y actualmente me encuentro aprendiendo desarrollo web de forma autodidacta, mi intereses se centran en web development, enfocado en lenguajes como JavaScript, y de maquetación como HTML y CSS</em></p>
      <p><em>En esta web encontrarás informacion acerca de mis habilidades, proyectos en los que he participado e información de contacto</em></p>
    </main>
    <nav>
      <ul class="un-list-dos">
        <li><a class="list-dos" href="#informacion">Información</a></li>
        <li><a class="list-dos" href="#habilidades">Habilidades</a></li>
        <li><a class="list-dos" href="#proyectos">Proyectos</a></li>
        <li><a class="list-dos" href="#contacto">Contacto</a></li>
      </ul>
    </nav>
    <hr>
    <section>
      <article>
        <h2 class="informacion">Acerca de mí</h2>
        <p class="descripcion-uno"><em>Mi nombre es Luis Eduardo Díaz, vivo en <u>Venezuela</u>, <a target="_blank" href="https://www.instagram.com/p/CUiMed4lFDS/">Estado Zulia</a>. Actualmente aprendo desarrollo web de forma autodidacta, mi objetivos se centran en aprender JavaScript y React.</em></p>
        <!-- mejorar redaccion de la presentacion -->
        <p class="descripcion-dos"><em>Aparte de desarrollo web tengo un <u>background en arquitectura</u>, donde mis intereses se centran en urbanismo e interior design.</em></p>
      </article>
    </section>
    <section>
      <article>
        <h2 id="habilidades">Habilidades</h2>
        <ol class="list-ord-1">
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
          <li>React</li>
          <li>Figma</li>
        </ol>
      </article>
    </section>
    <section>
      <article>
        <h2 id="proyectos">Proyectos</h2>
        <h4 class="tesis">Tesis de grado</h4>
        <a target="_blank" href="http://www.aknamarquez.com/manuelespinosainterv"><img src="https://images.squarespace-cdn.com/content/v1/575c3eec746fb9ca8e92d938/1466957193221-X8OTI2C8E6AI5O7UFNDB/zBoulevard+comercial.png?format=2500w" alt="tesis-de-grado"></a>
        <figcaption>Akna Márquez, Grecia Omaña (2016). Propuesta de intervención urbana, Ciudad de Panamá.</figcaption>
      </article>
    </section>
    <footer>
      <!-- agregar un encabezado -->
      <hr>
      <h3 class="contacto">Contacto:</h3>
        <ol class="ult-list">
          <li><a class="sub" target="_blank" href="#">Email</a></li>
          <li><a class="sub" target="_blank" href="https://twitter.com/naval/status/1002103360646823936">Twitter</a></li>
          <li><a class="sub" target="_blank" href="https://www.instagram.com/luiseduardodvz/">Instagram</a>
          </li>
          <li><a class="sub" target="_blank" href="https://www.linkedin.com/in/luiseduardodiazv/">LinkedIn</a></li>
        </ol>
    </footer>
    <!-- padding and margin -->
    <h5 class="texto-incrustado">Contacto</h5>
    <div class="box black-box">
      <h3 class="box caja-amarilla">Informacion</h3>
      <h3 class="box caja-azul">Contacto</h3>
    </div>
    <!-- padding and margin -->
    <!-- arreglar este "inicio" -->
    <section class="boton-inicio">
       <a href="#top">Inicio</a>
    </section>  
  </body>
</html>
