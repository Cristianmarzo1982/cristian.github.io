#1 HOJA HTML
<!DOCTYPE html>
<html lang="es">    
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"><!--elemento que nos permite tener nuestro sitio web full responsive, se introdujo en HTML 5   -->
    <title>CV Alvarez Cristian</title>

    <!--Libreria Boostrap
        <link rel="stylesheet" href="/css/bootstrap.min.css">-->
    <link rel="stylesheet" type="text/css" href="/Users/cristianalvarez/Downloads/Argentina Programa 2022/Desarrollo Frontend Enero 2023/ProyectoCVAlvarezCristian/css/style.css" /> 
    <!--Font elemento p1 fuente: google font-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@400;600&family=Barlow+Condensed:wght@500&family=Big+Shoulders+Inline+Display&family=Inria+Sans:ital,wght@0,300;0,400;1,400&family=Libre+Caslon+Display&family=Oswald&family=Tangerine&display=swap" rel="stylesheet">  
    <!--Font elemento h1 Cristian David Alvarez, fuente: google font-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@400;600&family=Barlow+Condensed:wght@500&family=Big+Shoulders+Inline+Display&family=Courgette&family=Inria+Sans:ital,wght@0,300;0,400;1,400&family=Libre+Caslon+Display&family=Oswald&family=Tangerine&display=swap" rel="stylesheet">
</head>
<body>
    <!--<img src="/Users/cristianalvarez/Downloads/Argentina Programa 2022/Desarrollo Frontend Enero 2023/ProyectoCVAlvarezCristian/imagenes/fondo.jpg" alt="fondo de pantalla"/>-->
    <header>


    </header>
    <video width="250" controls muted autoplay> <!--el atributo loop=bucle-->
        <source src="/Users/cristianalvarez/Downloads/Argentina Programa 2022/Desarrollo Frontend Enero 2023/ProyectoCVAlvarezCristian/multimedia/Presentacion.mp4" type="video/mp4"> <!--no me funciona la ruta relativa???-->
        <source src="/Users/cristianalvarez/Downloads/Argentina Programa 2022/Desarrollo Frontend Enero 2023/ProyectoCVAlvarezCristian/multimedia/clara.ogg" type="video/ogg"> <!--este formato amplia la reproducción en otros navegadores, salvo el safari-->
        Tu navegador no soporta la reproducción del video, por favor accedé con otro navegador.
    </video>
    <h1 id="nombre"> CV CRISTIAN DAVID ALVAREZ</h1>
        <img src="/Users/cristianalvarez/Downloads/Argentina Programa 2022/Desarrollo Frontend Enero 2023/ProyectoCVAlvarezCristian/imagenes/fotoAlvarezCristian.jpg" alt="Foto 4X4 del solicitante" height="200px" width="200px"/> <!--no me funciona la ruta relativa???-->
        <hr>    
   
    <section>
        <h2>Educación</h2>
        <p>Estudiante en Ingeniería en Sistemas (desde 2019), Universidad Abierta Interamericana. Cursando tercer año.</p>
        <p>Enfermero Profesional (Egresado 2010). Instituto Amado Olmos (ATSA CABA).</p>
        <hr>
    </section>
    <section>
        <h3>Experiencia Laboral</h3>
        <p>Enfermero Laboral, ASMEL SA. Control de ausentismo y atencion primaria a colaboradores.</p>
        <p>Enfermero Laboral, Grupo Bimbo Argentina. Septiembre 2018- Septiembre 2021. Control de ausentismo y atencion primaria de colaboradores.</p> 
        <p>Enfermero Servicio de Neurocirugia, Clínica Adventista Belgrano. Junio 2008- Marzo 2017. Gestión administrativa del paciente desde la primera consulta (Solicitud de autorización de internación, materiales de osteosíntesis).</p>
    </section>
        <p>Enfermero Servicio Resonancia Magnética, Clínica Adventista Belgrano. Junio 2015- Marzo 2017.</p>
        <hr>
    </section>
    <section>
        <h4>Cursos</h4>
        <p>Carrera Windows Server 2019
        (Academia Educación IT, inicio 2022 y en curso).</p>
        <p>Argentina Programa 2022 Desarrollo Full Stack (Certificación INTI SéProgramar, cursando segunda etapa).</p>
        <p>Master en SQL Server: Desde Cero a Nivel Profesional. 2021 (Udemy.com).</p>
        <p>Curso Online de Primeros Socorros con RCP y DEA. (Gardiens de la Vie, aprobado noviembre 2020).</p>
        <p>Diseño e Implementación de DataWarehouse con SQL Server 2019 (Udemy.com).
        </p>
        <p>Cuidados RN (Hospital Garrahan, curso aprobado 2010).</p>
        <hr>
    </section>
    <section>
        <h5>Conocimientos Generales</h5>
        <p>Suite Microsoft Office 365 (Word, Excel, PowerPoint) Sharepoint, One Drive, Power Apps, Power BI, suite Mac IOS (Pages, Numbers).</p>
        <p>Google Cloud Computing, Microsoft Azure.</p>
        <p>Lenguajes de programación (C, Python, SQL, JS, HTML).</p>
        <hr>
    </section>
    <script src="/Users/cristianalvarez/Downloads/Argentina Programa 2022/Desarrollo Frontend Enero 2023/ProyectoCVAlvarezCristian/JS/javascript.js"></script>
