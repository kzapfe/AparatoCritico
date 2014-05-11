![Emblema de git](http://upload.wikimedia.org/wikipedia/commons/e/e0/Git-logo.svg "git logo")

La Red nos permite hacer trabajos colectivos de forma más eficiente que 
el correo en papel, al menos en principio, pero herramientas que realmente 
exploten esta capacidad de forma intrínseca no se conocen mucho fuera del 
medio de los programadores, e incluso dentro de este grupo sólo son 
primordialmente usadas por aquellos que hacen proyectos de Código Libre. 
Creo que estas herramientas podrían ser de gran utilidad para otra gente 
que trabaja usualmente con texto, como ( _cof cof_) escritores de una revista 
virtual o física. Me propongo mostrar un poco de las virtudes de estos 
sistemas, con énfasis en el aspecto creativo.

El primero es un sistema de almacenaje de archivos con control de versiones, 
es lo que se conoce en el medio como un _repositorio_. 
El programa de fondo es `git`, que es quién se encarga de cuidar las múltiples 
versiones que pueden derivarse de una colección de archivos de texto, primordialmente. `git` existe como tal a partir de 2005, 
y es creación de Linus Torvalds 
(sí, [ese Linus](http://en.wikipedia.org/wiki/Linus_Torvalds)) 
y la idea era producir un sistema de versión de control que fuera rapidísimo, 
fuerte contra la corrupción de los archivos y _abierto_. 
El nombre git es una referencia en slang británico a una persona molesta desagradable, así que Linus bromea que el nombre, como el kernel `linux`,
hace referencia a sí mismo. `git` permite hacer algo que resulta  
muy difícil de lograr con otros sistemas de control de versiones: 
la creación de múltiples ramas de un trabajo. 
De esta forma uno o varios grupos de autores puede trabajar en versiones 
derivadas de un proyecto y explorar múltiples lineas creativas
 o de resolución de problemas, y volverlas a unir, 
o permitir que se sigan separando. 
Para que esto sea realmente interesante es necesario 
sincronizar el trabajo con un repositorio en linea. 
En este momento existen varios proyectos de repositorios 
públicos en la red, algunos de ellos exitosos proyectos comerciales, 
notoriamente [GitHub](https://www.github.com).

`git` fue desarrollado para su uso en archivos de texto crudo;
 la forma más flexible de compartir información hasta ahora. 
Muchos de los formatos que usamos ahora para generar contenido son 
realmente variaciones de texto crudo con sintaxis especiales que denotan
 instrucciones específicas, como las imágenes `svg`, las páginas `html`, 
`psp`, etc.   Esto plantea entonces la necesidad de poder escribir 
documentos con propósitos más generales que sean a su vez también texto crudo. 
Algo que no necesariamente sea un programa o instrucciones de compu, 
sino por ejemplo, un simple borrador de un proyecto de trabajo social, 
o una pieza de literatura más o menos estructurada...

Ahí es donde aparece [Markdown](http://daringfireball.net/projects/markdown/). 
Markdown es una sintáxis de texto plano que permite la creación de
 texto enriquecido, de hecho, es reínterpretado por las herramientas del 
mismo nombre como `html`. Markdown permite la escritura veloz y cómoda 
de textos con diferentes encabezados diferenciados, _marcas_ de 
**énfasis** y `diferencias` de contenido. 
Es impresionante mente fácil de aprender, 
y uno sacrifica complejidad por ello. 
Algo bonito de Markdown es que uno puede leer el archivo original 
sin percibir de forma obvia las marcas de formato,
 lo cual lo hace mucho más legible que por ejemplo, `html` crudo.

Me gustaría plantear a mis lectores una pregunta. 
Estas herramientas cumplen su función con la creación de 
objetos altamente estructurados, colaborativos y de desarrollo 
primordialmente horizontal, tales como los programas de código abierto, 
notoriamente GNU/Linux, Android y Google-OS y toda su paquetería. 
Últimamente también lo usamos para desarrollar computo científico, 
y lo estamos promoviendo en la comunidad, por su función como 
herramientas que promueven la _reproducibilidad y transparencia_ 
de los resultados. ¿Creen ustedes, mis caros lectores, 
que el uso de estas herramientas también podrían ser usadas 
por comunidades más amplias (e.g, artistas), o resultan demasiado específicas?

**Nota**: este texto fue hecho usando Markdown para todo excepto para la linea
de _"leer más"_. 
El archivo original se puede consultar [aquí](https://www.github.com/kzapfe/AparatoCritico).
