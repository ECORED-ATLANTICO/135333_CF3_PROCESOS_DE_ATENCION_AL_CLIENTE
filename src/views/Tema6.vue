<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .fullwidth-bg.fullwidth-bg--1
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Informes
    
    .row.justify-content-center.mb-4.mb-lg-5.z-2
      .col-xl-10
        p Son la herramienta de gestión más utilizada en el ámbito empresarial, en los informes se resume la planeación, gestión y/o seguimiento sobre un tema, actividad o proyecto en particular. Si bien los agentes de servicio a nivel general no están enfocados en la generación de informes, sí es importante que conozcan su estructura en caso de que le sean solicitados.
        p.mb-0 A nivel empresarial, los ítems que se suelen abordar en informes de tipo empresarial son:

    SlyderF(columnas="col-lg-6 col-xl-4").mb-5.z-2
      .tarjeta.bg-slider-f.p-4
        .row.justify-content-center.mb-3
          .col-8
            img.img-120(src='@/assets/curso/tema6/1.svg' alt='AvatarTop')
        h5.text-center Objetivo
        p.text-center Cuál es la razón que origina la presentación del documento.
      .tarjeta.bg-slider-f.p-4
        .row.justify-content-center.mb-3
          .col-8
            img.img-120(src='@/assets/curso/tema6/2.svg' alt='AvatarTop')
        h5.text-center Destinatario
        p.text-center A quién está dirigido el informe.
      .tarjeta.bg-slider-f.p-4
        .row.justify-content-center.mb-3
          .col-8
            img.img-120(src='@/assets/curso/tema6/3.svg' alt='AvatarTop')
        h5.text-center Desarrollo de la temática
        p.text-center Se aborda el tema objetivo del informe, para ello se sugiere la incorporación de gráficos, indicadores y tablas, que ayuden a un mejor entendimiento.
      .tarjeta.bg-slider-f.p-4
        .row.justify-content-center.mb-3
          .col-8
            img.img-120(src='@/assets/curso/tema6/4.svg' alt='AvatarTop')
        h5.text-center Conclusiones y/o recomendaciones
        p.text-center Este punto constituye el valor agregado de los informes y está orientado en conocer de una forma técnica cuál es la percepción de los grandes resultados del informe y cuáles son las opciones de mejora que se identifican.

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.z-2
      .col-6.col-lg-4.d-none.d-lg-block
        figure
          img.mb-4.mb-lg-0(data-aos="fade-down-right", src="@/assets/curso/tema6/4.png", alt="imagen de acompañamiento")
      .col-lg-8
        p A nivel de formatos, la mayoría de informes son realizados en programas de ofimática, tipo procesador de datos (Word) o tipo presentación (PowerPoint) y entregados en formato no editable (tipo PDF). No obstante, las empresas que implementan informes o reportes en aplicaciones de inteligencia de negocios (BI) acuden a la herramienta de visualización, con el fin de tener la información de forma digital y en tiempo real, lo anterior se conoce como #[em dashboards] o tableros de visualización, cada vez más implementados en las compañías.
        p.mb-0 Algunas de las aplicaciones de la inteligencia de negocios, que tienen componente de visualización de información son Power BI (de Microsoft), Qlik y Tableau.

    .row.justify-content-center
      .col-xl-10
        h4(data-aos='zoom-in-right').mb-4
          span.etiqueta-title Tipos de informe según su contenido

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Según su contenido, los informes pueden ser clasificados en: 

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.z-2
      .col-6.col-lg-3.col-xl-2
        figure
          img.mb-4.mb-lg-0(data-aos="fade-down-right", src="@/assets/curso/tema6/5.svg", alt="imagen de acompañamiento")
      .col-lg-9.col-xl-8
        TabsA.color-primario(data-aos="fade-down")
          .tarjeta.bg-primario-claro.p-4(titulo="Expositivos")
            .row.align-items-center.p-4
              .col-12
                p.mb-0 Cuando el fin es dar a conocer información de tipo descriptivo, usualmente no tienen profundidad en análisis, por lo que su objetivo es mostrar la realidad de hechos o actividades empresariales, en el mundo empresarial se conocen como “mostrar la foto”, es decir, contar lo que está aconteciendo tal cual como se está presentado la situación.
          .tarjeta.bg-primario-claro.p-4(titulo="Interpretativos")
            .row.align-items-center.p-4
              .col-12
                p.mb-0 Se realizan cuando tienen por fin no solo describir la información sino también suministrar análisis, conclusiones y recomendaciones.
          .tarjeta.bg-primario-claro.p-4(titulo="Demostrativos")
            .row.align-items-center.p-4
              .col-12
                p.mb-0 Son aquellos que propenden por mostrar los hallazgos respecto a alguna hipótesis de negocio planteada o dar a conocer una postura respecto a una situación específica, en este segundo caso de uso, siempre deberá quedar claro cuál es la situación (es decir, lo que está aconteciendo) y cuál es la postura (es decir, la reflexión personal).
          .tarjeta.bg-primario-claro.p-4(titulo="Estructura mixta")
            .row.align-items-center.p-4
              .col-12
                p.mb-0 Persuasivos, tienen por fin obtener alguna aprobación o convencer a determinado público respecto a una valoración que se está dando sobre un tema.

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p Desde la perspectiva de los agentes de atención al cliente cuando le es asignada la elaboración de informes, usualmente se realizan con fines expositivos, bajo dos tipos de escenarios, el primero, cuando se está analizando el protocolo de servicio implementado con un cliente, en este caso, se solicita describir el paso a paso seguido con el cliente desde el momento del contacto inicial para la recepción de su requerimiento, hasta la última interacción que se haya tenido con él; el segundo escenario se da cuando el jefe o supervisor solicita un informe de gestión desde el rol, en el cual el deberá desagregar las diferentes actividades que ha estado realizado en su día a día y cuáles han sido los logros obtenidos.
        

</template>

<script>
export default {
  name: 'Tema6',
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
