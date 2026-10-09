1. Flujo colaborativo
Supón que quieres colaborar con el repositorio de otro desarrollador. Ordena y explica los siguientes elementos:Push, Fork, Pull Request, Clone, Merge, Commit, Review, Branch y Modificar archivos.Agrega cualquier operacion que consideres necesaria.

R= Lo inicial sería solicitar el url del repositorio del otro desarrollador posteriromente lo abrimos en git hub y hacemos un fork para que tengamos como una copia exacta en nuestro propio git, copiaremos el url del fork ya hecho y lo clonaremos en vs code (git clone url) en nuetsro vs code crearemos una nueva rama para trabajar sbre ella y no directamente en main, depsues haremos las modificaciones necesarias una vez terminadas preparamos los archivos en la termianl creamos los commits y hacemos el push cuando regresemos al repositorio aparecerá la opción para enviar el pull request lo enviaremos y ya el desarrollador podra aceptarlo o regresarla (review) para hacer más modificaciones o corregir algo, una vez los cambios sean correctos el desarrollador hará un merge para aceptar los cambios para despues hacer un git pull y sincronizar los nuevos cambios con todo el proyecto.

2. Fork y Clone
Analiza la afirmación: "Clone crea una copia del proyecto dentro de mi cuenta de git hub" No, no es exactamente así, el clone clona el proyecto pero en tu disco duro en tu vs code, el fork es el que clona el repositorio en tu cuenta de git hub y esa es la diferencia.

3. Pull Request
Supón que realizaste fork, clone, branch, modificar, commit y push. ¿los cambios ya forman parte del repositorio original?¿Qué debe ocurrir para incorporarlos? no. aun no forman parte ya que para incorporarlos al original el otro desarrolladdor debe hacer la revision de los cambios (review changes) y posteriormente aceptarlos con un merge y a l final hacer un git pull en main para que se incorpore todo 

4. Request changes 
El propietario revisa tu pull request y selecciona un request changes. Explica que debes hacer, si necesitas crear otro pull request y que ocurre con un nuevo push.
Debo acatar las instrucciones o correcciones, modificar los archivos y una vez que esten coprrectos debo preparar de  uevo los archivos modificados, hcaer un nuevo commit y un nuevo push. No es necesario crear un nuevo pull request ya que la rama que creamos y en la que estamos trabajando sigue activa y con solo hacer el commit y el push actualiza los cambio en el pull request ya existente.

5. Merge y repositrio local
Un pull request fue aceptado y se realizo un merge en github. sin embargo, el repositorio local del propietariuo no contiene los cambio explica que paso. eso es por que le falata realizar el git pull origin main para sincronizar todo.

6. Sync fork
tu fork fue creado varios dias atras y el repositorio original recibio nuevos commits. que herramientas utilizarias, que repositorio se actualiza y que diferencia existe entre sync fork y git pull. la herramineta esta directamente en git aparace como sync fork
Sync fork actualiza tu copia en la nube de GitHub traída desde el original, mientras que git pull trae cambios de GitHub a tu propia compu.

