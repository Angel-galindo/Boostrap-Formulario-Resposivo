Formulario Boostrap
==============
    
## Descripción
        
<p align="justify">
    EL presente formulario busca estar centrado y ser visualmente agradable haciendo uso del framework <i>Boostrap</i>.
 </p>
        
        
<p align="center">
    <img src="" width="682" height="330">
</p>

 ## Desarrollo
        
 <ol>
    <li>
        Instalar Boostrap.
         <p align="justify">
            Instalamos <a href="https://nodejs.org/">npm</a> el cual es un <i>manejador de paquetes para Node.js</i> y a través del cual instalaremos <i>JQUERY</i> y <i>BOOSTRAP</i>.
         </p>
    </li>
    <li>
        Instalar <i>JQuery</i>
            <p align="justify">
                Una vez nos encontramos en la carpeta ejecutamos:
            </p>
            <p align="justify">
                <i>npm install jquery</i>
            </p>
    </li>   
    <li>
        Instalar <i>Boostrap</i>
            <p align="justify">
                En nuestra carpeta ejecutamos:
            </p>
            <p align="justify">
                <i>npm install boostrap</i>
            </p>
    </li>
    <li>
        Importamos <i>JQuery</i> y <i>Boostrap</i>. Creamos una hoja de estilos <i>signup.css</i> y agregamos nuestros campos.
    </li>
 </ol>
 
 * HTML
 
 ~~~  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sign Up</title>
    <link rel="stylesheet" href="node_modules\bootstrap\dist\css\bootstrap.min.css">
    <link rel="stylesheet" href="signup.css">
</head>
<body>
    <div class="container container-table">
        <div class="row vertical-center-row">
            <div class="col-md-4 col-md-offset-4">
                <form class="" action="signup.php">

                    <div class="form-group">
                        <label  for="nombre">Nombre:</label><br>
                        <input class="form-control" type="text" id="nombre" placeholder="José Juan"><br>
                    </div>

                    <div class="form-group">
                        <label  for="nombre">Apellido Paterno:</label><br>
                        <input class="form-control" type="text" id="paterno" placeholder="Pérez"><br>
                    </div>

                    <div class="form-group">
                        <label  for="materno">Apellido Materno:</label><br>
                        <input class="form-control" type="text" id="materno" placeholder="López"><br>
                    </div>

                    <div class="form-group">
                        <label  for="correo">Correo:</label><br>
                        <input class="form-control" type="email" id="correo" placeholder="juan.perez@gmail.com"><br>
                    </div>

                    <div class="form-group">
                        <label  for="password">Password:</label><br>
                        <input class="form-control" type="password" id="password"><br>
                    </div>

                    <div class="form-group">
                        <label  for="password">Verify Password:</label><br>
                        <input class="form-control" type="password" id="password"><br>
                    </div>

                    <div class="form-group">
                        <button type="button" class="btn btn-success btn-block">Agregar</button>
                    </div>

                </form>
            </div>
        </div>
    </div>

    <script src="./node_modules/jquery/dist/jquery.min.js"></script>
    <script src="node_modules\bootstrap\dist\js\bootstrap.min.js"></script>
</body>
</html>
 ~~~  
 
 * CSS
 
 ~~~
 html, body, .container-table {
     height: 100%;
 }
 
 .container-table {
     display: table;
 }
 
 .vertical-center-row {
     display: table-cell;
     vertical-align: middle;
 }
 ~~~
 
 ## Fuente
 
 * <a href="https://stackoverflow.com/questions/20142606/in-a-bootstrap-responsive-page-how-to-center-a-div">Stackoverflow Boostrap Responsive Page</a>
 
 


 
 