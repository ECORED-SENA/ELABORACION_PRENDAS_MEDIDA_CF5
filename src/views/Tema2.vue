<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 2
      h1 Patrones básicos superiores masculinos

    figure.mb-4
      img(src="@/assets/curso/tema2/img01.png")

    p.mb-4 Partiendo del patrón base superior masculino, se pueden aplicar modificaciones como amplitudes, cortes y largos que generan el nacimiento de otros moldes básicos con los que, a través de la interpretación desde el diseño, se obtienen las prendas masculinas en tipologías superiores.

    .row.justify-content-center.mb-4
      .col-12.col-md-6.mb-4.mb-md-0
        .tarjeta.color-primario.p-4.p-md-3
          .h4 Figura 3
          p Transformación de base a camisa masculino Slim fit
        .tarjeta.color-acento-contenido
          img(src="@/assets/curso/tema2/img02.svg")
    
    hr
    #t_2_1.titulo-segundo
      .h4 2.1 La camisa y sus variaciones 
    
    p.mb-4 Para la elaboración de la camisa masculina se pueden utilizar las medidas del cliente y seguir el paso a paso del patrón elaborado. Como esta tipología no es de silueta muy ajustada, se puede apoyar de la tabla de medidas anatómicas masculinas estandarizadas y tomando como referencia el contorno más amplio de la persona. Después de su construcción, se aplican desahogos, sistema de cierre y complementos de diseño (almillas, bolsillo de parche).

    .row.mb-4
      .col-12.col-md-5.mb-4.mb-md-0
        .tarjeta.color-primario.p-4.p-md-3
          .h4 Figura 4
          p Camisa clásica
        .tarjeta.color-acento-contenido
          img(src="@/assets/curso/tema2/img03.svg") 
      .col-12.col-md-7.mb-4.mb-md-0
        figure.mb-4
          img(src="@/assets/curso/tema2/img04.png")
        p.mb-4 Para el trazo de camisa clásica, en el esquema se encuentra un plano de referencia, en donde se identifican elementos como desahogos, sistemas de cierre y los complementos (almillas, prenses, bolsillo de parche) solo se toma como una guía o una referencia de cómo se puede implementar la base, no hace alusión a especificaciones o estándares para el trazo de una camisa, por lo que se debe tener en cuenta que cada prenda, diseño, referencia, dibujo plano, ficha técnica o imagen, tiene unas referencias específicas las cuales van de la mano con todos los conceptos de diseño o requerimientos que se entregan para producción.
        p.mb-4 Con el fin de referenciar y contextualizar la implementación, es de recordar que, aunque en el Manual se identifica un plano separado, se sugiere trabajar siempre en plano unido con el fin de validar medidas como largos o proporciones referenciadas en el diseño.
        p Para dar inicio al trazo desde los básicos, se debe trazar una línea de manera horizontal en el papel, sobre el que quedarán alineados o aplomados como línea base de construcción; en prendas superiores, la línea de aplome o línea base será la línea de profundidad de sisa.

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/PKd_D-0U968" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    hr
    #t_2_2.titulo-segundo
      .h4 2.2 Comportamiento de las cabezas de mangas
    
    p.mb-4 Las cabezas de la manga son la parte ubicada desde el centro desplazándose por la sisa. Existen diferentes tipos según la necesidad del diseño buscado, razón por la cual es primordial comprender su comportamiento para evitar mangas tirantes.

    .row.mb-4
      .col-12.col-md-4.d-flex.mb-4.mb-md-0
        .tarjeta.color-acento-contenido.p-4.p-md-5
          .row.justify-content-center.mb-4
            .col-6
              img(src="@/assets/curso/tema2/img05.svg")
          p Entre 
            strong más larga 
            | sea la altura de cabeza de manga, otorgará menor movimiento sobre el cuerpo, lo que es igual a incomodidad, pero mayor estructura, esta descripción corresponde a las prendas que van ajustadas o con la horma del cuerpo.
      .col-12.col-md-4.d-flex.mb-4.mb-md-0
        .tarjeta.color-acento-contenido.p-4.p-md-5
          .row.justify-content-center.mb-4
            .col-6
              img(src="@/assets/curso/tema2/img06.svg")
          p Entre 
            strong más corta 
            | sea la altura de cabeza de manga, otorgará mayor movimiento sobre el cuerpo, lo que es igual a comodidad, pero menor estructura, esta descripción corresponde a las prendas que van holgadas o desestructuradas sobre el cuerpo.
      .col-12.col-md-4.d-flex.mb-4.mb-md-0
        .tarjeta.color-acento-contenido.p-4.p-md-5
          .row.justify-content-center.mb-4
            .col-6
              img(src="@/assets/curso/tema2/img07.svg")
          p En este caso se identifican cabezas de manga muy cortas lo cual indica que son prendas que quedarán desestructuradas u holgadas sobre el cuerpo. 

    p.mb-4 Dentro de los ejercicios anteriores de cabezas de manga, se identifica la generalidad de cabeza de manga deducida y cómo esta se divide de acuerdo con el tipo de manga. Es importante tener en cuenta que a mayor amplitud de la prenda, se debe realizar una menor división. A continuación se relaciona un ejemplo:

    .row.justify-content-center.mb-4
      .col-12.col-md-10
          img(src="@/assets/curso/tema2/img08.svg")

    p.mb-4 Sin embargo, en este caso se sugiere trabajar con otra fórmula, la cual indica, por su comportamiento, que quedará con menor estructura y mayor comodidad sobre el cuerpo. Para este caso, se debe trabajar con sumatoria de acuerdo al tipo de camisa requerida. En el caso de las cabezas de mangas deducidas para las camisas clásica y Slim fit se sugiere trabajar con:

    .row.justify-content-center.mb-4
      .col-12.col-md-4.d-flex.mb-4.mb-md-0
        .tarjeta.color-acento-contenido.p-4.p-md-5
          .row.justify-content-center.mb-4
            .col-6
              img(src="@/assets/curso/tema2/img09.svg")
          p.text-center Cabeza de manga camisa clásica
          .h2.text-center =
          p.text-center sisa delantera + sisa posterior / 6 +2
      .col-12.col-md-4.d-flex.mb-4.mb-md-0
        .tarjeta.color-acento-contenido.p-4.p-md-5
          .row.justify-content-center.mb-4
            .col-6
              img(src="@/assets/curso/tema2/img10.svg")
          p.text-center Cabeza de manga camisa Slim fit
          .h2.text-center =
          p.text-center sisa delantera + sisa posterior / 6 +4
    
    p.mb-5 La sumatoria al final permite identificar que por la silueta una de las dos mangas quedará con mayor desestructura sobre el cuerpo.

    hr
    #t_2_3.titulo-segundo
      .h4 2.3 Cuellos, mangas y sus variaciones
    
    figure.mb-4
      img(src="@/assets/curso/tema2/img11.png")

    p.mb-4 Para el desarrollo de las mangas, cuellos y puños se trabaja con las generalidades de cada uno de los trazos o de las camisas clásicas y Slim fit. A continuación, se relacionan algunas de estas generalidades a tener en cuenta:

    .row.mb-4
      .col-12.col-md-5.mb-4.mb-md-0
        .tarjeta.color-primario.p-4.p-md-3
          .h4 Figura 5
          p Portañuela
        .tarjeta.color-secundario.p-4.p-md-3
          .row.justify-content-center
            .col-8
              img(src="@/assets/curso/tema2/img12.svg")
        .tarjeta.color-primario.p-4.p-md-3
          p 
            strong Fuente: 
            | coser es un placer, 2021
      .col-12.col-md-7.mb-4.mb-md-0
        ul.lista-ul--color
            li 
              i.lista-ul__vineta
              | Para el trazo de cuellos se debe tener siempre la referencia del tipo de cuello, medidas de cada uno de los escotes y el plano de la prenda con la que se va a trabajar. El cuello se trabaja según el estilo deseado y está enlazado con los escotes.
            hr
            li
              i.lista-ul__vineta
              p La manga se compone de 
                strong portañuela 
                | y otras piezas que lo complementan y está relacionada directamente con la sisa. Para el largo de la manga se identifican referencias o disminuciones dependiendo del comportamiento y ancho de puño, cada una de las medidas son únicamente referencias, por lo que se deben tener en cuenta siempre los requerimientos del diseño y que este es solo un ejercicio práctico para ejemplificar de qué manera manejar o modificar los básicos para el desarrollo de prendas.
            hr
            li
              i.lista-ul__vineta
              | Para el largo de la manga, se identifican referencias o disminuciones dependiendo del comportamiento y ancho de puño, cada una de las medidas son únicamente referencias, por lo que se deben tener en cuenta siempre los requerimientos del diseño y que este es solo un ejercicio práctico para ejemplificar cómo manejar o modificar los básicos para el desarrollo de prendas.
            hr
            li
              i.lista-ul__vineta
              p Para el desarrollo de la 
                strong portañuela
                | , prenses, pliegues y demás complementos de la manga se debe tener en cuenta el diseño y la referencia de la prenda, pues este es solo un ejercicio práctico para ejemplificar de qué manera manejar o modificar los básicos para el desarrollo de prendas.

    figure.mb-4
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/agDscYys1CY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .row.justify-content-center.mb-4
      .col-12.col-md-6.mb-4.mb-md-0
        .tarjeta.color-primario.p-4.p-md-3
          .h4 Figura 6
          p Manga Slim fit
        .tarjeta.color-acento-contenido
          img(src="@/assets/curso/tema2/img13.svg")
    
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/ktU9DxgPvH8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    hr
    #t_2_4.titulo-segundo
      .h4 2.4 Variantes de básicos superiores masculinos
    
    figure.mb-4
      img(src="@/assets/curso/tema2/img14.png")
    
    p.mb-4 Partiendo de los patrones básicos de la camisa clásica o Slim fit masculina, se pueden aplicar modificaciones para generar diferentes estilos desde el diseño. Para profundizar en los conceptos y detalles trabajados en el trazo de camisas, se hará el análisis de diferentes diseños desde imagen y dibujo plano, con el fin de tener referencias visuales de lo que se va trabajando en este punto, y con la firme intención de afianzar cada vez más el conocimiento, se hará o trabajará todo sobre análisis de proporciones.

    .row
      .col-12.col-md-5.mb-4.mb-md-0
        img(src="@/assets/curso/tema2/img15.png")
      .col-12.col-md-7.mb-4.mb-md-0
        p.mb-4 Las proporciones son las medidas que se obtienen de una imagen, muestra física, ficha técnica, dibujo plano o diseño que, al hacer un paralelo con los básicos o moldes bases de la línea, silueta o talla que se esté trabajando, permite obtener medidas o dimensiones de referencia para el desarrollo o trazo del molde correspondiente al diseño, si bien en ocasiones anteriores se han desarrollado ejercicios sobre análisis de proporciones, es importante resaltar que las medidas y el análisis de proporciones varía de acuerdo con el tamaño, diseño, impresión, dibujo, básico y sistema de medida; las referencias implementadas son solo ejemplos detallados de cómo y qué manera se debe implementar el desarrollo.
        p.mb-4 La finalidad del ejercicio es poder comparar de qué manera se puede implementar el básico llevándolo hacia diferentes tipos de diseño, bajo una misma tipología.
        p Cuando se empieza a trabajar el trazo de prendas desde los básicos, estos siempre deben ir alineados o aplomados sobre una línea base de construcción, en prendas superiores la línea de aplome o línea base será la línea de profundidad de sisa.

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/CxwJTRQh-aY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
