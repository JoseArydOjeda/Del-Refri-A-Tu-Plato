# Del-Refri-A-Tu-Plato

<!DOCTYPE html>
<html>
  <head>
    <tittle>Del Refri a tu Plato</tittle>
    <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css">
    <link rel="stylesheet" type="text/css" href="style.css"/>
  </head>
  
  <body>
    <h1>De-Tu-Refri-a-Tu-Cocina</h1>
    <h2><center>¡Hola!, bienvenido a tu nueva página favorita acerca de cocina, donde podrás encontrar diferentes recetas de cocina que saciarán tu paladar, prueba con algunas de las recetas que tenemos para ti.</center></h2>
    <br/>
      <article>
        <p>Selecciona alguna de las recetas que te presentamos a continuación:</p>
        <a href="Huevo con Jamón.md"> Huevos con jamón </a>
        <br />
        <a href="Link del apartado"> Frijol con puerco </a>
        <br/>
        <a href="Link del apartado"> Spaghetti </a>
        <br/>
        <a href="Link del apartado"> Burritas </a>
        <br/>
        <a href="Link del apartado"> HotCakes </a>
      </article>
      <article>
        <p>
          Mi-branch
          Sistema de Recetas en línea.
          Versión: Prototipo.
          Descripción:
          Se solicita un sitio web donde los visitantes puedan interactuar con un motor de búsqueda.
          El sitio debe ofrecer 4 funcionalidades básicas:
          <ul>
            <li>Buscar recetas por ingredientes.</li>
            <li>Crear nuevas recetas.</li>
            <li>Modificar recetas existentes.</li>
            <li>Eliminar recetas.</li>
          </ul>
        </p>
        <br/>  
        <p>
          Cuando se use el filtro para buscar una receta usando ingredientes, el sistema debe ser capaz de presentar todas las recetas que contengan este ingrediente.
          Para simplificar la presentación solo se deben presentar el nombre de la receta y los ingredientes, los detalles o pasos a seguir deben aparecer en una página independiente.
        </p>
        <br/>
    </article>
    <article>
      <h2> RF-01 </h2>
        <p>Al llegar  a la página se presentará una página de bienvenida.</p>
        <br/>  
      <h2> RF-02 </h2>
        <p>En la página aparecerán las 5 recetas más solicitadas y las instrucciones de uso del sitio.</p>
        <br/>
      <h2> RF-03 </h2>
        <p>En la parte superior tendremos las opciones. 
          a. Home (para regresar al principio)
          <br/>
          b. Recetas (Para ingresar a la aplicación)
          <br/>
          c. Aviso de privacidad.
          <br/>
          d. Acerca del sitio. (Créditos a los autores)
        </p>
          <br/>
      <h2> RF-04 </h2>
        <p>Si el visitante selecciona la opción "Recetas", ingresará a la aplicación.</p>
          <br/>
      <h2> RF-05 </h2>
        <p>En la parte superior aparecerá un filtro para que el usuario pueda escribir el nombre de alguno de los ingredientes de la receta que sea de su interés.</p>
          <br/>
      <h2> RF-06 </h2>
        <p>Si el visitante da clic en el botón del filtro sin haber escrito algo en la casilla, el sistema presentará todas las recetas.</p>
          <br/>
      <h2> RF-07 </h2>
        <p> Si se escribe una palabra o más palabras separadas por comas, el sistema realizará la búsqueda y presentará las recetas que contengan estos ingredientes. </p>
          <br/>
      <h2> RF-08 </h2>
        <p> La página deberá presentar la(s) receta(s) que contengan el ingrediente en una lista con nombre e ingredientes, sin las instrucciones. </p>
          <br/>
      <h2> RF-09 </h2>
        <p>En la lista presentada, a la derecha de cada receta tendremos dos opciones:</p>
          <ol>
            <li>Ver detalle (para ver las instrucciones o los pasos de elaboracion)</li>
            <li>Editar (Para poder modificar la receta)</li>
            <li>Eliminar (Para borrar una receta)</li>
         </ol>
          <br/>
      <h2> RF-10 </h2>
        <p>En la parte inferior del filtro antes de hacer una consulta aparecera un boton para agregar nuevas recetas</p>
          <br/>
      <h2> RF-11 </h2>
        <p>Cuando se presenten los resultados de la consulta, el botón aparecerá debajo del listado.</p>
          <br/>
      <h2> RF-12 </h2>
        <p>Una receta debe tener Nombre, instrucciones de elaboración (pasos) e ingredientes.</p>
          <br/>
    </article>
    <article>
      <h2>  RNF-01 </h2>
        <p>Las recetas deberán salir en menos de 3 segundos.</p>
          <br/>
      <h2>  RNF-02 </h2>
        <p>Se van a necesitar a 6 desarrolladores para realizar el código y un (1) QA que pruebe el producto.</p>
          <br/>
      <h2> RNF-03 </h2>
        <p>El producto estará disponible el 99.9% de las veces.</p>
          <br/>
      <h2>  RNF-04 </h2>
        <p>El producto se usará localmente en la laptop de forma local.</p>
          <br/>
      <h2> RNF-05 </h2>
        <p> La página será compatible con varios navegadores (brave,Chrome,Fox etc.). </p>
          <br/>
      <h2> RNF-06</h2>
        <p>El codigo de todo el producto estara documentado y bien estructurado para futuras lecturas y actualizaciones</p>
          <br/>
      <h2> RNF-07</h2>
        <p>Todo será de fácil navegación para la facilitación del disfrute y uso de la página.</p>
          <br/>
    </article>
    <article>
      <h2>Especificaciones técnicas para la versión Prototipo: </h2>
        <p>
          Las recetas no tendrán imágenes.
          El prototipo no tendrá seguridad.
          Cualquier persona podrá agregar una receta.
          Cualquier persona podrá editar una receta.
          Cualquier persona podrá eliminar una receta.
          Las recetas se almacenarán en memoria. 
          El sistema tendrá un archivo de Carga inicial, se trata de un archivo de texto con las recetas separadas por comas, una en cada renglón, que se lee y se carga en la memoria al iniciar el sistema.
          Esto quiere decir que al iniciar o al resetear el sistema, solo existirán las que hayamos capturado en el archivo de carga inicial.
          En caso de que ocurriera algún error, el sitio debe ser capaz de atraparlo y agregarlo al Log; al visitante se le presenta algún mensaje amigable.
        </p>
    </article>


</body>
</html>
