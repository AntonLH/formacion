---
layout: post
title: Formación Liferay
date: 2020-04-20 09:22
---


![logo-izfe](/images/image2.png)


## INDICE 

- [INTRODUCCIÓN](#introducción)

- [CONCEPTOS IMPORTANTES](#conceptos-importantes)

  * [Páginas](#páginas)

  * [Layouts](#layouts)

  * [Portlets (o aplicaciones)](#portlets-o-aplicaciones)

  * [Contenidos web](#contenidos-web)

  * [Contenidos multimedia](#contenidos-multimedia)

  * [Opciones de publicación](#opciones-de-publicación)

## INTRODUCCIÓN.

Esta es una guía rápida de uso del portal y gestor de contenidos basado
en Liferay. El objetivo de este manual es reconocer las acciones
necesarias para gestionar los contenidos de una web, y describiendo una
serie de pasos, conseguirlo de la forma más sencilla posible.

Un portal es una aplicación informática, habitualmente compleja, que
permite la creación y gestión continua de una web de casi cualquier
tipo. Esta capacidad de gestionar sitios complejos es lo que hace que en
algunos casos su manejo no sea todo lo sencillo que nos gustaría. Sin
embargo, la idea de este documento, y del curso asociado, es
precisamente filtrar sus muchas posibilidades para ceñirse a las
estrictamente necesarias para editar los contenidos y pequeñas acciones
de mantenimiento del día a día.

Las webs tienen tienen siempre dos perfiles: uno público, accesible a
todo el mundo en Internet, y otro privado, interno, restringido, donde
después de comprobar su identificación, determinados usuarios pueden
hacer diferentes tareas que tienen reflejo en la parte pública.

Empezaremos por cómo acceder, mediante un usuario y contraseña, e
identificar las opciones del menú reservadas para las tareas más
habituales. Para eso describiremos los conceptos más importantes, como
son las páginas, los portlets y los contenidos, y después pasaremos a
trabajar con ellos.

En este punto habrá que profundizar en otros aspectos o utilidades como
el multilingüismo de los contenidos, su clasificación, publicación
directa o planificada y el propio contenido, introducido con un editor
(casi) WYSIWYG o directamente con HTML.

Pero iremos paso a paso, tratando de fijar los conceptos previos antes
de pasar al siguiente.

## CONCEPTOS IMPORTANTES.

Decimos que Liferay es un portal web. Esto significa que es una
aplicación capaz de mostrar webs cuyas páginas a su vez están divididas
en bloques, en pequeñas porciones que son aplicaciones (conocidas como
portlets) que de forma independiente, pueden *hacer cosas* o mostrar
información de diferentes orígenes.

Esta es una de las razones que hace que no sea posible editar una página
web como si fuera un documento de Word, por ejemplo. En el navegador
estamos viendo informaciones diferentes, creadas por personas distintas
(o incluso por aplicaciones externas) y por eso sólo podemos editar
contenidos individuales, dentro de esos *bloques*. Vamos a hacer una
relación de los conceptos más importantes para poder entender el resto
del manual.

## Páginas.

Aunque en ocasiones hablamos de “página web” para referirnos a una web
en su conjunto, utilizaremos para esto el término “sitio web”. De esta
forma dejaremos *libre* el término “página”, que utilizaremos para esta
unidad de información.

![](/images/image42.png)

Una página es un concepto básico en Liferay, es un continente sobre el
que podemos ir añadiendo información, bloques, imágenes, y en definitiva
cualquier tipo de información. Es como un lienzo en blanco en el que
podemos colocar diferentes tipos de información, bien sea estática o
dinámica. Cada página puede formar parte del menú principal. Es decir,
que al crear una página, sin hacer nada, automáticamente, en el mapa web
de nuestro sitio aparecerá esa opción, a la que los usuarios pueden
acceder a través de un clic de ratón.

Cada página tiene una URL asociada (o dirección única, que aparece en la
barra de direcciones del navegador), la cual puede ser compartida
mediante enlaces, correo electrónico, redes sociales o tecleándola a
mano.

## Layouts.

Una vez que ya tenemos nuestro lienzo donde ir colocando información,
nos falta definir el *layout* o disposición de la página.

Un layout es una especie de rejilla donde poder ubicar aplicaciones
(*portlets*), una plantilla basada en filas y/o columnas donde podemos
arrastrar los diferentes bloques y organizar la información en la forma
que resulte más apropiada.

El layout más sencillo es el de una columna. Es una única zona donde los
portlets se colocan uno debajo de otro, ocupando toda la anchura
disponible de pantalla.

En la siguiente imagen podemos ver otros tipos de layouts que permiten
distintas distribuciones del contenido, definiendo varias filas y
columnas. Además de los propios de Liferay tenemos layouts desarrollados
especialmente para algunos casos.

![](/images/image52.png)

## Portlets (o aplicaciones).

El siguiente concepto que veremos es el de los portlets. Tras este
término se esconde algo tan sencillo como una *aplicación*. Las hemos
visto de todo tipo: algunas de escritorio, que se instalan en nuestro
ordenador y nos permiten hacer determinadas cosas, otras que instalamos
en nuestro teléfono o tablet y que se suelen llamar *apps*. Incluso
algunos widgets que podemos poner en sus pantallas de inicio. Pero
básicamente son lo mismo, programas informáticos que realizan algunas
operaciones que nos aportan ayuda o información. Lo que cambia en el
entorno, el *dónde* se ejecutan.

![](/images/image62.png)

Un portlet es exactamente lo mismo, una aplicación, pero que se ejecuta
dentro de un portal, Liferay en nuestro caso, en un bloque del layout de
una página. Pueden entenderse como pequeñas (o a veces no tan pequeñas)
aplicaciones que acompañadas de otras, dan forma a una web.

Hay múltiples tipos de portlets, cada uno de los cuales hace diferentes
funciones. La mayoría vienen ya incluidos con Liferay, aunque si en
algún caso se necesita algo concreto, es posible desarrollar portlets a
medida, instalarlo en Liferay y utilizarlo normalmente. Estos son los
portlets más habituales:

  - Visor de contenido web

  - Publicador de contenidos (para listados)

  - Visor de documentos y multimedia

  - Navegación (para visualizar las páginas en un bloque, aparte del
    menú)

  - Camino de migas

  - Galería multimedia

  - Y otros adicionales como
    
      - Blog
    
      - Foro
    
      - Calendario
    
      - …

Prácticamente todos los portlets deben configurarse para que hagan lo
que necesitamos, y cada uno según su funcionalidad. Por ejemplo, al
visualizador de contenido hay que decirle qué contenido debe mostrar, el
de listados lo configuraremos para que muestre exactamente lo que
queremos, filtrando por los criterios que sean necesarios, etcétera. Muy
pocos portlets funcionan directamente si no los ajustamos para que
actúen exactamente en la forma precisa.

## Contenidos web.

Poco a poco vamos desgranando elementos fundamentales para una web, y en
este caso nos centraremos en los contenidos. Los hay de dos tipos, unos
llamados “web” y otros “multimedia”. En este apartado hablaremos de los
primeros, los de tipo “web”.

Sin los demás no habría web, pero los contenidos web son la parte más
importante de una web. Los contenidos son los textos y elementos
gráficos que vemos en una web. En la inmensa mayoría de los casos,
cuando sea necesario realizar una tarea de edición en la web, esta
consistirá en crear (y en caso necesario modificar o eliminar) un
contenido. Una nueva noticia, un elemento de carrusel, un texto que irá
en una página nueva, los contenidos están por todas partes.

Los contenidos pueden ser de muchos tipos, y en función del tipo, el
formulario a rellenar será diferente. Si creamos un contenido básico,
únicamente tenemos que indicar un título y el texto (que podremos
teclear directamente en el editor WYSIWYG o en modo avanzado
directamente en HTML). Sin embargo, si por ejemplo queremos meter una
nueva noticia, además del obligatorio título anteriormente mencionado el
sistema nos pedirá introducir una imagen con su respectiva descripción,
una entradilla, la fecha y el contenido de la noticia. Esos datos
adicionales a un contenido básico son los que después nos permiten
filtrar contenidos y que la información aparezca automáticamente donde
se espera.

![](/images/image72.png)

Liferay tiene definido un funcionamiento muy interesante para el
multilingüismo. Para un sitio web pueden definirse varios idiomas. Uno
de ellos debe ser obligatoriamente definido como principal y los demás
son secundarios. Cuando añadimos un contenido obligatoriamente debe
introducirse la información en el idioma principal, y los demás son
opcionales. Esto es muy práctico cuando tenemos un sitio web con muchos
idiomas, incluso cuando no todos los contenidos están traducidos. El
efecto es muy sencillo de explicar. Si un usuario está está navegando en
una web en la que todos los contenidos están traducidos, verá todo en el
idioma en el que navega. Sin embargo, si llega a un contenido que no
tiene traducción, este se verá en el idioma establecido por defecto.

En el caso de Diputación, donde la inmensa mayoría de los sitios cuando
es habitual que sean sitios bilingües, el euskera se define como idioma
por defecto, y el castellano es secundario. Otros gestores de contenidos
tratan a todos los idiomas por igual, pero el hecho de que Liferay
soporte decenas de idiomas tiene esta pequeña contraprestación. El
editor es el responsable de introducir los contenidos en el idioma
secundario, porque el portal no se lo va a exigir. En cualquier caso,
esta forma de funcionamiento no resulta incómoda y es muy potente.

Es importante tener en cuenta que un contenido que está introducido en
dos o en más idiomas, es un único contenido.

![](/images/image82.png)

Crear un contenido bilingüe es muy sencillo. Una vez que el contenido principal ya existe
(es decir, en euskera), debemos añadir la versión en castellano,
haciendo clic el botón con la bandera y seleccionando el nuevo idioma.
Se generará una copia del contenido original, con los mismos campos,
donde el editor ya podrá introducir la traducción de todos los
elementos. Una vez terminado habrá que *Guardar* mediante el botón
correspondiente y *Publicar* (son dos pasos independientes).

![](/images/image92.png)

Durante el proceso de edición de un contenido, Liferay nos da la
posibilidad de guardar un borrador (y seguir más adelante) o publicarlo
directamente.

También proporciona un servicio de históricos (guarda las versiones
anteriores) así como una papelera de reciclaje, de forma que un
contenido que se elimina, permanece en ella durante 30 días antes de ser
borrada automáticamente.

## Contenidos multimedia.

Existe otro tipo de contenido, los denominados “documentos y
multimedia”. Este apartado viene a ser una especie de *Dropbox* donde,
ordenados por carpetas, se pueden subir documentos de todo tipo. Y tanto
es así, que hasta dispone de *app* para poder sincronizar una carpeta en
local con Liferay, bien en el móvil o en el propio ordenador. Aunque
habitualmente se usa desde la propia interfaz de Liferay, salvo que se
deba subir una gran cantidad de documentos de forma simultánea.

Cuando decimos que los documentos pueden ser de todo tipo, es así. Un
contenido web contiene principalmente código HTML, pero en este caso,
podemos subir documentos PDF, DOC, JPG, PNG, MP3, AVI, CSS, JS, o
cualquier tipo que se nos ocurra. La idea es que estén disponibles para
su uso, bien directamente o a través de un portlet que nos facilite la
navegación y descarga.

Los documentos de esta galería no son traducibles, no son como los
contenidos web. Es decir, si por ejemplo, es necesario subir unos
documentos PDF, y existe una versión en euskera, y otra en castellano,
habrá que subir los dos documentos, y además, realmente serán dos, y no
uno con dos opciones de descarga.

Otra acción habitual con los contenidos multimedia será la de subir
imágenes. Hay contenidos web que requieren imágenes, como por ejemplo
las noticias o el carrusel. Si vamos a meter una noticia, en el campo en
el que se nos pide la foto, tendremos que elegir una de entre las
disponibles en la galería. Por eso es conveniente que las imágenes se
registren antes en este apartado, para posteriormente poder
seleccionarlas al crear el contenido web.

Es importante tener clara la diferencia entre estos dos tipos de
contenido (web y multimedia) porque muchas veces trabajan de forma
complementaria y habrá que usar ambos para conseguir el objetivo de
publicar con éxito contenidos en nuestra web.

![](/images/image102.png)

## Opciones de publicación.

Cuando estamos creando un contenido hay información que es muy
específica y obligatoria y otra que es opcional. Sin embargo esta
información puede ser también muy importante, y en ocasiones también
útil.

Como ya hemos visto anteriormente, en la pantalla de edición de un
contenido web, por defecto, tenemos el título, un campo con texto con
formato, y otros adicionales en función del tipo de contenido
personalizado de que se trate. Sin embargo, dejamos aparcadas algunas
opciones muy interesantes.

Vamos a centrarnos en dos de ellas. La primera es la de “Metadatos”, que
nos permite aportar información complementaria para cada contenido en
base a una clasificación, y que aplicada en cada uno de los contenidos
puede servir para organizarlos en grupos, filtrarlos o incluso ordenarlos entre ellos.

![](/images/image112.png)

Existen dos tipos de clasificaciones, por categorías y por etiquetas,
como pueden verse en la imagen.

Las categorías son definiciones ya preestablecidas en “Vocabularios” de
entre las que se pueden seleccionar una o varias, según cómo esté
configurado. En el ejemplo, y tratándose de un contenido de tipo
“Noticia”, se selecciona la categoría Noticia dentro del vocabulario
Actualidad. Hay que tener en mente que las categorías son traducibles, y
al igual que los contenidos web, basta con elegirlas una vez.
Posteriormente los usuarios verán la descripción tal y como corresponda
en cada idioma.

La clasificación por etiquetas o tags es mucho más abierta. No partimos
de una serie de opciones de entre las que elegir, sino que el texto de
las etiquetas es totalmente libre, hasta el punto de que las etiquetas
son las que el editor escriba, tal cual, en cualquier idioma en el
idioma esté navegando el usuario de fuera.

