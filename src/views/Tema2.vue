<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Sistemas de información

    p Es un concepto que pareciera alusivo a personas con formación en informática, entonces ¿por qué una persona enfocada en servicio al cliente debería conocer sobre este concepto?, la respuesta es sencilla, porque hoy el mundo está conectado digitalmente y como parte de ello toda organización que posea un nivel de funcionamiento con orientación a los procesos cuenta en su compañía con diferentes aplicaciones o programas que ayudan a sistematizar la información, la cual es en primera instancia la relevancia de este tipo de sistemas.
    p.mb-4.mb-lg-5 A continuación, se enunciarán algunas definiciones complementarias que permitirán orientar mejor el concepto de sistemas de información, también denominados coloquialmente como S.I.:

    .row.align-items-stretch.justify-content-center.mb-xl-5
      .col-md-10.col-lg-6.col-xl-4
        .tarjeta-container.mb-4.custom-mh
          .position-relative.bg-secundario-medio.p-4.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.align-items-center
            img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema2/1.svg' alt='AvatarTop')
            p.ms-4.mb-0 Son un #[strong conjunto de aplicaciones que permiten administrar información] de interés para las empresas.
      .col-md-10.col-lg-6.col-xl-6
        .tarjeta-container.mb-4.custom-mh
          .position-relative.bg-secundario-medio.p-2.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.align-items-center
            img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema2/2.svg' alt='AvatarTop')
            p.ms-5.mb-0 Es el uso aplicado de la #[strong tecnología en pro de la agilidad de los procesos y personas] que realizan operaciones o transacciones en una organización.
      .col-md-10.col-lg-6.col-xl-6
        .tarjeta-container.mb-4.custom-mh
          .position-relative.bg-secundario-medio.p-4.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.align-items-center
            img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema2/3.svg' alt='AvatarTop')
            p.ms-4.mb-0 Es un sistema de tipo informático que posibilita la #[strong obtención, gestión y administración de la información de una forma ordenada y lógica], y con un fin determinado.

    .fullwidth-bg.fullwidth-bg--1
    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        h4(data-aos='zoom-in-right')
          span.etiqueta-title Importancia de los sistemas de Información

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Los sistemas de Información probablemente nunca han cobrado tanta vigencia como actualmente, aquellos tiempos en donde las cuentas e informes se hacían en hojas en papel bond o en calculadoras quedaron atrás, los S.I. llegaron para quedarse, por lo que cada vez son más completos y útiles para las empresas y sus colaboradores. A continuación, se listan algunos aspectos que muestran de una forma explícita por qué los sistemas de información son tan relevantes para las compañías, esto es:


    .row.justify-content-center
      .col-12.col-lg-8.col-xl-6
        PasosA.color-primario.mb-5(tipo="n")(data-aos="zoom-in")
          .row.align-items-center
            .col-4.col-md-3.col-lg-2
              figure
                img.mb-4.mb-lg-0(src='@/assets/curso/tema2/4.svg', alt='Texto que describa la imagen')
            .col-md-8.col-lg-9.align-items-center
              div  
                p.mb-0 Permiten #[strong procesar] la información y generar nuevos datos de interés para la compañía.
          .row.align-items-center
            .col-md-8.col-lg-9.align-items-center
              div  
                p.text-start.mb-4.mb-lg-0 Permite tener #[strong control] sobre la información a nivel organizacional y de usuarios.
            .col-4.col-md-3.col-lg-2
              figure
                img(src='@/assets/curso/tema2/5.svg', alt='Texto que describa la imagen')
          .row.align-items-center
            .col-4.col-md-3.col-lg-2
              figure
                img.mb-4.mb-lg-0(src='@/assets/curso/tema2/6.svg', alt='Texto que describa la imagen')
            .col-md-8.col-lg-9
              div  
                p.mb-0 Posibilita la #[strong distribución] de la información asociado al uso de permisos y ambientes de colaboración.
          .row.align-items-center
            .col-md-8.col-lg-9
              div  
                p.text-start.mb-4.mb-lg-0 Permiten #[strong obtener datos] de diversas fuentes de información de la empresa tanto internas como externas. 
            .col-4.col-md-3.col-lg-2
              figure
                img(src='@/assets/curso/tema2/7.svg', alt='Texto que describa la imagen')
          .row.align-items-center
            .col-4.col-md-3.col-lg-2
              figure
                img.mb-4.mb-lg-0(src='@/assets/curso/tema2/8.svg', alt='Texto que describa la imagen')
            .col-md-8.col-lg-9
              div  
                p.mb-0 #[strong Almacenan] la información de una forma centralizada y segura.
          .row.align-items-center
            .col-md-8.col-lg-9
              div  
                p.text-start.mb-4.mb-lg-0 Permite #[strong administrar la información] desde la lógica de procesos, por lo que la consolidación de la información es un beneficio sustancial.
            .col-4.col-md-3.col-lg-2
              figure
                img(src='@/assets/curso/tema2/9.svg', alt='Texto que describa la imagen')


    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        .cajon.color-terciario.p-4(data-aos="fade-up")
          p.mb-0 En resumen y atendiendo lo visto anteriormente sobre los S.I, estos son herramientas que permiten obtener, almacenar, administrar, procesar, controlar, distribuir y custodiar la información de la empresa de una forma tecnológica y confiable y aunque, si bien en el momento inicial pueden suponer una inversión considerable cuando se compran o se desarrollan in house (es decir, se realizan al interior de la empresa), la optimización a la que llevan, la minimización de los errores y la calidad de la información que se va a tener sin duda genera una relación costo - beneficio positiva.

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        h4(data-aos='zoom-in-right')
          span.etiqueta-title Importancia de los sistemas de Información

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Probablemente existan tantos tipos y clasificaciones de los sistemas de información como autores han hecho mención del tema; sin embargo, planteando la tipología en la forma cómo funcionan las empresas, se plantean los tipos de S.I. enfocados en el proceso o la variable al que responden; en este sentido, se visionan los siguientes S.I. como aquellos más usados en las empresas:

    .fullwidth-bg.fullwidth-bg--1
    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.z-2
      .col-4.col-lg-4.col-xl-3.d-none.d-lg-block
        figure
          img.mb-4.mb-lg-0(data-aos="fade-down-right", src="@/assets/curso/tema2/10.png", alt="descripcion")
      .col-lg-8.col-xl-7
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta custom-acordeon")
          .row(titulo="ERP")
            .col-md-12.px-5
              p.mb-0 Sistema de información en el que sistematiza varios procesos de su compañía, se dirá que la empresa tiene un Enterprise Resource Planning (Sistema de planificación de recursos empresariales) más conocido como ERP.
          .row(titulo="CRM")
            .col-md-12.px-5
              p Sistemas de información enfocados en clientes, es decir, si la empresa posee un sistema de información destinado solo a los clientes, se hará mención a un Customer Relationship Management (Sistema de gestión de las relaciones con los clientes), conocido como CRM.
          .row(titulo="<em>Billing</em>")
            .col-md-12.px-5
              p Sistema enfocado exclusivamente en procesos de facturación y se denominará Billing (facturadores).
          .row(titulo="Sistemas de BI")
            .col-md-12.px-5
              p Sistema enfocado al procesamiento de información de la empresa, se denomina Business Intelligence (Inteligencia de negocios) referenciado en el ámbito empresarial como sistemas de BI.

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Vale la pena mencionar que a nivel general, entre mayor sea el tamaño de la empresa mayor será la probabilidad que incorpore varios o todos estos tipos de sistemas de información, de manera análoga entre más pequeña sea la compañía menor será el nivel de usabilidad de estas herramientas.

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        h4(data-aos='zoom-in-right')
          span.etiqueta-title Sistemas de información transversales

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 De otra parte, existen diversos sistemas de información que cuentan con la capacidad para considerarse S.I. transversales en una organización. Se invita a que revise cuáles son y cuáles son sus características:


    .row.justify-content-center.align-items-center.z-2.mb-5
      .col-xl-10
        .titulo-sexto.color-acento-contenido.mb-4
          h5 Figura 1.
          span Sistemas de información transversales
        img.mb-2.d-sm-none(data-aos="fade-up", src="@/assets/curso/tema2/11-mob.svg", alt="La figura muestra los cuatro tipos de kilates de oro que se presentan en joyería.")
        img.mb-2.d-none.d-sm-block(data-aos="fade-up", src="@/assets/curso/tema2/11.svg", alt="La figura muestra los cuatro tipos de kilates de oro que se presentan en joyería.")
        figcaption #[strong Nota.] SENA, 2026

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        h4(data-aos='zoom-in-right')
          span.etiqueta-title Sistema de información enfocado en clientes

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p Los S.I. con enfoque al cliente se denominan Customer Relationship Management y son identificados en el ámbito empresarial como CRM. Este sistema permite tener consolidada, organizada y disponible la información de los clientes, de tal forma que el agente de servicio pueda revisar la información del cliente, cómo ha sido el comportamiento con el portafolio de la empresa y cómo son sus interacciones con los puntos de contacto; lo anterior, permitirá en el momento de tener alguna interacción con el cliente ser lo más empático y asertivo posible.
        p.mb-0 Algunos de los atributos que tiene un sistema tipo CRM son los siguientes:

    SlyderF(columnas="col-lg-6 col-xl-4").mb-5.z-2
      .tarjeta.bg-slider-f.p-4
        .row.justify-content-center.mb-3
          .col-8
            img.img-120.mb-4(src='@/assets/curso/tema2/12.svg' alt='AvatarTop')
        h5.text-center.mb-4 Vista única del cliente
        p.text-center Los CRM permiten agrupar la información del cliente integrando ventas, mercadeo y servicio al cliente.
      .tarjeta.bg-slider-f.p-4
        .row.justify-content-center.mb-3
          .col-8
            img.img-120.mb-4(src='@/assets/curso/tema2/13.svg' alt='AvatarTop')
        h5.text-center.mb-4 Optimización de procesos comerciales
        p.text-center Los CRM utilizan los workflow (flujos de trabajo) para eliminar la necesidad de dedicar tiempo a tareas repetitivas.
      .tarjeta.bg-slider-f.p-4
        .row.justify-content-center.mb-3
          .col-8
            img.img-120.mb-4(src='@/assets/curso/tema2/14.svg' alt='AvatarTop')
        h5.text-center.mb-4 Seguridad de la información
        p.text-center Los sistemas CRM tienen protocolos de seguridad que garantizan que la información siempre estará disponible para la empresa.
      .tarjeta.bg-slider-f.p-4
        .row.justify-content-center.mb-3
          .col-8
            img.img-120.mb-4(src='@/assets/curso/tema2/15.svg' alt='AvatarTop')
        h5.text-center.mb-4 Análisis de información
        p.text-center Al integrar toda la información de los clientes permite realizar agrupaciones para identificar subsegmentos o nichos de clientes y generar campañas de telemercadeo.
      .tarjeta.bg-slider-f.p-4
        .row.justify-content-center.mb-3
          .col-8
            img.img-120.mb-4(src='@/assets/curso/tema2/16.svg' alt='AvatarTop')
        h5.text-center.mb-4 Gestión del flujo comercial
        p.text-center Permite disponer de diferentes opciones y etapas personalizadas de acuerdo con el modelo comercial de la empresa y los flujos de ventas.

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        h4(data-aos='zoom-in-right')
          span.etiqueta-title Sistemas de facturación

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p Atendiendo al tema de cumplimiento jurídico-tributario o simplemente por organización de la empresa, las organizaciones deben facturar a sus clientes, los tiempos en los cuales la factura era una hoja de papel escrita con lapicero ya quedaron atrás, se requiere rapidez, fiabilidad y trazabilidad, con esos fines los sistemas de información de billing (facturación) surgen para las empresas como una solución en la entrega de facturas a los clientes, incluso ahora por temas de facturación electrónica permiten, incluso, que lleguen a los clientes de forma digital. Por esto, se listan algunas características de este tipo de sistema de facturación:

    .fullwidth-bg.fullwidth-bg--1
    .row.justify-content-center.mb-4.mb-lg-5.z-2
      .col-md-6.col-lg-5.col-xl-4.mb-4.mb-xl-0(data-aos="fade-up")
        .tarjeta-numerada.color-primario.ps-5.px-4.py-5.h-100.d-flex.flex-column.bg-white
          .tarjeta-numerada__numero
            .h2 1
          h5.mb-4 Cumplimiento tributario 
          P.mb-0  Tener en la compañía sistemas de facturación permite estar tranquilo respecto al cumplimiento en temas tributarios, dado que dichos sistemas permiten realizar las configuraciones de impuestos que se requieran.
      .col-md-6.col-lg-5.col-xl-4.mb-4.mb-xl-0(data-aos="fade-up")
        .tarjeta-numerada.color-primario.ps-5.px-4.py-5.h-100.d-flex.flex-column.bg-white
          .tarjeta-numerada__numero
            .h2 2
          h5.mb-4 Agilidad en la interacción con los clientes
          P.mb-0 Bajo condiciones estables de conectividad y accesos, los S.I. de facturación permiten realizar de forma rápida la entrega de facturas a los clientes comparado con un proceso manual.
      .col-md-6.col-lg-5.col-xl-4.mb-4.mb-xl-0(data-aos="fade-up")
        .tarjeta-numerada.color-primario.ps-5.px-4.py-5.h-100.d-flex.flex-column.bg-white
          .tarjeta-numerada__numero
            .h2 3
          h5.mb-4 Disminución de errores en cobros
          P.mb-0 las manualidades llevan inmersas el error humano y si bien los S.I. son operados por humanos, con sistemas de Billing, que minimiza el error, dado que una de las finalidades de los facturadores es realizar los cálculos respectivos asociados a cada transacción.

    .row.justify-content-center.mb-4.mb-lg-5.z-2
      .col-xl-10
        h4(data-aos='zoom-in-right')
          span.etiqueta-title Sistemas de inteligencia de negocios

    .row.justify-content-center.mb-4.mb-lg-5.z-2
      .col-xl-10
        p Actualmente, el tema de inteligencia de negocios, más conocido como BI es una de las temáticas más abordadas por las empresas, dada la importancia de la toma oportuna de decisiones, de acuerdo con ello, los sistemas de información son la herramienta que ayuda a procesar y a generar información. En el siguiente listado se enuncian algunas características de los S.I. enfocados en la inteligencia de negocios:

    .row.justify-content-center.mb-4.mb-lg-5.custom-tabs
      .col-xl-10
        TabsA.color-primario.mb-5(data-aos="fade-down")
          .tarjeta.bg-primario-claro.p-4(titulo="Integración con otras aplicaciones")
            .row.align-items-center.p-4
              .col-12.col-lg-3.align-items-center.mb-3.mb-lg-0
                figure.justify-center
                  img.img-95(src='@/assets/curso/tema2/17.svg', alt='Texto que describa la imagen')
              .col-12.col-lg-9
                p.mb-0  Los sistemas de BI permiten importar bases de datos desde otras aplicaciones a partir de exportes que suelen ser muy sencillos.
          .tarjeta.bg-primario-claro.p-4(titulo="Información en tiempo real")
            .row.align-items-center.p-4
              .col-12.col-lg-3.align-items-center.mb-3.mb-lg-0
                figure.justify-center
                  img.img-95(src='@/assets/curso/tema2/18.svg', alt='Texto que describa la imagen')
              .col-12.col-lg-9    
                p.mb-0 Este es un atributo general de los sistemas de información; sin embargo, es particularmente relevante en temas de BI, dado que el fin último es tener elementos certeros para la toma de decisiones empresariales.
          .tarjeta.bg-primario-claro.p-4(titulo="Son herramientas colaborativas")
            .row.align-items-center.p-4
              .col-12.col-lg-3.align-items-center.mb-3.mb-lg-0
                figure.justify-center
                  img.img-95(src='@/assets/curso/tema2/19.svg', alt='Texto que describa la imagen')
              .col-12.col-lg-9    
                p.mb-0 Gracias a que la mayoría de estos sistemas están en la nube, (es decir, están técnicamente en servidores por fuera de la empresa soportados en Internet), ello facilita que los colaboradores de la empresa puedan acceder a los distintos informes que se generan desde dichos aplicativos.
          .tarjeta.bg-primario-claro.p-4(titulo="Alcance de visualización")
            .row.align-items-center.p-4
              .col-12.col-lg-3.align-items-center.mb-3.mb-lg-0
                figure.justify-center
                  img.img-95(src='@/assets/curso/tema2/20.svg', alt='Texto que describa la imagen')
              .col-12.col-lg-9    
                p.mb-0 la visualización es el nombre técnico con el cual se conoce el procesamiento, la agrupación y consolidación de los datos para que sean vistos y entendidos por los usuarios. Hoy en día los sistemas de BI tienen grandes bondades en cuanto a este tema, ya que a través de métricas, gráficos y tablas se muestra de forma estética y precisa la información. 

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-12
        .d-flex.flex-column.flex-lg-row.justify-content-center.align-items-center.p-4(style="background-color: #FDFCF9;")
          .col-md-6.col-lg-5
            figure
              img.img-300.mb-4.mb-lg-0(data-aos="fade-down-right", src="@/assets/curso/tema2/21.svg", alt="descripcion")
          .col-lg-7
            p.mb-0 En este orden de ideas, es muy importante cuando los agentes de servicio ingresan a la operación, determinar cuáles son los sistemas de información que se utilizan en la empresa, establecer para cuáles de ellos se requiere su acceso y por supuesto, realizar un buen proceso de entrenamiento que permita garantizar una buena capacitación en el uso de estas herramientas, especialmente porque se debe tener presente que si bien los sistemas agilizan procesos y están soportados sobre tecnología, un inadecuado uso de estos puede tener grandes implicaciones no solo en temas de experiencia del cliente, sino en reprocesos e incluso hasta en temas legales, dado que para cierto tipo de requerimientos se tienen unos tiempos específicos de respuesta, que en caso de no tenerse podría llevar a la pérdida del cliente y a multas para la compañía.
</template>

<script>
export default {
  name: 'Tema2',
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
