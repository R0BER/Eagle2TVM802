# Eagle2TVM802
Convertidor Eagle Layout a TVM802 Pick and Place

El software esta solo disponible en Español.

Este programa carga archivos eagle mnt y mnb (que se exportan con el ULP estándar: mountsmd), asigna una lista de pila/bandeja a los componentes y genera un archivo pick&place compatible con TVM802.

Como impotar:
Dentro de eagle, abrir  FILE/RUN UPL
Seleccionar  mount-smd-tht
En el dialogo seleccionar solo smd y ok

Con esto tenemos los archivos para importar, luego en  este software seleccionar cargar archivo eagle, boton aguila roja

Permite una fácil edición y procesamiento automático de pilas, boquillas, visión, listados de componentes ... y todas las demás configuraciones.

El software está escrito en C# con Visual Studio 2022, el programa compilado y listo para usar se puede encontrar en la carpeta:
MyPickPlace\MyPickPlace\bin\publish
