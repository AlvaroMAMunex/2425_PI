*Asignatura: Programacióna Internet
*Curso: 2024/2025
Para Gestionar el proceso de autenticación mediante Firebase hay que seguir los siguientes pasos:
|--------------------------------------FRONTEND--------------------------------------|
1. Dirigirse a https://console.firebase.google.com/
2. Iniciar sesión con la cuenta de la UEx de alumnos
3. Crear un nuevo proyecto
4. Tras haber finalizado la creación del proyecto debemos entrar en él, normalmente nos autoredirige.
5. En el apartado Compilación --> Autenticación, nos vamos a método de acceso.
6. Añadimos el proovedor de acceso Google a través del check de habilitar.
7. Hacemos lo mismo con el método de correo electrónico y contraseña.
8. De esta forma ya hemos configurado lo necesario para el frontend.
|--------------------------------------FRONTEND--------------------------------------|
|--------------------------------------BACKEND--------------------------------------|
Ahora lo que necesitamos es tener un archivo de claves de cuenta de servicio para inicializar el SDK.
1. Vamos a la consola de Firebase y selecciona tu proyecto.
2. Seleccionamos "Configuración del proyecto" (el icono del engranaje).
3. En la pestaña "Cuentas de servicio". Hacemos clic en "Generar nueva clave privada" y descarga el archivo JSON.
|--------------------------------------BACKEND--------------------------------------|