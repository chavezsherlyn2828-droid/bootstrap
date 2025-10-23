[index.html](https://github.com/user-attachments/files/23091130/index.html)
<!DOCTYPE html> 
<HTML>
    <TITLE>1.3 Elementos de lenguaje HTML</TITLE>
   <head> Trabajo 2 biografia 
    <meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet"
 integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
   </head>
   <div style="weidth:50px">
    <h1 style="position: relative; top: 0px; left: 450px; bottom: ;right: ;">ARIEL CAMACHO</h1>
    </div>
   
   <body>
       <br>
       <hr>
       <div>
       <H2 class="display-6" >El Rey De Corazones</H2> 
     </div>
       <hr>
       <br>
       <div class="container">
       <p><em>José Ariel Camacho Barraza nació el 8 de julio de 1992 en Guamúchil, Sinaloa, México. Ariel Camacho a su corta edad empezó a mostrar un gran interés
         por la música y el género sierreño del regional mexicano debido a que su padre tocaba en un grupo musical. Es asi ya que su abuelo materno le regaló una
          guitarra como instrumento. </em> </P>
        <p><em>Fue un cantante y compositor mexicano, que fundó el grupo Los Plebes del Rancho en 2013, alcanzando gran éxito en la música regional mexicana con su estilo 
            sierreño-banda. Su carrera fue efímera; murió a los 22 años en un accidente automovilístico el 25 de febrero de 2015, pero dejó un importante legado musical, 
            inspirando a una nueva generación de artistas.</em> </p>
   </div>
       
  <hr></hr>
        <H4 >Canciones mas reproducidas</H4>
        <div >
       <OL class="list-inline">
           <LI class="list-inline-item"> "Te metiste"</LI>
           <LI class="list-inline-item"> "Hablemos"</LI>
           <LI class="list-inline-item"> "El karma" </LI>
           <LI class="list-inline-item"> "El señor de los cielos" </LI>
           </div>
           <br></br>
           <a href="https://open.spotify.com/artist/2Lxa3SFNEW0alfRvtdXOul">abre su pagina de spotify</a><br></br>
       </OL>
       <hr></hr>
       <video controls width="400"> <source src="video_ariel.mp4" type="video/mp4">  </video>
      
 <hr></hr>
       <div class="container">
    <div class="row">
      <div class="col border"><H5>Biografias de mis compañeros</H5></div>
      <div class="col border">Sabina Flores</div>
      <div class="col border">Santiago Cruz</div>
    </div>

       
        <div class="container py-4">
            <div class="w-25 mx-auto">
                <img width="300" heigth="200" src="foto.JPG" >
            </div>
        </div>

        <div class="container">
         <table class="table">
            <thead>
                
        <tr>
            <th>Compañer@s</th>
            <th>Link instagram</th>

        </tr>
        </thead>
        <tbody>
        <tr class="table-danger">
            <td>Sabina</td>
            <td><a href="https://www.instagram.com/saby.flop/?igsh=MXgxYzgyaXA3a291MQ%3D%3D#">saby.flop</a></td>
        </tr>
        <tr class="table-primary">
            <td>Santiago</td>
            <td><a href="https://www.instagram.com/santiagocruzvega?igsh=bjhxZnliNzJ6N2Ez">santiagocruzvega</a></td>
        </tr><br></br>
        </tbody>
    </table><br></br>
    </div>

 <hr></hr>
<div >
    <h3 style="position: relative; top: 0px; left: 450px; bottom: ;right: ; " class="display-6">Registrate</h3>
</div>
    <div>
        <form action="imprimir.php" method="POST">
        <div class="mb-3">
            <label for="nombre">Nombre:</label>
            <input placeholder="Ingrese su nombre" class="form-control" type="text" id="nombre" name="nombre">
            
        </div>
        <div class="mb-3">
            <label for="email">Correo:</label>
            <input placeholder="Ingrese su correo" class="form-control" type="email" id="email" name="email">
        </div>
        <div>
            <label for="description">Descripcion:</label>
            <textarea placeholder="Ingrese una descripcion" class="form-control" name="description" id="description" cols="30" rows="10"></textarea>
        </div>
    </form>
    </div>
     <hr></hr>

     <div class="container py-4">
            <div class="w-25 mx-auto">
                <img width="300" heigth="200" src="arielito.jpg" >
            </div>
        </div>
   
    

   </body>

</HTML>
