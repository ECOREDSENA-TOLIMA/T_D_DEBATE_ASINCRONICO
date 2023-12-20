<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Debate asíncrono

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Definición

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-12.col-md-5.mb-2
        img(src='@/assets/curso/temas/img-1.png', alt='')
      .col-12.col-md-7
        .cajon.color-primario.p-4.mb-3
          p.mb-0 En el debate asincrónico se facilita la discusión entre dos o más personas, que opinan acerca de uno o varios temas, exponiendo sus ideas y defendiendo sus opiniones e intereses. Los debates asincrónicos son útiles para desarrollar el pensamiento crítico, la comunicación electrónica y las habilidades de participación de los aprendices, mientras aprenden el contenido temático relacionado.
        p.mb-0 Además, “#[em El debate permite a sus participantes explorar los argumentos a favor y en contra de una resolución determinada, sus fortalezas y debilidades, y las diferentes maneras de expresarlos.]” Mamberti, Bonomo y Miller, 2009.

    Separador
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Elementos que componen un debate asincrónico
          
    .row.justify-content-center.mb-5
      .col-12.col-md-11.col-lg-9(data-aos="fade-left")
        //- .titulo-sexto.color-acento-contenido
        //-   p.titulo.pb-0.mb-0 <b>Figura 1. </b> <i>Gobierno, Riesgo y Cumplimiento GRC</i>
        figure
          img.d-none.d-sm-none.d-md-block(src='@/assets/curso/temas/fig-1a.svg', alt='El debate  asincrónico  se compone de  tres partes: 1 - Tema, 2 - Participantes y 3 - Formato')
          img.d-block.d-md-none(src='@/assets/curso/temas/fig-1b.svg', alt='El debate  asincrónico  se compone de  tres partes: 1 - Tema, 2 - Participantes y 3 - Formato') 

    p.mb-3(data-aos="fade-down") #[b Tema, resolución, premisa inicial:] el debate se centra en un tema o resolución que, básicamente es una afirmación que posee características particulares que facilitan el desarrollo de un debate en torno a ella.  
    p.mb-3(data-aos="fade-down") #[b Participantes:] habitualmente, los participantes, compiten en dos equipos: el afirmativo o a favor y el negativo o en contra. El equipo afirmativo debe apoyar la resolución que se debate a través de la presentación de un “caso o tema” a favor; una serie detallada de razones que muestran por qué se debería aceptar la resolución. Por su parte, el equipo negativo debe refutar el caso afirmativo. En algunos formatos, además, el equipo negativo también tiene el deber de presentar un caso propio en contra de la resolución.
    p.mb-5(data-aos="fade-down") En un debate, los equipos suelen tener tres responsabilidades centrales:

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-12.col-md-7.mb-2
        .tarjeta.color-acento-contenido.p-4.mb-3
          ol.lista-ol--cuadro.mb-0
            li 
              .lista-ol--cuadro__vineta
                span 1
              | Presentar argumentos a favor de su posición.
            li 
              .lista-ol--cuadro__vineta
                span 2
              | Refutar los argumentos presentados por el equipo contrario.
            li.mb-0
              .lista-ol--cuadro__vineta
                span 3
              | Defender los argumentos propios ante las refutaciones recibidas.
        p.mb-3 Dentro de los participantes, se encuentra un público imparcial que puede ejercer como “juez”. Las funciones del juez en algunos casos, es determinar el equipo ganador. La participación del jurado no es obligatoria, sin embargo, su presencia es muy importante al menos por dos razones. En primer lugar, el jurado es un incentivo que hace el ejercicio de debate más entretenido para los participantes. En segundo lugar, el jurado proporciona a los participantes una evaluación externa y consejos útiles para mejorar su desempeño. En los casos de debate educativo, en la mayoría de casos el docente ejerce este rol.
        p.mb-3 #[b Formato:] es aquel que determinará la estructura de la actividad, de acuerdo con el contexto, necesidades y objetivo educativo propuesto por el instructor. Acá se plantean los parámetros de participación dentro del debate, la participación no es en tiempo real, esto proporciona oportunidades para que los estudiantes refinan su comprensión del tema durante un período más largo. Este puede ser a través de un foro, o una herramienta #[em Web]. 
      .col-12.col-md-5
        img(src='@/assets/curso/temas/img-2.png', alt='')

    Separador
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Pasos para participar en  un debate asincrónico

    TabsA.color-acento-botones.mb-5
      .tarjeta.color-primario.p-4(titulo="Lectura")
        h4 Lectura
        .row
          .col-md-9.col-lg-9.mb-4
            p Se debe realizar la lectura de las indicaciones del instructor.
          .col-md-3.col-lg-2
            figure
              img(src='@/assets/curso/temas/img-3.png', alt='')
      .tarjeta.color-primario.p-4(titulo="Desarrollar el argumento")
        h4 Desarrollar el argumento
        .row
          .col-md-9.col-lg-9.mb-4
            p Pensar en una tesis y cómo apoyarla, luego leer las otras publicaciones y ver cómo apoyan o contradicen su idea, luego escribir sobre esto. Asegurarse de respaldar lo que se dice con referencias a materiales del curso o fuentes externas, como lecturas, y posteriormente llevar a publicación la idea personal. 
          .col-md-3.col-lg-2
            figure
              img(src='@/assets/curso/temas/img-4.png', alt='')
      .tarjeta.color-primario.p-4(titulo="Fomentar el debate")
        h4 Fomentar el debate
        .row
          .col-md-9.col-lg-9.mb-4
            p Leer las opiniones de los compañeros y tomar postura frente a estas, se puede estar a favor o en desacuerdo, para mostrar diferentes perspectivas, es posible contradecir a un compañero de clase. Si no se está de acuerdo, debe expresarse con respeto (sin insultos) y respaldar los puntos de vista con evidencias. La contribución ayuda a que la discusión sea más productiva para todos los involucrados.
            p También se debe estar revisando si la publicación realizada ha tenido comentarios, y responderlos si es el caso.
          .col-md-3.col-lg-2
            figure
              img(src='@/assets/curso/temas/img-5.png', alt='')
      .tarjeta.color-primario.p-4(titulo="Publicaciones claras")
        h4 Publicaciones claras
        .row
          .col-md-9.col-lg-9.mb-4
            p Escribir uno o dos párrafos significativos, porque los mensajes largos son difíciles de leer en línea.
          .col-md-3.col-lg-2
            figure
              img(src='@/assets/curso/temas/img-6.png', alt='')
      .tarjeta.color-primario.p-4(titulo="Citar las fuentes")
        h4 Citar las fuentes
        .row
          .col-md-9.col-lg-9.mb-4
            p Si se toman referentes para ratificar opiniones, se deben citar según las normas APA, séptima edición.
          .col-md-3.col-lg-2
            figure
              img(src='@/assets/curso/temas/img-7.png', alt='')
      
    Separador
    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.4 Recomendaciones para participar en un debate asincrónico

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/img-8.png')})`}"
      )
      .bloque-texto-g__texto.d-inline.p-4
        ul.lista-ul.mb-0
          li.mb-1.d-block
            span.icon ✔ 
            | Hacer preguntas que inviten a la reflexión.
          li.mb-1.d-block
            span.icon ✔ 
            | Dar y pedir ejemplos a sus compañeros si es necesario.
          li.mb-1.d-block
            span.icon ✔ 
            | Ser respetuosos con las opiniones de los demás, estar abiertos a nuevas perspectivas es uno de los objetivos de las discusiones académicas.
          li.mb-1.d-block
            span.icon ✔ 
            | Escribir de forma clara y concisa.
          li.mb-1.d-block
            span.icon ✔ 
            | Revisar la ortografía y la gramática antes de publicar.
          li.mb-1.d-block
            span.icon ✔ 
            | Evitar usar mayúsculas sostenida, porque se puede interpretar como gritar.
          li.mb-1.d-block
            span.icon ✔ 
            | Citar las fuentes de información y atribuciones. 
    
    Separador
    #t_1_5.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.5 Herramientas digitales para el debate asincrónico 

    p.mb-5(data-aos="fade-down") El instructor indicará la herramienta digital donde se desarrollará el debate asincrónico, no obstante, se listan a continuación algunas de ellas: 

    .row.justify-content-center.mb-5(data-aos="fade-right")
      .col-sm-6.col-xl-3.col-md-5.mb-4.mb-xl-0(data-aos="fade-right")
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/temas/cn_1.png' alt='')
          .tarjetas-up_card.p-xl-4.p-lg-3.p-4(style="background-color: #DBE5F3")
            .title.d-flex.align-items-center.mb-lg-2.mb-md-5.mb-3
              span
                i.fas.fa-caret-up.fa-2x.me-3(style="color:#B40E0E")
                i.fas.fa-caret-down.fa-2x.me-3(style="color:#B40E0E")
              h5.mb-0 Foro
            p Dentro de la plataforma LMS se encuentra los foros, espacio en el cual se pueden discutir diversos temas e intercambiar ideas.  
      .col-sm-6.col-xl-3.col-md-5.mb-4.mb-xl-0(data-aos="fade-up")
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/temas/cn_2.png' alt='')
          .tarjetas-up_card.p-xl-4.p-lg-3.p-4(style="background-color: #DBE5F3")
            .title.d-flex.align-items-center.mb-lg-2.mb-md-5.mb-3
              span
                i.fas.fa-caret-up.fa-2x.me-3(style="color:#B40E0E")
                i.fas.fa-caret-down.fa-2x.me-3(style="color:#B40E0E")
              h5.mb-0 #[em Appgree]
            p Es una plataforma que ofrece la posibilidad de realizar debates y votaciones en tiempo real con una particularidad, el recuento de votos es muy rápido.
      .col-sm-6.col-xl-3.col-md-5.mb-4.mb-xl-0(data-aos="fade-right")
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/temas/cn_3.png' alt='')
          .tarjetas-up_card.p-xl-4.p-lg-3.p-4(style="background-color: #DBE5F3")
            .title.d-flex.align-items-center.mb-lg-2.mb-md-5.mb-3
              span
                i.fas.fa-caret-up.fa-2x.me-3(style="color:#B40E0E")
                i.fas.fa-caret-down.fa-2x.me-3(style="color:#B40E0E")
              h5.mb-0 #[em Reddit]
            p Es una red de comunidades donde la gente puede explorar sus intereses, aficiones y pasiones. 
      .col-sm-6.col-xl-3.col-md-5.mb-4.mb-xl-0(data-aos="fade-up")
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/temas/cn_4.png' alt='')
          .tarjetas-up_card.p-xl-4.p-lg-3.p-4(style="background-color: #DBE5F3")
            .title.d-flex.align-items-center.mb-lg-2.mb-md-5.mb-3
              span
                i.fas.fa-caret-up.fa-2x.me-3(style="color:#B40E0E")
                i.fas.fa-caret-down.fa-2x.me-3(style="color:#B40E0E")
              h5.mb-0 #[em Loomio]
            p Sirve para crear discusiones sobre temas específicos. Los miembros autorizados pueden publicar comentarios y crear propuestas, o mejorar propuestas existentes.

    Separador
    #t_1_6.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.6 Ejemplo de un debate asincrónico 

    .row.justify-content-center.mb-5
      .col-12.col-md-11.col-lg-10(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 <b>Figura 1. </b> <i>Ejemplo de un debate asincrónico </i>
        figure
          img.d-none.d-sm-none.d-md-block(src='@/assets/curso/temas/figura-1a.svg', :alt='altImg1')
          img.d-block.d-md-none(src='@/assets/curso/temas/figura-1b.svg', :alt='altImg1') 
          figcaption Nota: adaptado de “Dinamización de evidencias y Foros con Audios”. Sena.edu.co


      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
    mostrarIndicador: true,
    altImg1: `Respuestas
Aprendiz A
2023-04-10 11:29:23
Id respuesta: 420554717
Mi aporte al foro es el siguiente:
Para que cumpla su función de sostener la vida, el medio ambiente debe conservar sus propiedades naturales. Es decir, si se trata de un río, el agua debe permanecer limpia y con suficiente oxígeno disuelto. Si es el medio ambiente de una ciudad, el aire debe ser saludable, el agua debe ser potable y no debe haber focos de enfermedades. Por tanto, todo aquello que contamine el medio ambiente, es decir que altera sus propiedades naturales, es dañino. Lamentablemente, son varias las fuentes de contaminación.
0 Me gusta 1 Comentario(s) 1 Nuevo(s)
Aprendiz E
2023-04-10 11:25:37
id respuesta: 420552607
Hola instructora, mi opinión frente al cuestionamiento planteado en el foro es que en numerosas ocasiones, las regiones y países del mundo que cuentan con una valiosa fuente de riquezas naturales sufren también diversos problemas ambientales. Este escenario de usos irracionales de los recursos naturales y de deterioro ambiental podemos encontrarlo en Colombia, el segundo país del mundo que vive más conflictos ambientales en su día a día. Sin lugar a dudas, la pérdida de bosques, agua y biodiversidad pone en riesgo la seguridad del país latinoamericano.
Gracias...
0 Me gusta 0 Comentario(s)
    `,
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
