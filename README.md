# Proyecto para NTT-DATA

## Intriducción

Proyecto prueba técnica para NTT DATA, lenguajes de programación React con Material UI, con gestor de paquetes npm, (npm run dev) para la conexión con el servidor.

## Funcionalidades

El proyecto NTT-DATA se conecta a una Api externa de países, con encarpetado de components, context, hooks, pages. La prueba de esta aplicación es conectarnos a la Api creando un buscardor de continentes, la cual se encuentra en: 
-components (Grouped), listando las categorías ya predeterminadas por la Api, haciendo la conexión con nuestro context e imprimiendo el resultado. seguido de componentes (Information), donde desestructuramos la información y creamos el objeto con peticiones en pantalla e imprimimos la información.
 En el archivo componentes (ListCountry) imprimimos la información en el listado de la pantalla principal después de hacer las consultas a la Api. Tenemos un Header principal para cada página en components(Header). -tenemos un buscador con un icono en cual nos buscar por los nombres de cada país,en components(Searchbq), conectándonos al context por medio de otra URL en axios para extraer la información e imprimirla.
 -Seguido el reto también es darle clic a la imagen de la lista y que nos lleve a otra página mostrando la información del país, para esto en components(NextInformation) donde hacemos la lógica para solicitar a la Api la información requerida para esta pantalla, esta parte tuve que realizar algo que no debería, lo hice por inconvenientes con la librería, un windows.localStorage ya que por muchas pruebas que hice no me estaba trayendo la información solicitada. después en components(ListNext) traemos toda la funcionalidad para imprimirla.



En los Pages(paginas), tenemos el App que es nuestro componente principal de la carpeta, en este componente realice la lógica para la implementación del Darkmode, extraído de nuestra librería de estilos seguido de un botón de encendido y apagado para obtener la pantalla clara o negra a gusto o preferencia del cliente, en este archivo también tenemos un rutado para la funcionalidad de las páginas.
 -Después tenemos el Home que es nuestra primera pantalla donde se le manda los componentes Header, Searchbq(buscador con icono, el Grouped que es el buscador de continentes y ListCountry que es el listado de las solicitudes de los componentes ya mencionados anteriormente. -Tenemos el Next que es la página donde se imprime la solicitud al darle clik a una imagen con el listado requerido y el botón para regresar a la página principal.


## Dificultades

El link de la Api que me mandaron en el correo no me funciono la v2, lo realice con la v3. Tuve la osadía de trabajar con Material UI, no la conocía mucho ya que normalmente trabajo con Tailwind, quise hacerlo como un reto personal.

## Agradecimientos

Gracias a la empresa NTT DATA por tomarme en cuenta para participar en la postulación de tan prestigiosa empresa.



