# comsumo-ws-cambioMoneda


Instrucciones para desplegar la app

Tecnologías utilizadas.
-	PHP 8.1.1
-	Composer 2.4.1
-	PhpMailer 6.8

1. Entorno
   - Tener un entorno de desarrollo local configurado con PHP y Composer instalados.

2. Iniciar el servidor apache (xamp , wamp, laragon)
   - descomprimir el archivo en la carpeta raíz del servidor (htdocs o www).
   

3. Configurar las credenciales de los correos electronicos
   - Dirigite al archivo app.php ubica la seccion "Configurar el servidor SMTP"
   - Colocar el correo electronico real y contraseña (gmail app password")
   - Crear gmail app password : 
https://www.youtube.com/watch?v=Q74nxFBCHCI&t=196s
4. Ejecutar el script
   - Iniciar el servidor

   - ingrese a http://localhost/consumo-ws-cambioMoneda/ (para XAMP)

   - Ingrese a http://comsumo-ws-cambiomoneda.test/  (para Laragon)
