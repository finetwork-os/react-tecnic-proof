![](assets/logo/finetwork_black.svg)

# Prueba técnica — React developer

## Objetivo
El objetivo de esta prueba técnica es que el candidato muestre sus habilidades con las herramientas que utilizará luego en su trabajo diario en Finetwork. Está diseñado para verificar las habilidades de desarrollo front-end utilizando React y su capacidad para resolver problemas. 

Pondremos el foco en obtener un código simple, bien diseñado y organizado, eficaz y testeado, así como el cumplimiento de todos los requerimientos solicitados. 

## Desarrollo del Proyecto
 - Se deberá clonar este repositorio para poder modificarlo y completarlo con la resolución del proyecto. 
 - Una vez que su código esté listo, suba el código a un repositorio público propio y envíenos el enlace a dicho repositorio para que lo revisemos. 

> Se pueden utilizar herramientas como [create-react-app](https://github.com/facebookincubator/create-react-app) y similares para inicializar el proyecto.

## Prueba técnica
Usando de referencia los estilos de la marca [Finetwork](https://www.finetwork.com/), deberá crear un pequeño flujo de contratación funcional, donde el cliente pueda seleccionar el producto que quiera y ser llevado al checkout, donde deberá elegir entre las promociones disponibles.

Se deberá incluir también `README` con instrucciones de configuración/ejecución y cualquier prueba u otra documentación que haya creado como parte de su solución.

Además, agregue la siguiente información a su archivo `README`:

- ¿Cómo decidió las opciones técnicas y arquitectónicas utilizadas como parte de su solución?
- ¿Hay alguna mejora que pueda hacer en su envío?
- ¿Qué haría de manera diferente si se le asignara más tiempo?

## Detalles
Necesitará mostrar un mini catalogo de selección de producto. 
La api a utilizar sera la siguiente:

    https://gateway.finetwork.com/product/offering/products?page=1&size=20
    
Necesitará construir un checkout divido en los siguientes pasos:
- Sección de oferta seleccionada con información adicional
- Selección de promoción
- Insercción de los datos de cliente
- Sección resumen de pedido

### Otras consideraciones

También necesitará manejar los estados de carga/loading y error de obtener los datos desde el archivo JSON, como de hacer la petición.
