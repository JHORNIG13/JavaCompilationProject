# Historias de Usuario

## Historia de Usuario 1
**ID**: HU-01  
**Rol**: Usuario del sistema  
**Funcionalidad**: Registrar y mostrar datos personales  
**Razón/Resultado**: Como usuario, quiero poder ingresar mi nombre y edad para que el sistema pueda registrar y mostrar mi información personal.  
**Criterios de Aceptación**:
- El sistema debe permitir al usuario ingresar su nombre y edad.
- El sistema debe mostrar los datos ingresados en pantalla.
- Los datos deben ser validados para asegurar que se ingresen en el formato correcto (por ejemplo, la edad debe ser un número entero).

**Prioridad**: Alta  
**Supuestos**:
- Se asume que el usuario tiene acceso al sistema y que entiende cómo utilizar la interfaz de entrada de datos.

## Historia de Usuario 2
**ID**: HU-02  
**Rol**: Administrador del sistema  
**Funcionalidad**: Ver un registro de todas las entradas de datos realizadas por los usuarios  
**Razón/Resultado**: Como administrador, quiero ver un registro de todas las entradas realizadas para asegurarme de que los datos se están recopilando correctamente.  
**Criterios de Aceptación**:
- El sistema debe permitir al administrador ver una lista de todos los registros de datos ingresados por los usuarios.
- La lista debe mostrar el nombre, edad y la fecha en que se ingresaron los datos.
- El administrador debe poder filtrar los registros por fecha o por nombre.

**Prioridad**: Media  
**Supuestos**:
- Se asume que los datos ingresados se almacenan en una base de datos accesible por el administrador.

## Historia de Usuario 3
**ID**: HU-03  
**Rol**: Desarrollador  
**Funcionalidad**: Documentar el código fuente y proceso de desarrollo  
**Razón/Resultado**: Como desarrollador, necesito documentar el código fuente y el proceso de desarrollo para que otros miembros del equipo puedan entender y mantener el proyecto en el futuro.  
**Criterios de Aceptación**:
- Cada línea de código debe estar documentada con comentarios claros y precisos.
- El proceso de desarrollo debe estar registrado en un documento separado (README.md), detallando los pasos seguidos y las herramientas utilizadas.

**Prioridad**: Alta  
**Supuestos**:
- Se asume que los desarrolladores tienen acceso a las herramientas necesarias para realizar la documentación (como un editor de texto y acceso al repositorio Git).

## Historia de Usuario 4
**ID**: HU-04  
**Rol**: Usuario del sistema  
**Funcionalidad**: Ver una confirmación después de ingresar los datos  
**Razón/Resultado**: Como usuario, quiero recibir una confirmación visual después de ingresar mis datos para estar seguro de que se registraron correctamente.  
**Criterios de Aceptación**:
- El sistema debe mostrar un mensaje de confirmación una vez que el usuario ha ingresado y enviado los datos correctamente.
- El mensaje debe ser claro y visible, indicando que la operación fue exitosa.

**Prioridad**: Alta  
**Supuestos**:
- Se asume que el sistema tiene la capacidad de mostrar mensajes dinámicos al usuario en la interfaz de usuario.
