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
---
![1](/img's/12.png)

## 4. Creación de usuarios y alumnos.

Para crear un usuario manualmente, dirígete a `Administración del sitio > Usuarios > Cuentas` y selecciona **Añade un usuario**. Crea un usuario llamado Bob con el método de autenticación manual.

![1](/img's/15.png)

### a) Crea manualmente un usuario llamado Bob que tiene que usar el método de autenticación manual. Esto se puede hacer desde Administración del lugar > Usuarios > Cuentas > Añade un usuario

### b) Genera diez alumnos que lo serán de los dos cursos A y B . Usa un archivo CSV para realizar esta creación en bloque. Ve a Administración del lugar > Usuarios > Cuentas > Carga usuarios y sigue los pasos que te marca.

### c) Elimina dos de los diez alumnos creados en el apartado anterior usando la opción Administración del lugar > Usuarios > Acciones con usuarios en bloque

## 5. Ahora matricula estos usuarios en los diferentes cursos.

### a) Fez que en el curso A no haya posibilitado de inscripción (es decir, que solo se permita el acceso de visitante de forma que el curso sea totalmente público sin control de usuarios -ni alumnos ni profesores-). Por otro lado, hiciera que en el curso B se necesite registro manual de usuarios (es decir, que sea el administrador -tú- quien matricule cada usuario en el curso, ya sea como profesor o como alumno). Todo esto lo puedes hacer desde Administración del curso > Ususaris > Métodos de inscripción. Si no sale algún método de inscripción disponible, tienes que activarlo a: Administración de lugar > Conectores > Autenticación > Gestión de la autenticación

### b) Asigna como profesor del curso B el usuario "Bob" y como alumnos a todos los que haces añadir desde el archivo CSV Todo esto lo puedes hacer yendo a Administración del curso > Usuarios inscritos > Inscribir.

### c) Comprueba que efectivamente, el contenido del curso A (añadido por el administrador del sistema -es decir, tú- esté disponible públicamente y que para acceder al curso B se tenga que iniciar sesión con un usuario registrado (alumno o profesor)

## 6. Cambia la apariencia estética de tu lugar. Concretamente, descárgate y activa un tema diferente a los que vienen por defecto y prueba de cambiar también la cabecera y el pie de página del lugar. Esto lo puedes hacer primero yendo a Administración del lugar > Conectores > Instalar complemento y después a Administración del lugar > Apariencia > Temas > Selector de temas Siempre puedes usar el enlace Cambio de rol del menú de la derecha para observar como se vería el lugar siendo alumno, profesor, etc.

## 7. Asigna un profesor y matricula alumnos en el curso A.

## 8. Con el profesor añade contenido en el curso A. Añade diferentes tipos de actividades y recursos. Crea una tarea con fecha de entrega abierta que pida la carga de un fichero PDF.

## 9. Entra con un alumno y comprueba que puedes librar la tarea.