<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Bases de datos

    .fullwidth-bg.fullwidth-bg--1
    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.z-2
      .col-6.col-lg-4
        figure
          img.mb-4.mb-lg-0(data-aos="fade-down-right", src="@/assets/curso/tema3/1.png", alt="descripcion")
      .col-lg-8
        p  Las bases de datos conocidas con las siglas BD (español) o DB (en inglés) o BBDD en términos informáticos, son estructuras diseñadas principalmente para recopilar y alojar información de diferentes tipos. En este sentido, podría afirmarse que varias bases de datos con fines específicos conforman en conjunto, es decir, un sistema de información. 
        p.mb-0 Hoy en día las bases de datos son una herramienta importante en la gestión empresarial, dado que a través de ellas es posible alojar, actualizar o ingresar información, y de acuerdo con esto tienen usabilidad tanto para realizar actividades individuales como colectivas dentro de la organización. Asimismo, permiten capturar información de los clientes logrando de esta manera tener procesos estandarizados y centralizados para los datos que se generan en la compañía. También, agrupan los datos de la empresa, posibilita que los datos sean compartidos entre los colaboradores, y con esto tener procesos más estructurados y almacenar gran volumen de información.

    .row.justify-content-center.mb-4.mb-lg-5.z-2
      .col-xl-10
        p.mb-0 En términos prácticos, una base de datos tiene una composición sencilla, los datos son agrupados mediante tablas, y cada una está integrada por columnas y filas, cada fila con diversos datos y se denomina registro y, las columnas conocidas como campos contienen la información específica para cada registro. Con fines ilustrativos en la siguiente figura se muestra su estructura y en la tabla siguiente un ejemplo aplicado con dichos conceptos.

    .row.justify-content-center.align-items-center.z-2.mb-5
      .col-xl-10
        .titulo-sexto.color-acento-contenido.mb-4
          h5 Figura 2.
          span Estructura de una base de datos
        img.mb-2.d-sm-none(data-aos="fade-up", src="@/assets/curso/tema3/3.png", alt="La figura muestra los cuatro tipos de kilates de oro que se presentan en joyería.")
        img.mb-2.d-none.d-sm-block(data-aos="fade-up", src="@/assets/curso/tema3/2.png", alt="La figura muestra los cuatro tipos de kilates de oro que se presentan en joyería.")
        figcaption #[strong Nota.] SENA, 2026

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 En términos empresariales, la mayoría de bases de datos que se utilizan son las denominadas “relacionales” y tal cual como se evidencia en la estructura anterior, dentro de la base de datos, las tablas deben tener algún tipo de conexión que permita que todas ellas tengan un campo en común, lo cual en el esquema anterior se observa mediante las flechas.
        
    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        .titulo-sexto.color-acento-contenido
          h5 Tabla 1.
          span Ejemplo de una tabla de clientes de una empresa
        .tabla-a.color-primario
          table
            caption #[strong Nota.] SENA, 2026
            thead
              tr(style="background-color: #F6F8FE")
                th Apellido
                th Nombres
                th Empresa
                th Número de contacto
                th Correo electrónico
                th Municipio
            tbody
              tr
                td Jaramillo Rojas
                td Diana Carolina
                td EPM
                td 315 563 51 63
                td diany@gmail.com
                td Medellín
              tr
                td López Escudero
                td Gloria Amparo
                td SENA
                td 399 000 00 20
                td gloria@gmail.com
                td Bogotá D.C.
              tr
                td Parra Guarín
                td Nelly
                td SENA
                td 300 800 90 00
                td nelly@gmail.com
                td Neiva
              tr
                td Cardona Grisales
                td Esperanza
                td Colpensiones
                td 380 00 00 00
                td espera@gmail.com
                td Cali

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        .cajon.color-terciario.p-4(data-aos="fade-up")
          p.mb-0 De acuerdo con los conceptos vistos previamente, en la tabla expuesta se observan cuatro registros de clientes y para cada uno se relacionan seis campos: apellido, nombres, empresa, número de contacto, correo electrónico y municipio. En el entendimiento de las bases de datos se debe tener presente que la primera fila hace relación a los campos de la base de datos, por tanto, no se consideran registros.

    .row.justify-content-center
      .col-xl-10
        h4(data-aos='zoom-in-right').mb-4
          span.etiqueta-title Tipos de bases de datos

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 A nivel de informática existen varios tipos de bases de datos, lo anterior, dado que las bases de datos varían según el fin con el cual se almacenará la información y el posterior uso que se le dará a dicha información. En cuanto a lo que tiene que ver con servicio al cliente, se hará mención a dos de estas clasificaciones: según la variabilidad y según el contenido. A continuación, podrá apropiar los tipos de bases de datos de una forma más clara:

    .row.align-items-stretch.justify-content-center.mb-xl-5
      .col-md-6.col-lg-4.col-xl-3
        .tarjeta-container.mb-4.custom-mh
          .position-relative.bg-secundario-medio.p-4.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.flex-column.justify-content-center
            img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema2/1.svg' alt='AvatarTop')
            h5.ms-4 Variabilidad
            p.ms-4.mb-0 Estáticas
            p.ms-4.mb-0 Dinámicas
      .col-md-6.col-lg-4.col-xl-3
        .tarjeta-container.mb-4.custom-mh
          .position-relative.bg-secundario-medio.p-4.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.flex-column.justify-content-center
            img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema2/2.svg' alt='AvatarTop')
            h5.ms-4 Según el contenido
            p.ms-4.mb-0 Bibliográficas
            p.ms-4.mb-0 De texto completo
            p.ms-4.mb-0 De directorio
      .col-md-6.col-lg-4.col-xl-3
        .tarjeta-container.mb-4.custom-mh
          .position-relative.bg-secundario-medio.p-4.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.flex-column.justify-content-center
            img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema2/3.svg' alt='AvatarTop')
            h5.ms-4 Según los modelos
            p.ms-4.mb-0 Transaccionales
            p.ms-4.mb-0 Relacionales
    
    .row.justify-content-center
      .col-xl-10
        h4(data-aos='zoom-in-right').mb-4
          span.etiqueta-title Bases de datos según la variabilidad

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 La agrupación con base en la variabilidad se da a partir del modelo en que los datos están estructurados dentro de la base de datos. En esta categoría existen dos tipos que son:

    .row.justify-content-center.align-items-stretch.mb-4.mb-lg-5
      .col-md-8.col-lg-6.mb-4.mb-lg-0
        .rounded-4.overflow-hidden.h-100
          img(data-aos="fade-up", src="@/assets/curso/tema3/7.png", alt="imagen de acompañamiento")
          .bg-secundario-medio.p-4.custom-mh
            h5 Estáticas
            p.mb-0 Son diseñadas exclusivamente con fines de lectura, almacenamiento y registro de datos históricos, sin embargo, luego son susceptibles de uso para análisis de proyecciones y comportamientos de una determinada variable. Por ejemplo, la empresa puede tener una base de datos del histórico de devoluciones que se han realizado en el último año, dicha información puede ser consultada o ser utilizada para dimensionar los recursos necesarios con el fin de poder atender dichos trámites al año siguiente. En este caso, la variable son las devoluciones y la utilidad será predecir la cantidad de agentes necesarios para atender este tipo de solicitudes.
      .col-md-8.col-lg-6
        .rounded-4.overflow-hidden.h-100
          img(data-aos="fade-up", src="@/assets/curso/tema3/8.png", alt="imagen de acompañamiento")
          .bg-secundario-medio.p-4.custom-mh
            h5 Dinámicas
            p.mb-0 Las cuales por su misma denominación son lo opuesto de las estáticas, ya que, si permiten realizar ajustes o modificaciones en la información registrada, dicho de otra manera, los datos que se ingresan pueden ser actualizados, eliminados o complementados. A nivel de ejemplo, se toma el caso de la base de datos de los datos de contacto de un cliente, esta es una información que cambia fácilmente, por lo que debe ser susceptible de actualizar en el momento que se requiera.

    .row.justify-content-center
      .col-xl-10
        h4(data-aos='zoom-in-right').mb-4
          span.etiqueta-title Bases de datos según el contenido

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Esta tipología responde a la categorización del contenido a partir del cual se espera dar la usabilidad a los datos. Allí, se identifican tres tipos que son: bibliográficas, de texto completo y de directorio.

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta custom-acordeon")
          .row(titulo="Bases de datos bibliográficas")
            .col-md-12.px-5
              p.mb-0 Las #[strong bases de datos bibliográficas] son aquellas que permiten recopilar información que responde a áreas de conocimiento específico, especialmente relacionadas con publicaciones académicas o técnicas; a nivel de tecnología se recogen en catálogos informáticos, por ejemplo, los investigadores tienen como la mejor fuente de búsqueda de información las bases de datos bibliográficas porque consolidan las referencias alrededor de temáticas específicas.
          .row(titulo="Bases de datos de texto completo")
            .col-md-12.px-5
              p Las #[strong bases de datos de texto completo] posibilitan la búsqueda de información a partir de key words (palabras clave), la diferencia con las bases de datos bibliográficas es que en estas se podrá tener acceso a la información completa, por ejemplo, Google es una base de datos de texto completo, ya que al ingresar en el buscador se puede acceder inmediatamente a consultar el documento, imagen o video que se requiera.
          .row(titulo="Bases de datos de directorio")
            .col-md-12.px-5
              p Las #[strong bases de datos de tipo directorio] alojan la información específica de un grupo de interés de la compañía, entendiendo estos como aquellos grupos con los cuales la empresa tiene relación constante, a nivel general son: los colaboradores, clientes, proveedores, distribuidores, entres de control, entre otros. Dichas bases de datos son de alta relevancia, ya que permiten organizar la información según los requerimientos puntuales que se tengan, por ejemplo, una base de datos que aloje la información de los colaboradores de la compañía relacionando sus datos de nombres, fecha de nacimiento, estado civil, estudios y datos de contacto.

    .row.justify-content-center
      .col-xl-10
        h4(data-aos='zoom-in-right').mb-4
          span.etiqueta-title Bases de datos según el modelo

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Esta es la clasificación más técnica en términos informáticos de las bases de datos y se interpretan como la forma en que se administran los datos al interior de las mismas. Tienen varios tipos; sin embargo, las más usadas en el contexto empresarial son: 

    .row.align-items-stretch.justify-content-center.mb-xl-5
      .col-md-6.col-lg-4.col-xl-3
        .tarjeta-container.mb-4.custom-mh
          .position-relative.bg-secundario-medio.p-4.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.flex-column.justify-content-center
            img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema3/9.svg' alt='AvatarTop')
            p.ms-4.mb-0 #[strong Las transaccionales]
      .col-md-6.col-lg-4.col-xl-3
        .tarjeta-container.mb-4.custom-mh
          .position-relative.bg-secundario-medio.p-4.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.flex-column.justify-content-center
            img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema3/10.svg' alt='AvatarTop')
            p.ms-4.mb-0 #[strong Las relacionales]

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Las bases de datos #[strong transaccionales] están orientadas a todo tipo de procesos, tanto básicos como complejos y tienen como característica fundamental que realizan una función determinada, adicionalmente que tienen la ventaja que envían y decepcionan datos a gran velocidad. Por su parte, las bases de datos #[strong relacionales], que son hoy en día las más utilizadas optimizan los procesos al interior de las tablas, es decir, el centro de este modelo son las “relaciones” entre datos.

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        .cajon.color-terciario.p-4(data-aos="fade-up")
          p.mb-0 Ambos tipos de bases de datos (transaccionales y relacionales) están desarrolladas bajo plataformas denominadas motores de bases de datos como Access, MySQL, Oracle, entre otras y estas a su vez se encuentran conectadas con lenguajes de programación, es decir, con códigos específicos, tales como Phyton, C++, Visual Basic, HTML, etc. y en este sentido la combinación entre un motor de base de datos y el lenguaje de programación da como resultado software (programas) con funciones específicas.

    h4(data-aos='zoom-in-right').mb-4.mb-lg-5.z-2
      span.etiqueta-title Registro de información en bases de datos


    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.z-2
      .col-sm-8.col-lg-4
        figure
          img.mb-4.mb-lg-0(data-aos="fade-down-right", src="@/assets/curso/tema3/11.png", alt="imagen de acompañamiento")
      .col-lg-8
        p En términos operativos de bases de datos, se entiende registro de información como el proceso mediante el cual una persona o un bot (robot que hace tareas operativas) ingresa información en un sistema, lo cual va originando algo que se conoce como “alimentar” la base de datos y es realizado a través de un usuario, que es aquella persona que tiene la potestad de ingresar a una DB o a un S.I.
        p.mb-0 Para el registro de información en la base de datos se deben tener presente los roles, entendidos estos como el tipo de accesos que se permiten a cada usuario, en este sentido asociado al tratamiento de bases de datos a nivel estándar se tienen los siguientes roles:


    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        .row.align-items-stretch.justify-content-center
          .col-md-6.col-lg-4.mb-4.mb-lg-0
            .tarjeta.bg-slider-f.p-4.custom-mh
              .row.justify-content-center.mb-3
                .col-8
                  img.img-120.mb-4(src='@/assets/curso/tema3/12.svg' alt='AvatarTop')
              h5.text-center.mb-4 Rol Administrador
              p.text-center Es aquel que tiene la facultad de realizar cualquier tipo de acciones sobre la base de datos, asociado tanto a los datos como a los usuarios.
          .col-md-6.col-lg-4.mb-4.mb-lg-0
            .tarjeta.bg-slider-f.p-4.custom-mh
              .row.justify-content-center.mb-3
                .col-8
                  img.img-120.mb-4(src='@/assets/curso/tema3/13.svg' alt='AvatarTop')
              h5.text-center.mb-4 Rol de Registro y Edición
              p.text-center Este tipo de roles están asociados a aquellos usuarios que ingresan, procesas y/o modifican los datos.
          .col-md-6.col-lg-4
            .tarjeta.bg-slider-f.p-4.custom-mh
              .row.justify-content-center.mb-3
                .col-8
                  img.img-120.mb-4(src='@/assets/curso/tema3/14.svg' alt='AvatarTop')
              h5.text-center.mb-4 Rol de consulta
              p.text-center Estos usuarios pueden ingresar a la base de datos con la finalidad de detallar la información y algunos casos, bajar información; sin embargo, no pueden modificar.


    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 De acuerdo con los roles, en cada empresa realizan sobre las bases de datos la asignación de perfiles, entendiendo este último concepto como la asociación para cada rol de transacciones (operaciones) específicas que puede realizar el usuario. A modo de ejemplo y para mayor comprensión se presenta esta situación: 


    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.g-0
      .col-8.col-md-4.col-lg-2.col-xl-2
        figure
          img(data-aos="fade-down-right", src="@/assets/curso/tema3/15.svg", alt="imagen de acompañamiento")
      .col-lg-8.col-xl-6
        .p-4.bg-secundario-extra-claro
          p.mb-0 #[strong Diana Carolina] es agente de servicio enfocada en la recepción de pedidos, por tanto, desde su rol de registro y edición tiene un perfil para ingresar pedidos, mientras que #[strong María Valentina] que es una agente de servicio en el contact center, enfocada en brindar información a los clientes tiene asociado a su rol de consulta un perfil para consultar los pedidos de los clientes.
      .col-8.col-md-4.col-lg-2.col-xl-2
        figure
          img(data-aos="fade-down-right", src="@/assets/curso/tema3/16.svg", alt="imagen de acompañamiento")


    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Según lo anterior, cada quien tendrá según su rol y perfil, diferentes formas de interactuar con las bases de datos. En este caso si María Valentina quisiera ingresar un pedido no lo podría realizar, dado que tiene asociado exclusivamente acceso en modo consulta, por lo que Diana Carolina tiene acceso a poder realizar más acciones sobre la base de datos que María Valentina consulta.

    .row.justify-content-center
      .col-xl-10
        h4(data-aos='zoom-in-right').mb-4
          span.etiqueta-title Seguridad de la información

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Dado que hoy en día la información es uno de los activos más importantes en una organización, en temas de bases de datos, no solo es importante garantizar el ingreso de información sino también asegurar la disponibilidad, actualización y alojamiento en pro de la continuidad del negocio. Se invita, a continuación, a que revise más sobre este importante tema:

    .row.justify-content-center.align-items-stretch.mb-4.mb-lg-5
      .col-md-8.col-lg-6.mb-4.mb-lg-0
        .rounded-4.overflow-hidden.h-100
          img(data-aos="fade-up", src="@/assets/curso/tema3/17.png", alt="imagen de acompañamiento")
          .bg-secundario-medio.p-4.custom-mh
            h5 Back-up
            p Las empresas deben tener por su seguridad un back-up (respaldo), que permita que en caso de que se tenga alguna falla técnica de tipo informático sea posible seguir contando con la información.
            p.mb-0 Técnicamente los back-up tienen por fin garantizar que la misma información se encuentre disponible mínimo en dos repositorios diferentes, ya sea físicos (instalaciones de la empresa) o en nube (servidores por fuera de ella), esto permitirá hacer frente a los ataques informáticos o errores humanos.
      .col-md-8.col-lg-6
        .rounded-4.overflow-hidden.h-100
          img(data-aos="fade-up", src="@/assets/curso/tema3/18.png", alt="imagen de acompañamiento")
          .bg-secundario-medio.p-4.custom-mh
            h5 ISO 27001 de 2013
            p.mb-0 Las empresas enfocadas en garantizar buenos procesos de gestión de la información cuentan con la ISO 27001 de 2013, que está enfocada en dar lineamientos sobre cómo las organizaciones deberán gestionar la información de forma segura y si bien las Normas ISO no son obligatorias, sí se convierten en lineamientos para las buenas prácticas empresariales.



</template>

<script>
export default {
  name: 'Tema3',
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
