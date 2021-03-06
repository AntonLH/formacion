---
layout: post
title: Formación GipuzkoaNatura
date: 2020-04-20 09:22
---

![logo-izfe](/images/image2.png)


## ÍNDICE 

- [INTRODUCCIÓN](#introducción)

- [NOTICIA](#noticia)

- [AGENDA](#agenda)

- [PARKETXE](#parketxe)

- [BILLBOARD](#billboard)

## INTRODUCCIÓN

Esta es una guía rápida de uso del portal y gestor de contenidos basado
en Liferay para la gestión de la web de GipuzkoaNatura.

El objetivo de este manual es recoger las acciones necesarias para
gestionar los diferentes tipos de contenido de esta web en concreto,
especialmente su creación, describiendo los pasos necesarios para
conseguirlo.

Es preciso que el lector tenga unas nociones mínimas sobre el
funcionamiento de Liferay, que podrá encontrar en [Formación Liferay](/2020/04/20/formacion-liferay).

Antes de empezar a editar contenidos tendremos que iniciar sesión. Para ello
entramos en [https://www.gipuzkoanatura.eus/es/entrada](https://www.gipuzkoanatura.eus/es/entrada), introducimos nuestro usuario y contraseña y pulsamos acceder. Veremos que ahora tenemos una barra ocupando la parte superior de la web, que nos permite acceder a la parte privada de administración, donde editaremos los contenidos.

![](/images/login.gif)

## NOTICIA 

En este apartado se describe la forma de añadir nuevas noticias a la web
de GipuzkoaNatura. Lo haremos con un contenido estructurado (Noticia),
uno por cada una de las noticias, que permitirán su listado completo, así como
búsqueda o filtrado posterior en distintas ubicaciones de la web.

El proceso es el siguiente:

1. Las noticias necesitan una imagen asociada. Siempre debe estar subida a
la galería de Documentos y Multimedia de Liferay de forma previa,
siguiendo el siguiente paso.

2. Accedemos a Documentos y Multimedia, en la ruta “Inicio \> EDUKIAK \>
AKTUALITATEA \> Albisteak”.

3. Pulsamos el botón de añadir y seleccionamos “Documento básico”, o
desde un explorador de archivos, hacer “arrastrar y soltar”.
![](/images/documentosnoticia.gif)

4. Una vez subida la imagen, accedemos a Contenido Web, en la ruta
“Inicio \> EDUKIAK \> AKTUALITATEA \> Albisteak”.

5. Pulsamos el botón de añadir y seleccionamos la estructura Noticia. Nos
presenta un formulario con los datos de la noticia para rellenar.
![](/images/noticia.gif)

6. Introducimos el Título de la noticia, por defecto cualquier contenido que
creemos se creará en euskera, si queremos añadir una traducción tenemos
que pulsar el botón con la bandera y seleccionar otro idioma, entonces
se vaciarán los campos y podremos rellenarlos en el nuevo idioma.
![](/images/idioma.gif)

7. Seleccionamos la imagen que hemos subido a Documentos y Multimedia, y
en el campo Descripción del artículo introducimos un texto corto como
descripción de la imagen, es opcional pero sería conveniente que todas
las imágenes lo tuvieran, ya que es necesario para asegurar la
accesibilidad de la página.
![](/images/imagen.gif)

8. Añadimos la entradilla, que es el texto que se mostrará en el listado
de noticias antes de entrar a leerlas y la fecha de publicación de la noticia.

9. Ahora hay que editar el contenido principal, en formato HTML. Podemos escribir aquí el contenido, pero si lo tenemos ya escrito en otro sitio
tendremos que copiarlo como texto sin formato (Ctrl+Mayús+V) y darle el formato en este editor. Para ello el editor tiene varias opciones.<br>
Mostrar texto como título, en negrita, cursiva o subrayado, en listado.
![](/images/editor.gif)
Añadir imágenes o enlaces a documentos previamente subidos a Liferay en la galería de documentos y multimedia.
![](/images/editor2.gif)

10. Es importante que recordemos respetar las normas de accesibilidad cuando creamos el contenido, todas las imágenes tienen que tener su texto descriptivo,
no podemos usar las opciones título 1 y título 2 ya que no respetarían la estructura de la página. 

11. Una vez rellenados todos los campos obligatorios en ambos idiomas pulsamos el botón Publicar para
publicar el contenido, si no hemos terminado pero queremos guardar los
cambios pulsamos Guardar borrador.

12. La noticia saldrá publicada en el inicio, junto a las dos últimas y en la página de noticias. Si queremos que salga además 
como destacada en la página de inicio tendremos que seleccionarla en la configuración del portlet. Pulsamos en configuración 
y en la ventana que se abre pulsamos el botón Seleccionar dentro del apartado Contenidos, seleccionamos la estructura Noticia y 
pulsamos sobre la noticia que queramos destacar. Se añadirá debajo de la actualmente destacada, por lo que tendremos que eliminar
la otra o subir la nueva pulsando la flecha.
![](/images/noticiadestacada.gif)

## AGENDA

En este apartado se describe la forma de añadir nuevos eventos a la
agenda de la web de GipuzkoaNatura. Lo haremos con un contenido
estructurado (Agenda), uno por cada uno de los eventos, que permitirán su
listado completo, así como búsqueda o filtrado posterior en distintas
ubicaciones de la web.

El proceso es el siguiente:

1. Los eventos de la agenda, al igual que las noticias tienen una imagen
asociada, pero en este caso es opcional. Siempre debe estar subida a la
galería de Documentos y Multimedia de Liferay de forma previa, siguiendo
el siguiente paso. En caso de no ser necesaria una imagen podemos saltar al paso 4.

2. Accedemos a Documentos y Multimedia, en la ruta “Inicio \> EDUKIAK \>
AGENDA”.

3. Pinchar en “Añadir \> Documento básico”, o desde un explorador de
archivos, hacer “arrastrar y soltar”.
![](/images/documentosagenda.gif)

4. Una vez subida la imagen, accedemos a Contenido Web, en la ruta
“Inicio \> Agenda”.

5. Pulsamos el botón de añadir y seleccionamos la estructura Agenda. Nos
presenta un formulario con los datos del evento para rellenar.
![](/images/agenda.gif)

6. Introducimos el Título del evento, por defecto cualquier contenido que
creemos se creará en euskera, si queremos añadir una traducción tenemos
que pulsar el botón con la bandera y seleccionar otro idioma, entonces
se vaciarán los campos y podremos rellenarlos en el nuevo idioma.

7. Seleccionamos la imagen que hemos subido a Documentos y Multimedia, y
en el campo Texto alternativo de la imagen (alt) introducimos un texto
corto como descripción de la imagen, es opcional pero sería conveniente
que todas las imágenes lo tuvieran, ya que es necesario para asegurar la
accesibilidad de la página.

9. Añadimos la entradilla, seleccionamos las fechas de inicio y fin del
evento, el enlace de detalle (página a la que irá al pulsar sobre el
título) y la localización, que será un enlace con la URL y el texto
indicados.
![](/images/image6.png)

10. En el caso de esta estructura los únicos campos obligatorios son el
título, la fecha y la URL de detalle, los demás son opcionales.

11. Una vez rellenados los campos necesarios pulsamos el botón Publicar
para publicar el contenido, si no hemos terminado pero queremos guardar
los cambios pulsamos Guardar borrador.

## PARKETXE

En este apartado se describe la forma de añadir nuevos parketxes en la 
web de GipuzkoaNatura. Lo haremos con un contenido estructurado (Parketxe),
uno por cada uno de los parketxes, que permitirán su
listado completo, así como búsqueda o filtrado posterior en distintas
ubicaciones de la web.

El proceso es el siguiente:

1. Los parketxes, además de imágenes también pueden tener documentos
asociados. Siempre deben estar subidos a la galería de Documentos y
Multimedia de Liferay de forma previa, siguiendo el siguiente paso.

2. Accedemos a Documentos y Multimedia, en la ruta “Inicio \> EDUKIAK \>
PARKETXEAK”.

3. Pinchamos en el botón de Añadir y seleccionamos subcarpeta, le ponemos
el nombre del Parketxe y entramos.
![](/images/documentosparketxe.gif)

4. Volvemos a pulsar añadir y seleccionamos múltiples documentos y
arrastramos o seleccionamos todos las imágenes o documentos de el
parketxe.

4. Una vez subidos las imágenes y documentos accedemos a Contenido Web,
en la ruta “Inicio \> EDUKIAK \> PARKETXEAK”.

5. Pulsamos el botón de añadir y seleccionamos la estructura Parketxe.
Nos presenta un formulario con los datos del evento para rellenar.
![](/images/parketxe.gif)

6. Introducimos el Título del contenido que será el nombre con el que se
mostrarán el título y los enlaces al parketxe, por defecto cualquier
contenido que creemos se creará en euskera, si queremos añadir una
traducción tenemos que pulsar el botón con la bandera y seleccionar otro
idioma, entonces se vaciarán los campos y podremos rellenarlos en el
nuevo idioma.

7. Introducimos en el campo “Nombre del parketxe” el texto que queramos
que aparezca como título en el detalle del parketxe, la descripción
inicial, como campo HTML, después introducimos las imágenes
seleccionándolas entre las que hemos subido a Documentos y Multimedia,
y en el campo Descripción de la imagen introducimos un texto corto como
descripción de cada imagen, es opcional pero sería conveniente que todas
las imágenes lo tuvieran, ya que es necesario para asegurar la
accesibilidad de la página, para añadir más de una imagen tenemos que
pulsar en el botón de la derecha, que creará los campos nuevos para
rellenar. Después introducimos el resto de la descripción que se
mostrará después del carrusel de imágenes. En estos campos HTML podemos incrustar
vídeos de youtube y otros proveedores, pulsando el botón de añadir y seleccionando
la opción de vídeo, tendremos que copiar el enlace al vídeo y aceptar.
![](/images/parketxe3.gif)

8. Añadimos un texto descriptivo de la oferta educativa y los documentos
que relacionados con ella, además del título correspondiente en cada
uno. Se pueden subir tanto documentos (pdf, doc…) como imágenes, pero
todos se mostrarán como enlaces a abrir en una nueva pestaña.
![](/images/parketxe2.gif)

9. Tras esto añadimos los datos de ubicación y contacto, los textos de
introducción de ubicación y dirección, las coordenadas en formato
ETRS89, los texto de contacto y cómo llegar en formato HTML y el
documento de horario.

10. Podemos añadir también documentos o enlaces externos que se mostrarán
al final de la página.

11. Añadimos en el campo Introducción dentro de Actividades el texto que
se mostrará antes del listado de actividades en formato HTML. Después
podemos añadir las actividades que queramos y rellenar sus campos
título, descripción, enlaces y documentos con sus textos
correspondientes.

12. Introducimos el ID de parketxe, necesario para obtener el listado de
senderos del parketxe y la URL a detalle.

13. Una vez rellenados los campos necesarios pulsamos el botón Publicar
para publicar el contenido, si no hemos terminado pero queremos guardar
los cambios pulsamos Guardar borrador.


## BILLBOARD

En este apartado se describe la forma de editar el contenido de la cabecera
principal de la web de GipuzkoaNatura para añadir noticias o eventos destacados.
Tendremos que editar el contenido "Billboard home" de tipo "Billboard - Inicio".

El proceso es el siguiente:

1. Desde la página principal pulsar el botón con tres puntos "Opciones de contenido web"
que permite editar el contenido, seleccionamos la opción "Editar contenido web" y se nos abrirá 
el formulario que tendremos que editar.
![](/images/billboard.gif)

2. De este formulario tendremos que editar únicamente los apartados "Billboard - Tituloa" y "Evento".
Editando o añadiendo un nuevo elemento "Billboard - Tituloa" podremos gestionar las noticias destacadas
y con el campo "Evento" seleccionaremos o añadiremos eventos nuevos.

3. Para añadir una nueva noticia tendremos que pulsar el botón azul con un plus (+), a la derecha del campo
"Billboard - Tituloa" que nos creará cuatro campos nuevos a rellenar. Después de rellenarlos podremos 
reorganizar las noticias arrastrándolas para ordenarlas.
![](/images/billboard2.gif)

4. Para añadir un evento pulsamos en el botón azul con un plus (+), a la derecha del campo "Evento" que nos
creará otro campo "Evento", pulsamos Seleccionar y buscamos el contenido de tipo "Agenda" que queramos destacar.
![](/images/billboard3.gif)

5. Una vez hechos todos los cambios en ambos idiomas pulsamos el botón Publicar
para publicar el contenido, si no hemos terminado pero queremos guardar
los cambios pulsamos Guardar borrador.

