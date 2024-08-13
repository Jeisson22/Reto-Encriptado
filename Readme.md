# Encriptador de Texto

## Descripción

Este proyecto es una aplicación web que permite encriptar y desencriptar mensajes de texto utilizando un cifrado simple. La aplicación está construida con HTML, CSS y JavaScript, y se enfoca en proporcionar una interfaz amigable y fácil de usar.

## Funcionalidades

- **Encriptar texto:** Convierte vocales en combinaciones específicas de caracteres.
- **Desencriptar texto:** Restaura el texto encriptado a su forma original.
- **Copiar al portapapeles:** Permite copiar el texto encriptado o desencriptado con un solo clic.
- **Validación del texto:** Asegura que solo se ingresen letras minúsculas y sin acentos, evitando caracteres no permitidos como números, símbolos, y emojis.

## Requisitos

- Un navegador web actualizado.

## Instalación y Configuración

1. Clona el repositorio en tu máquina local:

    ```bash
    git clone https://github.com/tu-usuario/encriptador-de-texto.git
    ```

2. Navega a la carpeta del proyecto:

    ```bash
    cd encriptador-de-texto
    ```

3. Abre el archivo `index.html` en tu navegador favorito para usar la aplicación.

## Estructura del Proyecto

- **`index.html`:** Archivo principal de la aplicación web.
- **`style.css`:** Hoja de estilos para la interfaz de usuario.
- **`script.js`:** Archivo JavaScript que contiene la lógica para encriptar, desencriptar, copiar texto y validar la entrada del usuario.
- **`img/`:** Carpeta que contiene imágenes utilizadas en el proyecto, como el logo y otros elementos gráficos.

## Uso

1. Ingresa el texto que deseas encriptar en el área de texto proporcionada.
2. Haz clic en el botón "Encriptar" para convertir el texto.
3. El texto encriptado se mostrará en la segunda área de texto.
4. Puedes desencriptar el texto ingresado o encriptado haciendo clic en "Desencriptar".
5. Usa el botón "Copiar" para copiar el texto procesado al portapapeles.

## Ejemplo de Cifrado

El encriptador transforma las vocales del texto ingresado de la siguiente manera:

- `a` se convierte en `ai`
- `e` se convierte en `enter`
- `i` se convierte en `imes`
- `o` se convierte en `ober`
- `u` se convierte en `ufat`

Por ejemplo, "hola mundo" se encriptaría como "hoberlai munderfat".

## Créditos

- Desarrollado por John Gonzales.

## Licencia

Este proyecto está bajo la Licencia MIT. Para más detalles, consulta el archivo `LICENSE`.
