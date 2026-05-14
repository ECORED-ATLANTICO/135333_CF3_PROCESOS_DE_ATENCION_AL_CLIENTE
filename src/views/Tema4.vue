<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Requerimientos

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Un requerimiento en términos de servicio al cliente es cualquier solicitud que realiza un cliente a una empresa a través de un canal oficial habilitado por la compañía. Son muy importantes estos requerimientos, ya que son los que materializan las necesidades de los clientes y en este sentido, permiten a la empresa tener contacto efectivo con ellos y en un escenario ideal obtener información valiosa para fidelizarlos e incluso para anticiparse a sus próximas necesidades de compra.

    .row.justify-content-center
      .col-xl-10
        h4(data-aos='zoom-in-right').mb-4
          span.etiqueta-title Características de los requerimientos

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p Las características están asociadas a su tipología, ya que dependiendo de ella dará el alcance para la aplicación del protocolo del servicio y en términos de personal, define incluso un perfil para el tipo de personal que se requiere para gestionar cada uno de ellos, por ejemplo, el perfil para una persona de televentas no es el mismo para una persona de servicio enfocada en soporte técnico.
        p.mb-0 Estos son los tipos de requerimientos que se abordan en las empresas con presencia en Colombia:

    .row.justify-content-center.align-items-stretch.mb-4.mb-lg-5
      .col-md-8.col-lg-6.mb-4.mb-lg-0
        .rounded-4.overflow-hidden.h-100
          img(data-aos="fade-up", src="@/assets/curso/tema4/1.png", alt="imagen de acompañamiento")
          .bg-primario-medio.p-4.custom-mh
            h5 Informativos
            p.mb-0 Los usuarios valoran su tiempo, por tanto, se comunican frecuentemente a las empresas con el fin de conocer información sobre canales de venta, horarios de atención, direcciones de sedes/sucursales, precios, características de los productos, políticas comerciales y otros aspectos que consideran básicos de las empresas.
      .col-md-8.col-lg-6
        .rounded-4.overflow-hidden.h-100
          img(data-aos="fade-up", src="@/assets/curso/tema4/2.png", alt="imagen de acompañamiento")
          .bg-primario-medio.p-4.custom-mh
            h5 Peticiones, quejas, reclamos, sugerencias, felicitaciones (PQRSF)
            p.mb-0 Las Peticiones (P), Quejas (Q), Reclamos (R), Sugerencias (S) y Felicitaciones (F) son en muchas ocasiones la mayor composición dentro de los requerimientos de los usuarios, ya que la mayoría de sus solicitudes hacia la empresa están enfocadas en ellas. A nivel general, las PQRS hacen alusión a inconformidades o dificultades con la empresa, su personal o los productos adquiridos, mientras que las felicitaciones aluden a un reconocimiento de cliente hacia la empresa y las sugerencias, una visión de mejora desde una perspectiva propositiva. 

    //- .row.align-items-stretch.mb-xl-5
    //-   .col-md-6.col-lg-4.col-xl-3.offset-xl-2
    //-     .tarjeta-container.mb-4.custom-mh
    //-       .position-relative.bg-secundario-medio.p-4.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.flex-column.justify-content-center
    //-         img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema4/3.svg' alt='AvatarTop')
    //-         p.ms-4.mb-0 #[strong Soporte técnico]
    //-   .col-md-6.col-lg-4.col-xl-2
    //-     .tarjeta-container.mb-4.custom-mh
    //-       .position-relative.bg-secundario-medio.p-4.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.flex-column.justify-content-center
    //-         img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema4/4.svg' alt='AvatarTop')
    //-         p.ms-4.mb-0 #[strong Pedidos]
    //-   .col-md-6.col-lg-4.col-xl-3
    //-     .tarjeta-container.mb-4.custom-mh
    //-       .position-relative.bg-secundario-medio.p-4.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.flex-column.justify-content-center
    //-         img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema4/5.svg' alt='AvatarTop')
    //-         p.ms-4.mb-0 #[strong Televentas]
    //-   .col-md-6.col-lg-4.col-xl-3.offset-xl-3
    //-     .tarjeta-container.mb-4.custom-mh
    //-       .position-relative.bg-secundario-medio.p-4.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.flex-column.justify-content-center
    //-         img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema4/6.svg' alt='AvatarTop')
    //-         p.ms-4.mb-0 #[strong Cobranza]
    //-   .col-md-6.col-lg-4.col-xl-3
    //-     .tarjeta-container.mb-4.custom-mh
    //-       .position-relative.bg-secundario-medio.p-4.rounded-4.tarjeta-label.custom-mh.ms-4.d-flex.flex-column.justify-content-center
    //-         img.tarjeta-label__icon.position-absolute.img-85(src='@/assets/curso/tema4/7.svg' alt='AvatarTop')
    //-         p.ms-4.mb-0 #[strong Sondeos]

    .row.justify-content-center.mb-4.mb-lg-5
      .col-lg-10.col-xl-8
        p.mb-0 Atendiendo la importancia de este tema, se invita a revisar el video que se muestra a continuación, con el fin de hacer mayor énfasis en las PQRSF:

    figure.mb-5
      .video.mb-2
        iframe(width="560" height="315" src="https://www.youtube.com/embed/08qeBEzkXCs" title="Tipo de requerimientos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Tipo de requerimientos

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-4 Adicionalmente y con el fin de que logre una mayor apropiación sobre este tema se expondrán #[strong dos ejemplos que darán alcance a la aplicación de los conceptos] vistos sobre requerimientos, esto es:

    div.slider-wrapper.z-2.mb-6
      .bg-fullwidth
      .tarjeta.tarjeta--blanca.position-relative.p-4.pt-5.z-2.my-5
        SlyderA(tipo="b")
          .row.z-2.justify-content-center.align-items-center
            .col-lg-5
              h5 Ejemplo 1
              p.mb-4.mb-lg-0 Manuel llega a la empresa y le indica que requiere una copia de su última factura porque la necesita para legalizar unos viáticos en su empresa, en este caso lo que Manuel está escalando a la empresa es una #[strong petición]; sin embargo, el agente de servicio que atiende su requerimiento lo trata de forma descortés y le indica que esto no es posible, por lo que Manuel indica que interpondrá una #[strong queja] a la empresa por el mal comportamiento del agente de servicio que lo atendió. 
            .col-lg-5
              figure
                img(src='@/assets/curso/tema4/8.png', alt='Imagen de acompañamiento')
          .row.z-2.justify-content-center.align-items-center
            .col-lg-5
              h5 Ejemplo 2
              p.mb-4.mb-lg-0 Gloria va a pagar su factura en un restaurante, pero al detallar ve que le han cobrado erróneamente, por lo que solicita que se llame al administrador para formular un #[strong reclamo], al llegar a la mesa el administrador le indica que los disculpe, que ya mismo le generan nuevamente la factura con el valor correcto, por lo que el cliente indica que a nivel de #[strong sugerencia], considera importante que se revisen las facturas por parte de los meseros antes de entregarlas a los comensales.
            .col-lg-5
              figure
                img(src='@/assets/curso/tema4/8.png', alt='Imagen de acompañamiento')

    p.mb-4.mb-lg-5 Se invita a revisar con mayor detalle a través del siguiente recurso todo lo que tiene que ver con PQRSF:

    TabsA.color-primario(data-aos="fade-down").mb-4.mb-lg-5
      .tarjeta.bg-primario-claro.p-4(titulo="Petición")
        .row.align-items-center.p-4
          .col-12
            p En términos generales, hace referencia a una solicitud formal de un cliente para obtener de igual manera una respuesta de la empresa ante un tema específico, el fin de una petición es obtener información. Cabe mencionar, que cuando se indica que es una solicitud formal implica que en la empresa debe quedar trazabilidad de la misma, es decir, documentada o registrada en algún sistema de información, así mismo, al usuario le debe quedar un soporte de su requerimiento, lo que usualmente se conoce como radicado o consecutivo.
            p También en términos normativos existe una definición en Colombia, dada en la Ley 1755 de 2015, donde se informa en su Artículo 14 que para las entidades públicas “Salvo norma legal especial y so pena de sanción disciplinaria, toda petición deberá resolverse dentro de los quince días siguientes a su recepción”.
            p.mb-0 Pese a lo anterior, es de destacar que en actividades económicas no reguladas, el tiempo de gestión de peticiones lo define la empresa a través de sus políticas internas, estableciendo procedimientos y protocolos que aseguren la oportuna respuesta al cliente, aunque es un término muy usado, la referencia de los 15 días mencionados previamente.
      .tarjeta.bg-primario-claro.p-4(titulo="Queja")
        .row.align-items-center.p-4
          .col-12
            p Se entiende como la manifestación del cliente sobre algo que considera injusto, un problema, dificultad o inconformidad. Se clasifica como queja cuando el motivo de la misma está asociado a cualquier temática, excepto el funcionamiento del producto o la prestación del servicio.
            p En otras palabras, las quejas son cuando el cliente manifiesta insatisfacción en la forma como fue atendido o manejado su requerimiento. Es de mencionar, que en Colombia, usualmente las quejas están relacionadas con el personal de la empresa, es decir, por una percepción de mal servicio.
            p.mb-0 Similar a como ocurre con las peticiones, también se debe asegurar que se tenga el registro de la acción interpuesta por parte del cliente, así como también el cliente/ usuario deberá tener alguna constancia de la presentación de la misma.
      .tarjeta.bg-primario-claro.p-4(titulo="Reclamo")
        .row.align-items-center.p-4
          .col-12
            p También se entiende como una manifestación de inconformidad, solo que en este caso, está directamente relacionado con el producto (si es una empresa de tangibles) o con la prestación del servicio (si es una empresa de intangibles). En Colombia, los reclamos suelen estar relacionados con el mal funcionamiento de los productos, incumplimiento de la promesa del servicio o temas asociados con cobros incorrectos (facturaciones erróneas o entregas tardías).
            p.mb-0 Al igual que en las peticiones y las quejas, los reclamos deben quedar documentados o registrados en la empresa y el cliente debe tener algún tipo de soporte de la acción interpuesta.
      .tarjeta.bg-primario-claro.p-4(titulo="Sugerencias")
        .row.align-items-center.p-4
          .col-12
            p Este es un concepto muy bonito, dado que el hecho que el cliente presente una sugerencia a la empresa, ya implica un nivel de involucramiento o interés en la misma, lo cual en primera instancia ya es una ganancia para la organización. Las sugerencias son una opción que tienen los clientes para dar a conocer a la empresa ideas, opiniones, propuestas, acciones de mejora o algún aspecto que consideran puede mejorar el desempeño de la compañía.
            p.mb-0 A diferencia de las peticiones, quejas y reclamos, de las sugerencias si bien debe quedar trazabilidad en la organización como parte de su compromiso con la mejora continua, en este caso, el cliente no debe quedarse con algún tipo de constancia asociada a la entrega de la misma.
      .tarjeta.bg-primario-claro.p-4(titulo="Felicitaciones")
        .row.align-items-center.p-4
          .col-12
            p.mb-0 Son la forma que tiene un cliente de dar a conocer a la empresa que desde su óptica está haciendo bien las cosas. Técnicamente, las felicitaciones expresadas de manera formal (es decir, a través de algún canal de la compañía), es la mejor representación de la satisfacción del cliente, lastimosamente, en nuestra cultura son menos frecuentes.

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Continuando con este aprendizaje, se invita a revisar los demás tipos de requerimientos que se abordan en las empresas, por favor consulte lo que se expone a continuación:

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.z-2
      .col-4.col-lg-4.col-xl-3.d-none.d-lg-block
        figure
          img.mb-4.mb-lg-0(data-aos="fade-down-right", src="@/assets/curso/tema4/10.png", alt="descripcion")
      .col-lg-8.col-xl-7
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta custom-acordeon")
          .row(titulo="Soporte técnico")
            .col-md-12.px-5
              p.mb-0 Este soporte tiene varios alcances, el primero de ellos es cuando los clientes tienen desconocimiento o dudas sobre el manejo de los productos o servicios de la empresa; el segundo es cuando tienen dificultad para acceder a alguno de los canales digitales de la compañía; finalmente, el tercero que es cuando tienen problemas con sus servicios y requieren de la empresa para validar remotamente o en el sitio su funcionamiento.
          .row(titulo="Pedidos")
            .col-md-12.px-5
              p.mb-0 En términos comerciales son los requerimientos de compras de un cliente hacia la empresa. En este orden de ideas, los agentes de servicio al cliente que están asociados a la gestión de pedidos deben estar en la capacidad de crearlos (tomarlos) e informar sobre el estado de los mismos (dar seguimiento).
          .row(titulo="Televentas")
            .col-md-12.px-5
              p.mb-0 Son canales especializados en las ventas a través de canales telefónicos, si bien hacen parte más del mundo comercial que del alcance de servicio al cliente, hoy en día es común que los agentes de servicio se vean orientados también a tener metas comerciales, es decir, a que su gestión también tenga asociados indicadores de ventas.
          .row(titulo="Cobranza")
            .col-md-12.px-5
              p.mb-0 Es la actividad donde se realizan gestiones para la recuperación del dinero que las empresas tienen pendiente por cobro, cuando hacen ventas a crédito. Es la actividad que completa el ciclo de la venta, con el fin de que el cliente compre nuevamente.
          .row(titulo="Sondeos")
            .col-md-12.px-5
              p.mb-0 La satisfacción del cliente es el fin último de las compañías en su relación con ellos, es por eso, que la realización de actividades enfocadas en conocer la opinión de estos respecto a la empresa, sus productos, sus canales de atención y su personal es vital para evaluar lo que está haciendo bien y lo que podría hacer mejor.
          .row(titulo="Otros tipos de requerimientos")
            .col-md-12.px-5
              p.mb-0 Las actividades de preventa, el agendamiento de citas, la actualización de bases de datos, la toma de domicilios y referidos de clientes. 

    .fullwidth-bg.fullwidth-bg--1
    .row.justify-content-center.z-2
      .col-xl-10
        h4(data-aos='zoom-in-right').mb-4
          span.etiqueta-title Técnicas para la gestión de requerimientos

    .row.justify-content-center.align-items-center.mb-4.z-2
      .col-sm-8.col-lg-4
        figure
          img.mb-4.mb-lg-0(data-aos="fade-down-right", src="@/assets/curso/tema4/11.png", alt="Imagen de acompañamiento")
      .col-lg-6
        p Con el fin de comprender de manera asertiva el lenguaje comunicacional en los procesos de atención al cliente y antes de ver el paso a paso para la gestión de requerimientos, se hace necesario conocer algunos conceptos básicos que se tienen a nivel operativo, en este sentido, surgen: #[strong la creación del caso, como el momento en el que se formaliza el requerimiento por parte del cliente hacia la empresa; el escalamiento del caso], obedece al momento en el que el agente de servicio debe direccionar el requerimiento para que sea gestionado por otra persona o área de la compañía y el cierre del caso se da cuando el recurso que está atendiendo el requerimiento tiene la competencia para dar la solución al cliente.

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-0 Ahora bien, desde la perspectiva de la atención al cliente, el procedimiento técnico para la gestión de requerimientos se basa en el protocolo de servicio definido por la compañía, ya que este es elaborado teniendo en cuenta la identidad de la empresa, el perfil de clientes y los diferentes tipos de solicitudes que un cliente pudiese presentar. No obstante, podrían mapearse a través de un flujo como son a nivel general las actividades que sigue la gestión de requerimientos en una compañía, todo ello desde la óptica de un agente de servicio, donde siempre se tendrá como fin la satisfacción de los clientes.

    h4(data-aos='zoom-in-right').mb-4.mb-lg-5.z-2
      span.etiqueta-title Flujo para la atención de requerimientos

    .row.justify-content-center.align-items-center.z-2.mb-5
      .col-12
        .titulo-sexto.color-acento-contenido.mb-4
          h5 Figura 3.
          span Flujo para la atención de requerimientos
        img.mb-2.d-sm-none(data-aos="fade-up", src="@/assets/curso/tema4/12-mob.svg", alt="Se detalla en la figura el flujo de atención de requerimientos así: inicio, el agente verifica la identidad del usuario o cliente, el cliente o usuario es quien dice ser, el requerimiento tiene alcance si o no?, el agente tiene alcance para dar solución? ingresar gestión en sistema de información o base de datos, fin.")
        img.mb-2.d-none.d-sm-block(data-aos="fade-up", src="@/assets/curso/tema4/12.svg", alt="Se detalla en la figura el flujo de atención de requerimientos así: inicio, el agente verifica la identidad del usuario o cliente, el cliente o usuario es quien dice ser, el requerimiento tiene alcance si o no?, el agente tiene alcance para dar solución? ingresar gestión en sistema de información o base de datos, fin.")
        figcaption <strong>Nota.</strong> SENA, (2026).
          
    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p Lo que muestra este flujo hace alusión a que el primer paso técnico por parte del agente de ventas es validar la identidad del usuario, posteriormente se debe verificar si el requerimiento que pretende presentar es viable o no para la empresa, ello implica revisar si en efecto está dentro de las políticas y tiempos que tiene en sus lineamientos la organización para registrarlo, una vez se tiene dicha validación se procede a revisar si dentro del perfil el agente tiene el perfil para dar solución, en caso que sí pueda gestionarlo debe proceder a cerrarlo, en caso que no, debe escalarlo al área o persona que corresponda. En cualquiera de estos escenarios siempre deberá cerrar la gestión en el sistema de información o base de datos indicada en el procedimiento de la empresa. 
        p.mb-0 Para un mejor entendimiento de este tema se plantean los siguientes ejemplos:

    .row.mb-5
      .col-12.col-md-6.p-4.mb-3.mb-md-0.bg-secundario-light(data-aos="zoom-in-right")
        .row.align-items-center.align-items-lg-end.mb-4
          .col-9
            h5.mb-0 Agente de servicio con alcance para dar gestión al requerimiento y cerrarlo
          .col-3.col-lg-3.col-xl-2
            figure
              img.img-85(src='@/assets/curso/tema4/13.svg', alt='Texto que describa la imagen')
        p El agente de servicio recibe una llamada de un cliente indicando que requiere realizar una devolución de un pedido que llegó con la talla equivocada, el primer paso que hace el agente es validar los datos de la persona que realiza la llamada, una vez realizada la revisión en el CRM y valida que efectivamente la persona sí hizo el pedido y que adicional se encuentra en los días hábiles para realizar el cambio del producto, por lo que procede a ingresarlo en el sistema de información y le informa al cliente que en el transcurso de 5 días hábiles recibirá el nuevo producto y deberá también tener listo el enviado previamente para entregarlo al domiciliario.
        p.mb-0 Estado del caso: cerrado.
      .col-12.col-md-6.p-4.bg-secundario-claro(data-aos="zoom-in-left")
        .row.align-items-center.align-items-lg-end.mb-4
          .col-9
            h5.mb-0 Agente de servicio NO tiene alcance para dar gestión al requerimiento y escalarlo
          .col-3.col-lg-3.col-xl-2
            figure
              img.img-85(src='@/assets/curso/tema4/14.svg', alt='Texto que describa la imagen')
        p El agente de servicio recibe una llamada de un cliente indicando que su servicio de Internet no funciona, el agente procede a realizar las validaciones sobre el usuario, una vez identifica que el suscriptor sí es quien dice ser, registra en el CRM el daño y le informa al cliente que el caso ha sido creado, escalando el caso para que sea atendido por el equipo de mantenimiento de redes quienes en el transcurso del día irán a su domicilio a resolver la situación.
        p.mb-0 Estado del caso: escalado.



    .row.justify-content-center
      .col-xl-10
        h4(data-aos='zoom-in-right').mb-4
          span.etiqueta-title Inclusión en la recepción de requerimientos desde el rol de agente de servicio

    .row.justify-content-center.mb-4.mb-lg-5
      .col-xl-10
        p.mb-4 En un sentido amplio, la inclusión significa considerar y valorar los diferentes puntos de vista bajo las particularidades, estilos y necesidades de las personas. En este sentido, dado que el primer momento de verdad de un cliente cuando está escalando una solicitud a la empresa es la recepción del requerimiento, deben tenerse en cuenta algunas consideraciones en el momento de la interacción entre agente de servicio y cliente; por ello, revise con atención lo que se expone a continuación:

    div.slider-wrapper.z-2.mb-6
      .bg-fullwidth
      .tarjeta.tarjeta--blanca.position-relative.p-4.pt-5.z-2.my-5
        SlyderA(tipo="b")
          .row.z-2.justify-content-center.align-items-center
            .col-lg-5
              h5 Empatía
              p.mb-4.mb-lg-0 Si bien las empresas tienen estipulados los protocolos de servicio, justamente con el fin de estandarizar procesos y formas de atención, desde la conversación y la forma de entablar la relación con el cliente los agentes de servicio deben mostrarse empáticos, y para ello hay una pregunta clave ¿qué haría si lo que está mencionado el cliente me estuviera pasando a mí?, frecuentemente ponerse en el lugar del otro, ayuda a tener relaciones más constructivas.
            .col-lg-5
              figure
                img(src='@/assets/curso/tema4/15.png', alt='Imagen de acompañamiento')
          .row.z-2.justify-content-center.align-items-center
            .col-lg-5
              h5 Escucha
              p.mb-4.mb-lg-0 El principio de una comunicación efectiva es la escucha, por eso, el agente de servicio debe tener esta actitud hacia su cliente, esto no solo le permitirá ser más asertivo en la forma de abordar el requerimiento, sino que también generará un ambiente de interés y confianza.
            .col-lg-5
              figure
                img(src='@/assets/curso/tema4/19.png', alt='Imagen de acompañamiento')
          .row.z-2.justify-content-center.align-items-center
            .col-lg-5
              h5 Flexibilidad
              p.mb-4.mb-lg-0 Ello no significa pasarse por alto el protocolo de servicio, al contrario, el reto es cómo aplicar el protocolo, mostrándose comprometido con el cliente en tratar de dar solución al requerimiento, implica buscar alternativas y espacios para la concertación. Bajo esta perspectiva se debe tener presente que flexibilidad no implica saltarse el debido proceso, ni pasar por encima de los lineamientos técnicos, lo que propende es aplicar el principio de la apertura.
            .col-lg-5
              figure
                img(src='@/assets/curso/tema4/16.png', alt='Imagen de acompañamiento')
          .row.z-2.justify-content-center.align-items-center
            .col-lg-5
              h5 Entender la individualidad
              p.mb-4.mb-lg-0 Si bien las personas son sujetos activos dentro de una comunidad, en el momento de interactuar con un cliente, se deben dejar de lado los estereotipos, las pretensiones y asociaciones negativas que se tengan, por el contrario, el enfoque de servicio actual se enfoca en brindar experiencias memorables a partir del entendimiento de la individualidad.
            .col-lg-5
              figure
                img(src='@/assets/curso/tema4/17.png', alt='Imagen de acompañamiento')
          .row.z-2.justify-content-center.align-items-center
            .col-lg-5
              h5 Respeto por la diferencia
              p.mb-4.mb-lg-0 Indistinto de las condiciones físicas, mentales, económicas o comportamentales, todos los clientes tienen como factor común ser seres humanos, por tanto, merecen tener consideración y valoración de sus necesidades, y bajo este panorama, donde los agentes de servicio son la cara de la empresa y deben ser los primeros embajadores del respeto.
            .col-lg-5
              figure
                img(src='@/assets/curso/tema4/18.png', alt='Imagen de acompañamiento')

</template>

<script>
export default {
  name: 'Tema4',
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
