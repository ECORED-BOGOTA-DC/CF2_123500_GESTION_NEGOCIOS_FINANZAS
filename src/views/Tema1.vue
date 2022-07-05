<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.container01.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero
        span 1
      h1 Administración

    p.mb-5 Las organizaciones, en general, necesitan una administración eficaz para alcanzar sus objetivos empresariales. Existen diferentes niveles de administración, que tienen como fin organizar y coordinar las funciones comerciales de una empresa. La administración debe considerar los intereses de todas las partes interesadas de la empresa, incluidos los empleados, los clientes y el gobierno. 

    .row.justify-content-center.mb-5
      .col-md-10.col-12
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1/img01.png')})`}"
          )(data-aos="fade-right")
          .bloque-texto-g__texto.p-4
            p.mb-0 Los administradores son responsables de establecer y lograr los objetivos de la organización. Por lo general, el objetivo principal de una organización consiste en lograr el crecimiento mediante la utilización de sus recursos humanos, materiales y financieros.
        p.mb-5 La administración es el proceso de planificación y organización de los recursos y actividades de una empresa para lograr objetivos específicos, de la manera más eficaz y eficiente posible. Para mayor claridad, la figura expone en qué consiste cada uno de los conceptos involucrados.

        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
          h5 Figura 1
          span Conceptos administrativos

        figure(data-aos="zoom-in")
          img(src='@/assets/curso/tema1/img02.svg')

    p.mb-5 Lo anterior permite, entonces, crear una organización dinámica, en la que la gerencia ayuda a su personal a adaptarse al cambio para que la organización continúe manteniendo su ventaja competitiva. Este aspecto correspondiente a la importancia de la adaptación puede llegar a significar la diferencia entre su éxito y su fracaso. Por tal motivo, se debe ver la dinámica de la siguiente forma: 

    .row.justify-content-center.mb-5
      .col-md-10.col-12
        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
          h5 Figura 2
          span Dinámica organizacional del logro

        figure(data-aos="zoom-in")
          img(src='@/assets/curso/tema1/img03.svg')

    p.mb-5 La administración también posee algunas características fundamentales. 

    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-primario.p-5(data-aos="fade-right")
        .row.justify-content-center.mb-4
          .col-4
            figure
              img(src='@/assets/curso/tema1/img04.svg')          
        h2.text-center Multidimensional
        p La mayoría de la gerencia supervisa el servicio o el ciclo de producción de una empresa u organización. Los gerentes trabajan en estrecha colaboración y brindan orientación a los miembros de su equipo. Un gerente considera a un miembro del personal como un individuo con diversas necesidades y como un componente del grupo más grande. Para ser efectivos, los gerentes influyen en los miembros de su equipo para que apliquen sus fortalezas únicas para lograr las metas de la organización.
      .col-md.tarjeta.color-acento-contenido.p-5
        .row.justify-content-center.mb-4
          .col-4
            figure
              img(src='@/assets/curso/tema1/img05.svg')          
        h2.text-center Dinámica
        p La administración es una función dinámica y evoluciona, se adapta a los cambios de su entorno, ya sean económicos, sociopolíticos o tecnológicos. Que la empresa pueda sobrevivir todavía depende de la eficacia con la que su administración pueda adaptarse a los nuevos requisitos del mercado.
      .col-md.tarjeta.color-acento-botones.p-5(data-aos="fade-left")
        .row.justify-content-center.mb-4
          .col-4
            figure
              img(src='@/assets/curso/tema1/img06.svg')          
        h2.text-center Intangible
        p La gestión no es un producto tangible, pero su presencia puede cambiar la forma en que funciona una organización. La gestión consiste en ideologías, políticas e interacción humana. Una buena gestión ayuda a mejorar los índices de consecución de los objetivos de una empresa, los niveles de satisfacción de los empleados y la facilidad general en el funcionamiento de la empresa.

    p.mb-5 Ahora bien, dichas características se fundamentan en las funciones de la administración, las cuales se explican a continuación:

    TabsC.color-acento-botones
      .py-3.py-md-4.px-4.BG02(titulo="Planeación")
        .row.justify-content-center.align-items-center
          .col-md-5.col-12.mb-3
            figure
              img(src='@/assets/curso/tema1/img07.png') 
          .col-md-7.col-12
            p La planeación implica la creación de una línea de tiempo de las tareas que deben completarse para lograr un objetivo específico. Los gerentes ejecutan la planeación, que debe llevarse a cabo de manera sistemática para evitar el desperdicio de recursos y tiempo. Un plan de acción detallado minimiza la confusión, el riesgo, el desperdicio y la incertidumbre. 
            .BG01.px-3.py-2
              p Por ejemplo, la alta dirección de una pequeña empresa puede establecer un objetivo de ventas alto para un trimestre y así compensar las pérdidas del trimestre anterior. El fundador de una empresa nueva puede planear hacer esfuerzos formales para asociarse con el gobierno y otras instituciones grandes para expandir la escala de sus operaciones.
      .py-3.py-md-4.px-4.BG02(titulo="Organización")
        .row.justify-content-center.align-items-center
          .col-md-5.col-12.mb-3
            figure
              img(src='@/assets/curso/tema1/img08.png') 
          .col-md-7.col-12
            p El objetivo de la organización es fomentar una relación simbiótica entre el personal, los recursos financieros y físicos de la empresa. La adecuada organización proporciona el curso de acción que cumple con todos los parámetros para el éxito. La organización implica la identificación y clasificación de las actividades empresariales, la delegación y la coordinación. 
            .BG01.px-3.py-2
              p Por ejemplo, los altos directivos pueden asignar fondos o recursos a diferentes sucursales. Los gerentes de sucursal, luego, deben asignar fondos a los departamentos dentro de la sucursal, según sus requisitos operativos. Posteriormente, los jefes de departamento realizan un seguimiento del gasto diario de los fondos.
      .py-3.py-md-4.px-4.BG02(titulo="Talento humano")
        .row.justify-content-center.align-items-center
          .col-md-5.col-12.mb-3
            figure
              img(src='@/assets/curso/tema1/img09.png') 
          .col-md-7.col-12
            p La dotación de personal implica reclutar y formar un equipo para la organización. El proceso de dotación de personal de las empresas suele ser largo y profundo. 
            p La gerencia identifica los roles profesionales en la empresa y las habilidades/cualidades requeridas para desempeñarse bien en estos roles. Luego, el gerente selecciona al personal para esos roles a través de los procesos de contratación. Una vez seleccionados, los candidatos reciben formación y se incorporan a la plantilla de la empresa. Los gerentes también son responsables de otorgar evaluaciones y promociones como parte de la dotación de personal
      .py-3.py-md-4.px-4.BG02(titulo="Dirección")
        .row.justify-content-center.align-items-center
          .col-md-5.col-12.mb-3
            figure
              img(src='@/assets/curso/tema1/img10.png') 
          .col-md-7.col-12
            p Dirigir implica dar los pasos necesarios para poner en marcha el trabajo y mantener la productividad para lograr los objetivos de la empresa, mediante acciones como supervisar, motivar y orientar a los miembros del personal; lo que es fundamental para las funciones de un gerente. 
            p También requiere excelentes habilidades de liderazgo, comunicación y relaciones interpersonales para impulsar al equipo hacia la consecución de los objetivos de la organización.
      .py-3.py-md-4.px-4.BG02(titulo="Control")
        .row.justify-content-center.align-items-center
          .col-md-5.col-12.mb-3
            figure
              img(src='@/assets/curso/tema1/img11.png') 
          .col-md-7.col-12
            p Esta función administrativa verifica que en cada nivel se evita la desviación general de las especificaciones de calidad prescritas. 
            .BG01.px-3.py-2
              p Por ejemplo, los supervisores de una cadena de comida rápida a menudo microgestionan a los cajeros, el personal de cocina, el personal de entrega y los meseros, para asegurarse de que la comida y el servicio en su sucursal cumplan con los estándares de calidad. La alta dirección prescribe estos estándares de calidad y, por lo general, evolucionan con el tiempo.

    p.mb-5 Sumado a lo anterior, toda administración necesita trazar una ruta de mando interno que permita establecer niveles, roles y responsabilidades, que a su vez se asumen para enfrentar el rumbo de la organización, teniendo en cuenta tanto sus características como sus funciones per se. Los niveles de la administración se pueden clasificar en tres escalas: la alta dirección, el mando intermedio y la gestión operativa, tal como se aprecia en la figura.

    .row.justify-content-center.mb-5
      .col-md-10.col-12
        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
          h5 Figura 3
          span Niveles administrativos

        ImagenInfograficaB.color-acento-botones
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema1/img12.svg')
          div(x="11.5%" y="69.9%" tooltip="tooltip de max 35 caracteres")
            p.mb-5 La <b>alta dirección</b>, por lo general, está conformada por los ejecutivos más importantes de la empresa, los cuales son:
            ul.lista-ul.mb-5
              li 
                <i class="fas fa-circle fa-xs" style="color:#359547!important;"></i>
                | El presidente directivo
              li 
                <i class="fas fa-circle fa-xs" style="color:#359547!important;"></i>
                | El director ejecutivo
              li 
                <i class="fas fa-circle fa-xs" style="color:#359547!important;"></i>
                | El director de operaciones
              li 
                <i class="fas fa-circle fa-xs" style="color:#359547!important;"></i>
                | El presidente y el vicepresidente
            p Su función radica en la integración de diversos componentes de la empresa y la coordinación de las actividades de los diferentes departamentos. También analizan el entorno empresarial y sus implicaciones para formular objetivos con el fin de garantizar la supervivencia de la empresa y el bienestar de sus grupos de interés. 
          div(x="51.5%" y="87%" tooltip="tooltip de max 35 caracteres")
            p.mb-5 El <b>mando intermedio</b> vincula la gestión operativa con la alta dirección. Los jefes de división y/o departamento reciben orientación de los gerentes superiores y son líderes para los gerentes operativos. Su trabajo es comprender las políticas enmarcadas por la alta dirección y transmitirlas a sus respectivas divisiones y/o departamentos para garantizar que cumplan con las políticas y decisiones de la empresa.
            ul.lista-ul.mb-5
              li 
                <i class="fas fa-circle fa-xs" style="color:#359547!important;"></i>
                | Jefes de división
              li 
                <i class="fas fa-circle fa-xs" style="color:#359547!important;"></i>
                | Jefes de departamento
          div(x="90%" y="75%" tooltip="tooltip de max 35 caracteres")
            p.mb-5 La <b>gestión operativa</b> está conformada por:
            ul.lista-ul.mb-5
              li 
                <i class="fas fa-circle fa-xs" style="color:#359547!important;"></i>
                | Los supervisores 
              li 
                <i class="fas fa-circle fa-xs" style="color:#359547!important;"></i>
                | Jefes de sección
              li 
                <i class="fas fa-circle fa-xs" style="color:#359547!important;"></i>
                | Delegados 
            p Supervisan directamente los esfuerzos de la fuerza laboral. Son responsables del control de calidad y se aseguran de que el trabajo cumpla con los plazos. La alta dirección elabora los planes que definen la autoridad y responsabilidad de los supervisores.

    separador

  .container.BGIMG01.px-4.px-md-5.pt-4
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1	Objetivos 

    p.mb-5 Las empresas exitosas se basan tanto en metas como en objetivos, ya que aclaran el propósito de la empresa y ayudan a identificar las acciones necesarias. 
    
    .row.justify-content-center.mb-5
      .col-md-10.col-12
        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
          h5 Figura 4
          span Metas y objetivos
        
        figure(data-aos="zoom-in")
          img(src='@/assets/curso/tema1/img14.svg')
    p La gestión por objetivos está estrechamente relacionada con la evaluación y revisión del desempeño; mide y juzga el desempeño individual con las metas de la organización, para aclarar tanto el trabajo a realizar como las expectativas de logro, y así fomentar la competencia, el crecimiento y motivación del subordinado y la comunicación entre partes. Adicionalmente a ello, busca servir como dispositivo de control e integración organizacional.
  
  .container.container02.p-4.p-md-5
    p.mb-5 La administración considera tener principalmente dos tipos de objetivos, en los cuales la gerencia debe tener presentes los intereses de todas las partes interesadas de la empresa, incluidos los empleados, los clientes y el gobierno. Estos son los objetivos organizacionales generales para cualquier empresa: 

    .row.justify-content-center.mb-5
      .col-lg-5.col-md-6.col-10.mb-3
        .tarjeta.tarjeta-avatar-slide.BG03.p-5.h-100
          .tarjeta-avatar-slide__img.mb-4
            .tarjeta-avatar-slide__img__item: img.w-50(src='@/assets/curso/tema1/img15.svg')
            .tarjeta-avatar-slide__img__item: img.w-50(src='@/assets/curso/tema1/img17.svg')
          h5.mb-4 ●	Supervivencia:
          p Una organización necesita generar suficientes ingresos para cubrir sus costos operativos. 
      .col-lg-5.col-md-6.col-10.mb-3
        .tarjeta.tarjeta-avatar-slide.BG03.p-5.h-100
          .tarjeta-avatar-slide__img.mb-4
            .tarjeta-avatar-slide__img__item: img.w-50(src='@/assets/curso/tema1/img16.svg')
            .tarjeta-avatar-slide__img__item: img.w-50(src='@/assets/curso/tema1/img18.svg')
          h5.mb-4 ●	Beneficio:
          p El beneficio proporciona un incentivo y es esencial para cubrir costos y riesgos sin precedentes asociados con la gestión de una empresa. 

    .cajon.color-secundario.p-4.mb-4
      p  Aunque no son tan mencionados, <span style="color:#2B7E3B !important; font-weight: bold;">los objetivos sociales</span>se utilizan en cierto punto; la gerencia es responsable de crear beneficios para la sociedad a través de su trabajo. Las empresas eligen hacer esto de diferentes maneras. Algunos pueden incorporar métodos de producción amigables con el medio ambiente, mientras que otros implementan salarios y oportunidades justos. Las empresas más grandes, a menudo, mantienen o financian iniciativas que brindan servicios básicos como atención médica y educación. Según la escala de sus operaciones, las empresas, a menudo, inician campañas de responsabilidad social.

    p Es vital que se creen objetivos específicos como parte de un plan de negocios. Establecer objetivos ayuda a impulsar a la empresa hacia el éxito continuo y sigue siendo un punto de referencia incluso en tiempos difíciles. 
    p Los objetivos de la empresa son medibles y describen efectivamente las acciones requeridas para realizar una tarea. Los objetivos también definen las técnicas que utilizará la organización para lograr el éxito de ventas, los estándares de servicio al cliente y las oportunidades de marca, así como cualquier otra aspiración medible.
    p.mb-5 A continuación, se describen los objetivos que se establecen para el desempeño y éxito de la organización.

    .row.justify-content-center.mb-5
      .col-md-10.col-12
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.justify-content-center.px-4(titulo="Objetivos de ventas")
            .col-4.p-0
              figure
                img(src='@/assets/curso/tema1/img19.png')
            .col-8
              p Ayudan a las empresas a medir su posición frente a los competidores de la industria. Estos objetivos tienden a enfocarse en las formas en que una organización puede superar a la competencia en participación de mercado, calidad del producto y reconocimiento de marca. 
              p Por ejemplo, si se posee una tienda de zapatos, un ejemplo de un objetivo de ventas podría ser <span style="color:#2B7E3B !important; font-weight: bold;">“aumentar sus ventas mensuales en un 10 % durante el transcurso del año”</span>. Para hacer esto, es posible que deba implementar una estrategia de marketing para atraer nuevos compradores o introducir nuevos artículos que le permitan aumentar las ventas a sus clientes existentes. Su empresa debe contratar empleados talentosos, que puedan implementar sus decisiones y mantener la productividad y la eficiencia. 
          .row.justify-content-center.px-4(titulo="Objetivos de recursos")
            .col-4.p-0
              figure
                img(src='@/assets/curso/tema1/img20.png')
            .col-8
              p Cubren los objetivos de capacitación y desarrollo de los empleados de la organización. Un objetivo de recursos humanos podría ser <span style="color:#2B7E3B !important; font-weight: bold;">“reducir la rotación de empleados en un 20 % mediante la introducción de un nuevo programa de asistencia para empleados”</span>. 
              p La dotación de personal de una organización es también un foco de recursos humanos. Un objetivo para satisfacer las necesidades de personal podría ser la contratación activa de trabajadores calificados en la organización. 
            p Uno de los objetivos que a menudo se pasa por alto para las pequeñas empresas es garantizar que los empleados talentosos y capacitados permanezcan en la empresa. Cuando encuentre este tipo de trabajadores, su objetivo debe ser retenerlos ofreciéndoles salarios competitivos, incentivos y un ambiente de trabajo que sea inclusivo y armonioso. Invertir en programas de capacitación que brinden a sus empleados educación adicional también puede ayudar a lograr este objetivo.
          .row.justify-content-center.px-4(titulo="Objetivos comerciales")
            .col-4.p-0
              figure
                img(src='@/assets/curso/tema1/img21.png')
            .col-8
              p Centrándose en el servicio al cliente, los gerentes comerciales establecen objetivos que se enfocan en brindar un servicio de calidad al cliente. Estos objetivos intentan <span style="color:#2B7E3B !important; font-weight: bold;">medir la satisfacción del cliente con los costos y la calidad general de un producto o servicio</span>. Otro podría ser reducir el número y la frecuencia de las devoluciones y quejas de los clientes, o mejorar el tiempo de respuesta a las consultas de los clientes. Establecer conciencia de marca.
              p En la era del <em>marketing</em> en redes sociales, muchas pequeñas empresas están descubriendo que el marketing de marca es otro objetivo vital. La marca trata de vender la experiencia de su producto o servicio al comunicarle a su audiencia cómo su negocio satisface un deseo o necesidad y hace que sus vidas sean más convenientes. Un objetivo de marca podría ser <span style="color:#2B7E3B !important; font-weight: bold;">“aumentar su conocimiento de las redes sociales mediante el análisis de una métrica como las visitas al sitio web”</span>.
            .BG01.p-4
              p Un objetivo comercial común es ejecutar una operación rentable, lo que generalmente significa aumentar los ingresos y limitar los gastos. Para alcanzar esta meta, los objetivos podrían consistir en <span style="color:#2B7E3B !important; font-weight: bold;">aumentar las ventas anuales en un 10 % o conseguir tres nuevas cuentas cada mes</span>.
          .row.justify-content-center.px-4(titulo="Objetivos de <em>marketing</em>")
            .col-4.p-0
              figure
                img(src='@/assets/curso/tema1/img22.png')
            .col-8
              p Un plan de promoción describe las herramientas y tácticas que utilizará una empresa para lograr sus objetivos de <em>marketing</em>. Por ejemplo, si un objetivo de <em>marketing</em> es <span style="color:#2B7E3B !important; font-weight: bold;">“crear conciencia de marca para un material de construcción entre los constructores de una ciudad específica”</span>, las herramientas y tácticas pueden incluir anuncios en las revistas de asociaciones locales de constructores de viviendas, patrocinar un evento al que asistan constructores u ofrecer descuentos promocionales a los constructores para que prueben el producto.
          .row.justify-content-center.px-4(titulo="Objetivos operativos")
            .col-4.p-0
              figure
                img(src='@/assets/curso/tema1/img23.png')
            .col-8
              p Los objetivos operativos son el desglose de las metas diarias, semanales o mensuales del proyecto en tareas factibles, para ayudar a la gerencia y al personal a lograr el plan estratégico de promoción general. 
              p Establecer los objetivos correctos es crucial para crear conciencia, atraer clientes potenciales y convertirlos en clientes. Al igual que con los objetivos estratégicos, los objetivos operativos de marketing deben ser cuantificables y específicos, pero con un enfoque más limitado.
          .row.justify-content-center.px-4(titulo="Objetivos financieros")
            .col-4.p-0
              figure
                img(src='@/assets/curso/tema1/img24.png')
            .col-8
              p Generan rentabilidad y solvencia a la empresa, por ende, es fundamental que se diseñen y se ejecuten para aumentar el rendimiento económico de la empresa. Un ejemplo de un objetivo financiero podría ser el crecimiento de los ingresos y ganancias de la empresa. Adjuntar un número cuantificable, como un <span style="color:#2B7E3B !important; font-weight: bold;">crecimiento del 15 % en los ingresos y ganancias dentro de los próximos 12 meses</span>, es ideal porque puede medirse y ajustarse si es necesario.
              p Otro objetivo financiero podría centrarse en aumentar el capital y las inversiones, como <span style="color:#2B7E3B !important; font-weight: bold;">“atraer nuevos accionistas e inversores mejorando la solvencia y el flujo de caja”</span>. Aumento de las cifras de ventas.

    p.mb-5 Es importante establecer periodos de tiempo que sean realistas y puedan lograrse razonablemente. Adicionalmente a ello, deben redactarse claramente, usando palabras de acción. Estos son algunos ejemplos de objetivos comunes de toda organización.

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
      h5 Figura 5
      span Ejemplos de objetivos comunes

    figure(data-aos="zoom-in")
      img(src='@/assets/curso/tema1/img25.svg')

    p Finalmente, los objetivos deben basarse en un cronograma. Es posible que se requiera que el empleado logre los objetivos en tres meses, seis meses o antes de la próxima revisión de desempeño. 

    separador

  .container.BGIMG02.px-4.px-md-5.pt-4  
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2. Planeación estratégica

    .row.justify-content-center
      .col-md-6.col-12.mb-3
        p La planeación estratégica es un proceso en el que los líderes de una organización definen su visión para el futuro e identifican las metas y objetivos de su organización. El proceso incluye establecer la secuencia en la que se deben realizar esos objetivos para que la organización pueda alcanzar su visión determinada. La planeación estratégica generalmente representa objetivos a mediano y largo plazo, con una vida útil de tres a cinco años, aunque puede durar más.
      .col-md-6.col-12.mb-3
        p El producto de la planeación estratégica es un documento que puede ser fácilmente compartido, entendido y seguido por varias personas, incluidos empleados, clientes, socios comerciales e inversionistas. Un plan estratégico puede actualizarse y revisarse en ese momento para reflejar cualquier cambio estratégico, pues es una hoja de ruta para llegar a los objetivos comerciales. Los siguientes tres aspectos del desarrollo de la estrategia merecen atención.
      .col-lg-10.col-12
        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
          h5 Figura 6
          span Aspectos del plan estratégico
        <hr style="color: #2B7E3B; background-color: #2B7E3B; height: 2px; border-color: #2B7E3B; opacity: 1;" />
        .row.justify-content-center.align-items-center
          .col-2
            figure(data-aos="zoom-in")
              img.p-4(src='@/assets/curso/tema1/img27.svg')
          .col-10
            h4 Misión
            p.mb-0 Ofrece a la empresa un sentido de propósito y dirección. La misión de la organización describe quién es, qué hace y hacia dónde quiere ir. Las misiones suelen ser amplias pero procesables.
  .container.container02.px-4.px-md-5
    .row.justify-content-center.mb-5
      .col-lg-10.col-12
        <hr style="color: #2B7E3B; background-color: #2B7E3B; height: 2px; border-color: #2B7E3B; opacity: 1;" />
        .row.justify-content-center.align-items-center
          .col-2
            figure(data-aos="zoom-in")
              img.p-4(src='@/assets/curso/tema1/img28.svg')
          .col-10
            h4 Objetivos
            p La mayoría de la planeación utiliza objetivos específicos, medibles, alcanzables, realistas y con plazos determinados. 
            p Los objetivos medibles son importantes porque permiten a los líderes empresariales determinar qué tan bien se está desempeñando el negocio en comparación con los objetivos y la misión general.
        <hr style="color: #2B7E3B; background-color: #2B7E3B; height: 2px; border-color: #2B7E3B; opacity: 1;" />
        .row.justify-content-center.align-items-center
          .col-2
            figure(data-aos="zoom-in")
              img.p-4(src='@/assets/curso/tema1/img29.svg')
          .col-10
            h4 Evaluación y revisión
            p La planeación estratégica ayuda a los líderes empresariales a evaluar periódicamente el progreso con respecto al plan y realizar cambios o ajustes en respuesta a las condiciones cambiantes.
        <hr style="color: #2B7E3B; background-color: #2B7E3B; height: 2px; border-color: #2B7E3B; opacity: 1;" />

    p.mb-5 Ahora bien, para construir una planeación estratégica, se requiere tener en cuenta ciertos pasos fundamentales. En el interactivo, se puede visualizar y explorar en qué consiste cada uno de ellos.

    ImagenInfograficaB.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema1/img30.svg')
      div(x="8.7%" y="99.9%" tooltip="tooltip de max 35 caracteres")
        .row.justify-content-center.align-items-center
          .col-md-2
            figure
                img(src='@/assets/curso/tema1/img31.svg')
          .col-md-9
            h5 Identificar la situación de la empresa a través de un análisis DOFA.
            p  Como todo componente que requiere un proceso de establecimiento y desarrollo,  la planeación parte de la situación actual o plan estratégico existente en la empresa; aquí se incluyen la misión y los objetivos estratégicos a largo plazo, para realizar evaluaciones del negocio y su entorno. Estos últimos pueden incluir una evaluación de necesidades o un análisis FODA (fortalezas, debilidades, oportunidades y amenazas) para comprender el estado del negocio y el camino a seguir.
      div(x="29.7%" y="99.9%" tooltip="tooltip de max 35 caracteres")
        .row.justify-content-center.align-items-center
          .col-md-2
            figure
                img(src='@/assets/curso/tema1/img32.svg')
          .col-md-9
            h5 Priorizar objetivos estratégicos alineados con la fundamentación de la misión. 
            p Luego, los planeadores estratégicos establecen objetivos e iniciativas que se alinean con la misión y las metas de la empresa y harán que el negocio avance hacia el logro de sus metas. Puede haber muchos objetivos potenciales, por lo que la planeación prioriza los más importantes, relevantes y urgentes. 
            p Los objetivos pueden incluir una consideración de los requisitos de recursos, como presupuestos y equipos; y a menudo implican una línea de tiempo y métricas comerciales para medir el progreso. 
      div(x="50%" y="99.9%" tooltip="tooltip de max 35 caracteres")
        .row.justify-content-center.align-items-center
          .col-md-2
            figure
                img(src='@/assets/curso/tema1/img33.svg')
          .col-md-9
            h5 Desarrollar estrategias para ayudar a visualizar y modificar el plan.
            p Seguidamente, se desarrollan estrategias orientadas al objetivo principal de la planeación estratégica en la que las partes interesadas colaboran para formular los pasos o tácticas necesarias para lograr un objetivo estratégico visible. 
            p Esto puede implicar la creación de numerosos planes comerciales tácticos a corto plazo, que se ajusten a la estrategia general. 
      div(x="70.5%" y="99.9%" tooltip="tooltip de max 35 caracteres")
        .row.justify-content-center.align-items-center
          .col-md-2
            figure
                img(src='@/assets/curso/tema1/img34.svg')
          .col-md-9
            h5 Implementación mediante la distribución de responsabilidades entre los colaboradores.
            p Una vez que se desarrolla el plan estratégico, es hora de ponerlo en marcha. Esto requiere una comunicación clara en toda la organización para establecer responsabilidades, realizar inversiones, ajustar políticas y procesos, y establecer mediciones e informes. 
            p La implementación generalmente incluye la gestión estratégica, con revisiones estratégicas periódicas para garantizar que los planes se mantengan encaminados.
      div(x="90.8%" y="99.9%" tooltip="tooltip de max 35 caracteres")
        .row.justify-content-center.align-items-center
          .col-md-2
            figure
                img(src='@/assets/curso/tema1/img35.svg')
          .col-md-9
            h5 Actualizar los planes estratégicos conforme surgen nuevas oportunidades. 
            p Un plan estratégico se revisa periódicamente para ajustar las prioridades y reevaluar los objetivos a medida que cambian las condiciones comerciales y surgen nuevas oportunidades. Las revisiones rápidas pueden ocurrir trimestralmente y los ajustes al plan estratégico pueden ocurrir anualmente. 
            p Las partes interesadas pueden utilizar otras herramientas para evaluar el desempeño frente a los objetivos.

    p.mb-5 Se hace énfasis también sobre la ruta de las estrategias que favorecen el cumplimiento de los objetivos, ya que así, se ayuda a las partes interesadas a visualizarla de forma completa, como un gráfico interrelacionado, revisando las relaciones de causa y efecto entre los elementos de una estrategia empresarial.
    p.mb-5 Las estrategias se centran en cuatro áreas o categorías comerciales principales.

    .row.justify-content-center.mb-5
      .col-md-8.col-11
        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
          h5 Figura 7
          span Áreas comerciales
        figure(data-aos="zoom-in")
          img.p-4(src='@/assets/curso/tema1/img36.svg')

    .BGIMG03.p-4  
      p.mb-5 En otras compañías, se utiliza el término de mapa estratégico, que puede ayudar a traducir los objetivos generales en un plan de acción y objetivos específicos que se pueden alinear e implementar. El mapa de estrategias también puede ayudar a identificar desafíos estratégicos que pueden no ser obvios. 

      .row.justify-content-center.mb-5
        .col-md-10.col-12.mb-5
          .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
            .bloque-texto-g__img(
              :style="{'background-image': `url(${require('@/assets/curso/tema1/img38.png')})`}"
            )(data-aos="fade-right")
            .bloque-texto-g__texto.p-4
              p Por ejemplo, un objetivo de aprendizaje y crecimiento puede ser aumentar la experiencia de los empleados, pero eso puede exponer desafíos inesperados en la retención y compensación de los empleados.
              p.mb-0 Las actividades de planeación estratégica suelen centrarse en tres áreas: comercial, corporativa y funcional; a continuación, se describe cada uno de los tipos de planes estratégicos:
          .row.justify-content-center.mb-5
            .col-xl-4.col-lg-6.col-11.mb-3
              .tarjeta.tarjeta-flip.color-acento-botones(@mouseover="indicadorTarjetaFlip = false")
                .indicador--hover(v-if="indicadorTarjetaFlip")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img39.svg')})`}")
                  .tarjeta-flip__contenido.p-md-4.p-5
                    p <b>Comercial:</b> un plan estratégico centrado en el negocio se enfoca en los aspectos competitivos de la organización, creando ventajas competitivas y oportunidades de crecimiento. 
                    p Estos planes adoptan una misión que evalúa el entorno comercial externo, establece metas y asigna recursos financieros, humanos y tecnológicos, para cumplir con esas metas.
            .col-xl-4.col-lg-6.col-11.mb-3
              .tarjeta.tarjeta-flip.color-acento-botones(@mouseover="indicadorTarjetaFlip = false")
                .indicador--hover(v-if="indicadorTarjetaFlip")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img40.svg')})`}")
                  .tarjeta-flip__contenido.p-md-4.py-5.p-5.mb-5
                    p.mb-5.mt-5 <b>Corporativo:</b> Un plan centrado en la empresa define cómo funciona la misma. Se enfoca en organizar y alinear la estructura del negocio, sus políticas, procesos y su liderazgo, para alcanzar las metas deseadas.
            .col-xl-4.col-lg-6.col-11.mb-3
              .tarjeta.tarjeta-flip.color-acento-botones(@mouseover="indicadorTarjetaFlip = false")
                .indicador--hover(v-if="indicadorTarjetaFlip")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img41.svg')})`}")
                  .tarjeta-flip__contenido.p-md-4.p-5
                    p <b>Funcional:</b> los planes estratégicos centrados en funciones se ajustan a las estrategias a nivel corporativo y brindan un examen general de departamentos o segmentos específicos, como marketing, recursos humanos y finanzas. 
                    p Los planes funcionales se centran en la política y el proceso, como la seguridad y el cumplimiento, asimismo, se establecen presupuestos y asignaciones de recursos.

    .row.justify-content-center.mb-4
      .col-md-10.col-12.mb-5
        p En la mayoría de los casos, un plan estratégico involucra elementos de las tres áreas de enfoque, pero el plan puede inclinarse hacia un área de enfoque, según las necesidades y el tipo de negocio. 
        .cajon.color-secundario.p-4
          p La planeación estratégica puede mejorar los planes operativos y la eficiencia. También ayuda a las organizaciones a limitar el tiempo dedicado a la gestión de crisis, donde reaccionan a cambios inesperados que no pudieron anticipar ni prepararse.

    separador

    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3. Modelos

    .row.justify-content-center.align-items-center
      .col-md-7.col-12.mb-3.order-md-1.order-1
        p Los modelos que se desarrollan tanto al interior como en lo externo de la organización examinan la orientación de los procesos que perfeccionan el desempeño de los actores involucrados en la satisfacción de las necesidades entre las partes. Son herramientas para ayudar a una empresa a desarrollar un plan de acción. El uso de modelos de estrategia ayudan en el proceso a analizar la estructura general. 
        p Los modelos son flexibles y pueden alertarlo sobre los ajustes necesarios. Se sugiere usarlos para competir con éxito, hacer crecer un negocio y manejar con capacidad los diversos recursos económicos, para mejorar la eficiencia productiva de una empresa.
      .col-md-5.col-12.mb-3.order-md-2.order-1
        figure(data-aos="zoom-in")
          img(src='@/assets/curso/tema1/img41.png')

    .row.justify-content-center.mb-5
      .col-md-10.col-12
        .BG04.p-2
          p.mb-0.text-center Estos son algunos de los modelos a seguir: modelos administrativos, modelos de planeación estratégica y modelos gerenciales.

    .row.mb-5
      .col-auto
        figure
          img(src='@/assets/curso/tema1/img42.svg')

    p.mb-5  Un modelo administrativo describe la organización de una empresa y muestra cómo se gestiona y cómo se ve en el organigrama de una empresa. Un modelo administrativo es una estructura lógica, conformada por componentes que permiten organizar la direccionalidad y los recursos.
    p.mb-5 El personal se asignará a diferentes departamentos, que estarán bajo la jurisdicción de personas de otros departamentos, que responderán a su vez a las divisiones de gestión, que, en última instancia, rendirán cuentas a la alta dirección. En algunos casos, la empresa puede dividirse aún más en sucursales o divisiones que residen en diferentes ubicaciones geográficas, o se separan por motivos comerciales o políticos, debido a que la estructura y la cadena de mando de una empresa variarán frente a las demás; de ahí la importancia de comprender el modelo administrativo que se utiliza.

    .row.justify-content-center.mb-5
      .col-lg-8.col-md-10.col-12
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img.w-75.ms-3.ps-4(src='@/assets/curso/tema1/img43.svg' alt='AvatarTop')
          .tarjeta.tarjeta--blanco
            .py-4.pe-4 
              p.mb-0 En las empresas más pequeñas, por su parte, hay quienes toman las decisiones y quienes las siguen; esta estructura de mando se vuelve más compleja a medida que la empresa crece.
          
    p Al observar los componentes que conforman la estructura lógica, es fácil ver la necesidad de comprender el modelo administrativo utilizado por una empresa. Al comprender cómo está organizada la empresa, puede aplicar ese conocimiento al diseño.  Hay varias formas en las que puede identificar el modelo actual utilizado por una empresa, estos elementos incluyen:

  .container.BGIMG04.px-4.px-md-5.pt-4  
    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
      h5 Figura 8
      span Elementos para identificar el modelo administrativo
    figure.mb-5(data-aos="zoom-in")
      img(src='@/assets/curso/tema1/img45.svg')

    p.mb-5 Los organigramas sirven como un mapa de la estructura administrativa de la empresa, estos departamentos pueden tener divisiones que están bajo su administración, como en el caso de los departamentos de Nóminas que están bajo el departamento de Finanzas, por ejemplo. Al observar los componentes del diagrama de flujo, se puede ver que cada uno de estos podría convertirse en unidades organizativas individuales. Siguiendo este modelo, se podría crear fácilmente un diseño que funcione con el modelo existente que utiliza la empresa; entre los más conocidos, se encuentran los siguientes.

    .row.justify-content-center.mb-5
      .col-lg-10.col-12
        .BG05.p-4
          SlyderA(tipo="b")
            .row.justify-content-center
              .col-lg-6.col-11
                h5.mb-5 Estructura jerárquica
                p Se refiere a la cadena de mando de una empresa, normalmente va desde la alta dirección y los ejecutivos hasta los empleados generales. 
                p Hay que tener en cuenta que es importante evaluar los pros y los contras, así como las necesidades de la empresa, para poder tomar la decisión más beneficiosa para la organización.
              .col-lg-6.col-11
                figure
                  img(src='@/assets/curso/tema1/img46.svg')
            .row.justify-content-center
              .col-lg-6.col-11
                h5.mb-5 Estructura horizontal
                p Este modelo se usa en las empresas que están iniciando su actividad económica, puesto que muestra un orden jerárquico horizontal como columna vertebral de los procesos que se desarrollan en ella. 
                p Permite que los colaboradores puedan contar con líderes que orienten su trabajo, mas no se visualiza como jefe y subordinados que obedecen según órdenes.
              .col-lg-6.col-11
                figure
                  img(src='@/assets/curso/tema1/img47.svg')
            .row.justify-content-center
              .col-lg-6.col-11
                h5.mb-5 Estructura de red
                p Este modelo relaciona todas las dependencias que forman parte de la organización, por lo que permite que la línea de mando sea flexible, asumiendo la responsabilidad que recae sobre cada unidad administrativa. Cuando una empresa se entrega a una estructura de red, se dispersa más.                
              .col-lg-6.col-11
                figure
                  img(src='@/assets/curso/tema1/img48.svg')
            .row.justify-content-center
              .col-lg-6.col-11
                h5.mb-5 Estructura de división
                p La estructura de división genera no solo unidades administrativas, sino oficinas productoras o equipos de trabajo que contribuyen a la realización de los objetivos de las dependencias principales; por tanto, cada subdivisión cuenta con líderes a cargo de estos equipos de trabajo. 
                p A su vez, se asume que hay una máxima autoridad que entrega jerarquía a estos líderes que orientan las divisiones, sin dejar de lado que esta máxima autoridad es quien analiza y toma las decisiones trascendentales de la organización.
              .col-lg-6.col-11
                figure
                  img(src='@/assets/curso/tema1/img49.svg')
            .row.justify-content-center
              .col-lg-6.col-11
                h5.mb-5 Estructura de línea
                p Una estructura organizativa de línea refleja la autoridad de arriba hacia abajo, con una cadena de mando establecida. Este tipo de estructura organizacional se observa a menudo en organizaciones que tienen tareas rutinarias.
              .col-lg-6.col-11
                figure
                  img(src='@/assets/curso/tema1/img50.svg')
            .row.justify-content-center
              .col-lg-6.col-11
                h5.mb-5 Estructura basada en equipos
                p En esta estructura organizacional, los empleados tienen más autonomía y más autoridad para tomar decisiones, sin necesidad de aprobación gerencial, ya que permite comunicarse o intercambiar ideas en pro del desempeño laboral.
              .col-lg-6.col-11
                figure
                  img(src='@/assets/curso/tema1/img51.svg')

  .container.container02.px-4.px-md-5
    .row.mb-5
      .col-auto
        figure
          img(src='@/assets/curso/tema1/img52.svg')

    p Un modelo de planeación estratégica es un término colectivo para varios elementos que contribuyen al proceso de planificación estratégica. Se puede pensar en los modelos de planificación estratégica como plantillas en las que puede colocar sus propias ideas. Al final, obtendrá un plan estratégico que está estructurado de manera sensata y le brinda un conjunto claro de acciones sobre las cuales trabajar.
    p.mb-5 Los modelos de planeación estratégica proporcionan una estructura general que aplica a su proceso de planificación estratégica; es decir, los modelos de planificación estratégica proporcionan una forma de estructurar la información de su estrategia y el contenido de su plan estratégico, los diversos componentes y cómo interactúan entre sí de manera coherente: lo que hacen, cómo encajan y en qué orden. 

    .row.justify-content-center.mb-5
      .col-lg-10.col-md-11.col-12.BGIMG05.py-4  
        .row.justify-content-center
          .col-md-11.col-12.px-4  
            p.text-center Ahora, una vez definido qué es realmente un modelo de planeación estratégica, se deben tener en cuenta los elementos que la contienen: estructura y evaluación.  
            .tarjeta-avatar-b.mb-5
              .tarjeta-avatar-b__img
                img.px-3(src='@/assets/curso/tema1/img55.svg' alt='AvatarTop')
              .tarjeta.BG06
                .py-4.pe-4 
                  p.mb-0 La <b>estructura</b> se refiere a los diferentes componentes del plan estratégico y cómo encajan todos juntos. Por ejemplo, la estructura puede comenzar con la formulación de la visión, luego fluir hacia valores, áreas de enfoque y cualquier número de niveles de objetivos.
            .tarjeta-avatar-b.mb-5
              .tarjeta-avatar-b__img
                img.px-3(src='@/assets/curso/tema1/img56.svg' alt='AvatarTop')
              .tarjeta.BG06
                .py-4.pe-4 
                  p.mb-0 La <b>evaluación</b> se refiere a cómo hará el seguimiento y la presentación de informes sobre los elementos de la meta de su estrategia.
            p De igual forma, para su desarrollo, se hace necesario reconocer a fondo los siguientes aspectos de la organización.
      .col-lg-8.col-md-10.col-12.mb-5
        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
          h5 Figura 9
          span Aspectos organizacionales esenciales
        figure.mb-5(data-aos="zoom-in")
          img(src='@/assets/curso/tema1/img57.svg')
      .col-lg-10.col-md-11.col-12.BGIMG06.py-3
        .row.justify-content-center
          .col-md-11.col-12.px-4  
            p Independientemente de cuál modelo de planeación estratégica se elija como el más apropiado para sus necesidades, existen mejores prácticas para asegurarse de que tenga éxito. Por ejemplo, al hacer la investigación, busque reunir un grupo que sea diverso, pero también apropiado para la meta, de tal forma que genere más ideas al equipo de trabajo.

    p.mb-5 Cuando se tiene un plan, se debe ser realista. Si no puede ser ejecutado, entonces no se ha hecho bien el trabajo. Este debe ser accionable, con objetivos, tareas, responsabilidades delineadas, rendición de cuentas y plazos claramente definidos, sin querer decir esto que no pueda ser flexible; los planes cambian, por lo que es mejor no ser rígido al respecto.

    .row.justify-content-center
      .col-md-4.col-8.mb-3
        figure(data-aos="zoom-in")
          img(src='@/assets/curso/tema1/img58.png')
      .col-md-8.col-12.mb-3
        p Si no se tiene un plan para alcanzar los objetivos, se está condenado al fracaso, lo que podría ser perder participación de mercado o cerrar, ninguno de los cuales es un camino a seguir para una empresa viable. Cada organización es única, por lo tanto, cada plan estratégico es único, el objetivo aquí es brindarle una perspectiva sobre cómo puede abordar su planeación antes de sumergirse en los detalles.
        p A continuación, se exponen algunos modelos de planeación estratégica, los cuales no son camisa de fuerza, puesto que la organización puede ser autora de su propio modelo de planeación estratégica.

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
      h5 Tabla 1
      span Modelos de planeación

    table.mb-5(data-aos="fade-right")
      thead
        tr(style="background-color: #3AE3FE; color: #000")
          th(colspan="6")
            h4.text-center.py-2 Tipos de modelos
      tbody
        tr
          td(style="background-color: #E1EFE3; color: #000").text-center
          td(style="background-color: #E1EFE3; color: #000").text-center <b>Modelo lineal</b>
          td(style="background-color: #E1EFE3; color: #000").text-center <b>Cuadro de mando Integral</b>
          td(style="background-color: #E1EFE3; color: #000").text-center <b>Modelo cero o básico</b>
          td(style="background-color: #E1EFE3; color: #000").text-center <b>Modelo desconocido</b>
          td(style="background-color: #E1EFE3; color: #000").text-center <b>Modelo de objetivos</b>
        tr  
          td.text-center <b>Descripción</b>
          td Requiere de la cooperación de varias unidades administrativas para ejecutar dicho modelo, tal es el caso de las áreas comerciales y de los ingenieros de sistemas que tienen como responsabilidad la seguridad de la información que produce la empresa. 
          td En él se establece la valoración de las oficinas relacionadas con el cumplimiento de los objetivos que se describen en el plan estratégico, ejecutado a través de comunicaciones asertivas que se apliquen a las estrategias planteadas.
          td Este modelo es sencillo y lo utilizan empresas pequeñas para introducir la planeación estratégica, no requiere de grandes volúmenes de información, por ello es ideal para las empresas que quieren iniciar con un plan estratégico.
          td Este modelo de la planeación estratégica apunta a desarrollar estrategias y objetivos basados en nuevos descubrimientos, como el estudio de factibilidad de un nuevo producto, competencias existentes en el mercado y los segmentos a quienes estará dirigido. Busca insertar su producción en un mercado innovador.
          td Es el más recomendado para las empresas consolidadas, ya que enfatiza su desarrollo en la ampliación de los objetivos a largo plazo, haciendo exploración de todo el contexto que rodea a la organización, sin dejar brechas que perjudiquen el cumplimiento de los cronogramas.
        tr 
          td.text-center <b>Aspectos para su desarrollo</b>
          td *Ejecución de la estrategia de negocio.<br>*Herramientas tecnológicas que aporten al desarrollo de las estrategias comerciales.<br>*Medir la competencia para lanzar nuevos productos y servicios.
          td *Indicadores de los objetivos.<br>*Evaluaciones de desempeño al personal.<br>*Controles financieros.<br>*Los planes de acción trazados para el desarrollo del plan estratégico. 
          td *Misión de la organización.<br>*Objetivos a alcanzar.<br>*Estrategias y actividades para cumplir con los objetivos.<br>*Control e informes de resultados sobre la planeación estratégica.
          td *Mercados para crecer.<br>*Capturar nueva demanda.<br>*Productos únicos.<br>*No haya competencia.
          td *Análisis DOFA (debilidades, oportunidades, fortalezas y amenazas).<br>*Misión.<br>*Planeación.<br>*Presupuesto.<br>*Cronograma.<br>*Monitoreo o control de los avances.

    .row.mb-5
      .col-auto
        figure
          img(src='@/assets/curso/tema1/img59.svg')

    p.mb-5 Este tipo de modelo, al igual que los anteriores, tiene una clasificación específica, la cual está enfocada, como bien lo indica, en procesos gerenciales de una organización. Dependiendo del logro a alcanzar, se implementa alguno de estos modelos.

    ImagenInfograficaB.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema1/img60.svg')
      div(x="16.3%" y="72%" tooltip="tooltip de max 35 caracteres")
        .row.justify-content-center.align-items-center
          .col-md-11
            h5 Calidad total
            p Los colaboradores de bajo nivel hasta los ejecutivos de más alto rango se concentran en mejorar la calidad y, por lo tanto, brindar servicios al cliente dejando como resultado la satisfacción.
            p Se centra en las mejoras de procesos a largo plazo, en lugar de simplemente enfatizar las ganancias financieras a corto plazo.
      div(x="33.4%" y="72%" tooltip="tooltip de max 35 caracteres")
        .row.justify-content-center.align-items-center
          .col-md-11
            h5 Kaizen
            p Cuando se aplica al lugar de trabajo, significa una mejora continua que involucra a todos, tanto a los gerentes como a los trabajadores, implica hacer que el ambiente de trabajo sea más eficiente y eficaz, creando una atmósfera de equipo, mejorando los procedimientos cotidianos y asegurando el compromiso de los empleados.
      div(x="50.6%" y="72%" tooltip="tooltip de max 35 caracteres")
        .row.justify-content-center.align-items-center
          .col-md-11
            h5 Justo a tiempo
            p Las empresas emplean esta estrategia para aumentar la eficiencia y disminuir el desperdicio. Se aplica justo a tiempo a través de un sistema de inventario que alinea los pedidos de materias primas de los proveedores directamente con los programas de producción; también reduce los costos de inventario. 
            p Este método requiere que los productores pronostiquen la demanda con precisión, solo cuando la necesiten para el proceso de producción, reduciendo los costos de inventario. 
      div(x="68%" y="72%" tooltip="tooltip de max 35 caracteres")
        .row.justify-content-center.align-items-center
          .col-md-11
            h5 Reingeniería
            p La ejecución adecuada de la reingeniería puede cambiar las reglas del juego para cualquier negocio. Si se maneja adecuadamente, la reingeniería de procesos de negocios puede hacer milagros en una empresa en quiebra o estancada, aumentando las ganancias e impulsando el crecimiento.
            p La productividad de los empleados definitivamente se ve afectada durante la reingeniería de procesos; si los procesos se gestionan mejor durante el tiempo de ejecución, la necesidad de reingeniería se reduce considerablemente.
      div(x="84.7%" y="72%" tooltip="tooltip de max 35 caracteres")
        .row.justify-content-center.align-items-center
          .col-md-11
            h5 Benchmarking
            p Tiene como objetivo proponer un modelo de evaluación comparativa, que se puede aplicar para todos los tipos de mediciones. Es necesario evaluar los puntos fuertes y débiles de la operación interna. 
            p Solo se estará preparado para diferenciar sus posibilidades en el mercado si se conoce la fuerza y debilidad de las competencias.

    separador

    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.4. Recursos

    p.mb-5 Cuando se comienza un negocio, es posible que se haya pensado que todo se trataba de los ingresos que puede obtener, qué tan grande puede llegar a ser y en qué piso estará la oficina. Los recursos organizacionales se combinan, usan y transforman en productos terminados durante el proceso de producción.

    .row.justify-content-center
      .col-md-10.col-12.mb-3
        .bloque-texto-c.color-secundario.p-4.mb-5
          i.fas.fa-quote-right
          h5.mb-2 Desde el punto de vista de Peter Drucker, en el escrito de Sánchez Murillo (2006), los gerentes dan dirección a sus organizaciones, brindan liderazgo y deciden cómo usar los recursos de la organización para lograr las metas.
        p.mb-5 A continuación, se describen los tipos de recursos existentes y necesarios en una organización para posicionarse en el mercado:
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.justify-content-center.px-4(titulo="Recursos humanos")
            .col-4.p-0
              figure
                img(src='@/assets/curso/tema1/img61.png')
            .col-8
              p Son las personas que trabajan para una organización. Sus habilidades y conocimientos son invaluables para los gerentes. La actitud de los expertos debe administrar la organización y saber trabajarla de manera efectiva. Enfatiza la oportunidad de aplicar el conocimiento y la necesidad de aprender y crecer al hacerlo, el conocimiento no tiene sentido a menos que haya la oportunidad de aplicarlo y esto se logra a través de la exposición.
              p La capacitación, por otro lado, es un esfuerzo organizacional destinado a ayudar a un empleado a adquirir las habilidades básicas requeridas para la ejecución efectiva y eficiente de las funciones para las que ha sido contratado.
            p El desarrollo de la mano de obra es típicamente una parte de la estrategia de recursos humanos de la organización y tiene como objetivo maximizar el potencial del capital humano para alcanzar los objetivos comerciales estratégicos 
          .row.justify-content-center.px-4(titulo="Recursos monetarios o financieros")
            .col-4.p-0
              figure
                img(src='@/assets/curso/tema1/img62.png')
            .col-8
              p Estos, a menudo, incluyen efectivo, crédito y líneas de crédito, junto con la capacidad de tener opciones de planes de acciones para los empleados de la organización. La mayoría de las empresas tienen recursos financieros de manera regular, pero pocas empresas tendrán recursos financieros extremadamente sólidos, como los bancos, que se basan completamente en recursos financieros y los utilizan como un recurso clave.
            p La función de la administración es planificar, organizar, dotar de personal, dirigir y controlar. Cada una de estas funciones está influenciada en gran medida por la cantidad de dinero que hay. Los gerentes y el personal del programa simplemente no pueden llevar a cabo sus responsabilidades asignadas de manera efectiva sin comprender sus limitaciones financieras. Los gerentes deben tener algún medio para saber lo que está sucediendo con respecto a sus recursos financieros si van a tomar decisiones gerenciales informadas. Necesitan hacer un seguimiento de cómo se gasta el dinero, un informe que dicte cuánto dinero había, cuánto se gastó, en qué se gastó y cuánto queda. 
            p Esta responsabilidad se lleva a cabo instalando y administrando un sistema de contabilidad financiera, se dispone de una serie de programas informáticos aceptables para satisfacer esta necesidad contable. Por lo general, es innecesario para la mayoría de las organizaciones dedicar tiempo y recursos a diseñar e implementar un sistema único. 
          .row.justify-content-center.px-4(titulo="Recursos de capital o de producción")
            .col-4.p-0
              figure
                img(src='@/assets/curso/tema1/img63.png')
            .col-8
              p Las materias primas son los elementos utilizados directamente para la fabricación de productos, proporcionando un suministro adecuado de materiales al menor costo posible; es decir, se ocupa de las materias primas, la adquisición de máquinas y otros equipos necesarios para el proceso de producción, y repuestos para el mantenimiento de la planta. 
              p Comienza con la determinación de la calidad y cantidad de los materiales, y finaliza con su envío a producción para satisfacer la demanda del cliente, según el cronograma y al menor costo.  
          .row.justify-content-center.px-4(titulo="Recursos comerciales")
            .col-4.p-0
              figure
                img(src='@/assets/curso/tema1/img64.png')
            .col-8
              p Los recursos comerciales son de naturaleza no física e intangible, como las patentes del producto, las marcas de la organización, los datos del cliente y el conocimiento del cliente, e incluso el talento en la organización como una forma de recurso intelectual. 
              p Una vez que se desarrollan, pueden ofrecer ventajas únicas a la organización, como ofrecer descuentos y ofertas especiales para clientes habituales o compras repetidas del mismo cliente. Los tipos de recursos comerciales afectarán la sostenibilidad de la organización junto con su rentabilidad. 
          .row.justify-content-center.px-4(titulo="Recursos físicos")
            .col-4.p-0
              figure
                img(src='@/assets/curso/tema1/img64.png')
            .col-8
              p Estos se consideran activos tangibles que la organización utiliza para crear una oferta de valor y una propuesta para sus clientes. Los recursos físicos pueden incluir el equipo, los edificios, el inventario, la planta de fabricación y la red de distribución, que son extremadamente cruciales para que el negocio funcione correctamente. Los recursos físicos son importantes para el funcionamiento de la organización, ya que, sin cosas como equipo, inventario y planta de fabricación es difícil que la empresa funcione.
            p Son las máquinas utilizadas durante el proceso de fabricación. Las máquinas modernas pueden mejorar en gran medida la eficiencia del proceso de fabricación. Si una organización usa maquinaria vieja y obsoleta, es posible que no pueda competir con una organización que use maquinaria más eficiente.  La gestión de materiales es la planificación, dirección, control y coordinación de aquellas actividades relacionadas con los requisitos de materiales e inventario, desde el punto de su inicio hasta su introducción en el proceso de fabricación.
      .col-md-8.col-10.mb-3.BG07.p-3
        p.mb-0 Los recursos que son importantes para la organización y crean una propuesta de valor en el servicio a sus clientes, y además le entregan el producto, se denominan recursos clave. Estos tipos de recursos comerciales son cruciales y es importante tenerlos para que su negocio tenga éxito. Suelen basarse en recursos tangibles e intangibles.

    separador

  .container.BGIMG07.px-4.px-md-5.pt-4  
    #t_1_5.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.5 Planeación

    p.mb-5 Aquí es donde se pronosticarán los objetivos y metas que debe cumplir la empresa y los métodos a llevar a cabo. También contribuye a asignar eficientemente los recursos. Entre sus premisas, se encuentran:

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
      h5 Figura 10
      span Premisas de la planeación
    figure.mb-5(data-aos="zoom-in")
      img(src='@/assets/curso/tema1/img67.svg')

    .row.justify-content-center.mb-5
      .col-md-10.col-12
        p.mb-5 En una organización, la planeación de la gestión es el establecimiento de una estrategia que permite alcanzar un conjunto de objetivos preestablecidos. Dentro del proceso de planeación, se pueden identificar los siguientes pasos en los que se involucran algunas actividades específicas.
        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
          h5 Figura 11
          span Proceso de planeación
        figure.mb-5(data-aos="zoom-in")
          img(src='@/assets/curso/tema1/img68.svg')
      .col-md-6.col-12
        p Los principios de la planeación, por su parte, se pueden describir de esta manera:

    SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
      .tarjeta-avatar
        img(src='@/assets/curso/tema1/img69.svg' alt='AvatarTop')
        .tarjeta.color-primario
            .p-5
              p <b>Inherencia:</b> toda organización debe contar con un plan que determine cómo resolver determinados problemas y así alcanzar los objetivos de la forma más eficiente posible.
      .tarjeta-avatar
        img(src='@/assets/curso/tema1/img70.svg' alt='AvatarTop')
        .tarjeta.color-primario
            .p-4
              p.mb-0 <b>Racionalidad:</b> consiste en comprender un problema para luego determinar los criterios de diseño del plan, el establecimiento de alternativas y su aplicación. 
              p Las decisiones deben tomarse con base en la lógica y la razón, no de acuerdo con las emociones y los valores.
      .tarjeta-avatar
        img(src='@/assets/curso/tema1/img71.svg' alt='AvatarTop')
        .tarjeta.color-primario
            .p-5
              p.mb-0 <b>Unidad:</b> se asignan objetivos que, a su vez, deberán orientarse hacia una meta común; si bien existe un plan para cada una de las funciones, todas deben unirse en un plan principal.
      .tarjeta-avatar
        img(src='@/assets/curso/tema1/img72.svg' alt='AvatarTop')
        .tarjeta.color-primario
            .p-5
              p.mb-0 <b>Compromiso:</b> para llegar a la meta, se debe calcular el tiempo que implica el compromiso de cada recurso.
      .tarjeta-avatar
        img(src='@/assets/curso/tema1/img73.svg' alt='AvatarTop')
        .tarjeta.color-primario
            .p-5
              p.mb-0 <b>Exactitud:</b> el plan debe ser exacto, cualquier error puede afectar el resto de funciones de la organización, cuanto más precisos los planes, mayores serán las posibilidades de lograr los objetivos.
      .tarjeta-avatar
        img(src='@/assets/curso/tema1/img74.svg' alt='AvatarTop')
        .tarjeta.color-primario
            .p-5
              p.mb-0 <b>Factibilidad:</b> todo plan debe ser realista: diseñado con base en la experiencia, hechos concretos y recursos disponibles.            

    p.mb-5 Ahora bien, con base en toda la descripción previamente dada sobre la planeación, se destacan ciertos elementos que la componen de manera transversal. 

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
      h5 Figura 12
      span Elementos que componen la planeación
    figure.mb-5(data-aos="zoom-in")
      img(src='@/assets/curso/tema1/img75.svg')

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
