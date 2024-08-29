Práctica de desarrollo 1. PD01. Hola Mundo<small><br>Geomorfología
(GEO-131)<br>Universidad Autónoma de Santo Domingo (UASD)<br>Semestre
2024-02</small>
================
El Tali
2024-08-29

Versión HTML (quizá más legible),
[aquí](https://geomorfologia-master.github.io/hola-mundo/README.html)

> “Hola Mundo … sin embargo, el mundo nunca contesta. Dado que el mundo
> no contesta, mejor pongámonos manos a la obra con análisis, que sí
> responden.”

“Hola Mundo” es el programa más simple y básico que se escribe al
aprender un nuevo lenguaje de programación, utilizado para mostrar un
mensaje de texto simple en pantalla y verificar que el entorno de
desarrollo está configurado correctamente.

# Fecha/hora de entrega

**6 de septiembre de 2024, 11:59 pm.**

# Objetivos de aprendizaje

- Saludar al mundo.

- Aprender los tipos de objetos básicos en R.

- Aprender los elementos básicos de la IDE RStudio (Desktop o en mi
  servidor).

- Crear una cuenta y tóken de escritura en GitHub.

- Aceptar una asignación de GitHub Classroom.

- Configurar el ambiente en RStudio para garantizar reproducibilidad.

- Realizar tu primer análisis reproducible.

- Aprender lo básico del lenguaje de tipado Markdown.

- Crear tu primer cuaderno reproducible RMarkdown generando una salida
  en formato PDF.

- Realizar tu primer *commit*\>*push*.

# Resultados Esperados

- Comprendes los tipos de objetos básicos en R y su aplicación en un
  análisis geomorfológico.

- Manejas los elementos principales de la interfaz de RStudio para
  ejecutar código y visualizar resultados.

- Configuras tu ambiente de trabajo en RStudio para asegurar la
  reproducibilidad de tus análisis.

- Desarrollas y documentas un análisis reproducible utilizando un
  cuaderno RMarkdown y lo exportas en formato PDF.

- Aplicas la prueba de hipótesis de dos muestras pareadas, interpretando
  correctamente los resultados estadísticos obtenidos.

- Utilizas herramientas de control de versiones en GitHub para gestionar
  tu trabajo de forma eficaz.

- Generas gráficos y tablas en R que presentan los datos de manera clara
  y comprensible, integrándolos en tu análisis.

# Mandato

Realiza, en el cuaderno RMarkdown `mi-primer-manuscrito.Rmd` de tu
propio repo clonado, el ejercicio de inferencia a partir de dos muestras
apareadas de la [práctica de aula 2
(PA02)](https://github.com/geomorfologia-master/mapa-geomorfologico-rd-y-elevaciones)
usando las funciones de R al efecto, siguiendo un guión de manuscrito
científico reproducible, que incluye lo siguiente (deberás rellenar en
el archivo `mi-primer-manuscrito.Rmd` y también “tejerlo”):

> En el archivo `mi-primer-manuscrito.Rmd`, coloqué mayúsculas allí
> donde debes rellenar contenido.

- “Hola Mundo”. Un bloque de código con las distintas formas de saludar
  al mundo en R.

- Introducción. Un párrafo.

- Materiales y métodos. Un párrafo.

- Resultados. Un párrafo.

- Discusión. Un párrafo.

- Requisitos adicionales que debes cumplir:

  - ORCID insertado.

  - Al menos 3 referencias bibliográficas usando el estándar Bibtex, que
    tendrás que citar en el documento allí donde lo consideres oportuno,
    y que deberán aparecer en la lista de referencias.

  - Al menos un diagrama de caja generado por ti con código de R
    reproducible. El código fuente debe quedar oculto en el PDF de
    salida.

  - Al menos una figura de archivo (e.g. un único archivo, sólo uno, que
    muestre, aunque sea parcialmente, lo que entregaste en la
    práctica 02. si no tienes dicho archivo, puedes usar cualquier otro
    archivo alegórico al tema o a la práctica).

  - Al menos una tabla generada manualmente en Markdown. Por ejemplo,
    genera una tabla con los resultados de la prueba t de student.
    Existen herramientas en línea para hacerlo; de hecho, el propio foro
    de la asignatura también es capaz de convertir tablas desde Excel a
    Markdown, basta con copiar desde la hoja de cálculo y pegar en la
    caja de mensajes del foro.

  - Al menos una tabla estilizada generada por ti usando código de R
    reproducible, comando `knitr::kable`. El código fuente debe quedar
    oculto en el PDF de salida.

# Entregable

Tu repositorio de GitHub, subido a la organización
<https://github.com/geomorfologia-202402>, conteniendo tanto el cuaderno
RMarkdown reproducible editado por ti (`mi-primer-manuscrito.Rmd`), así
como el archivo `mi-primer-manuscrito.pdf` que generarás “tejiendo” el
referido cuaderno (más explicación en el vídeo tutorial).

# Procedimiento sugerido

Sigue los siguientes pasos recomendados:

1.  Realiza el tutorial interactivo [“Introducción a
    R”](https://geofis.shinyapps.io/tutorial1/). Este tutorial te
    introducirá al uso de los distintos tipos de objetos en R, y te
    ayudará a conocer y practicar la sintaxis básica. No evaluaré tu
    desempeño respecto de dicho tutorial, **pero te recomiendo *muy pero
    que muy pero que muy encarecidamente* que lo realices de forma
    interactiva, y que comprendas su contenido tanto como puedas**. La
    página número 3 del tutorial, “Observaciones y ‘truquitos’” es
    importante; aprende a teclear los carácteres especiales en
    programación. Si la modalidad del tutorial no te gusta, entonces
    recurre a cualquiera de estas opciones:

- Busca vídeos tutoriales que resulten más atractivos.
- Usa inteligencia artificial para que te enseñe y que, al mismo tiempo,
  te evalúe.
- Lo que te funcione mejor, así de simple.

2.  Verifica que eres miembro/a de la organización
    <https://github.com/geomorfologia-202402>. Si iniciaste sesión en
    GitHub, al entrar a la URL de la organización, debería ver que eres
    miembro/a en la sección “People”. También puedes verlo en tu perfil
    de cuenta de GitHub, haciendo clic en tu avatar (en la página de
    GitHub, derecha superior), ve a “Your organizations” y debería ver
    la organización allí. De lo contrario, si no lo eres, pide que te
    envíe una invitación.

3.  Acepta la invitación de GitHub Classroom de esta “Prácticas de
    desarrollo 1. Hola Mundo” (PD01).

4.  Confirma que se creó tu repositorio en la organización
    <https://github.com/geomorfologia-202402>.

5.  Reproduce el [vídeo tutorial “Hola Mundo …”]().

6.  Rellena las partes correspondientes en `mi-primer-manuscrito.Rmd`,
    siguiendo el mandato y el vídeo tutorial.

7.  Teje para generar tu `mi-primer-manuscrito.pdf`. Hazlo
    periódicamente, no lo dejes para al final.

8.  Identifícate para git (`git config ...`).

9.  Haz *commit*\>*push*.

10. Confirma que tus cambios se subieron a tu repositorio en GitHub.

# Software, hardware y servicios (imprescindibles para esta práctica)

- Navegador (desactiva el traductor para la página del servidor
  RStudio).

- PC.

- Cuenta en mi servidor RStudio (esta ya te la creé yo).

- Cuenta en GitHub.

- Tóken de escritura en GitHub (explicado en el tutorial).

- Cuenta en OpenAI/ChatGPT, u otros servicios de IA, como Gemini,
  Claude, etc.

- Código ORCID.

# Software y servicios recomendados para el futuro

> No los necesitarás para desarrollar esta práctica, pero sí para las
> venideras.

- QGIS Desktop (software).

- GRASS GIS Desktop.

- Cuenta en Google Earth Engine.

# Software y servicios útiles, todos OPCIONALES

## Software en tu propia PC

> Todas estas aplicaciones están disponibles por medio de interfaz de
> línea de comandos (CLI, “consola”, “terminal”) en mi servidor. Sólo
> instala estas aplicaciones si quieres aprender más o tener
> independencia en tu propia PC.

- R+RStudio Desktop. Si quieres ejecutar código de R en tu PC.

- Python3 \| Anaconda \| Jupyter Hub \| Jupyter Notebook \| JupyterLab
  \| Spyder \| VS Code. Si quieres ejecutar código de Python en tu PC.

- Git.

- LaTeX en tu PC. Procesador de texto, pensado sobre todo para artículos
  científicos.

- Docker, para manejar o crear software contenerizado.

- Zotero Desktop.

## Cuentas en los siguientes servicios

- Docker.

- Overleaf.

- Zotero Online.

## Enlaces útiles

- [Tutorial interactivo “Introducción a
  R”](https://geofis.shinyapps.io/tutorial1/)

![](qr-tutorial1.jpg)

- [Vídeo tutorial de esta práctica (PD01)]().

![](qr-video-tutorial.jpg)

- [Invitación de GitHub Classroom de esta
  práctica](https://classroom.github.com/a/8b5Nk4vy).

![](qr-invitacion-gh-classroom.jpg)