</body>
<footer>
    <p class="pie"><a href="www.linkedin.com/in/cristiandavidalvarez"> Visita mi perfil en Linkedin</a></p>
    <p class="pie">Autor: Cristian David Alvarez</p>
    <p class="pie">Contacto celular: 11-6691-5182</p>
</footer>
</html>

#2 HOJA HTML

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="/Users/cristianalvarez/Downloads/Argentina Programa 2022/Desarrollo Frontend Enero 2023/ProyectoCVAlvarezCristian/css/style.css" />
    <title>Login</title>
</head> 
<body class="login">
    <h6>Por favor, ingrese sus datos para leer el CV:</h6>
    <section>
        <form class="formulario" action="" method="post">
            <legend style="text-align: center;"> Login: </legend>
            <label for="apellido" class="labe"> Apellido</label><br>
            <input class="tex" type="text" name="apellido" id="apellido" placeholder="Ingrese su apellido"/><br>
            <label for="nombre" class="labe"> Nombre </label><br>
            <input class="tex" type="text" name="nombre" placeholder="Ingrese su nombre"/><br>
            <label for="documento" class="labe"> Documento de identidad</label><br>
            <input class="tex" type="number" name="documento" placeholder="Ingrese su número de documento sin puntos"><br><br>
            <div id="error"></div>
            <button id="boton"> Enviar </button>
        </form> 
    </section>
    <script src="/Users/cristianalvarez/Downloads/Argentina Programa 2022/Desarrollo Frontend Enero 2023/ProyectoCVAlvarezCristian/JS/javascript.js"></script>
</body>
</html>

#3 HOJA CSS
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    
}
.formulario {
    
    width: 400px;
    height: 340px;
    background: gray;
    margin: auto;
    margin-top: 100px;
    box-shadow: 7px 13px 37px #000;
    padding: 25px 30px;
    color: white;
    

}
#nombre {
    position:fixed;
    top:0;
    left: 0;
    width: 100%;
    padding: 20px 50px;
    background:#017bab;
    font-family: 'Baloo Bhai 2', cursive;
    font-size: 55px;
    color: whitesmoke;
    text-align: center;
    
}
h2,h3,h4,h5 {
    color:#017bab;
    font-size: 35px;
    margin: 25px 30px 35px 60px;
    text-decoration: underline;
}
p {
    font-family: 'Barlow Condensed', sans-serif;
    font-size: 24px;
    margin: 25px;
    text-indent: 60px;
}
.login {
    background-image: url('/Users/cristianalvarez/Downloads/Argentina Programa 2022/Desarrollo Frontend Enero 2023/ProyectoCVAlvarezCristian/imagenes/fondo.jpg'); 
    background-repeat: no-repeat;
}

body {
    background-image: url('/Users/cristianalvarez/Downloads/Argentina Programa 2022/Desarrollo Frontend Enero 2023/ProyectoCVAlvarezCristian/imagenes/fondo3.jpg'); 
    background-size: cover;
    width: 100%;
    height: auto;
    
}

legend {
    border-bottom: 2px solid;
    padding-bottom: 5px;
    margin-bottom: 3px;
    font-size: 25px;
}

.tex {
    width: 100%;
    border: 2px solid blue;
    border-radius: 4px;
    background-color: blanchedalmond;
    color: black;
    margin-top: 2px;
    margin-bottom: 10px;
    padding: 8px;
    font-size: 11px;
    font-weight:bolder;
    text-transform: uppercase;
}
button {
    width: 100%;
    height: 40px;
    background-color: #017bab;
    color: white;
    font-size: 20px;
}   
.pie {
    text-align: right;
    font-size: 20px;
}
h6 {
    margin-top: 50px;
    font-size: 30px;
    font-family:Arial, Helvetica, sans-serif;
    color: whitesmoke;
    margin-left: 200px;
    
}
.labe {
    font-size: 20px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
video {
    margin-right: 50px;
    max-width: 100%;
    height: auto;   
    position: -webkit-sticky;
    position: sticky;
    margin-top: 175px;
    float: right;
 
}
img {
    margin-top: 135px;
    margin-left: 450px;
    width: 25%;
    height: auto;
}

#4 HOJA DE JAVASCRIPT

document.getElementById("boton").addEventListener("click", abrirNuevaVentana);

function abrirNuevaVentana()
 {
  window.open("/Users/cristianalvarez/Downloads/Argentina Programa 2022/Desarrollo Frontend Enero 2023/ProyectoCVAlvarezCristian/proyecto/cvAlvarezCristian.html");
 }


 
