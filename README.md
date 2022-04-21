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
      <a target="_blank" href="https://www.linkedin.com/in/luiseduardodiazv/"><img class="imagen-de-perfil" src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fpublic.notion-static.com%2F42bdc3e0-7c8f-48b8-ba88-8497dcc0b36b%2Fphoto_2020-12-05_14-51-59.jpg?width=180&userId=2df478bb-ed80-4268-838b-761757425b08&cache=v2" alt="imagen-de-perfil"></a>
      <h1 class="encabezado-principal" id="top"><strong>Luis Eduardo Díaz</strong></h1>
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
      <p>Hola! Mi nombre es Luis Eduardo Díaz, y actualmente me encuentro aprendiendo desarrollo web de forma autodidacta, mi intereses se centran en web development, enfocado en lenguajes como JavaScript, y de maquetación como HTML y CSS</p>
      <p>En esta web encontrarás informacion acerca de mis habilidades, proyectos en los que he participado e información de contacto</p>
    </main>
    <nav>
      <ul class="un-list-dos">
        <li><a href="#informacion">Información</a></li>
        <li><a href="#habilidades">Habilidades</a></li>
        <li><a href="#proyectos">Proyectos</a></li>
        <li><a href="#contacto">Contacto</a></li>
      </ul>
    </nav>
    <section>
      <article>
        <h2 class="informacion" id="informacion">Acerca de mí</h2
        <p class="descripcion">Mi nombre es Luis Eduardo Diaz, vivo en Venezuela, <a target="_blank" href="https://es.wikipedia.org/wiki/Estado_Zulia">estado Zulia</a>. Actualmente aprendo desarrollo web de forma autodidacta, mi objetivos se centran en aprender JavaScript y React</p>
        <!-- mejorar redaccion de la presentacion -->
        <p class="descripcion">Aparte de desarrollo web tengo un background en arquitectura, donde mis interes se centran en urbanismo e interior design</p>
      </article>
    </section>
    <section>
      <article>
        <h2 id="habilidades">Habilidades</h2>
        <ol>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
        </ol>
      </article>
    </section>
    <section>
      <article>
        <h2 id="proyectos">Proyectos</h2>
        <h3>Tesis de grado</h3>
        <a target="_blank" href="#"><img src="" alt="tesis-de-grado"></a>
      </article>
    </section>
    <section>
      <form action="url-where-you-want-to-submit-form-data">
        <input type="text" placeholder="Datos" required>
        <button type="submit">Submit</button>
      </form>
    </section>
    <footer>
      <!-- agregar un encabezado -->
      <p class="contacto" id="contacto">Contacto</p>
        <ol>
          <li><a target="_blank" href="https://mail.google.com/mail/u/0/#inbox">Email</a></li>
          <li><a target="_blank" href="https://twitter.com/naval/status/1002103360646823936">Twitter</a></li>
          <li><a target="_blank" href="https://www.instagram.com/luiseduardodvz/">Instagram</a></li>
          <!-- arreglar este "inicio" -->
          <a href="#top">-> Inicio</a>
        </ol>
    </footer>
    <!-- padding and margin -->
    <h5 class="texto-incrustado">Contacto</h5>
    
    <div class="box black-box">
      <h3 class="box caja-amarilla">Informacion</h3>
      <h3 class="box caja-azul">Contacto</h3>
    </div>
    <!-- padding and margin -->
  </body>
</html>
