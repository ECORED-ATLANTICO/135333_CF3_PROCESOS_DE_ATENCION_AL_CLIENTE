<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 El componente formativo Recepción de requerimientos de clientes aborda la organización empresarial como contexto estructural donde se gestionan las solicitudes, destacando su estructura, funciones y niveles jerárquicos; desarrolla el estudio de los sistemas de información como herramientas para registrar, procesar y dar seguimiento a las interacciones; profundiza en el manejo de bases de datos para garantizar almacenamiento, consulta y actualización segura de la información; analiza los requerimientos del cliente, su clasificación y tratamiento adecuado; estudia las objeciones como parte del proceso de atención y su manejo estratégico; y finaliza con la elaboración de informes como instrumento formal para documentar solicitudes, soluciones y resultados, asegurando trazabilidad y calidad en el servicio.
    .row.justify-content-center
      .col-auto.mb-5
        figure
          img(src="@/assets/curso/sintesis.svg", alt="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris eu tincidunt erat. Fusce cursus mauris in nulla egestas vulputate. Phasellus viverra accumsan libero, sed luctus diam maximus euismod. Mauris sem risus, tincidunt vel libero in, lobortis commodo ante. Sed pulvinar luctus orci in rhoncus. Nulla ut dapibus risus, ac tempor est. Donec nulla augue, vehicula quis malesuada vitae, fermentum non nisi. Donec tincidunt nibh a magna bibendum rutrum. ")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
