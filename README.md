# Proyecto Segundo Bimestre

**Autor**: Jonathan Andres Rosero Soto

BINNARIUM Pizza's es un aplicación mediante la cual los usuarios podrán crear su propia Pizza totalmente Personalizada la cual se compartirá en la aplicación con otros usuarios para que cualquier persona pueda pedirla. La aplicación otorgará beneficios a la semana a las pizzas con mayor creatividad e índice de popularidad (pedidos realizados y reseñas obtenidas).

Para esta aplicación se usará una ontología y un razonador que permitan realizar pizzas de todo tipo con los ingredientes existentes en la pizzería. Además el razonador nos ayudará a determinar las pizzas de mayor creatividad mediante las cuales los usuarios pueden obtener beneficios, esto permitirá crear una red de creación de pizzas aumentando la cantidad de venta.


## Archivos

El presente proyecto se divide en tres carpetas principales:

 1. **Documentación**: en esta carpeta se encuentran informes y presentaciones que ayudarán a mejorar el entendimiento de lo creado, incluyendo diagramas de flujo para la creación del chatbot así como modelos C4.
 2. **Ontología**: esta carpeta contiene la ontología inicial así como la versión extendida para el funcionamiento de Binnarium Pizzas, la versión extendida cuenta con el personal, pizzerías y clientes así como sus relaciones y propiedades.
 3. **Proyecto**: en esta carpeta es donde reside el código tanto del chatbot como del sistema REST para la consulta hacía la ontología y se subdivide en:
	 - chatbot: contiene los códigos del chatbot: intentos, entidades y reconocimiento de lenguaje natural, este proyecto fue desarrollado en Dialogflow junto con funciones nodejs, el sistema se encuentra operando en Telegram mediánte este enlace https://t.me/BinnariumBot.
	 - pizza-tutorial: este proyecto contiene un servicio REST para la consulta de la ontología, esta desarrollado utilizando JAVA con el framework SPRING BOOT y Jena con Fuseki para la lectura de la ontología y exportación a json, el sistema opera en local al ejecutar el proyecto, se podrá revisar la ontología mediante este endpoint http://localhost:8080/recommendation.

## Licencias

Todo el proyecto fue desarrollado mediante software de distribución abierta, este repositorio cuenta con una licencia MIT, la que permite a cualquier persona hacer uso de este proyecto, de su código y de su documentación. Para mayor información revise licencias MIT (https://opensource.org/licenses/MIT)
