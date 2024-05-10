# Desafío - Black and White

Procesamiento de imágenescon JIMP y la descarga de aplicaciones.

## Descripción

La empresa Black and White Spa está promocionando una campaña para las redes sociales en donde quieren ofrecer un sitio web que permita escribir la URL de una imagen de internet y que ésta sea procesada por el servidor para ser devuelta en blanco y negro. Deberás crear un servidor que disponibilice una ruta raíz que devuelva un HTML con el formulario para ingresar la URL de la imagen con estilos CSS de un documento interno en los archivos del servidor. El formulario debe redirigir a otra ruta del servidor que procese la imagen y la devuelva en blanco y negro.

## Requerimientos📜

1. El servidor debe disponibilizar una ruta raíz que devuelva un HTML con el formulario
   para el ingreso de la URL de la imagen a tratar. (3 Puntos)
2. Los estilos de este HTML deben ser definidos por un archivo CSS alojado en el
   servidor. (2 Puntos)
3. El formulario debe redirigir a otra ruta del servidor que deberá procesar la imagen
   tomada por la URL enviada del formulario con el paquete Jimp. La imagen debe ser
   procesada en escala de grises y redimensionada a unos 350px de ancho. (3 Puntos)
4. La imagen alterada debe ser almacenada con un nombre incluya una porción de un
   UUID y con extensión “jpg”, por ejemplo: 3dcb6d.jpeg. (2 Puntos)

## Empezando 🚀

Estas instrucciones te guiarán para obtener una copia de este proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas.

```bash
git git@github.com:Percy-182/black_and_White.git
```

### Pre-requisitos 📋

Lista de software y herramientas, incluyendo versiones, que necesitas para instalar y ejecutar este proyecto:

- Sistema Operativo (Ubuntu 20.04, Windows 10, MacOS 10.15)
- Navegador (Firefox, Opera, Chrome, Brave, Safari)
