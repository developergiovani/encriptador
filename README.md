## Encriptador de Texto: Un Desafío Alura Latam

### Descripción
Esta aplicación web, desarrollada como parte de un desafío de Alura Latam, realiza operaciones básicas de cifrado y descifrado de texto utilizando un conjunto predefinido de reglas de sustitución. Es una herramienta sencilla pero efectiva para experimentar con técnicas básicas de criptografía.

### Funcionalidades
* **Cifrado:** Convierte texto en minúsculas a una forma cifrada siguiendo reglas específicas de sustitución.
* **Descifrado:** Revierte el proceso de cifrado, devolviendo el texto a su estado original.
* **Copiado al Portapapeles:** Permite copiar fácilmente el texto cifrado o descifrado para su posterior uso.

### Reglas de Cifrado y Descifrado
| Letra Original | Letra Cifrada |
|---|---|
| e | enter |
| i | imes |
| a | ai |
| o | ober |
| u | ufat |

### Uso
1. **Ingresar Texto:** Escribe el texto que deseas cifrar o descifrar en el campo de texto provisto.
2. **Seleccionar Operación:** Haz clic en el botón "Cifrar" o "Descifrar" para realizar la operación correspondiente.
3. **Copiar Resultado:** Utiliza el botón "Copiar" para copiar el texto cifrado o descifrado al portapapeles.

### Estructura del Proyecto
* **index.html:** Archivo principal que define la estructura de la página web.
* **styles.css:** Hoja de estilos CSS para personalizar la apariencia de la aplicación.
* **encrypter.js:** Archivo JavaScript que contiene la lógica de cifrado y descifrado.

### Requisitos
* **Texto en Minúsculas:** La aplicación solo procesa texto en minúsculas.
* **Sin Caracteres Especiales:** No se permiten acentos ni otros caracteres especiales.

### Instalación y Uso Local
1. **Clonar el Repositorio:** Utiliza Git para obtener una copia local del proyecto.
2. **Abrir index.html:** Abre el archivo `index.html` en tu navegador web preferido.

### Mejoras Futuras
* **Validación de Entrada:** Implementar una validación más robusta para asegurar que el usuario solo ingrese texto válido.
* **Interfaz de Usuario:** Mejorar la interfaz de usuario para hacerla más intuitiva y atractiva.
* **Múltiples Conjuntos de Reglas:** Permitir al usuario seleccionar diferentes conjuntos de reglas de cifrado.
* **Cifrados Más Complejos:** Explorar algoritmos de cifrado más sofisticados, como el cifrado César o el cifrado por sustitución polialfabética.
* **Historial de Operaciones:** Mantener un historial de las operaciones realizadas para facilitar la revisión y edición.

**Nota:** Este encriptador es una herramienta educativa y no está diseñado para proteger información sensible. Para aplicaciones de seguridad, se recomienda utilizar algoritmos de cifrado más robustos y establecidos.
