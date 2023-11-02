# Configuracion Moodle

## 1. Inicia sesión como administrador de tu Moodle y realiza las siguientes tareas previas de administración.

### a) Cambia tu dirección de correo electrónico y también tu contraseña por otra. Añádete además un avatar. Todo esto se puede hacer yendo a tu perfil (opción que aparece bajo tu nombre que se ve a la parte superior derecha de la ventana del Moodle) y clicando sobre el enlace Editar (o también yendo a la opción Preferencias, situada al mismo lugar).

Para cambiar el correo electronico, la contraseña y el avatar debemos entrar en el apartado de `preferencias > editar perfil` y cambiar el correo y la contraseña 

> para poder cambiar la contraseña debemos cumplir los requisitos de seguridad establecidos por el administrador.

![1](/img's/1.png)

---- 

para cambiar la foto de perfil debemos dirigirnos al mismo apartado `preferencias > editar perfil` y desde nuestra maquina deberemos subir la imagen que utilizaremos como foto de perfil y guardar los cambios.

![1](/img's/3.png)

### b) Cambia el nombre de tu lugar (tanto largo como corto) e hiciera que la página principal no muestre nada por los usuarios que no estén autentificats. Esto se puede hacer yendo a la opción Administración del lugar > Primera plana > Parámetros

para cambiar el  nombre del sitio debemos entrar en `Administración del lugar > Parámetros y cambia el nombre

![1](/img's/5.png)

### c) Comprueba que la franja horaria de tu lugar sea la correcta. Esto se puede hacer yendo a la opción Administración del lugar > Ubicación > Parámetros.

para cambiar la franja horaria debemos ir a `Administración del sitio > General > Ubicación` y en la **zona horaria por defecto** colocamos la deseada

![1](/img's/6.png)

### d) Cambia el idioma de tu lugar. Esto se puede hacer yendo a la opción Administración del lugar > Idioma > Parámetros y teniendo en cuenta tanto el checkbox Detección automática del idioma como el desplegable Idioma por defecto

Para cambiar el idioma de tu sitio, dirígete a la opción `Administración del sitio > Idioma > Parámetros` y selecciona "Idioma" en el menú desplegable. Asegúrate de configurar tanto la casilla "Detección automática del idioma" como el menú desplegable "Idioma por defecto" según tus preferencias.

![1](/img's/7.png)

### e) Cambia la política de contraseñas de forma que los usuarios que se creen tengan una contraseña de como mínimo 4 caracteres incluyendo, mayúsculas, minúsculas y cifras. Esto se puede hacer yendo a la opción Administración del lugar > Seguridad >Normativas del lugar.

Para modificar la política de contraseñas y requerir que los usuarios creen contraseñas de al menos 8 caracteres, incluyendo mayúsculas, minúsculas y cifras, accede a la opción `Administración del lugar > Seguridad > Normativas del lugar`. Ajusta las configuraciones de contraseñas de acuerdo con tus preferencias de seguridad.

![1](/img's/9.png)

## 2. Crea los siguientes cursos: un curso denominado A (sin categoría) que esté formado por 3 temas y otro llamado B (también sin categoría) que esté formado por 5 temas. Todo esto lo puedes hacer desde Administración del lugar->Gestiona cursos y categorías o también desde el cuadro Navegación yendo a Cursos > Añade curso

Para crear los cursos A y B, ve a `Administración del sitio > Gestiona cursos y categorías` o usa la opción `Cursos > Añade curso` en el cuadro de Navegación. Crea un curso A con 3 temas y otro curso B con 5 temas.

![1](/img's/10.png)

## 3. Ve a alguno de los cursos creados en su punto anterior (simplemente seleccionándolo dentro del cuadro Navegación) y fes que contenga en alguno del suyos temas algún tipo de material (un documento PDF, por ejemplo), cambia el título de algún tema y, en general, investiga las posibilidades que te da el botón Activar edición en un curso.

Para modificar un curso existente, selecciona uno desde el cuadro de Navegación. Puedes cambiar el título de un tema y agregar material, como un documento PDF, a través del botón **Activar edición**.

![1](/img's/11.png)


![1](/img's/12.png)


## 4. Creación de usuarios y alumnos.


### a) Crea manualmente un usuario llamado Bob que tiene que usar el método de autenticación manual. Esto se puede hacer desde Administración del lugar > Usuarios > Cuentas > Añade un usuario

Para crear un usuario manualmente, dirígete a `Administración del sitio > Usuarios > Cuentas` y selecciona **Añade un usuario**. Crea un usuario llamado Bob con el método de autenticación manual.

![1](/img's/15.png)

### b) Genera diez alumnos que lo serán de los dos cursos A y B . Usa un archivo CSV para realizar esta creación en bloque. Ve a Administración del lugar > Usuarios > Cuentas > Carga usuarios y sigue los pasos que te marca.

Para generar diez alumnos y asignarlos a los cursos A y B, utiliza un archivo CSV en `Administración del sitio > Usuarios > Cuentas > Carga usuarios`.

![1](/img's/21.png)

### c) Elimina dos de los diez alumnos creados en el apartado anterior usando la opción Administración del lugar > Usuarios > Acciones con usuarios en bloque

Para eliminar dos de los diez alumnos, usa la opción `Administración del lugar > Usuarios > Acciones con usuarios en bloque`.

![1](/img's/30.png)

## 5. Ahora matricula estos usuarios en los diferentes cursos.

### a) Fez que en el curso A no haya posibilitado de inscripción (es decir, que solo se permita el acceso de visitante de forma que el curso sea totalmente público sin control de usuarios -ni alumnos ni profesores-). Por otro lado, hiciera que en el curso B se necesite registro manual de usuarios (es decir, que sea el administrador -tú- quien matricule cada usuario en el curso, ya sea como profesor o como alumno). Todo esto lo puedes hacer desde Administración del curso > Ususaris > Métodos de inscripción. Si no sale algún método de inscripción disponible, tienes que activarlo a: Administración de lugar > Conectores > Autenticación > Gestión de la autenticación

Para matricular usuarios en los cursos, configura el curso A para que sea público y el curso B para que requiera registro manual en `Administración del curso` > `Usuarios` > `Métodos de inscripción`.

![1](/img's/29.png)

### b) Asigna como profesor del curso B el usuario "Bob" y como alumnos a todos los que haces añadir desde el archivo CSV Todo esto lo puedes hacer yendo a Administración del curso > Usuarios inscritos > Inscribir.

Asigna a Bob como profesor del curso B y matricula a los alumnos en `Administración del curso > Usuarios inscritos > Inscribir`.

![1](/img's/25.png)

### c) Comprueba que efectivamente, el contenido del curso A (añadido por el administrador del sistema -es decir, tú- esté disponible públicamente y que para acceder al curso B se tenga que iniciar sesión con un usuario registrado (alumno o profesor)



## 6. Cambia la apariencia estética de tu lugar. Concretamente, descárgate y activa un tema diferente a los que vienen por defecto y prueba de cambiar también la cabecera y el pie de página del lugar. Esto lo puedes hacer primero yendo a Administración del lugar > Conectores > Instalar complemento y después a Administración del lugar > Apariencia > Temas > Selector de temas Siempre puedes usar el enlace Cambio de rol del menú de la derecha para observar como se vería el lugar siendo alumno, profesor, etc.

ara cambiar la apariencia estética, descarga y activa un tema diferente en `Administración del sitio > Conectores > Instalar complemento y Apariencia > Temas > Selector de temas`. Puedes cambiar la cabecera y el pie de página.

![1](/img's/33.png)

## 7. Asigna un profesor y matricula alumnos en el curso A.

Asigna un profesor al curso A y matricula a los alumnos en "Administración del curso".

![1](/img's/32.png)

## 8. Con el profesor añade contenido en el curso A. Añade diferentes tipos de actividades y recursos. Crea una tarea con fecha de entrega abierta que pida la carga de un fichero PDF.

Con el profesor, agrega contenido al curso A, como actividades y recursos. Crea una tarea con una fecha de entrega abierta que requiera la carga de un archivo PDF.

![1](/img's/31.png)

## 9. Entra con un alumno y comprueba que puedes librar la tarea.

![1](/img's/27.png)


## En el curs A fes que un alumne completi totes les tasques evaluables (entrant amb la seva compta). Calificales amb el professor i configura el calificador per a que doni una nota de la UF automàticament a Administració del Curs > Configuració de qualificacions.

Para configurar el calificador de manera que dé una nota de la UF automáticamente, debes acceder a la sección `Administración del Curs > Configuración de calificaciones` y configurar los parámetros apropiados. Sin embargo, los detalles específicos de esta configuración pueden variar según la versión y configuración de Moodle que estés utilizando.

## Crea una insignia i atorga-la a aquest alumne des de Administració del Lloc > Insígnies

 Para crear una insignia y otorgarla a un estudiante, debes acceder a `Administración del Lloc > Insígnies`. Sin embargo, los pasos exactos para crear una insignia pueden variar según la versión de Moodle y la configuración del sitio. Deberás seguir los pasos proporcionados en la interfaz de administración de tu instancia de Moodle.

## Crea un qüestionari i afegeix preguntes del banc de preguntes. Crea diferents categories dintre del banc de preguntes i diverses preguntes en cada categoria. A l'hora de crear el qüestionari has de seleccionar les preguntes del banc de preguntes. Respon les preguntes del qüestionari amb un usuari estudiant i mira les qualificacions amb l'usuari professor. 

Para crear un cuestionario en Moodle y agregar preguntas del banco de preguntas, así como organizarlas en diferentes categorías, debes acceder al área de creación de cuestionarios en tu instancia de Moodle. Asegúrate de haber creado previamente un banco de preguntas con las preguntas que deseas utilizar. Luego, al crear el cuestionario, tendrás la opción de seleccionar las preguntas del banco de preguntas y asignarlas a categorías específicas. Para evaluar el cuestionario, puedes responder las preguntas como un usuario estudiante y luego verificar las calificaciones como un usuario profesor. Los pasos específicos pueden variar según la versión de Moodle que estés utilizando y su configuración.

## Entra a la zona Administració > Cursos > Còpies i fes una còpia de seguretat del teu curs. Després envia aquest fitxer a un company i que l'importi al seu moodle. Has d'importar al teu moodle un altre curs d'un company.

Para realizar una copia de seguridad de un curso y luego compartirlo con otro usuario, debes acceder a la sección `Administració > Cursos > Còpies` en Moodle. Desde allí, podrás crear una copia de seguridad del curso que deseas compartir. Luego, debes compartir el archivo de copia de seguridad con tu compañero y pedirle que lo importe en su propia instancia de Moodle. El proceso de importación de un curso puede variar dependiendo de la configuración y la versión de Moodle utilizada. Asegúrate de que tu compañero siga los pasos correctos para importar el curso en su Moodle.

## Baneja una IP i aplica una política de seguretat. Pots posar la que vulguis però l’hauràs de justificar.

El proceso de banear una IP y aplicar una política de seguridad en Moodle se debe entrar a `seguridad > bloqueo ip'sp` y agregar la ip a bloquear.

![1](/img's/37.png)

## Crea 10 usuaris alumnes i un usuari professor posant-li dades. Administració del Lloc > Usuaris > Crear Usuari / Pujar Usuaris (de cop amb un arxiu csv, hi ha un model de csv al final del document).

Para crear 10 usuarios alumnos y un usuario profesor, debes acceder a "`dministración del Lloc > Usuaris > Crear Usuari` o "Pujar Usuaris" si deseas cargarlos desde un archivo CSV. Debes proporcionar los datos requeridos para cada usuario, como nombre, apellido, nombre de usuario, dirección de correo electrónico y contraseña. Luego, puedes matricular a los estudiantes en los cursos A y B utilizando "Administración del Curs > Usuaris > Usuaris Matriculats". Los detalles exactos pueden variar según la configuración de Moodle.



## Assigna al professor a A i B. Matricula els alumnes a A mitjançant Administració del Curs > Usuaris > Usuaris Matriculats i connectat amb un alumne i matricula'l a B amb la contrassenya.