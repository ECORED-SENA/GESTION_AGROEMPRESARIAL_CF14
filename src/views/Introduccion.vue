<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p Se da la bienvenida al estudio del componente #[b “Seguimiento de las estrategias de mercado”]; se desea que todos los participantes tengan una buena experiencia de aprendizaje. Se debe comenzar con la observación del video que se muestra enseguida. 
    p #[span.txt-color1 ¡Adelante!]

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/LpQhFuXyVVo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)(data-aos="fade-right")
        
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
