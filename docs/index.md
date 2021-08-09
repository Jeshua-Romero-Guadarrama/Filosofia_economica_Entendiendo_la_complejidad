---
title: "Filosofía económica: Entendiendo la complejidad"
cover-image: "images/cover.jpg"
author: "Jeshua Romero Guadarrama"
date: "2021-08-09"
site: bookdown::bookdown_site
output: 
  bookdown::word_document2: default
  bookdown::pdf_book:
    pandoc_args: ["+RTS", "-K64m", "-RTS", "--csl", "apa-old-doi-prefix.csl"]
    includes:
      in_header: preamble.tex
    citation_package: natbib
    keep_tex: yes
  bookdown::gitbook:
    config:
      toc:
        collapse: subsection
        scroll_highlight: yes
      fontsettings:
        theme: white
        family: serif
        size: 2
    split_by: section+number
    highlight: tango
    includes:
      in_header: [header_include.html]
always_allow_html: yes
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
biblatexoptions:
  - sortcites
link-citations: yes
github-repo: "https://github.com/Jeshua-Romero-Guadarrama/Filosofia_economica_Entendiendo_la_complejidad"
description: "Filosofía económica: Entendiendo la complejidad"
url: 'https://jeshua-romero-guadarrama.github.io/Filosofia_economica_Entendiendo_la_complejidad/'
tags: [Academia, Economía aplicada, Economía, Filosofías económicas, Complejidad económica]
favicon: "images/logo.png"
---

# Prefacio {-}














<center><img style = 'width:60%;' src='images/Filosofia_economica_entendiendo_la_complejidad.png'></center>



<center><img style = 'width:30%;' src='images/cover.jpg'></center>
<br><center><img style='float: center; width:50%' src='images/logo_claim_en_rgb.png'/></center>
<br><center><a href="https://www.jeshuanomics.com/" target="blank">Publicado por Jeshua Romero Guadarrama en colaboración con JeshuaNomics:</a></center>
<br><center><a href="https://github.com/JeshuaNomics" class="fa fa-github"><span class="label">  Git Hub</span></a>
<a href="https://www.facebook.com/JeshuaNomics/" class="fa fa-facebook"><span class="label">  Facebook</span></a>
<a href="https://twitter.com/JeshuaNomics" class="fa fa-twitter"><span class="label">  Twitter</span></a>
<a href="https://www.linkedin.com/in/jeshua-romero-guadarrama/" class="fa fa-linkedin"><span class="label">  Linkedin</span></a>
<a href="https://vk.com/jeshuanomics" class="fa fa-vk"><span class="label">  Vkontakte</span></a>
<a href="https://jeshuanomics.tumblr.com/" class="fa fa-tumblr"><span class="label">  Tumblr</span></a>
<a href="https://www.youtube.com/channel/UCY7f84mJGvMN7TF7XI4-Jgg?view_as=subscriber/" class="fa fa-youtube-play"><span class="label">  YouTube</span></a>
<a href="https://www.instagram.com/JeshuaNomics/" class="fa fa-instagram"><span class="label">  Instagram</span></a></center>

<br> Jeshua Romero Guadarrama es economista y actuario por la <a href="http://www.economia.unam.mx/">Universidad Nacional Autónoma de México</a>, quien ha construido el presente proyecto en colaboración con <a href="https://www.jeshuanomics.com">JeshuaNomics</a>, ubicado en la Ciudad de México, se puede contactar mediante el siguiente correo electrónico: jeshuanomics@gmail.com.
<br>
<br> Última actualización el lunes 09 del 08 de 2021
<br>



El presente texto nace al calor de las exigencias pedagógicas de entender los Fundamentos de la FIlosofía Económica, así como los Fundamentos y aplicaciones de la economía de la complejidad

#### Reconocimiento {-}

A mi alma máter: Universidad Nacional Autónoma de México (Facultad de Economía y Facultad de Ciencias). Por brindarme valiosas oportunidades que coadyuvaron a mi formación.



