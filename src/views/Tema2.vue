<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 2
      h1 OptiTex

    .row.mb-5
      .col-lg-7.d-flex(data-aos="fade-right")
        .cajon.color-acento-botones.fondo-c.p-5.d-flex.align-items-center
          div 
            p.mb-5 OptiTex es un sistema CAD/CAM (Diseño Asistido por Computador y Manufacturas Asistidas por Computador) 2D y 3D, el cual mejora la rentabilidad en las empresas permitiendo un ahorro de tiempo y minimización del desperdicio de la materia prima, en la elaboración de sus productos. Este software es el más utilizado en Colombia actualmente por las empresas manufactureras.
            p En esta unidad temática el enfoque se realiza en patrones únicamente de la línea femenina, sin embargo, cabe resaltar que las herramientas del programa y manejo de interfaz, aplica para cualquier línea y debe tener en cuenta el desarrollo del trabajo manual para aplicarlo de manera digital.
      .col-lg-5(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema2/img01.svg' alt="Imagen decorativa")

    p.mb-5(data-aos="fade-right") OptiTex ofrece un paquete completo para suplir este tipo de necesidades, estos softwares son:
    
    .row.mb-5
      .col-lg-4.d-flex(data-aos="fade-right")
        div.borde-1.d-flex.flex-column     
          div.p-4.fondo-rojo-claro-1
            h3.m-0.text-center PDS
          div.p-5.d-flex.align-items-center(style="height:100%")
            p.text-center Sistema de diseño de patrones, también se pueden anexar por la mesa digitalizadora. 
      .col-lg-4.d-flex(data-aos="fade-up")
        div.borde-1.d-flex.flex-column          
          div.p-4.fondo-rojo-claro-1
            h3.m-0.text-center Marker
          div.p-5.d-flex.align-items-center(style="height:100%")
            p.text-center Es el acomodo de piezas para el corte industrial, se puede realizar de forma manual o automática. Reportes del trazo.
      .col-lg-4.d-flex(data-aos="fade-left")
        div.borde-1.d-flex.flex-column           
          div.p-4.fondo-rojo-claro-1
            h3.m-0.text-center RunwayViewer
          div.p-5.d-flex.align-items-center(style="height:100%")
            p.text-center Es un sistema de simulación de prendas en un avatar, que puede ser personalizado según la tabla de medidas, se basa en las características de los patrones realizados en PDS y en las características precisas de las telas reales.

    p.mb-5(data-aos="fade-right") A continuación, se describirán las características generales del software enfocado en el desarrollo de patrones y escalado de prendas de vestir. 

    h3.mb-5(data-aos="fade-right") Características del software OptiTex
    p.mb-5(data-aos="fade-right") Optitex permite construir de manera dinámica patrones con alta precisión, para ello, emplea una ubicación espacial basados en el plano cartesiano y ángulos que permiten ser muy exactos en el momento de generar cualquier tipo de patrón, partiendo de figuras geométricas o líneas dibujadas. Cabe resaltar que el escalado se realiza en este software también.
    p.mb-5(data-aos="fade-right") Su interfaz es muy intuitiva, generando que el mismo programa le indique el paso a seguir en cada herramienta que se vaya a implementar, escala y modifica patrones ya creados.

    .row.fondo-gris-1.py-5.mb-5
      .col-lg-1
      .col-lg-10.py-3(data-aos="fade-left")
        figure.mb-4
          .titulo-sexto.color-acento-contenido(data-aos='fade-right')
            h5 Figura 15.
            span Interfaz general de OptiTex PDS
          img(src='@/assets/curso/tema2/img02.png' alt="Imagen decorativa")
          figcaption Fuente: SENA 2021
      .col-lg-1
    
    p.mb-5 <b>Dentro de las características generales de PDS se encuentran:</b>

    .row.mb-5
      .col-lg-1
      .col-lg-10
        ol.lista-ol--cuadro.lista-ol--separador
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span a
            p.mb-0(data-aos="fade-left") Se pueden copiar moldes o patrones de un archivo a otro sin necesidad de generar un nuevo archivo.
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span b
            p.mb-0(data-aos="fade-left") Cuenta con funciones de guardado en versiones anteriores y se pueden abrir sin ningún inconveniente.
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span c
            p.mb-0(data-aos="fade-left") Contiene herramientas que propician la construcción de patrones desde cero, transformación, marcaciones, mediciones, escalado y posee características que permite el complemento con los demás paquetes de software.
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span d
            p.mb-0(data-aos="fade-left") Importación y exportación de diferentes extensiones de patrones realizados en otros softwares de trazo de aplicaciones CAD/CAM.
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span e
            p.mb-0(data-aos="fade-left") Interfaz intuitiva y muy fácil de manejar.
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span f
            p.mb-0(data-aos="fade-left") Se pueden imprimir moldes o patrones directamente a una impresa a la escala que se desee. 
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span g
            p.mb-0(data-aos="fade-left") No hay límite de espacio, es demasiado amplio para poder integrar en un mismo archivo muchos patrones. 
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span h
            p.mb-0(data-aos="fade-left") Cantidad   de   características: ojales, pinzas, pliegues, costuras, manejo de curvas complicadas, esquinas, cortes, técnicas avanzadas de medición, botones y piquetes.
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span i
            p.mb-0(data-aos="fade-left") Permite la marcación de cada uno de los nombres de los patrones, descripciones o acotaciones especiales que se necesiten para el ploteo de los moldes.
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span j
            p.mb-0(data-aos="fade-left") Cuenta con herramientas de texto.
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span k
            p.mb-0(data-aos="fade-left") El programa que complementa a OptiTex PDS es Marker, en donde una vez se realice el trazado de los moldes en un espacio que está determinado a partir de anchos de tela y largos de tendido para producción, es posible pasar a hacer el plano que guie el tendido y corte de la producción a confeccionar.
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span l
            p.mb-0(data-aos="fade-left") Facilidad de creación de reportes.
          li
            .lista-ol--cuadro__vineta.color-acento-botones-1(data-aos="fade-right")
              span m
            p.mb-0(data-aos="fade-left") Reporte de información de piezas a Excel para integración con cualquier generador de reportes a su gusto.

    p.mb-5(data-aos="fade-right") En complemento con lo anterior, dentro de las características generales de Marker encontramos:
    
    .row.mb-5
      .col-lg-1
      .col-lg-10
        ol.lista-ol.lista-ol--separador
          li(data-aos="fade-right")
            span.text-bold 1. 
            | Mayor precisión al trabajar en telas de rayas y cuadros, para diferentes repites ya sean regulares o diagonales.
          li(data-aos="fade-right")
            span.text-bold 2. 
            | Detección automática de moldes con intersección.
          li(data-aos="fade-right")
            span.text-bold 3. 
            | Permite importar la tela o escanearla.          
          li(data-aos="fade-right")
            span.text-bold 4. 
            | Capacidad de cambiar cualquier parámetro.
          li(data-aos="fade-right")
            span.text-bold 5. 
            | Opciones y herramientas que permiten lograr un mejor rendimiento en la eficiencia del trazo.
          li(data-aos="fade-right")
            span.text-bold 6. 
            | Cambio de cantidades, cambio de dimensiones de trazo, número de capas, y todos los demás parámetros del sistema en cualquier momento.
          li(data-aos="fade-right")
            span.text-bold 7. 
            | Permite realizar un cálculo óptimo de capas y sobrantes de materia prima.
          li(data-aos="fade-right")
            span.text-bold 8. 
            | Manejo de paquetes completos en el trazo.    
      .col-lg-1

    .row.fondo-gris-1.py-5.mb-5
      .col-lg-1
      .col-lg-10.py-3(data-aos="fade-left")
        figure.mb-4
          .titulo-sexto.color-acento-contenido(data-aos='fade-right')
            h5 Figura 16.
            span Interfaz Marker
          img(src='@/assets/curso/tema2/img03.png' alt="Imagen decorativa")
          figcaption Fuente: SENA 2021
      .col-lg-1

    .row.mb-4
      .col-lg-2
      .col-lg-8(data-aos="fade-right")
        a.anexo(href="https://www.youtube.com/watch?v=fscxWYsenLE" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
          .anexo__texto
            p <b>Trazado de patrones MARKER.</b> A continuación, le invitamos a visualizar el video de “Herramientas digitales moda”, en donde se explica y profundiza la funcionalidad de Marker.
      .col-lg-2

    Separador

    #t_2_1.titulo-segundo.color-acento-contenido
      h2 2.1  Funciones básicas de PDS

    p.mb-4(data-aos="fade-right") El programa cuenta con una serie de pestañas integradas de manera secuencial, sin embargo, las vistas se pueden configurar y ajustar según lo considere el patronista.
    p.mb-5(data-aos="fade-right") Para el manejo e implementación del software de patronaje, es necesario tener conocimientos de patronaje y escalado, asociados a la elaboración de básicos.
    
    .row.fondo-a.py-5.mb-5
      .col-lg-1
      .col-lg-10.py-3(data-aos="fade-left")
        ImagenInfografica.color-secundario.mb-5
          template(v-slot:imagen)
            figure
              .titulo-sexto.color-acento-contenido(data-aos='fade-right')
                h5 Figura 17.
                span Divisiones en la interfaz PDS
              img(src='@/assets/curso/tema2/img04.png' alt="Imagen decorativa")
              figcaption Fuente: SENA 2021

          .tarjeta.tarjeta--gris.p-3(x="13%" y="16%")
            .h5 1. Barra de título

          .tarjeta.tarjeta--gris.p-3(x="40%" y="18%")
            .h5 2. Barra de menú

          .tarjeta.tarjeta--gris.p-3(x="75%" y="23%")
            .h5 3. Barra de herramientas

          .tarjeta.tarjeta--gris.p-3(x="27%" y="33%")
            .h5 4. Ventana de piezas

          .tarjeta.tarjeta--gris.p-3(x="10%" y="70%")
            .h5 5. Ventana de herramientas

          .tarjeta.tarjeta--gris.p-3(x="75%" y="65%")
            .h5 6. Área de trabajo

        
            

           

      .col-lg-1

    p.mb-5(data-aos="fade-right") A continuación, vamos a conocer la configuración y utilización de las herramientas básicas antes de iniciar con la elaboración de patrones digital y escalado.
    
    AcordionA.mb-4(tipo="a" clase-tarjeta="tarjeta tarjeta--gris" data-aos="fade-left")
      .row(titulo="A. Activación de herramientas")
        .col-lg-2               
        .col-md-9
          p.mb-5 En la barra de menú ver, seleccionar la opción “Caja de herramientas” y activar la ventana de herramientas del lado izquierdo de nuestra pantalla.
          figure.mb-5
            .titulo-sexto.color-acento-contenido(data-aos='fade-right')
              h5 Figura 18.
              span Caja de herramientas
            img(src='@/assets/curso/tema2/img05.png' alt="Imagen decorativa")
            figcaption Fuente: SENA 2021

          p.mb-5 Otra manera de visualizar las herramientas es situar el cursor debajo de la barra de menú y con clic derecho observar las que están disponibles. De igual manera, se pueden activar las herramientas que se necesitan y dejar inactivas las que no se estén utilizando en el momento.

          figure.mb-5
            .titulo-sexto.color-acento-contenido(data-aos='fade-right')
              h5 Figura 19.
              span Activación de herramientas
            img(src='@/assets/curso/tema2/img06.png' alt="Imagen decorativa")
            figcaption Fuente: SENA 2021
        .col-lg-1 
      .row(titulo="B. Configurar área de trabajo")
        .col-lg-2               
        .col-md-9
          p.mb-5 Podrá elegir la unidad de medida y los colores de las piezas y del área de trabajo: seleccionar la opción “Preferencias”.
          figure.mb-5
            .titulo-sexto.color-acento-contenido(data-aos='fade-right')
              h5 Figura 20.
              span Preferencias
            img(src='@/assets/curso/tema2/img07.png' alt="Imagen decorativa")
            figcaption Fuente: SENA 2021
          figure.mb-5
            .titulo-sexto.color-acento-contenido(data-aos='fade-right')
              h5 Figura 21.
              span Unidades de trabajo
            img(src='@/assets/curso/tema2/img08.png' alt="Imagen decorativa")
            figcaption Fuente: SENA 2021
          .row
            .col-lg-7
              figure.mb-5
                .titulo-sexto.color-acento-contenido(data-aos='fade-right')
                  h5 Figura 22.
                  span Configuración de colores
                img(src='@/assets/curso/tema2/img09.png' alt="Imagen decorativa")
                figcaption Fuente: SENA 2021
            .col-lg-5.py-5
              p.mb-4 En esa ventana se puede configurar para:
              ol.lista-ol
                li 
                  span.text-bold 1. 
                  | Colorear.
                li 
                  span.text-bold 2. 
                  | Activar o desactivar relleno de la pieza.
                li 
                  span.text-bold 3. 
                  | Activar ventanas de diálogo de las herramientas.
                li 
                  span.text-bold 4. 
                  | Unidades de trabajo (unidades de medida).
                li 
                  span.text-bold 5. 
                  | Atributos de herramientas.
      .row(titulo="C. Activación de herramientas en la barra menú ver")
        .col-lg-2               
        .col-md-9
          p.mb-4 Es importante saber cómo activar las ventanas con las que más se trabajan en la construcción de patrones y del escalado. Se pueden activar en la barra menú ver y las más importantes son las siguientes:
          
          ol.lista-ol.mb-5
                li 
                  span.text-bold 1. 
                  | Tabla de escalado.
                li 
                  span.text-bold 2. 
                  | Ventana de pieza.
                li 
                  span.text-bold 3. 
                  | Ventana 3D.
                li 
                  span.text-bold 4. 
                  | Reglas.
                li 
                  span.text-bold 5. 
                  |  Otras Ventanas (calculadora). 
                li 
                  span.text-bold 6. 
                  | Habilitar colores por comandos.
                li 
                  span.text-bold 7. 
                  | Mostar líneas guías.

          figure
            .titulo-sexto.color-acento-contenido(data-aos='fade-right')
              h5 Figura 23.
              span Divisiones en la interfaz PDS
            img(src='@/assets/curso/tema2/img10.png' alt="Imagen decorativa")
            figcaption Fuente: SENA 2021            
              
      .row(titulo="D. Menú principal")
        .col-lg-2               
        .col-md-9
          p.mb-5 Estos menús contienen las opciones para dibujar, editar, cambiar, grabar, plotear y modificar los patrones. En cada opción se despliegan diferentes herramientas, las más utilizadas se encuentran también como iconos en las hileras siguientes a esta. Podrá observar, dentro de cada menú los comandos rápidos que son una combinación de teclas que te llevan a activar de manera más rápida.
          figure.mb-5
            .titulo-sexto.color-acento-contenido(data-aos='fade-right')
              h5 Figura 24.
              span Menú principal
            img(src='@/assets/curso/tema2/img11.png' alt="Imagen decorativa")
            figcaption Fuente: SENA 2021
      .row(titulo="E. Menú de herramientas gráficas")
        .col-lg-2               
        .col-md-9          
          p.mb-4 Contiene las herramientas básicas para interactuar entre los archivos y acciones simples. Estos son sus nombres y especificaciones según el orden de la figura 25. 

          p.mb-4 <b>Herramientas de selección:</b> permite elegir una o varias piezas en el área de trabajo.

          p.mb-4 <b>Nuevo:</b> permite abrir nueva hoja.

          p.mb-4 <b>Abrir:</b> se utiliza para abrir el archivo de un molde ya existente.

          p.mb-4 <b>Guardar:</b> sirve para almacenar los cambios y guardar el trabajo realizado.

          p.mb-4 <b>Imprimir:</b> permite establecer una escala más pequeña, puede ser en hoja tamaño A4 o Legal para acceder a los moldes impresos.

          p.mb-4 <b>Plotear:</b> imprime moldes a escala real.

          p.mb-4 <b>Organizar para plotear área de trabajo:</b> se utiliza para acomodar los moldes en el área de trabajo y ser impresos desde allí.

          p.mb-4 <b>Reporte a Excel:</b> se puede crear con la información de las piezas, cantidad por molde, especificaciones en la marcación para acceder a los archivos fuera del software fuente.

          p.mb-4 <b>Digitalizar:</b> permite pasar un patrón físico (en papel) a una versión computarizada o digital.

          p.mb-4 <b>Acercar, deshacer, rehacer, cortar, copiar, pegar:</b> herramientas que facilitan el trabajo con el software.

          p.mb-4 <b>Reemplazar original:</b> se interactúa con las piezas en el área de trabajo y en la ventana de piezas transfiriendo elementos de un archivo a otro.

          p.mb-5 <b>Ayuda en línea:</b> permite recibir asistencia del área de soporte del proveedor del software.
      
          figure.mb-4
            .titulo-sexto.color-acento-contenido(data-aos='fade-right')
              h5 Figura 25.
              span Herramientas generales
            img(src='@/assets/curso/tema2/img12.png' alt="Imagen decorativa")
            figcaption Fuente: SENA 2021
      .row(titulo="F. Ventana de piezas")
        .col-lg-2               
        .col-md-9
          p.mb-5 Está arriba del área de trabajo. En esta ventana aparecen todos los patrones que han sido creados en el archivo.
          figure.mb-5
            .titulo-sexto.color-acento-contenido(data-aos='fade-right')
              h5 Figura 26.
              span Ventana piezas
            img(src='@/assets/curso/tema2/img13.png' alt="Imagen decorativa")
            figcaption Fuente: SENA 2021

    Separador 

    #t_2_2.titulo-segundo.color-acento-contenido
      h2 2.2  Patronaje en OptiTex de prendas inferiores y superiores

    p.mb-5(data-aos="fade-right") Para patronar en el software OptiTex, lo más común es partir de un rectángulo, conformado con la medida más ancha y la medida más larga por utilizar. Por ejemplo, en una falda utilizamos para el ancho del rectángulo el contorno más grande que sería la cadera y para el alto, ubicamos el largo de la falda. Esta acción se realiza con los siguientes pasos: Menú barra Pieza / Nueva Pieza / Crear rectángulo.
    
    .row.fondo-a.py-5.mb-5
      .col-lg-1
      .col-lg-10.py-3(data-aos="fade-left")
        figure.mb-4
          .titulo-sexto.color-acento-contenido(data-aos='fade-right')
            h5 Figura 27.
            span Creación de rectángulo
          img(src='@/assets/curso/tema2/img14.png' alt="Imagen decorativa")
          figcaption Fuente: SENA 2021
      .col-lg-1

    p.mb-5(data-aos="fade-right") Para observar cómo funciona el programa en práctica, se recomienda ver los siguientes videos sobre creación de prendas en el software de PDS:
    
    .row.mb-4
      .col-lg-2
      .col-lg-8
        .row.mb-4(data-aos="fade-right")
          .col-lg-1
          .col-lg-5
            p.mb-4 <b>1. Trazo de la falda</b>
            a.mb-4.anexo(href="https://www.youtube.com/watch?v=WV4cu53pWxI" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
              .anexo__texto
                p <b>Enlace web.</b> Trazo de la falda
          .col-lg-5
            p.mb-4 <b>2. Trazo de la base superior femenina</b>
            a.mb-4.anexo(href="https://www.youtube.com/watch?v=p5r2Sm5N7nw" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
              .anexo__texto
                p <b>Enlace web.</b> Trazo de la base superior femenina            
          .col-lg-1
        .row.mb-4(data-aos="fade-left")
          .col-lg-1
          .col-lg-5
            p.mb-4 <b>3. Traslados de pinza</b>
            a.mb-4.anexo(href="https://www.youtube.com/watch?v=gUEDWvGuc2k" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
              .anexo__texto
                p <b>Enlace web.</b> Traslados de pinza
          .col-lg-5
            p.mb-4 <b>4. Cortes base superior femenina</b>
            a.mb-4.anexo(href="https://www.youtube.com/watch?v=ii4H63hkOZQ" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
              .anexo__texto
                p <b>Enlace web.</b> Cortes base superior femenina            
          .col-lg-1
        .row.mb-4(data-aos="fade-right")
          .col-lg-1
          .col-lg-5
            p.mb-4 <b>5. Blusa hasta la cadera delantero</b>
            a.mb-4.anexo(href="https://www.youtube.com/watch?v=TYk4x8LnIXU" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
              .anexo__texto
                p <b>Enlace web.</b> Blusa hasta la cadera delantero
          .col-lg-5
            p.mb-4 <b>6. Blusa hasta la cadera espalda</b>
            a.mb-4.anexo(href="https://www.youtube.com/watch?v=8-oyqpzDseo" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
              .anexo__texto
                p <b>Enlace web.</b> Blusa hasta la cadera espalda            
          .col-lg-1
        .row.mb-4(data-aos="fade-left")
          .col-lg-1
          .col-lg-5
            p.mb-4 <b>7. Cortes princesa y francés</b>
            a.mb-4.anexo(href="https://www.youtube.com/watch?v=RMw9IStPYzA" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
              .anexo__texto
                p <b>Enlace web.</b> Cortes princesa y francés
          .col-lg-5
            p.mb-4 <b>8. Modelos de faldas</b>
            a.mb-4.anexo(href="https://www.youtube.com/watch?v=DwDBOSykx2o" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
              .anexo__texto
                p <b>Enlace web.</b> Modelos de faldas
          .col-lg-1

    Separador 

    #t_2_3.titulo-segundo.color-acento-contenido
      h2 2.3 Escalado de patrones en Marker OptiTex

    .row.fondo-d.mb-5
      .col-lg-5.p-5(data-aos="fade-right")
        figure.mb-4
          .titulo-sexto.color-acento-contenido(data-aos='fade-right')
            h5 Figura 28.
            span Escalado
          img(src='@/assets/curso/tema2/img15.png' alt="Imagen decorativa")
          figcaption Fuente: SENA 2021
      .col-lg-7.d-flex.p-5(data-aos="fade-left")
        div.fondo-blanco.d-flex.align-items-center.p-5
          div
            p.mb-5 El escalado en Marker también se trabaja con plano cartesiano en coordenadas X, Y; en este caso se encuentra con una variación que se presenta como dy, dx. Y si el movimiento es para -X o -Y se debe escribir el número con el signo menos (-) adelante. 
            p A nivel general, el escalado digital o a través de un software de patronaje, se trabaja de la misma manera o con el mismo análisis que se hace de forma manual; en esta ocasión, únicamente se va a trabajar la programación, interfaz y herramientas del programa para hacer cualquier tipo de escalado, se tomará como referente únicamente la base de falda, sin embargo, estos mismos pasos y esta configuración se debe realizar para cualquier tipo de base, prenda, trazo, molde o interpretación.
    
    p.mb-5 <b>Preparación para iniciar el escalado:</b> Partimos de un patrón elaborado con aumentos de costura.
    
    PasosA.color-acento-contenido.mb-5(tipo="n" data-aos="fade-left")
      div        
        p Revisar que los puntos que escalan tengan atributos de escaldo y los puntos que no deben escalar (según la prenda) se les debe quitar el atributo de escalado.
      div
        p(style="text-align: left !important;") Crear el cuadro de tallas en que queremos escalar el diseño trazado. Para ello, vamos a la barra menú, Escalado, activamos Tabla de Tallas o comando <b>Shif+F4</b>. En esta ventana utilizamos el botón Insertar, para crear tallas menores a la talla básica y el botón Agregar, para crear tallas mayores a la talla base. En nuestro caso crearemos el cuadro de tallas de la 6 a la 18 para patronaje femenino. Cada vez que creamos una talla podemos desplegar el cursor que aparece debajo de la casilla color, para asignar colores diferentes a cada talla en el nido de escalado. La tecla Borrar, se utiliza para eliminar las tallas creadas.
    
    .row.mb-5
      .col-lg-6.d-flex(data-aos="fade-right")
        div.fondo-a.p-5
          figure.mb-4
            .titulo-sexto.color-acento-contenido(data-aos='fade-right')
              h5 Figura 29.
              span Apertura de tabla de tallas
            img(src='@/assets/curso/tema2/img16.png' alt="Imagen decorativa")
            figcaption Fuente: SENA 2021
      .col-lg-6.d-flex(data-aos="fade-left")
        div.fondo-b.p-5
          figure.mb-4
            .titulo-sexto.color-acento-contenido(data-aos='fade-right')
              h5 Figura 30.
              span Tallas
            img(src='@/assets/curso/tema2/img17.png' alt="Imagen decorativa")
            figcaption Fuente: SENA 2021

    .row.mb-5(data-aos="fade-right")
      .col-lg-1
      .col-lg-6
        p Para ampliar la información le recomendamos revisar los recursos que se presentan a continuación, en los que podrá conocer el paso a paso para la realización de este proceso.
      .col-lg-4
        a.anexo.mb-4(:href="obtenerLink('/downloads/CF4_Anexo_pasos_para_escalar_en_Optitex.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg" alt="Imagen decorativa")
          .anexo__texto
            p <b>Anexo.</b> Pasos para escalar en OptiTex
      .col-lg-1

    .row.mb-5
      .col-lg-1
      .col-lg-10(data-aos="fade-left")
        figure
          .video          
            iframe(width="1280" height="720" src="https://www.youtube.com/embed/NdZGHw_-8bA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      .col-lg-1
    //.align-items-center
    //.justify-content-center
</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({}),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass" scoped></style>
