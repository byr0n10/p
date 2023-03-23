<html lang="es">
  <head>
    <title>AppDeGatos</title>

    <link href="style.css" rel="stylesheet">
  </head>
  <body  background="jj.gif">
    <center><h2>AppDeGatos</h2></center>
    <main>
      <h1>Imágenes de Gatos:</h1>
      <!-- TODO: Agregar enlace a imágenes de gatos -->
      <p>Haz click aquí para ver más <a href="https://unsplash.com/es/images/animals/kitten" target="_blank" rel="noopener noreferrer">imágenes de gatos.</a></p>

      <a href="#" target="_blank" rel="noopener noreferrer"><img src="https://bit.ly/fcc-relaxing-cat" alt="Un lindo gato naranja recostado sobre su espalda."></a>

      <hr color="black">

      <h3>Listas de Gatos</h3>

      <div>
        <h6><p>Cosas que los gatos aman:</p><h6></h6>
        <ul>
          <li>Menta gatuna</li>
          <li>Apuntadores Láser</li>
          <li><s>Lasaña</s></li>
        </ul>
        <img src="https://images.pexels.com/photos/5949888/pexels-photo-5949888.jpeg?auto=compress&cs=tinysrgb&w=600" width="300" height="200" alt="Lasaña">
        <h6><p>Cosas que los gatos <strong>odian</strong>:</p></h6>
        <ol>
          <li>Tratamientos antipulgas</li>
          <li>Truenos</li>
          <li>Otros gatos</li>
        </ol>
      </div>
      <img src="https://images.pexels.com/photos/617278/pexels-photo-617278.jpeg?auto=compress&cs=tinysrgb&w=600" width="300" height="200" alt="Gatos">

      <form action="/enviar-respuesta">
        <!-- Botones de Radio -->
        <label for="interior">
          <input id="interior" type="radio" value="interior" name="interior-exterior">Interior
        </label>
        <br>
        <label for="exterior">
          <input id="exterior" type="radio" value="exterior" name="interior-exterior">Exterior
        </label>
        <br>
        <main class="main">
            <div class="card">
        <h2>Ingrese su nombre</h2>
        <input type="text" placeholder="Ingrese su nombre"></label>
        <h2>Ingrese su apellido</h2>
            </div>
        <input type="text" placeholder="Ingrese su apellido"></label>
        <form action="/uno/juan.txt">
          <h3>¿Como es ser un  gato?</h3>
          <input type="checkbox">Amoroso
          <input type="checkbox">Peresoso
          <input type="checkbox">Amargado
        <br>
        
        <input type="text" placeholder="URL de la foto de su gato" required><br>
        <button type="submit">Enviar</button>
        <button type="reset">Limpiar</button>
      </form>
    </main>
    <br>
    <footer>
      <p><small>Sin Derechos de Autor - <a href="https://www.freecodecamp.org/espanol/">freeCodeCamp.org</a></small></p>
    </footer>
 
