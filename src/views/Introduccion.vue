<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info.text-white
      h1 Introducción
    
    p.mb-4(data-aos="fade-right") En la supervisión de procesos de confección, desde el que hacer es importante interpretar los patrones de las prendas según requerimientos de ficha técnica y orden de producción; para cumplir con este propósito se hace necesario el aprendizaje en el desarrollo de moldes, planos, y escalados en softwares especializados de patronaje. La industrialización y modernización de procesos exige cada vez más, el conocimiento básico y destreza en el manejo de programas digitales, en este caso, se aprenderá el manejo básico de tres (3) de ellos, Audaces 360, OptiTex y Gerber, para los procesos productivos según disponibilidad de la empresa.

    .bloque1.bloque-texto-b.color-acento-contenido.p-4.mb-5(data-aos="fade-left")
      .bloque-texto-b__texto
        figure
          img(src='@/assets/curso/img01.png')          
        

    p(data-aos="fade-right") El manejo de un software permite optimizar tiempos en la elaboración de patrones en las diferentes líneas de producción. La inmersión en el mundo digital se hace cada vez más predominante; es por ello, que en este espacio se hará un reconocimiento de la interfaz y el manejo de diferentes tipos de herramientas, sin embargo, el conocimiento técnico sobre el desarrollo de patrones o moldes ya ha sido adquirido y se implementará la misma base teórica con la que se trabaja de manera manual. Dentro de la cadena de producción, uno de los pasos del patronaje corresponde a trazo y corte, en este espacio se hará un contexto general, bajo la terminología de producción industrial en trazo y corte, este tipo de vocabulario, herramientas y conocimiento hace parte de los conceptos en cultura general que debe tener un patronista.

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
