<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero
        span 1
      h1 Plan de mercadeo
    .row.justify-content-center.align-items-center
      .col-lg-12
        .bloque-texto-g.color-custom-2.p-3.p-sm-4.p-md-5.mb-5.d-none.d-lg-block
          .bloque-texto-g__img.m-left(data-aos="fade-left")(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img1.png')})`}"
        )
          .bloque-texto-g__texto.p-5(data-aos="fade-right")
            p.mb-3 Un producto con un diseño llamativo y con una buena calidad cuenta con los elementos más importantes para ser aceptado por sus clientes e incluso, fidelizarlos para hacer recurrentes las ventas. No obstante, no basta con ello, es importante establecer estrategias que permitan definir el tipo de cliente al que se espera llegar y programar las tareas necesarias para convencerlos de adquirir los productos de forma recurrente.   
        .bloque-texto-a.color-custom-3.p-md-0.mb-5.d-block.d-lg-none
          .row.m-4.align-items-center.justify-content-between
            .col-lg-9(data-aos="fade-right")
              .bloque-texto-a__texto.p-5.my-5
                p Un producto con un diseño llamativo y con una buena calidad cuenta con los elementos más importantes para ser aceptado por sus clientes e incluso, fidelizarlos para hacer recurrentes las ventas. No obstante, no basta con ello, es importante establecer estrategias que permitan definir el tipo de cliente al que se espera llegar y programar las tareas necesarias para convencerlos de adquirir los productos de forma recurrente.   
            .col-lg-3.mb-3.mb-lg-0(data-aos="fade-left")
              figure
                img(src='@/assets/curso/tema1/img1.png' alt='', style="width:400px; display:block; margin:-1rem 0 ;")
    
    .bg1
      .row.justify-content-center.mb-5
        .col-lg-12
          .cajon.color-acento-contenido.p-4
            p.mb-0 El plan de mercadeo es el documento que abarca esta y otras medidas necesarias para garantizar el éxito comercial de un buen producto o servicio. 
      .row.justify-content-center.align-items-end.mb-5(data-aos="fade-left")
        .col-lg-6.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/tema1/img3.png', alt='Texto que describa la imagen')
        .col-lg-6.mb-5
            p El plan de mercadeo implica:
            ul.lista-ul
              li.mb-0 
                i.fas.fa-angle-right
                p.mb-0 Conocer la empresa y todos sus procesos.
              li.mb-0 
                i.fas.fa-angle-right
                p.mb-0 Conocer el ambiente en el que se desarrolla la operación empresarial.
              li.mb-0 
                i.fas.fa-angle-right
                p.mb-0 Conocer la población objetivo, el nicho de mercado.
              li.mb-0 
                i.fas.fa-angle-right
                p.mb-0 Conocer la competencia a la que se enfrentará la organización.
        .col-lg-10.mb-3
          p.pt-5 Es vital conocer la competencia a la que se enfrentará la organización, no solo a nivel global sino por cada producto ofrecido en su portafolio.
        .col-lg-6.d-flex.justify-content-center
          figure
            img(src='@/assets/curso/tema1/img4.svg', alt='Texto que describa la imagen')
      .bg2
        .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
          .col-lg-12
            p.text-center En relación con el plan de mercadeo tenga en cuenta los siguientes elementos:
          .col-lg-5.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema1/img5.png', alt='Texto que describa la imagen')
          .col-lg-5.mb-5.mt-5
            h4 Enfoques
            p Existen diversos enfoques para abordar el plan de mercadeo, al igual que medidas que se pueden implementar según cada situación.
            h4 Herramientas efectivas
            p En un mercado muy competido, ajustar el precio puede ser una de las herramientas más efectivas; pero si el bien es un producto suntuoso, tal vez resulte más apropiado un diseño más atractivo que evoque sentimientos de satisfacción o éxito.
            h4 Estrategias acertadas
            p Definir las estrategias acertadas puede convertirse en un proceso de ensayo y error, puesto que al tratar de manipular variables que se salen del control de la administración, la forma en la que reaccione el mercado a cada propuesta puede terminar siendo impredecible.

    separador
    #t_1_1
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Estructura
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-6.mb-5
        p El diseño de un plan de mercadeo puede variar entre cada empresa; al fin y al cabo la forma en la que se abordan las estrategias comerciales y el sustento tras ellas puede depender de multitud de factores, como el tamaño de la organización, el tipo o la cantidad de productos ofrecidos al mercado o la escala de la oferta.
        p Sin embargo, generalmente, existen elementos comunes en este tipo de documentos, aun cuando la terminología varíe el propósito detrás de cada uno de ellos suele coincidir.
        p Un adecuado plan de mercadeo debe estar soportado por lo menos en los siguientes cuatro elementos fundamentales: 
        ul.lista-ul
          li.mb-3 
            i.fas.fa-angle-right
            p.mb-0 Un análisis del entorno socioeconómico.
          li.mb-3
            i.fas.fa-angle-right
            p.mb-0 La evaluación de la competencia.
          li.mb-3 
            i.fas.fa-angle-right
            p.mb-0 Un estudio del mercado y la demanda.
          li.mb-0 
            i.fas.fa-angle-right
            p.mb-0 Un análisis de la empresa.
      .col-lg-6.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema1/img6.png', alt='Texto que describa la imagen')
    ol.lista-ol--cuadro
      li 
        .lista-ol--cuadro__vineta
          span 
        h3 Análisis del entorno socioeconómico.
    p El primer paso para establecer el camino a tomar, en el ámbito mercantil, es ubicarse dentro del entorno económico y social. Dependiendo del tipo de producto o servicio que se ofrezca, la empresa se clasifica dentro de uno de los cuatro grandes sectores económicos.
    p.mb-5 Aprópiese de los aspectos que definen y describen los sectores económicos, señalados en el siguiente recurso: 
    h5.text-center.m-4 Sectores económicos
    .tarjeta.tarjeta--gris.p-4.bg3.mb-5.p-5(data-aos="zoom-in-down")    
      PasosB.color-acento-botones
        .row(titulo="")
          .col-lg-6.mb-4.mb-md-0
            h5 1. Primario- Extractivo
            p Comprende actividades asociadas con explotación de los recursos naturales. Incluye agricultura, ganadería o minería. Las unidades productivas agroempresariales en principio encajan en este sector. Así como cualquier empresa dedicada a la cría de ganado, producción de leche o extracción de carbón, y demás tareas que involucren un proceso mayoritariamente extractivo.
          .col-lg-6
            figure
              img(src='@/assets/curso/tema1/img8.png', alt='Texto que describa la imagen')
        .row(titulo="")
          .col-lg-6.mb-4.mb-md-0
            h5 2. Secundario- Industrial
            p Empresas dedicadas a la transformación de materias primas en productos terminados. La actividad industrial puede presentarse esencialmente en dos formas, la producción masiva, a través de procesos estandarizados complejos que requieren inversiones significativas en maquinaria y equipo, o por medio de las actividades de artesanía, que trabajan bajo la misma mecánica; pero en una menor escala con procesos más simplificados.  Empresas del sector: construcciones, producción textil, elaboración de productos bioquímicos y cualquier otra en la que se dé mayor relevancia a la transformación de materiales en productos terminados diferenciados.
          .col-lg-6
            figure
              img(src='@/assets/curso/tema1/img9.png', alt='Texto que describa la imagen')
        .row(titulo="")
          .col-md-6.mb-4.mb-md-0
            h5 3. Terciario- Comercial/Servicios
            p Empresas que adquieren bienes para venderlos sin someterlos a transformaciones significativas. Puede variar presentación, tamaños, colores, etc. Se concibe en este grupo a tiendas o grandes superficies, almacenes de ropa, electrodomésticos, entre otros. Además de la comercialización, este sector involucra las actividades de servicios donde prima el factor material así como el uso de herramientas especializadas, transporte de personas o materiales, reparaciones locativas o electrónicas,  intermediación inmobiliaria, etc.
          .col-lg-6
            figure
              img.img-t(src='@/assets/curso/tema1/img10.png', alt='Texto que describa la imagen')
        .row(titulo="").mx-auto
          .col-md-6.mb-4.mb-md-0
            h5 4. Cuaternario- Información
            p Su concepción es mucho más reciente y surge producto del desarrollo constante de la dinámica económica. Este sector comprende la prestación de servicios donde prima el factor intelectual sobre el material, y ha tomado especial relevancia debido a la forma en la que participa e interactúa con los demás sectores, puesto que potencia la efectividad de la gestión y producción de estos. En este segmento se incluyen empresas dedicadas a la investigación y desarrollo, a las tecnologías de la información, a la innovación o a la consultoría especializada.
          .col-lg-6
            figure
              img.img-t(src='@/assets/curso/tema1/img11.png', alt='Texto que describa la imagen').mx-auto
    p.py-3 Una vez se defina el sector económico al que pertenece la empresa, se debe buscar toda la información relevante de este, para analizar potenciales oportunidades y amenazas. Existen diversas bases de datos que aportan información estadística útil y práctica; en Colombia, la entidad líder en este marco es DANE (Departamento Administrativo Nacional de Estadística), que recolecta información útil para el diseño de políticas públicas, involucrando temas demográficos, sociales y económicos. 
    .row.justify-content-center.mb-5(data-aos="fade-right")
      .col-lg-12
        .cajon.color-acento-contenido.p-4
          p.mb-0 El estudio del sector implica identificar las tendencias de crecimiento o desarrollo, para saber si el producto tiene un buen margen de evolución, apalancado por las ventajas del sector. En ese proceso también pueden encontrarse amenazas, como regulaciones estrictas por parte del estado o aversión de parte de la población a prácticas que sean consideras controversiales.       
    ol.lista-ol--cuadro
      li 
        .lista-ol--cuadro__vineta
          span 
        h3 Análisis de la competencia.
    p Salvo que se diseñe o elabore un producto completamente innovador es muy probable que en el mercado al que se piense involucrar ya existan otros bienes o servicios que suplan las mismas necesidades. Esto se erige como una de las principales amenazas de cualquier empresa nueva, la competencia.
    p Cuando se trata de nuevos emprendimientos la competencia siempre cuenta con una gran ventaja, puesto que su historia lo respalda; ya cuentan con una aceptación en el mercado y de manera natural, las personas suelen ser renuentes a los cambios. 
    p En lo relacionado con el análisis de la competencia tenga en cuenta las siguientes generalidades:
    .tarjeta.tarjeta--azul.p-5.mb-5
      SlyderA(tipo="b")(data-aos="fade-right")
        .row.align-items-center.justify-content-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Generación del plan de mercado]
            p El plan de mercadeo debe plantearse previo a cualquier inversión significativa o trabajo de fondo, pues la viabilidad de una organización depende en gran medida de los resultados comerciales que se esperen. 
          .col-lg-8
            figure
              img.img-t(src='@/assets/curso/tema1/img12.png').mx-auto
        .row.align-items-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Escala de competición y tradición histórica]
            p Si se destina una cantidad de recursos muy elevada para crear, por ejemplo, una bebida gaseosa que compita con titanes del marketing como Coca Cola, es posible que los resultados efectivos nunca alcancen las expectativas, puesto que este mercado se encuentra fuertemente dominado por un competidor de escala inmensa y de una tradición histórica que pocas empresas tienen en el mundo.
          .col-lg-8
            figure
              img.img-t(src='@/assets/curso/tema1/img13.png').mx-auto
        .row.align-items-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Plan detallado]
            p Para sobresalir en un mercado, la empresa debe ser muy estratégica, contar con un plan de acción muy detallado que involucre no solo las tareas a llevar a cabo sino también los recursos necesarios, de tal forma que el capital se invierta de forma organizada, garantizando un flujo constante que no deje las estrategias implementadas a media marcha.
          .col-lg-8
            figure
              img.img-t(src='@/assets/curso/tema1/img14.png').mx-auto
        .row.align-items-center(data-aos="fade-right")
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Evaluación de la competencia]
            p En esta fase es muy importante indagar a fondo las empresas que se consideren como competencia, esto significa una evaluación de sus estados financieros, un estudio de sus diseños y productos, un análisis de su cadena de distribución e incluso, el abordaje a sus clientes para identificar la concepción que se tiene de estas en el mercado objetivo.
          .col-lg-8
            figure
              img.img-t(src='@/assets/curso/tema1/img15.png').mx-auto
    p.mb-4 Pero ¿cómo evaluar a la competencia? El siguiente listado presenta algunos elementos clave, analícelos y procure llevar registro de lo más destacado en su libreta personal de apuntes:
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul1")(data-aos="fade-right").justify-content-center
      .row(titulo="Antecedentes")(data-aos="fade-right")
        .col-md-6.align-items-center
          h5.ps-5 Antecedentes
          p.ps-5 ¿Cómo nacen estas empresas, cuál ha sido su trayectoria y cuál es su magnitud en la actualidad?
        .col-lg-5.col-md-6.col-12.p-0
          img(src='@/assets/curso/tema1/img16.png')
      .row(titulo="Tipo de empresa")
        .col-md-6.align-items-center
          h5.ps-5 Tipo de empresa
          p.ps-5 Si son relevantes dentro del mercado, obtener información de ellas puede redundar en una guía de aquello a lo que se puede llegar si se toma decisiones correctas. De ellas se pueden tomar las buenas prácticas que se consideren efectivas para la consecución de objetivos comerciales.
        .col-lg-5.col-md-6.col-12.p-0
          img(src='@/assets/curso/tema1/img17.png')
      .row(titulo="Portafolio de productos")
        .col-md-6.align-items-center
          h5.ps-5  Portafolio de productos
          p.ps-5 La mayoría de las empresas consolidadas en el mercado lo logran a través de una oferta variada de productos. Es importante evaluar cuántos de ellos compiten con los del emprendimiento, así como la forma en la que estas variaciones repercuten en la demanda, de allí pueden surgir ideas respecto a la forma en la que se debe abordar el mercado y cómo ampliar las posibilidades del negocio.
        .col-lg-5.col-md-6.col-12.p-0
          img(src='@/assets/curso/tema1/img18.png')
      .row(titulo="Estructura organizacional")
        .col-md-6.align-items-center
          h5.ps-5 Estructura organizacional
          p.ps-5 La gestión de una empresa de la competencia puede dar luces a la forma de administrar la propia, es así como resulta conveniente analizar sus políticas comerciales, su estructura organizacional o su énfasis en la innovación.
        .col-lg-5.col-md-6.col-12.p-0
          img(src='@/assets/curso/tema1/img19.png')
    p.mb-5 Una vez se cuente con la información suficiente respecto a la competencia, procede una etapa de análisis y evaluación de medidas para saber cómo integrarse en el mercado, siendo lo suficientemente diferenciadores para sobrevivir a las ventajas competitivas de los demás. Las expectativas deben ser realistas, esperar apoderarse de un mercado con solo trabajo duro no es lo más prudente, no se pueden subestimar los esfuerzos que otros han dedicado para estar donde están.
    .row.justify-content-center.mb-5(data-aos="fade-right")
      .col-lg-10
        .tarjeta--container.row.mb-5
          .col-md.tarjeta.color-secundario.border-tarjetas_t6.p-5.mb-5.mb-lg-0
            .row.justify-content-center
              .col-5
                figure
                img.img505(src='@/assets/curso/tema1/img20.png', alt='Texto que describa la imagen')
            p.pt-5 Otra estrategia que amerita aplicar en el análisis de la competencia es una comparativa con las demás empresas para determinar las diferencias más representativas en aspectos tales como tecnología, situación financiera, procesos productivos y buen nombre. 
          .col-md.tarjeta.color-secundario.border-tarjetas_t6.tar1.p-5
            .row.justify-content-center
              .col-5
                figure
                  img.img505(src='@/assets/curso/tema1/img21.png', alt='Texto que describa la imagen')
            p.pt-5 Medir las diferencias y categorizarlas puede facilitar la priorización de medidas, de tal forma que se aborden las debilidades más prominentes en el corto plazo, haciendo un uso inteligente de los recursos disponibles.
    ol.lista-ol--cuadro
      li 
        .lista-ol--cuadro__vineta
          span 
        h3 Estudio del mercado y la demanda.
    p Sin importar lo saturado del mercado siempre existirán necesidades insatisfechas o inconformidades por parte de los clientes. Esto quiere decir que siempre habrá cabida para una empresa más en el sector, pero dependerá de su capacidad el penetrar el mercado y lograr una porción de la demanda.
    p Para lograr incursionar de forma exitosa en el mercado se deben tener en cuenta aspectos de suma importancia como los que se enuncian a continuación:
    .row.mt-5(data-aos="fade-right")
        .col-lg-6
          .row.mb-5
            .col-md-12.mb-5.mb-md-0
              LineaTiempoD.color-primario
                p(numero="1" titulo="Acercamiento a destinatarios") Efectuar un acercamiento a la población objetivo y determinar las necesidades a través de la indagación.
                p(numero="2" titulo="Identificación de eventos") Algunas de las situaciones que se pueden identificar son baja calidad en los productos de la competencia, precios poco favorables, aversión por factores culturales a ciertas características propias de los productos existentes o hábitos de consumo que no han sido tenidos de cuenta.                
                p(numero="3" titulo="Importancia de la identificación") Una correcta identificación puede abrir una ventana de oportunidad a crear un producto adecuado para algunas de estas necesidades, creando una ventaja competitiva en el medio.                
                p(numero="4" titulo="Cuantificar la demanda") En esta fase resulta prioritario cuantificar la demanda del producto que se ofrecerá al mercado.
                p(numero="5" titulo="Identificación de hábitos de consumo") Existen diversas posturas desde la cual abordar la demanda; pero la más directa consiste en la identificación de los hábitos de consumo del bien o servicio a ofertar, es decir, la periodicidad con la que se compraría y utilizaría, así como el tipo de público al que está dirigido. 
                p(numero="6" titulo="Estudio demográfico") A lo anterior se debe sumar un estudio demográfico donde, a partir de las estadísticas disponibles, se determine cuántas personas en aquella población cumplen el criterio para ser clientes. Esto puede dar un volumen aproximado de ventas totales.
        .col-lg-6.d-flex.align-items-center
          img(src='@/assets/curso/tema1/img22.png', alt='Texto que describa la imagen').mb-5
    P Analice la siguiente situación ejemplo y determine los pasos que en ella se siguen para lograr la incursión en un mercado objetivo:
    .row.mt-5
        .col-lg-6.d-flex.align-items-center.mb-5
          img(src='@/assets/curso/tema1/img23.png', alt='Texto que describa la imagen')
        .col-lg-6
          .row.mb-5
            .col-md-12.mb-5.mb-md-0
              LineaTiempoD.color-primario
                .row(numero="1" titulo="Indagación")
                  .col-md-4.pt-2.mb-3
                    figure
                      img(src='@/assets/curso/tema1/img24.png', alt='Texto que describa la imagen')
                  .col-md-8.mb-4.mb-md-0
                    p.mb-2 Si se espera vender tomate en una región aledaña de donde se ubican los cultivos, se puede indagar sobre el consumo de tomate en los hogares que habitan dicha región. Con ello se puede estimar una demanda semanal promedio. 
                .row.pt-2(numero="2" titulo="Establecimiento de cantidad de consumidores") 
                  .col-md-4.pt-2.mb-3
                    figure
                      img(src='@/assets/curso/tema1/img25.png', alt='Texto que describa la imagen')
                  .col-md-8.mb-4.mb-md-0
                    p.mb-2 Luego, a partir de los datos publicados por la alcaldía de ese municipio o directamente del DANE se puede establecer el número de familias que viven en la actualidad. Así la cantidad de tomate que consume una familia, multiplicada por el número de familias de ese municipio, dan como resultado la demanda total de tomate en esa locación.
                .row.pt-2(numero="3" titulo="Identificación de la demanda cubierta") 
                  .col-md-4.pt-2.mb-3
                    figure
                      img(src='@/assets/curso/tema1/img29.png', alt='Texto que describa la imagen')
                  .col-md-8.mb-4.mb-md-0
                    p.mb-2 Una vez se tenga esta estimación, hay que identificar cuánta demanda ya se encuentra cubierta por la competencia, y apuntar o bien a apropiarse de una porción de esa demanda, o a suplir aquella que no ha sido satisfecha hasta ahora. 
                .row.pt-2(numero="4" titulo="Porción de mercado objetivo") 
                  .col-md-4.pt-2.mb-3
                    figure
                      img(src='@/assets/curso/tema1/img26.png', alt='Texto que describa la imagen')
                  .col-md-8.mb-4.mb-md-0
                    p.mb-2 Lograr una porción del mercado, según la escala de este, puede representar una oportunidad valiosa que garantice la subsistencia de la empresa en el tiempo. No siempre hace falta crear necesidades nuevas, solo basta con tomar una porción del mercado que se encuentre desatendida o capturar clientes que no tienen un fuerte sentido de fidelidad con los productos de la competencia.
                .row.pt-2(numero="5" titulo="Visualización de la demanda") 
                  .col-md-4.pt-2.mb-3
                    figure
                      img(src='@/assets/curso/tema1/img27.svg', alt='Texto que describa la imagen')
                  .col-md-8.mb-4.mb-md-0
                    p.mb-2 La demanda suele visualizarse como un gran pastel, donde cada competidor espera quedarse con una porción. La figura representa gráficamente la ambición propia de cada agente productor por apropiarse de una parte del mercado.
                .row.pt-2(numero="6" titulo="Evitar demanda sobreestimada") 
                  .col-md-4.pt-2.mb-3
                    figure
                      img(src='@/assets/curso/tema1/img28.png', alt='Texto que describa la imagen')
                  .col-md-8.mb-4.mb-md-0
                    p.mb-2 Para evitar una sobreestimación de la demanda se debe acudir a los sistemas objetivos de medición de necesidades de la población. Las herramientas tecnológicas actuales facilitan la labor de recolección de información con bajo costo. Efectuar encuestas a personas ubicadas en el mercado objetivo, indagar volúmenes de venta en zonas de oferta o llevar a cabo estudios de investigación de mercados puede dar una cifra más realista con la cual trabajar.
    ol.lista-ol--cuadro
      li 
        .lista-ol--cuadro__vineta
          span 
        h3 Análisis de la empresa.
    p Para la última etapa del plan de mercadeo hace falta analizar los elementos clave que componen la empresa como factor productivo. El sector económico, la competencia y la demanda son todas variables sobre las que se puede indagar para tomar medidas que contrarresten las desventajas; pero sobre las que siempre existirá un fuerte factor de incertidumbre. Es entonces, en los factores endógenos donde la empresa goza de un mayor margen de maniobra. 
    p En cuanto al análisis de la empresa, existen diversos elementos a tener en cuenta. Enseguida se muestran algunos de los más importantes:
    .row.mt-5.align-items-center
        .col-lg-6
          .row.mb-5(data-aos="fade-right")
            .col-md-12.mb-5.mb-md-0
              LineaTiempoD.color-primario
                p(numero="1" titulo="Producto") ¿Qué tipo de producto se va a vender al mercado?, ¿cumple con las necesidades observadas en los clientes potenciales? Se debe evaluar si existe una variedad suficiente de opciones para cada tipo de comprador, también puede verificarse si su presentación es atractiva y, en caso de que aplique, si cumple con la normatividad correspondiente. 
                p(numero="2" titulo="Situación financiera") Validar que los recursos de la empresa son los necesarios para mantener una operación continua, si las estrategias a implementar pueden costearse o si existen mecanismos que garanticen suplir las necesidades de producción a lo largo del tiempo. Evaluar sistemas de financiación con el sector financiero o con los mismos proveedores y, de forma paralela, determinar las políticas de recaudo de las ventas a crédito si hay lugar a ellas.
                p(numero="3" titulo="Importancia de la identificación") Una correcta identificación puede abrir una ventana de oportunidad a crear un producto adecuado para algunas de estas necesidades, creando una ventaja competitiva en el medio.                
                p(numero="4" titulo="Cuantificar la demanda") En esta fase resulta prioritario cuantificar la demanda del producto que se ofrecerá al mercado.
        .col-lg-6.d-flex.align-items-center
          img(src='@/assets/curso/tema1/img30.png', alt='Texto que describa la imagen').mb-4
    .row.mb-5
      .col-12.bg-color4.p-4
        .row.align-items-center.justify-content-center
          .col-lg-1.mb-3
            figure
              img.img-t(src='@/assets/curso/tema1/img31.png').mx-auto(data-aos="fade-right").mx-auto
          .col-lg-11
            h5 Para tener presente
            p.mb-0 La conjunción de las cuatro fases del plan de mercadeo otorga un panorama claro y detallado de los aspectos internos y externos que tienen relación con la gestión comercial. Lograr aprovechar las ventajas y oportunidades descubiertas para afrontar la competencia y suplir las necesidades de la demanda, no solo se convierte en el objetivo primordial del plan de mercadeo, sino en el propósito que garantiza la subsistencia de la organización. 
    .row.justify-content-center(data-aos="fade-right")
      .col-lg-12
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1/img32.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Finalmente, como herramienta de apoyo en la gestión estratégica es recomendable hacer uso de la matriz DOFA (Debilidades, Oportunidades, Fortalezas y Amenazas), con la cual se pueden ubicar los puntos a favor y en contra que tiene la empresa para alcanzar sus objetivos. Lo que se logra con ella es conjugar los diferentes escenarios identificados y proponer estrategias que mitiguen los riesgos, potencien las fortalezas y ataquen las amenazas que surgen en el ambiente competitivo.
    p.mb-4 Reconozca en la siguiente tabla el esquema elemental de una matriz DOFA, en la que las casillas internas deben contener las estrategias para aprovechar la conjunción de las situaciones que se presentan en sus extremos:
    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      p.mb-0 #[b Tabla 1]. Matriz DOFA
    .tabla-a.color-primario(data-aos="fade-right")
          table
            thead
              tr(style="background-color: #CED371")
                th 
                  h5 Matriz DOFA
                  h5 Área comercial
                th 
                  h5 FORTALEZAS
                  h5 * Fortaleza 1
                  h5 * Fortaleza 2
                  h5 * Fortaleza 3
                  h1.text-center F
                th
                  h5 DEBILIDADES
                  h5 * Debilidad 1
                  h5 * Debilidad 2
                  h5 * Debilidad 3
                  h1.text-center D
            tbody
              tr
                td 
                  p.text-center OPORTUNIDADES
                  p.text-center • Oportunidad  1
                  p.text-center • Oportunidad  2
                  p.text-center • Oportunidad  3
                  h1.text-center O
                td 
                  p.mb-4.text-center.mb-0 • Conjugar una fortaleza y una oportunidad = Estrategia #[b FO].
                  p.text-center.mb-0 • Conjugar otra fortaleza y otra oportunidad = Otra Estrategia #[b FO].
                td 
                  p.mb-4.text-center.mb-0 • Conjugar una debilidad y una oportunidad = Estrategia #[b DO].
                  p.text-center.mb-0 • Conjugar otra debilidad y otra oportunidad = Otra Estrategia #[b DO].
              tr(style="background-color: #F6F6F6")
                td 
                  p.text-center AMENAZAS
                  p.text-center • Amenaza 1
                  p.text-center • Amenaza 2
                  p.text-center • Amenaza 3
                  h1.text-center A
                td 
                  p.mb-4.text-center.mb-0 • Conjugar una fortaleza y una amenaza = Estrategia #[b FA].
                  p.text-center.mb-0 • Conjugar otra fortaleza y otra amenaza = Otra estrategia #[b FA].
                td 
                  p.mb-4.text-center.mb-0 • Conjugar una debilidad y una amenaza = Estrategia #[b DA].
                  p.text-center.mb-0 • Conjugar otra debilidad y otra amenaza = Otra Estrategia #[b DA].
    separador
    #t_1_2
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Programación de actividades    
    p.mb-4 El análisis detallado, elaborado previamente, deja consigo una serie de estrategias a implementar en un periodo de tiempo determinado. Las estrategias se componen por un número de tareas de menor escala que se encaminan a un propósito común; su ejecución suele comprender la interacción de diversos actores de forma secuencial y/o paralela, por lo que una coordinación adecuada permite un progreso orgánico, continuo y eficiente.
    .row.justify-content-center.mb-4
      .col-lg-12
        .cajon.color-acento-contenido.p-4
          p.mb-0 Para lograrlo se hace necesaria una programación que contemple cada escenario de forma independiente y como un engranaje que se complementa y retroalimenta de los resultados anteriores de trabajo.    
    p En el siguiente video se amplían las generalidades más importantes de la programación de actividades dentro del plan de mercadeo:         
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)(data-aos="fade-right")
    .row.mb-5
      .col-12.bg-color4.p-4
        .row.align-items-center.justify-content-center(data-aos="fade-right")
          .col-lg-1.mb-3
            figure
              img.img-t(src='@/assets/curso/tema1/img31.png').mx-auto(data-aos="fade-right").mx-auto
          .col-lg-11
            p.mb-0 Si bien existen herramientas especializadas en el diseño de este diagrama, es posible elaborar una versión simplificada del mismo haciendo uso de una hoja de cálculo.
    p Observe con atención el siguiente ejemplo de cronograma para la ejecución de una estrategia que involucra una campaña publicitaria en medios masivos:
    .titulo-sexto.color-acento-contenido
      p.mb-0 #[b Tabla 2]. Ejemplo de cronograma de actividades
    .tabla-a.color-primario.mb-5(data-aos="fade-right")
          table
            thead
              tr(style="background-color: #CED371")
                th 
                  h5 Proceso
                th 
                  h5 Fecha Inicial
                th
                  h5 Fecha final
                th
                  h5 Duración (días)
            tbody
              tr(style="background-color: #F6F6F6")
                td 
                  p.text-center Rediseño de la imagen de la marca
                td 
                  p.mb-4.text-center.mb-0 15-abr 
                td 
                  p.mb-4.text-center.mb-0 28-abr
                td 
                  p.mb-4.text-center.mb-0 13
              tr
                td 
                  p.text-center Cambio del etiquetado de productos
                td 
                  p.mb-4.text-center.mb-0 29-abr
                td 
                  p.mb-4.text-center.mb-0 5-may
                td 
                  p.mb-4.text-center.mb-0 6
              tr(style="background-color: #F6F6F6")
                td 
                  p.text-center Diseño de imágenes publicitarias
                td 
                  p.mb-4.text-center.mb-0 29-abr 
                td 
                  p.mb-4.text-center.mb-0 10-may
                td 
                  p.mb-4.text-center.mb-0 11
              tr
                td 
                  p.text-center Publicación de la nueva imagen en medios 
                td 
                  p.mb-4.text-center.mb-0 11-may
                td 
                  p.mb-4.text-center.mb-0 30-may
                td 
                  p.mb-4.text-center.mb-0 19
              tr(style="background-color: #F6F6F6")
                td 
                  p.text-center Evento de clausura en el almacén
                td 
                  p.mb-4.text-center.mb-0 29-may
                td 
                  p.mb-4.text-center.mb-0 30-may
                td 
                  p.mb-4.text-center.mb-0 1
    .row.justify-content-center
      .col-lg-10 
        figure
          img(src='@/assets/curso/tema1/img33.svg').mx-auto(data-aos="fade-right")
    separador
    #t_1_3
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Asignación de responsables 
    p.mb-4 En el transcurso del análisis y planeación comercial es natural que se determinen tareas y actividades que dependen unas de otras. En este proceso se presentan desafíos en cada nivel de la gestión administrativa. Los tres niveles que se suelen dar en una organización son: nivel estratégico, nivel táctico y nivel operativo.
    p A continuación se explican en detalle estos tres niveles y se describen algunos aspectos relacionados con ellos:     
    .tarjeta.tarjeta--azul.p-4.mb-5
      SlyderA(tipo="b")(data-aos="fade-right")
        .row.align-items-center.justify-content-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Nivel estratégico]
            p Suele encargarse de la planeación a largo plazo, definiendo objetivos y políticas que abarcan toda la empresa de forma general. Representan de forma directa la visión de la empresa y sus directivas. Dada su envergadura, la programación no se detalla demasiado, sino que le otorga un norte a cada área organizacional.
          .col-lg-8.ps-4
            figure
              img.img-t(src='@/assets/curso/tema1/img34.png').mx-auto
        .row.align-items-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Nivel táctico]
            p Es una escala intermedia en la que se plantean propósitos y objetivos a mediano plazo. Las tareas les corresponden, por lo tanto, a jefes de área y personal de supervisión. Aquí se incluyen actividades que involucren partidas presupuestales a ejecutarse en los meses siguientes, por ejemplo, definir la contratación con medios para una campaña publicitaria o el desarrollo de una nueva presentación del producto estrella.
          .col-lg-8.ps-4
            figure
              img.img-t(src='@/assets/curso/tema1/img35.png').mx-auto
        .row.align-items-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Nivel operativo]
            p Es el nivel más básico, donde se ejecutan las tareas propias del día a día, asociadas al personal de menor jerarquía en la empresa. Aquí se pueden incluir tareas como visitar tiendas determinadas, asistir a eventos comerciales como ferias o simplemente dedicarse a vender según las directrices otorgadas por los niveles superiores.
          .col-lg-8.ps-4
            figure
              img.img-t(src='@/assets/curso/tema1/img36.png').mx-auto
        .row.align-items-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Tareas independientes y conjuntas]
            p La programación de las actividades requiere definir tareas para cada nivel de forma independiente y conjunta, por ejemplo, las actividades más repetitivas y básicas serán desarrolladas por el nivel operativo, mientras que la supervisión de esas tareas se erige como otro compromiso independiente, a cargo de los niveles jerárquicos superiores.
          .col-lg-8.ps-4
            figure
              img.img-t(src='@/assets/curso/tema1/img37.png').mx-auto
        .row.align-items-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Representación gráfica de las tareas]
            p El mismo diagrama de Gantt permite este tipo de asignaciones, bien sea haciendo uso de códigos de color, donde cada barra puede tomar un color diferente dependiendo del empleado asignado, o incluso diligenciando el nombre del responsable en el cuerpo de la propia barra de tiempo.
          .col-lg-8.ps-4
            figure
              img.img-t(src='@/assets/curso/tema1/img38.png').mx-auto
        .row.align-items-center
          .col-lg-4.mb-4.mb-lg-0.ps-5
            p #[b Seguimiento y compensaciones]
            p El seguimiento de cada tarea con un responsable asignado,favorece implementar medidas de recompensa para los empleados que ejecuten su labor de forma oportuna y cumpliendo con los requisitos determinados; de la misma forma, se pueden reprender a quienes hayan presentado falencias por falta de atención a las actividades. También permite determinar si existen colaboradores que no cumplen con los requerimientos necesarios para desempeñar su trabajo, y tomar las decisiones que sean necesarias, como el cambio de cargo o el despido justificado.
          .col-lg-8.ps-4
            figure
              img.img-t(src='@/assets/curso/tema1/img39.png').mx-auto
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
