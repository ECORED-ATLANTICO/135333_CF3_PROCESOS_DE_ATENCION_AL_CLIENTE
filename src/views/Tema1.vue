<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 La organización empresarial

    p La organización o empresa es la estructura económica sobre la cual funciona la economía. También puede atenderse la definición del Código de Comercio de Colombia, que en su página 9 define la empresa como #[strong “Toda actividad económica organizada para la producción, transformación, circulación, administración o custodia de bienes, o para la prestación de servicios”.]
    p.mb-6 Las empresas son creadas para atender diversas misiones como las que se pueden ver a continuación:

    div.slider-wrapper.z-2.mb-6
      .bg-fullwidth
      .tarjeta.tarjeta--blanca.position-relative.p-4.pt-5.z-2.my-5
        SlyderA(tipo="b")
          .row.z-2.justify-content-center.align-items-center
            .col-lg-5
              p.mb-4.mb-lg-0 Atendiendo a su finalidad, las empresas son creadas para atender a una misión económica, a través de la generación de lucro y una misión social dada la oportunidad que presentan para la creación de empleo, a la vez que contribuyen a la satisfacción de las necesidades humanas.
            .col-lg-6
              figure
                img(src='@/assets/curso/tema1/1.png', alt='Imagen de acompañamiento')
          .row.z-2.justify-content-center.align-items-center
            .col-lg-5
              p.mb-4.mb-lg-0 Desde la perspectiva económica, las empresas tienen a nivel general una función y es el lucro, es decir, la obtención de ganancias a partir del desarrollo de una actividad comercial legal. Es por ello, que usualmente cuando un cliente va a adquirir un producto debe pagar un precio para que a cambio la empresa le entregue el bien o servicio requerido.
            .col-lg-6
              figure
                img(src='@/assets/curso/tema1/2.png', alt='Imagen de acompañamiento')
          .row.z-2.justify-content-center.align-items-center
            .col-lg-5
              p.mb-4.mb-lg-0 Desde la perspectiva económica, las empresas tienen a nivel general una función y es el lucro, es decir, la obtención de ganancias a partir del desarrollo de una actividad comercial legal. Es por ello, que usualmente cuando un cliente va a adquirir un producto debe pagar un precio para que a cambio la empresa le entregue el bien o servicio requerido.
            .col-lg-6
              figure
                img(src='@/assets/curso/tema1/3.png', alt='Imagen de acompañamiento')
          .row.z-2.justify-content-center.align-items-center
            .col-lg-5
              p.mb-4.mb-lg-0 Paralelamente, las organizaciones en cumplimiento de su objeto producen u ofrecen al mercado diferentes bienes y servicios para que estos sean adquiridos por los consumidores que los necesitan, de esta forma gana la empresa obteniendo sus ganancias con la venta de los productos y ganan los clientes satisfaciendo su necesidad.
            .col-lg-6
              figure
                img(src='@/assets/curso/tema1/1.png', alt='Imagen de acompañamiento')
          .row.z-2.justify-content-center.align-items-center
            .col-lg-5
              p.mb-4.mb-lg-0 Una vez teniendo clara su perspectiva económica y su perspectiva social, las organizaciones proceden a definir su planeación estratégica, la cual define los elementos empresariales sobre los cuales operará la empresa, planeación que se convierte a su vez en su principal herramienta de gestión.
            .col-lg-6
              figure
                img(src='@/assets/curso/tema1/4.png', alt='Imagen de acompañamiento')
          .row.z-2.justify-content-center.align-items-center
            .col-lg-6
              p.mb-4.mb-lg-0 Comúnmente, el paso inicial consiste en definir cuál es la estrategia sobre la cual operará la empresa, lo que posteriormente, se formaliza en los siguientes elementos: la misión, representa la razón de ser, usualmente se define a través de uno o dos párrafos donde las empresas declaran el porqué de su existencia; mientras que por su parte, la visión plasma usualmente en un horizonte de tiempo definido (aproximadamente tres a cinco años) a dónde quiere llegar la compañía; la diferencia entre la misión y la visión es que la primera se formula desde el presente y la segunda desde el futuro.
            .col-lg-5
              figure
                img(src='@/assets/curso/tema1/5.png', alt='Imagen de acompañamiento')
          .row.z-2.justify-content-center.align-items-center
            .col-lg-6
              p En el siguiente ejemplo se mostrará cómo el Servicio Nacional de Aprendizaje (SENA) define dos de los elementos clave de su planeación estratégica, la misión y la visión:
              p Misión: el SENA está encargado de cumplir la función que le corresponde al Estado de invertir en el desarrollo social y técnico de los trabajadores colombianos, ofreciendo y ejecutando la formación profesional integral, para la incorporación y el desarrollo de las personas en actividades productivas que contribuyan al desarrollo social, económico y tecnológico del país (Ley 119/1994).
              p.mb-4.mb-lg-0 Visión: en el año 2022 el SENA se consolidará como una entidad referente de formación integral para el trabajo, por su aporte a la empleabilidad, el emprendimiento y la equidad, que atiende con pertinencia y calidad las necesidades productivas y sociales del país.
            .col-lg-5
              figure
                img(src='@/assets/curso/tema1/14.png', alt='Imagen de acompañamiento')
 
</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
