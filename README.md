<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-compatible" content="IE=edge">
<title>
    Curriculum Vitae
</title>
<style>
    * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
  padding: 20px;
}

/* Header */
header {
  background-color: #007BFF;
  color: white;
  padding: 20px;
  text-align: center;
}

.header-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  
}

.perfil {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  object-fit: cover;
  margin-bottom: 15px;
}

h1 {
  font-family: 'Lato', sans-serif;
  margin-bottom: 5px;
}

p {
  font-size: 1.2em;
}

.desc{margin-left: 10px;}

/* Secciones */
section {
  margin-bottom: 30px;
  padding: 20px;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

h2 {
  font-family: 'Lato', sans-serif;
  color: #007BFF;
  margin-bottom: 10px;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  margin-bottom: 10px;
  padding-left: 20px;
  position: relative;
}

li:before {
  content: '•';
  color: #007BFF;
  position: absolute;
  left: 0;
  font-size: 1.2em;
  top: 0;
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  margin-top: 20px;
  background-color: #007BFF;
  color: white;
  border-radius: 8px;
}

footer a {
  color: #FFC107;
  text-decoration: none;
  font-weight: bold;
}

footer a:hover {
  text-decoration: underline;
}

/* Diseño Responsivo */
@media (min-width: 768px) {
  .header-content {
    flex-direction: row;
    justify-content: center;
    align-items: center;
  }

  .perfil {
    margin-right: 20px;
  }

  section {
    max-width: 700px;
    margin: 0 auto;
  }
}
    </style>
</head>
<body>
    <header>
        <div class="header-content">
          <img src="perfil.jpg" alt="Foto de perfil" class="perfil">
          <h1>Elias Raphael Cardozo Pereira</h1>
          <p class="desc">Desarrollador Web | Programador</p>
        </div>
      </header>
    <section id="Sobre mí">
    <H1>Elias Raphael Cardozo Pereira</H1>
    <p>Actualmente estudio en la carrera de ingenieria informatica en la Universidad de la integración de las americas (UNIDA),<br> soy un estudiante sobresaliente que desea aprender y obtener más experiencias de las oportunidades que se me ofrecen. <br>
    Poseo experiencia básica en HTML,lenguaje de programación C++ y base de datos. </p>
    </section>
    <section id="Experiencia">
    <h3>Experiencia laboral:</h3>
<Ol><li>Entidad Binacional Yacyreta (EBY):</li>
Pasante-3 meses de duración
</Ol>
<p>Me encargaba del mantenimiento y reparación de computadores e impresoras, formateo e instalación de sistemas operativos, instalación y puesta a punto de switches.</p>
    </section>
<section id="Estudios"><H3>Estudios</H3>
<ol>
<li>Primaria</li>
<p>Colegio Nuestra Señora del Huerto <br>
2011-2017
</p>
<li>Secundaria</li>
    <p>Colegio Nuestra Señora del Huerto <br>
2018-2020
    </p>
    <li>Educación Media</li>
    <p>Titulo de Bachillerato tecnico en informatica <br>
        Escuela Nacional de Comercio N°2 <br>
2021-2023
    </p>
</ol>
</section>
<section>
<h3>Habilidades</h3>
<ol> <p>Habilidades tecnicas</p>
    <li>Programación</li>
    <li>Gestión de base de datos</li></ol>
    <ol><p>Habilidades blandas</p>
    <li>Puntual</li>
    <li>Responsable</li>
    <li>Proactivo</li>
    <li>Autodidacta</li>
    <li>Trabajo en equipo</li>
    </ol>
</section>
<section>
    <H3>Información de contacto</H3>
    <ol>
        <li>eliascardozo013@gmail.com </li>
            <li><a href="https://www.linkedin.com/public-profile/settings?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BFEd1p6LbTIGcWypTxbsABA%3D%3D&licn=gdpr_notice_toast">Linkedin</a></li>
</ol>
</section>
<footer><a href="https://github.com/E1I4S">Github</a></footer>
</body>
</html>