El libro muestra el fundamento ideológico del trabajo del economista, y las perspectivas ideológicas son las que han prevalecido en gran medida en los últimos dos siglos: liberalismo, nacionalismo y socialismo. Sobre la base y la fuerza de estas ideologías se han construido los sistemas de economía política. Roselli explora las conexiones entre teoría y juicios de valor para identificar las premisas filosóficas detrás del razonamiento económico de economistas tan diversos como Smith, Ricardo, Marx, Pareto, Keynes, Hayek, entre otros.

El liberalismo se inclinó originalmente hacia un laissez-faire sin trabas, luego hacia un papel más amplio del Estado en el sistema económico, bajo la influencia de la ideología socialista, luego nuevamente se ha apoyado en un enfoque individualista de las cuestiones de producción y distribución de riqueza; Más recientemente, la irrealidad de este enfoque ha sido revelada por las crisis sistémicas, lo que sugiere nuevas reflexiones e incertidumbres sobre la coherencia del razonamiento económico con la idea liberal: una perspectiva institucional e histórica puede abrir nuevos espacios para la comprensión de una economía liberal y capitalista. 

Se examinan las vicisitudes del nacionalismo económico, sus rasgos estatistas y proteccionistas, su declive y resurgimiento reciente, no quedando claro qué forma está tomando actualmente desde el punto de vista económico y político. Esto es particularmente oscuro en el caso de esa forma específica de nacionalismo llamada populismo. 

El declive y la caída del materialismo histórico de Marx no pueden ocultar el contraste inherente de intereses entre los dos lados de un contrato laboral. El legado duradero del socialismo es la relevancia duradera y multiforme, desde una fuerza laboral acobardada hasta cuestiones ambientales, de los temas sociales en las economías modernas.

Este libro presenta un estudio de los aspectos de la complejidad económica, con un enfoque en ideas fundamentales e interdisciplinarias. El tan esperado seguimiento de su volumen de 2011  Complex Evolutionary Dynamics in Urban-Regional and Ecologic-Economic Systems: From Catastrophe to Chaos and Beyond , este volumen reúne los hilos del trabajo anterior de Rosser sobre la teoría de la complejidad y sus amplias aplicaciones en economía y economía. una lista ampliada de disciplinas relacionadas. 

El libro comienza con una descripción completa de las categorías más amplias de complejidad en economía (dinámica, computacional, jerárquica y estructural) antes de pasar a un análisis más detallado. Los dos capítulos siguientes abordan problemas asociados con la complejidad computacional, especialmente los de computabilidad, y discuten el Teorema de incompletitud de Godel con un enfoque en la reflexividad. Los capítulos intermedios discuten la relación entre la entropía, la econofísica, la evolución y la complejidad económica, respectivamente, con aplicaciones en la dinámica urbana y regional, la economía ecológica, la teoría del equilibrio general y la dinámica del mercado financiero. El capítulo final trabaja para reunir estos temas en un marco más amplio y exponer algunos de los límites relacionados con el análisis de cuestiones fundamentales más profundas.

Con aplicaciones en todas las disciplinas caracterizadas por sistemas adaptativos no lineales interconectados, este libro es apropiado para estudiantes graduados, profesores y profesionales de la economía y disciplinas relacionadas como ciencias regionales, matemáticas, física, biología, ciencias ambientales, filosofía y psicología.

Palabras clave:

- Filosofía económica
- Liberalismo clásico
- Nacionalismo económico
- Socialismo marxista
- Filosofía social
- Economía heterodoxa
- Filosofia politica
- Teoría económica clásica
- Iluminación
- Economía política
- Historicismo económico alemán
- Liberalismo económico
- El liberalismo de Keynes
- Corporativismo
- Historia de las ideas
- Complejidad económica 
- Teoría económica 
- Teorema de incompletitud de Gödel
- Reflexividad
- Dinámica del mercado
- Teoría del equilibrio
- Complejidad computacional
- Econofísica

# Contenido {-}

Parte I Teoría elemental de números

Capítulos:

- Congruencias

## Índice de contenido {-}

Capítulo 1. Congruencias

- Introducción a las congruencias

- Sistemas de residuos y función $\phi$ de Euler

- Congruencias lineales

- El teorema del resto chino

- Teoremas de Fermat, Euler y Wilson