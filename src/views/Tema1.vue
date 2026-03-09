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
            .col-6.col-lg-5
              figure
                img(src='@/assets/curso/tema1/14.png', alt='Imagen de acompañamiento')

    h4(data-aos='zoom-in-right').mb-4.mb-lg-5
      span.etiqueta-title Conceptos clave de las empresas en Colombia

    p.mb-4 Estos conceptos se describen en detalle en el siguiente documento: 

    .bg-franja.mb-5
      .row.justify-content-center.align-items-center
        .col-12.col-sm-8.col-lg-4(data-aos="fade-right")
          figure
            img.img-250(src='@/assets/curso/tema1/7.svg' alt='AvatarTop')
        .col-12.col-lg-6.align-items-center(data-aos="fade-left")
          div.p-4.p-lg-5
            p Para comprender la dinámica de las empresas en Colombia, lo primero que se debe tener claro es la perspectiva legal. En este orden de ideas, surgen algunos conceptos que se deben apropiar:
            a.boton.bg-azul-oscuro.me-3.text-white(:href="obtenerLink('downloads/Conceptos_Empresa.pdf')" target="_blank" type="application/pdf")
              span Descargar
              i.fas.fa-file-download

    .row.justify-content-center
      .col-xl-10
        h4(data-aos='zoom-in-right').mb-4
          span.etiqueta-title Funcionamiento de las empresas
    
    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Todo en la vida requiere de una estructura para poder funcionar de manera adecuada y las empresas no son la excepción, es por ello que la organización dependiendo de su tamaño y su planeación estratégica, define cómo en términos de recursos humanos orientarán su funcionamiento, lo cual a su vez se refleja en sus esquemas de mando y asignación de responsabilidades. A nivel general, se conocen cuatro tipos de mando que son el  horizontal, vertical, circular o mixtos, los cuales podrá ver con mayor detalle a continuación:

    .row.justify-content-center.mb-4.mb-lg-5.custom-tabs
      .col-xl-10
        TabsA.color-primario(data-aos="fade-down")
          .tarjeta.bg-primario-claro.p-4(titulo="Estructura horizontal")
            .row.align-items-center.p-4
              .col-12.col-lg-8
                p Se caracterizan porque existen pocos jefes y se privilegia la interacción entre áreas y procesos.
                p Positivo: los colaboradores tienen empoderamiento para tomar decisiones, por tanto, las acciones se toman rápidamente.
                p.mb-4.mb-lg-0 Desventaja: puede ser complejo llegar a consensos. 
              .col-12.col-lg-4.align-items-center.mb-3.mb-lg-0
                figure.justify-center
                  img.img-180(src='@/assets/curso/tema1/8.svg', alt='Imagen de acompañamiento')
          .tarjeta.bg-primario-claro.p-4(titulo="Estructura vertical")
            .row.align-items-center.p-4
              .col-12.col-lg-8
                p Esta es la orientación tradicional de las empresas, donde la línea de mando va de arriba hacia abajo.
                p Positivo: son muy organizadas y suelen ser eficientes porque hay  figuras que representan la dirección, organización  y control.
                p.mb-4.mb-lg-0 Desventaja: el proceso para la toma de decisiones es lento. Puede ocurrir cambio de estrategia cuando cambian los directivos. 
              .col-12.col-lg-3.align-items-center.mb-3.mb-lg-0
                figure.justify-center
                  img.img-120(src='@/assets/curso/tema1/15.svg', alt='Imagen de acompañamiento')
          .tarjeta.bg-primario-claro.p-4(titulo="Estructura circular")
            .row.align-items-center.p-4
              .col-12.col-lg-8
                p En la mitad de la estructura está la máxima autoridad de la empresa y alrededor de él se forman círculos con otros roles de jerarquía.
                p Positivo:  se pueden tener ambientes de trabajo más igualitarios, si se define en el centro al cliente será una empresa muy orientada al mercado.
                p.mb-4.mb-lg-0 Desventaja: es difícil visualizar cuál es el esquema de mando.
              .col-12.col-lg-4.align-items-center.mb-3.mb-lg-0
                figure.justify-center
                  img.img-180(src='@/assets/curso/tema1/16.svg', alt='Imagen de acompañamiento')
          .tarjeta.bg-primario-claro.p-4(titulo="Estructura mixta")
            .row.align-items-center.p-4
              .col-12.col-lg-8
                p Representa una combinación de la estructura vertical a nivel de mando y dentro de cada proceso / área hay una estructura. 
                p Positivo:  mezclan lo mejor de cada tipo de estructura, por tanto, son prácticos y funcionales.
                p.mb-4.mb-lg-0 Desventaja: en la práctica pueden ser complejos de estructurar porque están basado s en conceptos individualmente contradictorios.
              .col-12.col-lg-4.align-items-center.mb-3.mb-lg-0
                figure.justify-center
                  img.img-180(src='@/assets/curso/tema1/17.svg', alt='Imagen de acompañamiento')

    .fullwidth-bg.fullwidth-bg--1
    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.z-2
      .d-none.d-lg-block.col-6.col-lg-3
        figure
          img.mb-4.mb-lg-0(data-aos="fade-down-right", src="@/assets/curso/tema1/9.png", alt="Imagen de acompañamiento")
      .col-lg-7
        p En Colombia, muchas de las empresas operan con estructuras verticales donde las áreas están estructuradas a partir de organigramas (cartas organizacionales) donde se tienen unos líderes, que gestionan los equipos y reportan a sus jefes, que siempre están por encima de ellos; sin embargo, en varias empresas, especialmente del sector servicios, del sector de la tecnología y otras lideradas por personas jóvenes, las estructuras circulares comienzan a ganar participación, apareciendo en el centro de la organización el cliente.
        p.mb-0 Podría decirse entonces que las organizaciones de acuerdo con su planeación estratégica y la visión de sus entes de dirección elegirán cuál es la estructura a implementar, lo que no solo se reflejará en sus líneas de mando y decisión, sino también en su cultura organizacional, representando así los valores y prácticas que personifican la marca y sus colaboradores.

    h4(data-aos='zoom-in-right').mb-4
      span.etiqueta-title Las empresas, la inclusión y la discapacidad

    .row.justify-content-center.align-items-center.mb-3.z-2
      .col-lg-8
        p Muchas empresas hoy en día desarrollan al interior de sus organizaciones programas de Responsabilidad Social Empresarial (RSE) donde plasman la forma cómo contribuirán a la sociedad, es algo así como la retribución por los recursos que de ella reciben y este es un aspecto muy bien valorado, máxime cuando estas acciones no solo se verán reflejadas en temas sociales, sino también ambientales, tributarios y económicos, por ejemplo, hay estudios que muestran explícitamente cómo los consumidores están dispuestos a pagar un poco más cuando van a adquirir bienes o servicios de empresas socialmente responsables.
        p.mb-0 En este sentido, #[strong la inclusión y el reconocimiento de la diversidad es uno de los pilares dentro de la responsabilidad social empresarial], antes este podía ser un tema exclusivo de las entidades públicas; sin embargo, ahora se ve cómo desde las grandes empresas hasta los emprendedores dan ejemplo de ello, hoy en día temas tan aparentemente sencillos como la accesibilidad a las instalaciones de una empresa para personas con discapacidad da un signo claro de cómo una empresa o marca aborda esta temática.
      .d-none.d-lg-block.col-6.col-lg-4
        figure
          img(data-aos="fade-down-right", src="@/assets/curso/tema1/10.png", alt="imagen de acompañamiento")

    p.mb-4.mb-lg-5 En temas de discapacidad ahora la pregunta a resolver es #[strong ¿cómo las empresas implementan políticas o programas para la inclusión en temas de discapacidad?], en el siguiente esquema se muestra una propuesta para implementar en una empresa un protocolo de atención a personas en condición de discapacidad:

    .row.justify-content-center
      .col-xl-10
        .row.justify-content-center.align-items-stretch.mb-4.mb-lg-5
          .col-md-6.col-lg-4
            .tarjeta.bg-slider-f.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img.img-120.mb-4(src='@/assets/curso/tema1/11.svg' alt='AvatarTop')
              h5.text-center.mb-4 Compromiso por parte de la dirección
              p.text-center Definir política de discapacidad. Socializarlas con los colaboradores en todos los niveles.
          .col-md-6.col-lg-4.mt-4.mt-sm-0
            .tarjeta.bg-slider-f.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img.img-120.mb-4(src='@/assets/curso/tema1/12.svg' alt='AvatarTop')
              h5.text-center.mb-4 Documentar el protocolo de discapacidad
              p.text-center Documentar el protocolo incluyendo glosario, alcance y acciones a realizar. 
          .col-md-6.col-lg-4.mt-4.mt-lg-0
            .tarjeta.bg-slider-f.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img.img-120.mb-4(src='@/assets/curso/tema1/13.svg' alt='AvatarTop')
              h5.text-center.mb-4 Garantizar la implementación del protocolo
              p.text-center Realizar seguimiento a cómo está operando el protocolo y cómo es evaluado el tema de por parte de la población impactada.

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p Por ejemplo, el SENA como parte del compromiso de la Dirección, tiene dos marcos normativos para dar lineamientos en el actuar de la entidad en temas de discapacidad. En la Resolución 01726 de 2014 se adopta la política institucional para la atención de personas con discapacidad y en el Acuerdo 010 de 2016 se adopta la política de atención con enfoque pluralista y diferencial.
          
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
