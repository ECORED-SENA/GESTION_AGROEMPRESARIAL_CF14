<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero
        span 2
      h1 Monitoreo y supervisión
    .bg4
      .row.justify-content-center.align-items-center
        .col-lg-12
          .bloque-texto-g.color-custom-2.p-3.p-sm-4.p-md-5.mb-5.d-none.d-lg-block
            .bloque-texto-g__img.m-left(data-aos="fade-left")(
          :style="{'background-image': `url(${require('@/assets/curso/tema2/img1.png')})`}"
          )
            .bloque-texto-g__texto.p-5(data-aos="fade-right")
              p.mb-3 La planeación puede considerarse uno de los pilares fundamentales de la administración, puesto que permite dilucidar los objetivos que se esperan alcanzar, en un periodo de tiempo determinado y el cúmulo de acciones a través de los cuales se materializarán.
          .bloque-texto-a.color-custom-3.p-md-0.mb-5.d-block.d-lg-none
            .row.m-4.align-items-center.justify-content-between
              .col-lg-9(data-aos="fade-right")
                .bloque-texto-a__texto.p-5.my-5
                  p La planeación puede considerarse uno de los pilares fundamentales de la administración, puesto que permite dilucidar los objetivos que se esperan alcanzar, en un periodo de tiempo determinado y el cúmulo de acciones a través de los cuales se materializarán.
              .col-lg-3.mb-3.mb-lg-0(data-aos="fade-left")
                figure
                  img(src='@/assets/curso/tema2/img1.png' alt='', style="width:400px; display:block; margin:-1rem 0 ;")
      .row.justify-content-center.mb-5
        .col-lg-12
          .cajon.color-acento-contenido.p-4
            p.mb-0  De forma paralela y transversal a la ejecución de los planes se debe llevar a cabo la labor de monitoreo y supervisión, a través de la cual se identifican las falencias e imperfecciones que lastren la gestión y proponer medidas que permitan corregirlas de forma oportuna para mitigar su efecto en el resultado final.
      .row.justify-content-center
        p.mb-4.text-center En relación con el monitoreo y la supervisión tenga presente:
        .col-lg-4.mb-4
          .tarjeta.tarjeta.bg-color5.p-4.h-100
            img(src='@/assets/curso/tema2/img2.png', alt='Texto que describa la imagen' ).mb-5
            h4.text-center Aspectos mejorables
            p.text-center El seguimiento de cada tarea con un responsable asignado,favorece implementar medidas de recompensa para los empleados que ejecuten su labor de forma oportuna y cumpliendo con los requisitos determinados; de la misma forma, se pueden reprender a quienes hayan presentado falencias por falta de atención a las actividades. También permite determinar si existen colaboradores que no cumplen con los requerimientos necesarios para desempeñar su trabajo, y tomar las decisiones que sean necesarias, como el cambio de cargo o el despido justificado.
        .col-lg-4.mb-4
          .tarjeta.tarjeta.bg-color5.p-4.h-100
            img(src='@/assets/curso/tema2/img3.png', alt='Texto que describa la imagen' ).mb-5
            h4.text-center Contrastar resultados reales y proyectados
            p.text-center Sin una adecuada supervisión no hay forma de contrastar los resultados reales con los proyectados, por lo que se queda sin bases cualquier juicio relacionado con la efectividad de las medidas implementadas, de forma ocasional o permanente.
    separador
    #t_2_1
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1 Evaluación estratégica
    .row.align-items-center.mb-5
      .col-lg
        .row.align-items-start.mb-4(data-aos="fade-left")
          .col
            p.mb-4 La evaluación estratégica comprende el análisis de los aspectos globales más importantes del modelo de negocio. 
            p Por lo tanto, comprende el estudio de políticas de tipo gerencial, la evaluación de los planes estratégicos financieros, comerciales y de producción y la de los resultados obtenidos por estas áreas. 
        .cajon.color-acento-contenido.p-4
          p.mb-0 Este tipo de supervisión se centra en medir la gestión efectuada por los niveles jerárquicos superiores, lo que involucra al personal de nivel estratégico y táctico.
      .col-lg-auto
        figure
          img(src='@/assets/curso/tema2/img5.png')(data-aos="fade-right")
    p.mb-5.text-center Estos son algunos aspectos clave de la evaluación estratégica que debe tener presentes:
    .row.justify-content-center(data-aos="fade-right")
        p.mb-4.text-center En relación con el monitoreo y la supervisión tenga presente:
        .col-lg-3.mb-4
          .tarjeta.tarjeta.bg-color6.p-4.h-100
            img(src='@/assets/curso/tema2/img6.png', alt='Texto que describa la imagen' ).mb-5
            h4.text-center ¿Quién la efectúa?
            p.text-center Este tipo de evaluación es efectuada por los altos rangos del área administrativa, puesto que los jefes de área y el personal operativo no cuentan con la autoridad ni el conocimiento necesario. 
        .col-lg-3.mb-4
          .tarjeta.tarjeta.bg-color6.p-4.h-100
            img(src='@/assets/curso/tema2/img7.png', alt='Texto que describa la imagen' ).mb-5
            h4.text-center Agentes adicionales
            p.text-center Sin embargo, pueden involucrarse al proceso agentes de información adicional, puesto que tienen un acercamiento directo a los clientes y a los terceros relacionados con el negocio.
        .col-lg-3.mb-4
          .tarjeta.tarjeta.bg-color6.p-4.h-100
            img(src='@/assets/curso/tema2/img8.png', alt='Texto que describa la imagen' ).mb-5
            h4.text-center Pasos sistemáticos
            p.text-center El proceso de evaluación sigue una serie de pasos sistemáticos que se incluyen dentro de un ciclo que se repite continuamente para mantener constante la evolución del negocio.
    p.mb-4.text-center Identifique las fases del proceso de evaluación que se mencionan y explican en el siguiente recurso:
    .row(data-aos="fade-up-left")
      .col-xxl-12.col-lg-12.col-12.p-0
        ImagenInfograficaB.color-acento-botones.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema2/img8.svg')
          div(x="14.5%" y="47.6%" tooltip="Click para leer mas..." numero="+")
            .row.justify-content-center.align-items-center
              .col-lg-10
                h4.mb-3.text-dark Establecer lo que se medirá
              .row
                .col-lg-2
                  img.mb-3(src='@/assets/curso/tema2/img9.svg')
                .col-lg-10
                  p.text-dark El planteamiento de los objetivos estratégicos definidos en la planeación serán el insumo principal para elegir los elementos a evaluar. En principio deben elegirse los procesos y resultados que serán medidos, es recomendable que se distingan por naturaleza o área funcional. Esto posibilita la designación de responsables y la elaboración de informes independientes para cada departamento de la empresa. 
          div(x="32.3%" y="47.2%" tooltip="Click para leer mas..." numero="+")
            .row.justify-content-center.align-items-center
              .col-lg-10
                h4.mb-3.text-dark Definir indicadores
              .row
                .col-lg-2
                   img.mb-3(src='@/assets/curso/tema2/img10.svg')
                .col-lg-10
                  p.text-dark Son razones en las que se relacionan diferentes datos para medir las variaciones en un periodo de tiempo. Los indicadores pueden ser diseñados por la parte evaluadora en función de lo que se espere medir, y se pueden expresar en términos absolutos (unidades) o relativos (porcentajes).
          div(x="85.5%" y="47.7%" tooltip="Click para leer mas...")
            .row.justify-content-center.align-items-center
              .col-lg-10
                h4.mb-3.text-dark Aplicar medidas productivas
              .row
                .col-lg-2
                   img.mb-3(src='@/assets/curso/tema2/img14.svg')
                .col-lg-10
                  p.text-dark Tomar medidas correctivas cuando no se alcanzan los resultados esperados, es procedente evaluar cuáles fueron los factores responsables de ello. Esto conlleva a nuevas propuestas que modifican parcial o completamente las estrategias iniciales. Este paso implica el reinicio del ciclo, puesto que una vez son sometidas a cambio las estrategias a aplicar se debe retomar la ejecución con las nuevas reglas y posteriormente, volver a evaluar los resultados para determinar si los cambios resultaron beneficiosos para los propósitos empresariales.           
          div(x="68%" y="86.5%" tooltip="Click para leer mas...")
            .row.justify-content-center.align-items-center
              .col-lg-10
                h4.mb-3.text-dark Alto
              .row
                .col-lg-2
                   img.mb-3(src='@/assets/curso/tema2/img13.svg')
                .col-lg-10
                  p.text-dark Si se había presupuestado incrementar el número de unidades vendidas de un producto en 10.000 unidades; pero el incremento apenas alcanzó las 5.000 unidades, la comparación de los resultados indica que solo se logró un 50% de la efectividad esperada con las estrategias implementadas.
          div(x="67.6%" y="47.7%" tooltip="Click para leer mas...")
           .row.justify-content-center.align-items-center
              .col-lg-10
                h4.mb-3.text-dark ¿Concuerda con lo esperado?
              .row
                .col-lg-2
                   img.mb-3(src='@/assets/curso/tema2/img12.svg')
                .col-lg-10
                  p.text-dark Es una actividad clara y directa, se deben comparar los resultados presupuestados durante la planeación con los efectivamente alcanzados. Esta comparativa debe medirse en términos relativos, donde lo estimado inicialmente equivale al 100% de efectividad.
          div(x="50.6%" y="47.4%" tooltip="Click para leer mas...")
              .row.justify-content-center.align-items-center
                .col-lg-10
                  h4.mb-3.text-dark Medir el rendimiento
                .row
                  .col-lg-2
                     img.mb-3(src='@/assets/curso/tema2/img11.svg')
                  .col-lg-10
                    p.text-dark En esta fase se debe tener claridad respecto al plazo que se le dará a las estrategias para medir su efectividad. Tratándose de aspectos estratégicos, usualmente se evalúa a partir de un año desde su implementación; sin embargo, existe una supervisión permanente sobre los detalles para minimizar los eventos que lastren la efectividad de las medidas aplicadas.
          
    separador
    #t_2_2
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.2 Técnicas de monitoreo y recolección de información
    p El monitoreo como uno de los procesos clave en el seguimiento de las estrategias implementadas en el negocio tiene como función principal la obtención de datos relevantes que luego serán contrastados en la evaluación, para la constitución de juicios de valor, relacionados con la utilidad o efectividad de las tareas ejecutadas.
    p Para garantizar su utilidad existen algunos métodos muy efectivos para la recopilación de información en el ámbito empresarial. En el video que se muestra enseguida se mencionan los más destacados:
    .tarjeta.tarjeta--azul.p-4.mb-5
      SlyderA(tipo="b")(data-aos="fade-right")
        .row.align-items-center.justify-content-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Medición directa]
            p Consiste en una tarea que se ejecuta junto con las demás contenidas en la estrategia, es decir, es una tarea accesoria para el personal operativo, y funciona como uno de los sistemas más detallados, gracias a su proximidad con el trabajo realizado y su permanencia. El tipo de evidencia puede variar dependiendo de la naturaleza del trabajo, y va desde documentos, hasta fotografías o grabaciones.
          .col-lg-8.ps-4
            figure
              img(src='@/assets/curso/tema2/img15.png')
        .row.align-items-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Estudios específicos]
            p Es una de las estrategias más avanzadas. Normalmente se contratan consultores especialistas en un área específica, para que desarrolle un trabajo de investigación avanzado sobre una temática precisa. Los resultados suelen evidenciarse en informes o monografías, así como reportes técnicos con información de utilidad.
          .col-lg-8.ps-4
            figure
              img(src='@/assets/curso/tema2/img16.png')
        .row.align-items-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Confrontación de puntos de vista]
            p En muchas ocasiones, las opiniones de diferentes trabajadores puede aportar información útil, que desde la perspectiva del evaluador se pasa por alto. Para ello, se recomienda efectuar reuniones periódicas con los miembros del equipo de cada área para recopilar todos los hechos identificados en el desarrollo del trabajo. Lo ideal es que cada quien aporte desde su experticia y que la evidencia se sustente en actas o documentos firmados por los participantes.
          .col-lg-8.ps-4
            figure
              img(src='@/assets/curso/tema2/img17.png')
        .row.align-items-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Entrevista]
            p Se recomienda el uso de entrevistas semiestructuradas, es decir, que cuenten con una lista de preguntas de base sobre las cuales iniciar el trabajo. Acudir y efectuar las entrevistas a las personas que realizan tareas relevantes y sobre las cuales se desee profundizar. La retroalimentación proveniente de las respuestas puede abrir espacios nuevos de discusión motivados por los hallazgos.
          .col-lg-8.ps-4
            figure
              img(src='@/assets/curso/tema2/img18.png')
        .row.align-items-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Observación]
            p La supervisión directa suele generar resultados válidos y de gran valor, consiste en estar presente durante la ejecución de las tareas y a través de la observación identificar conductas o procedimientos susceptibles de mejora.  Es recomendable prepararse previo a la visita con la indagación a que haya lugar, para que se focalice el trabajo en aquellos aspectos que demanden especial atención.
          .col-lg-8.ps-4
            figure
              img(src='@/assets/curso/tema2/img19.png')
        .row.align-items-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Encuesta]
            p Es el sistema más práctico para recolectar la información de un gran número de personas. Se recomiendan preguntas cerradas para facilitar la compilación y la tabulación de los datos; sin embargo, el espacio para preguntas abiertas puede complementar las respuestas y otorgar información adicional que no haya sido contemplada inicialmente. En función de estas respuestas es posible codificarlas para efectuar análisis estadísticos que lleven a identificar situaciones generalizadas o tendencias.
          .col-lg-8.ps-4
            figure
              img(src='@/assets/curso/tema2/img20.png')
    .row.mb-5
      .col-12.bg-color4.p-4
        .row.align-items-center.justify-content-center
          .col-lg-1.mb-3
            figure
              img(src='@/assets/curso/tema1/img31.png').mx-auto(data-aos="fade-right")
          .col-lg-11
            h5 Atención
            p.mb-0 La realización de las actividades de monitoreo no se debe limitar a la recolección de información, si bien constituyen el insumo principal, apenas y aportan la materia prima para los resultados finales.
    p.mb-5 Identifique los componentes del sistema de monitoreo y detalle sus características observando con atención el video que se muestra enseguida:     
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)(data-aos="fade-right")
    separador
    #t_2_3
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.3 Plan de acciones de seguimiento
    p La supervisión y monitoreo son labores que se desarrollan de manera paralela a la aplicación de las estrategias; pero al ser actividades anexas y secuenciales requieren de un cronograma independiente para desarrollarse de forma orgánica y según lo previsto.
    p La siguiente figura presenta un modelo a seguir respecto al proceso de seguimiento y las fases que lo integran: 
    .row.justify-content-center.mb-5
      .col-lg-10
        .titulo-sexto.color-acento-contenido.mb-5
          p.mb-0 #[b Figura 5]. Flujograma de acciones de seguimiento
        figure
          img(src='@/assets/curso/tema2/img21.svg')
          figcaption #[b Nota]. Adaptado de la Junta de Andalucía (2016).
    p Sobre el plan de acciones de seguimiento tenga presente las siguientes generalidades:
    .row.mt-5.mb-5.mb-lg-0
      .col-lg-6
        .row.mb-5
          .col-md-12.mb-5.mb-md-0
            LineaTiempoD.color-primario
              .row(numero="1" titulo="Elaboración del informe de seguimiento")
                .col-md-4.pt-2.mb-3
                  figure
                    img(src='@/assets/curso/tema2/img23.png', alt='Texto que describa la imagen')
                .col-md-8.mb-4.mb-md-0
                  p.mb-2 El personal encargado de las tareas de supervisión y monitoreo debe elaborar un informe respecto al estado actual de las tareas en ejecución y objeto de evaluación. En este informe se deberá detallar el flujo de actividades de los procesos, y la forma en la que el equipo efectuará la supervisión.  
              .row.pt-2(numero="2" titulo="Contenido del informe") 
                .col-md-4.pt-2.mb-3
                  figure
                    img(src='@/assets/curso/tema2/img24.png', alt='Texto que describa la imagen')
                .col-md-8.mb-4.mb-md-0
                  p.mb-2 Este informe debe contener la información vigente más importante, lo que contempla el grado de avance o aplicación de las estrategias, los riesgos y problemáticas identificados hasta entonces. Las acciones de supervisión a realizar hasta la siguiente revisión y actualización de este documento y las modificaciones efectuadas al alcance del trabajo.
              .row.pt-2(numero="3" titulo="Reunión de seguimiento") 
                .col-md-4.pt-2.mb-3
                  figure
                    img(src='@/assets/curso/tema2/img25.png', alt='Texto que describa la imagen')
                .col-md-8.mb-4.mb-md-0
                  p.mb-2 El líder del equipo de seguimiento convocará a los demás involucrados para socializar los hallazgos efectuados por cada uno de ellos. Se revisará lo que se ha adelantado en el informe y se recomendarán todos los ajustes que consideren apropiados, de acuerdo con el análisis hecho sobre las evidencias suministradas.
              .row.pt-2(numero="4" titulo="Análisis de riesgos y amenazas") 
                .col-md-4.pt-2.mb-3
                  figure
                    img(src='@/assets/curso/tema2/img26.png', alt='Texto que describa la imagen')
                .col-md-8.mb-4.mb-md-0
                  p.mb-2 En estas reuniones se deberán analizar los potenciales riesgos o amenazas a las que se somete la aplicación de las estrategias, que pueden ir desde aspectos de insuficiencia presupuestal, hasta la inviabilidad por regulaciones o falta de personal. A partir de esto, pueden surgir modificaciones en cuanto a tareas o plazos, que deberán ser sometidos a consideración por parte del equipo.
              .row.pt-2(numero="5" titulo="Actualización del informe") 
                .col-md-4.pt-2.mb-3
                  figure
                    img(src='@/assets/curso/tema2/img27.png', alt='Texto que describa la imagen')
                .col-md-8.mb-4.mb-md-0
                  p.mb-2 Posterior a cada reunión de seguimiento, se levantará un acta con los hechos más relevantes de la misma, detallando los temas pendientes y pasos futuros a aplicar durante la ejecución del programa. Esta acta debe ser aprobada por los asistentes, lo que implica la revisión por parte de cada uno de ellos, de tal forma que se evite documentar eventos imprecisos que lleven a decisiones equivocadas y ajustes improcedentes al informe. 
              .row.pt-2(numero="6" titulo="Cambios, modificaciones y actualizaciones") 
                .col-md-4.pt-2.mb-3
                  figure
                    img(src='@/assets/curso/tema2/img28.png', alt='Texto que describa la imagen')
                .col-md-8.mb-4.mb-md-0
                  p.mb-2 Una vez el acta ha sido aprobada, los hallazgos allí expuestos aportarán la información necesaria para modificar el informe de seguimiento hasta entonces vigente. Debido a la dinámica del monitoreo es posible que tras cada reunión se efectúen cambios, lo que convierte a este informe en un documento dinámico que evoluciona según la situación lo amerite. 
      .col-lg-6.d-flex.align-items-center
        img(src='@/assets/curso/tema2/img22.png', alt='Texto que describa la imagen')
    .row.mb-5
      .col-12.bg-color4.p-4
        .row.align-items-center.justify-content-center
          .col-lg-1.mb-3
            figure
              img.mx-auto(src='@/assets/curso/tema1/img31.png')
          .col-lg-11
            h5 Importante
            p.mb-0 El informe de seguimiento, continuará siendo objeto de modificaciones hasta cuando finalice el ciclo de supervisión, que dará cabida a un nuevo proceso, una vez se modifiquen las estrategias a aplicar en la operación del negocio.
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
