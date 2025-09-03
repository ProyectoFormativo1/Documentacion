---
title: Autenticación de Usuario
description: usuario
---
El sistema debe permitir que los usuarios inicien sesión de manera segura mediante credenciales válidas. 

A continuación, se describen los pasos para realizar el inicio de sesión de manera adecuada:

:::note
Asegurese de ingresar correctamente sus credenciales como correo y contraseña.
:::
### Credenciales para ingreso

```json
{
  "correo": "daniela@gmail.com",
  "contraseña": 123456
  
}
```
##### 1. Ingresar sus credenciales, para continuar dar clic en Iniciar Sesion

![Pantalla de inicio de sesión](/public/inicio_sesion.png)


##### 2. Después de que el usuario se autentique correctamente en el sistema (correo y contraseña válidos), el sistema debe redirigirlo automáticamente al apartado de Inicio. 

![Panel principal](/public/inicio.png)

##### 3. En caso de que la contraseña o correo sean incorrectos no le permitira seguir y prensentara una alaerta.

![Alerta credenciales incorrectas](/public/alerta.png)
