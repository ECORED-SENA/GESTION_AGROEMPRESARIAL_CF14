<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Informe gerencial
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12
        .bloque-texto-g.color-custom-2.p-3.p-sm-4.p-md-5.mb-5.d-none.d-lg-block
          .bloque-texto-g__img.m-left(data-aos="fade-left")(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/img1.png')})`}"
        )
          .bloque-texto-g__texto.p-5(data-aos="fade-right")
            p.mb-3 Un plan de mercadeo, desde el diseño de las estrategias, el planteamiento de los objetivos que se espera alcanzar, la asignación de tareas a responsables y determinación de fechas, hasta su posterior supervisión y monitoreo, corresponde a labores propias del desarrollo del mismo. 
        .bloque-texto-a.color-custom-3.p-md-0.mb-5.d-block.d-lg-none
          .row.m-4.align-items-center.justify-content-between
            .col-lg-9(data-aos="fade-right")
              .bloque-texto-a__texto.p-5.my-5
                p Un plan de mercadeo, desde el diseño de las estrategias, el planteamiento de los objetivos que se espera alcanzar, la asignación de tareas a responsables y determinación de fechas, hasta su posterior supervisión y monitoreo, corresponde a labores propias del desarrollo del mismo. 
            .col-lg-3.mb-3.mb-lg-0(data-aos="fade-left")
              figure
                img(src='@/assets/curso/tema3/img1.png' alt='', style="width:400px; display:block; margin:-1rem 0 ;")
    .row.justify-content-center.mb-5(data-aos="fade-left")
      .col-lg-6.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema3/img2.png', alt='Texto que describa la imagen')
      .col-lg-6.mb-5
          p Como elemento final se debe presentar un informe de resultados que:
          ul.lista-ul
            li.mb-0 
              i.fas.fa-angle-right
              p.mb-3 Contiene los resultados alcanzados.
            li.mb-0 
              i.fas.fa-angle-right
              p.mb-3 Recopila la información más relevante respecto a la inversión efectuada.
            li.mb-0 
              i.fas.fa-angle-right
              p.mb-3 Relaciona la inversión tanto en recursos materiales como de tiempo.
            li.mb-0 
              i.fas.fa-angle-right
              p.mb-3 Detalla la evaluación de los resultados alcanzados con relación a las propuestas iniciales.
            li.mb-0 
              i.fas.fa-angle-right
              p.mb-3 En caso de que existan objetivos inconclusos, también revelará las situaciones que dieron lugar a ello. 
      
    separador
    #t_3_1
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.1 Estructura
    p El esquema general del informe gerencial no difiere mucho de cualquier otro informe ejecutivo de hallazgos o resultados.  Debido a que su propósito es recopilar toda la información relevante asociada con el proceso, su contenido debe explorar cada una de las etapas por las que atravesó el diseño e implementación de las estrategias.
    p A continuación se presenta un listado de los elementos que deben quedar incluidos en un informe gerencial; sin embargo, pueden adicionarse todos aquellos elementos que el autor considere pertinentes:
    .row.mt-5.justify-content-center.align-items-center(data-aos="fade-left")
        .col-lg-6
          .row.mb-5
            .col-md-12.mb-5.mb-md-0
              LineaTiempoD.color-primario
                p(numero="1" titulo="Resumen gerencial") Un breve resumen que recapitule la temática que va a ser desarrollada más a detalle en las páginas siguientes. Es recomendable que su extensión no supere las dos páginas, puesto que su propósito es principalmente introductorio.
                p(numero="2" titulo="Descripción de la situación inicial") El objetivo de la implementación de estrategias es mejorar procesos actuales o implementar nuevos. Resulta idóneo describir las situaciones problemáticas o las ineficiencias que motivaron poner a prueba nuevas tareas o efectuar modificaciones a los procesos.  
                p(numero="3" titulo="Estrategias a aplicar") Implica describir los objetivos, las tareas a implementar, los responsables asignados y los objetivos que se esperaban conseguir. Si hay lugar, justificar la elección de las estrategias a través de los análisis o interpretaciones que llevaron a ellas.                
                p(numero="4" titulo="Presupuesto") Recopilar los datos de los costos y gastos asociados a la ejecución del programa expuesto. Se deben incluir recursos materiales, como los insumos o inversiones en maquinaria, así como los asociados con el talento humano; es recomendable ubicarlo dentro de periodos de tiempo, de tal forma que sea más fácil hacerse una idea de los flujos de efectivo necesarios.
                p(numero="5" titulo="Objetivos alcanzados") Presentar los resultados alcanzados con las estrategias implementadas, contrastadas con los egresos, para estimar la relación costo - beneficio. Se recomienda incluir gráficas y tablas que faciliten la comprensión del contenido.
                p(numero="6" titulo="Falencias o limitaciones") Detallar las situaciones imprevistas que llevaron a limitar la aplicación o modificación de las estrategias. Si es posible, medir el impacto de estas limitaciones tanto en resultados como en las variaciones respecto a la inversión.
                p(numero="7" titulo="Proyecciones") Incluir las estimaciones sobre los resultados a obtener en fechas posteriores a la de la presentación del informe. En caso de que se deban modificar las estrategias debido al bajo nivel de efectividad, ofrecer una introducción a lo que se espera implementar posteriormente.  
        .col-lg-4.d-flex.align-items-center
            img(src='@/assets/curso/tema3/img3.svg', alt='Texto que describa la imagen')
    separador
    #t_3_2
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.2 Resultados
    .row.align-items-center.mb-5
      .col-lg
        .row.align-items-start.mb-4(data-aos="fade-right")
          .col
            p.mb-4 La medición de los resultados depende esencialmente de dos factores: los #[b objetivos propuestos] o estimados y su #[b nivel de cumplimiento]. Un plan de mercadeo debe apuntar siempre a un mismo objetivo general, la maximización de las utilidades, a través de la aplicación de medidas eficientes que minimicen costos o de la mejora en los indicadores de ventas alcanzadas.    
        .cajon.color-acento-contenido.p-4(data-aos="fade-left").mb-5
          p.mb-0 Es así como se debe incluir en el informe una comparativa que contemple las métricas y las contraste antes y después de la aplicación del plan, como con los resultados proyectados previos a la aplicación.
      .col-lg-auto
        figure
          img(src='@/assets/curso/tema3/img4.png')(data-aos="fade-right")
    p Los siguientes elementos constituyen los pilares fundamentales en la medición de los resultados de un plan de mercadeo:
    .row.mt-5.justify-content-center.align-items-center(data-aos="fade-left").mb-5
        .col-lg-6
          .row.mb-5
            .col-md-12.mb-5.mb-md-0
              LineaTiempoD.color-primario
                p(numero="1" titulo="Mejora del canal de ventas") Robustecer bases de datos de clientes otorga nuevas posibilidades de crecimiento de ventas. Contar con datos de contacto de terceros, interesados en bienes ofertados es considerada una de las mejores herramientas para aumentar el alcance de la empresa, puesto que son potenciales clientes que repercutirán en resultados posteriores.
                p(numero="2" titulo="Nuevos clientes") Las estrategias del plan de mercadeo deben facilitar la consecución de nuevos clientes. Es uno de los indicadores más importantes puesto que conservando los demás, esto se traduce en mayores niveles de ventas. Esta métrica resulta más fácil de medir, cuando la frecuencia de recompra de los productos es muy baja. 
                p(numero="3" titulo="Percepción de la marca") Parámetro de naturaleza cualitativa, no existe una forma precisa de cuantificar la aceptación de los productos y la buena imagen de la empresa; pero esto no significa que no tenga validez y no resulte un indicador relevante para la gestión comercial. Posicionar los productos en un mercado competitivo resulta una tarea compleja pero gratificante y productiva, puesto que facilita la proyección en nuevos mercados o la incursión de nuevos productos.               
                p(numero="4" titulo="Retorno de la inversión") Las erogaciones del diseño y ejecución del plan de mercadeo debe retornarse a través de la mejora de los indicadores. De lo contrario, resultaría más favorable no desgastarse implementando medidas ineficaces. Se debe medir el valor de la inversión y contrastarlo con los beneficios cuantificables obtenidos a través de la ejecución de las estrategias comerciales. 
        .col-lg-6.d-flex.align-items-center
            img(src='@/assets/curso/tema3/img5.png', alt='Texto que describa la imagen')
    .row.justify-content-center.mb-5
        .col-lg-12
          .cajon.color-acento-contenido.p-4
            p.mb-0 No existe una única forma de medir los resultados, puesto que los métodos pueden variar según el tipo de producto vendido o el elemento que se espera dimensionar. 
    p Observe con atención la siguiente tabla, que presenta el sistema que goza de mayor aceptación, y consiste en la presentación de los resultados de forma comparativa, midiendo la variación absoluta y relativa de cada rubro relevante:
    .titulo-sexto.color-acento-contenido
      p.mb-0 #[b Tabla 3]. Informe histórico de ventas
    .tabla-a.color-primario.mb-5(data-aos="fade-right")
      table
        thead
          tr 
            th(colspan="5").text-center Informe histórico de ventas  
        tbody        
          tr(style="background-color: #F6F6F6")
            td(rowspan="2")
            td(rowspan="2").text-center #[b Año 20x1]
            td(rowspan="2").text-center #[b Año 20x0]
            td(colspan="2").text-center #[b Variación]
          tr(style="background-color: #F6F6F6")
            td.text-center $
            td.text-center %
          tr
            td 
              h5.text-center Producto A
            td 
              p.mb-4.text-center.mb-0 15.000
            td 
              p.mb-4.text-center.mb-0 13.000
            td 
              p.mb-4.text-center.mb-0 2000
            td 
              p.mb-4.text-center.mb-0 15,4%
          tr(style="background-color: #F6F6F6")
            td 
              h5.text-center Producto B
            td 
              p.mb-4.text-center.mb-0 2.500
            td 
              p.mb-4.text-center.mb-0 2.200
            td 
              p.mb-4.text-center.mb-0 300
            td 
              p.mb-4.text-center.mb-0 13,6%
          tr
            td 
              h5.text-center Producto C

            td.mb-4.text-center.mb-0 3.000
              
            td.mb-4.text-center.mb-0 3.200
             
            td.mb-4.text-center.mb-0 -200
              
            td.mb-4.text-center.mb-0 -6,3%
          tr(style="background-color: #F6F6F6")
            td 
              H5.text-center Total
            td 
              p.mb-4.text-center.mb-0 20.500
            td 
              p.mb-4.text-center.mb-0 18.400
            td 
              p.mb-4.text-center.mb-0 2.100
            td 
              p.mb-4.text-center.mb-0 11,4%
    .row.justify-content-center.mb-5
      .col-lg-12
        .cajon.color-acento-contenido.p-4
          p.mb-0 De la tabla 3 pueden extraerse múltiples apreciaciones que contribuyen a medir la efectividad de las estrategias aplicadas, por ejemplo, si las acciones relativas al producto C difieren de los demás deben replantearse a futuro, puesto que las variaciones negativas indican una tendencia negativa en el nivel de ventas. Situación contraria se observa con los productos A y B que mostraron un crecimiento de un año a otro.
    p.mb-4.text-center En relación con los resultados tenga en cuenta los aspectos clave que se enuncian a continuación: 
    .row.justify-content-center.align-items-center(data-aos="fade-left")
      .col-lg-12
        SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
          .tarjeta.tarjeta.bg-color6.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema3/img6.png', alt='Texto que describa la imagen' )
            h4.text-center Evolución
            p.text-center El análisis puede ser tan detallado y diverso como los analistas lo consideren; para este caso, podría incluirse la evolución respecto a años anteriores, así como la variación de los precios de venta históricos.
          .tarjeta.tarjeta.bg-color6.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema3/img7.png', alt='Texto que describa la imagen' )
            h4.text-center Aislamiento de aspectos clave
            p.text-center Existen otros aspectos que podrían influir sobre el producto y, por lo tanto, convendría aislar los aspectos clave para no juzgar las estrategias por otros factores ajenos a la gestión comercial. 
          .tarjeta.tarjeta.bg-color6.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema3/img8.png', alt='Texto que describa la imagen' )
            h4.text-center Ejemplo de ventas mejoradas
            p.text-center Un ejemplo de lo anterior es que las ventas pueden haberse visto mejoradas debido al cierre de una marca competidora en este mercado.
          .tarjeta.tarjeta.bg-color6.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema3/img9.png' alt='AvatarTop')
            h4.text-center Análisis histórico
            p.text-center En el caso anterior, se mide la evolución entre dos años, lo que redunda en un análisis histórico que mide la evolución en un periodo de tiempo determinado. 
          .tarjeta.tarjeta.bg-color6.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema3/img10.png' alt='AvatarTop')
            h4.text-center Medición de la efectividad
            p.text-center No obstante, otra forma muy recurrente de medir la efectividad de los programas es contrastando lo efectivamente alcanzado con las expectativas descritas en el diseño y en las etapas tempranas de implementación.
    p La siguiente tabla presenta un comparativo como el mencionado en los aspectos clave:
    .titulo-sexto.color-acento-contenido
      p.mb-0 #[b Tabla 4]. Informe de ejecución
    .tabla-a.color-primario.mb-5(data-aos="fade-right")
      .tabla-b__header
        h4.mb-0 Informe de ejecución
      table         
        tr(style="background-color: #F6F6F6")
          td 
            h5
          td 
            h5.mb-4.text-center.mb-0 Incremento obtenido
          td 
            h5.mb-4.text-center.mb-0 Incremento proyectado
          td
            h5.mb-4.text-center.mb-0 Cumplimiento             
        tr
          td 
            h5.text-center Producto A
          td 
            p.mb-4.text-center.mb-0 2.000
          td 
            p.mb-4.text-center.mb-0 2.000
          td 
            p.mb-4.text-center.mb-0 100%
          
        tr(style="background-color: #F6F6F6")
          td 
            h5.text-center Producto C
          td 
            p.mb-4.text-center.mb-0 300
          td 
            p.mb-4.text-center.mb-0 800
          td 
            p.mb-4.text-center.mb-0 38%
          
        tr
          td 
            h5.text-center Producto C

          td 
            p.mb-4.text-center.mb-0 -200
          td 
            p.mb-4.text-center.mb-0 1000
          td 
            p.mb-4.text-center.mb-0 -20%
          
        tr(style="background-color: #F6F6F6")
          td 
            H5.text-center Total
          td 
            p.mb-4.text-center.mb-0 2.100
          td 
            p.mb-4.text-center.mb-0 3.800
          td 
            p.mb-4.text-center.mb-0 55%
         
    p.mb-5 La forma de interpretar sigue siendo similar a la anterior; pero las conclusiones derivadas de este análisis son diferentes. Aquí se mide la efectividad en relación con las proyecciones, en lugar de con datos históricos. Así, el producto A resultó potencialmente beneficiado con las estrategias, pues se alcanzó el cumplimiento total de lo presupuestado. El producto B, por otra parte, tuvo un nivel de cumplimiento discreto, lo que significa que las medidas fueron efectivas; pero muy por debajo de lo esperado. Finalmente, el producto C redujo sus ventas, lo que implica que las medidas fueron inadecuadas y no tuvieron la aceptación comercial esperada.
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-5.mb-lg-0
        figure
          img(src='@/assets/curso/tema3/img11.png', alt='Texto que describa la imagen').mb-5
      .col-lg-7.mb-5
          p Estos resultados usualmente vienen acompañados de un margen de tolerancia. En este sentido:
          ul.lista-ul
            li.mb-3 
              i.fas.fa-angle-right
              p.mb-0 Una estrategia puede ser considerada como acertada si se alcanza un porcentaje significativo de cumplimiento.
            li.mb-3 
              i.fas.fa-angle-right
              p.mb-0 Así, un nivel de consecución del 80% podría considerarse satisfactorio para algunos analistas, mientras para otros, solo lo sería con un cumplimiento del 95% en adelante.
            li.mb-3 
              i.fas.fa-angle-right
              p.mb-0 La forma de abordar estas interpretaciones y trasladarlas al informe ejecutivo contendrán un componente altamente subjetivo; puesto que los márgenes de tolerancia varían entre unos analistas y otros.
            li.mb-3 
              i.fas.fa-angle-right
              p.mb-0 El informe deberá complementarse con los demás factores que pudieron tener influencia sobre los resultados, así como las expectativas para implementaciones futuras.
            li.mb-3 
              i.fas.fa-angle-right
              p.mb-0 Finalmente, se debe concluir con las apreciaciones más relevantes y las medidas correctivas a aplicar o el rediseño de estrategias que fracasaron en su propósito.
    
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
