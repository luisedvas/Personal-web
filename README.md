# Personal-web
Web Personal
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luiseduardodev</title>
    <link rel="stylesheet" type="text/css" href="./styles.css">
  </head>
  <body>
  <!----------------------- header ------------------------>
    <header>
      <h1 id="home" class="heading">Luis Eduardo Díaz</h1>
      <!-- Tengo que arreglar esta barra de navegación. Hacerla más responsiva -->
      <nav id="navbar">Navigation bar 
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about-me">About</a></li>
          <li><a href="#information">Information</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
      <a target="_blank" href="https://www.linkedin.com/in/luiseduardodiazv/"><img src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fpublic.notion-static.com%2F42bdc3e0-7c8f-48b8-ba88-8497dcc0b36b%2Fphoto_2020-12-05_14-51-59.jpg?width=180&userId=2df478bb-ed80-4268-838b-761757425b08&cache=v2" width="800px" height="800px" alt="imagen-de-perfil" class="imagen-de-perfil" id="top"></a>
      <h2 class="encabezado-principal" id="about-me"><strong>HTML, CSS & JavaScript Developer</strong></h2>
      </header> 
      <!-- Presentation -->
      <aside class="un-list">
        <ul>
          <strong>
            <li>Age: 28 years old.</li>
            <li>Direction: Ciudad Ojeda, Venezuela.</li>
            <li>Nationality: Venezuelan.</li>
          </strong> 
        </ul>
      </aside>
    <main class="presentation">
      <p>Who am I:</p>
      <p>Hello!<br><br>I´m Luis, I live in Venezuela and am studying to be an architect. I also enjoy talking about urban design, research and software development. My interests are focused on web development, focused on urban design, reasearch and programming languages such as JavaScript and Python.</p>
      <p>On this website you will find information about my skills and projects that I have created during my apprenticeship and contact information.</p>
    </main>
    <nav class="un-list-dos" id="information">
      <ul>
        <h3 class="barra">Table of Contents</h3>
        <li><a href="#information">Information</a></li>
        <li><a href="#habilidades">Skills</a></li>
        <li><a href="#proyectos">Projects</a></li>
      </ul>
    </nav>
    <hr>
    <section id="information">
      <article>
        <h2>About me</h2>
        <p class="descripcion-uno">I am a student in the last semester of architecture whose interests are focused on technology, design and software development, based on <a target="_blank" href="https://es.wikipedia.org/wiki/Estado_Zulia">Zulia</a>, <u>Venezuela</u>.  I am currently learning web development in a self-taught way, my goals are focused on learning JavaScript and React.</p>
        <!-- mejorar redaccion de la presentacion -->
        <p class="descripcion-dos">Apart from web development, I have a <u>background in architecture</u>, where my interests lie in urban planning and interior design.</p>
      </article>
    </section>
    <section id="habilidades">
        <h2>Skills</h2>
        <ol class="list-ord-1">
          <strong>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>React</li>
            <li>Figma</li>
          </strong>
        </ol>
    </section>
    <section id="proyectos">
      <article>
        <h2>Projects</h2>
        <h3 class="tesis">Thesis</h3>
        <!-- Ejemplo de tesis hasta terminar la mia -->
        <!-- arreglar este "figure" y "figurecaption" hasta que funcione -->
        <figure><a target="_blank" href="http://www.aknamarquez.com/manuelespinosainterv"><img src="https://images.squarespace-cdn.com/content/v1/575c3eec746fb9ca8e92d938/1466957193221-X8OTI2C8E6AI5O7UFNDB/zBoulevard+comercial.png?format=2500w" alt="tesis-de-grado" class="img"></a>
        <figcaption class="figcap">Autors: Akna Márquez, Grecia Omaña (2016). Architectural urban intervention proposal, Av. Manuel Espinoza Batista, City of Panamá, Panamá.</figcaption>
        </figure>
      </article>
    </section>
    <section id="contact">
      <hr>
      <h3>Contact:</h3>
        <nav>
        <ol class="ult-list">
          <li><a class="sub" target="_blank" href="#">Email</a></li>
          <li><a class="sub" target="_blank" href="https://twitter.com/naval/status/1002103360646823936">Twitter</a></li>
          <li><a class="sub" target="_blank" href="https://www.instagram.com/luiseduardodvz/">Instagram</a>
          </li>
          <li><a class="sub" target="_blank" href="https://www.linkedin.com/in/luiseduardodiazv/">LinkedIn</a></li>
        </nav>
        </ol>
    </section>
    <!-- use padding and margin -->
    <h5 class="texto-incrustado">Thanks!</h5>
    <div class="box black-box">
      <h3 class="box caja-amarilla">Buy me a coffee</h3>
      <h3 class="box caja-azul">Share my work here</h3>
    </div>
    <div>
    <!-- use padding and margin -->
    <!-- arreglar este "inicio" -->
    <section class="boton-inicio">
        <a href="#top">Start</a>
    </div>
    <footer>
<!-- activar si quiero poner la animación de corazón
      <div class="back"></div>
      <div class="heart"></div> -->
      <p>&copy; Luis Eduardo Díaz, 2022.</p>
    </footer>
  </body>
</html>
