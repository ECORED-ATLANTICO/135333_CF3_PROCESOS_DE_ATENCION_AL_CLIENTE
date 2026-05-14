<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p.mb-5 Estimado aprendiz, se da la bienvenida a este momento de aprendizaje orientado a detallar, entre otras cosas, el concepto de organización (empresa), al igual que la importancia de los clientes y la interacción con los mismos, con sus necesidades y la atención a sus requerimientos, técnicas para la gestión de los mismos denominados PQRSF y finalmente, a todo el tema de informes y su tipología. Antes de empezar, se invita a revisar el siguiente video para identificar el contexto de aprendizaje.
    
    figure.mb-5
      .video.mb-2
        iframe(width="560" height="315" src="https://www.youtube.com/embed/sPaHxbTNR8k" title="Recepción de requerimientos de clientes" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Recepción de requerimientos de clientes introducción

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
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

<style lang="sass"></style>
