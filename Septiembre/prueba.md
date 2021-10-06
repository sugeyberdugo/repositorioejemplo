### Req Funcional

| Código | Nombre | Fecha | Grado necesidad |
| --- | --- | --- | --- |
| RF001 | Inicio de sesión | 18/09/21 | Alto |
| Descripción | En este módulo los usuarios podrán iniciar sesión con correo electrónico y contraseña. Contará con botón de “Ingresar”. Y tendrán la opción de recuperar la contraseña. |
| Entradas | Fuente | Salida | Destino | Restricciones |
|Correo electrónico | Nombre completo, Foto de perfil | Menú principal, página de promoción | El usuario no podrá tener acceso al sistema y sus funcionalidades si no se registra e inicia sesión.|
|Proceso| Digitar correo electrónico y contraseña > Clic en botón “ingresar” > Verificación en la base de datos. Si los datos son correctos, se realiza el ingreso. De lo contrario, se muestra un mensaje al usuario, pidiendo que por favor verifique la información e intente nuevamente.> Si el usuario olvidó su contraseña de acceso, dará clic en “recuperar contraseña”.  En la misma interfaz se solicitará ingresar número de identificación, y correo electrónico. >  Una vez digite la información de manera correcta, se enviará detalles de recuperación.|
| Efecto colateral | El usuario no podrá ingresar al sistema, no podrá tener acceso a todas las funcionalidades para realizar pedidos, Bloqueo por intentos fallidos, Cierre de sesión automático | 