<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-between.align-items-center.mb-4
      .col-lg-9
        p Una red inalámbrica es la red que no emplea cables para transmitir la información, utilizando estándares especialmente de la <b>IEEE con siglas en inglés (Institute of Electronics and Electrical Engineers)</b>.
        p El primer ejemplo de comunicación sin cables fue en 1880, en este año Graham Bell y Summer Tainter inventaron el fotófono, que permitía transmitir sonido por medio de una emisión de luz, luego en 1888 el físico alemán Rudolf Hertz descubrió la propagación de las ondas electromagnéticas, así, seis años después, las ondas de radio ya eran un medio de comunicación. Se menciona que en 1899 el italiano Guillermo Marconi logró establecer comunicaciones mediante señales inalámbricas a través del canal de la Mancha, entre las ciudades de Dover y Wilmereux.
      .col-lg-3
        img(src="@/assets/curso/i-f1.svg", alt="Imagen alusiva a redes").p-4
    .row.justify-content-between.align-items-center.mb-4
      .col-lg-3
        img(src="@/assets/curso/i-f2.svg", alt="Imagen alusiva a redes").p-4
      .col-lg-9
        p En 1907 se comunicaron los primeros mensajes completos a través del Atlántico. Otro dato a tener en cuenta sobre el año 1971 es que un grupo de investigadores bajo la dirección de Norman Abramson, de la Universidad de Hawái, fueron pioneros con el sistema de conmutación de paquetes mediante una red de comunicación por radio llamada ALOHA. Se puede describir que esta fue la primera WLAN, estaba formada por siete computadores situados en distintas islas que se podían comunicar por medio de un servidor. De ahí nació lo que hoy en día se conoce como wifi, en 1997 sale al mercado gracias a la creación del comité 802.11, en el que se dio paso a la estandarización IEEE 802.11 para redes de área local inalámbricas (WLAN).
    .cajon.color-acento-contenido.p-4.mb-4
      p En relación con la elaboración del componente es importante especificar que se abordaron varios autores conocidos en el campo de las redes inalámbricas; se referencian en la bibliografía aquellos de quienes se tomaron los conceptos y ejemplos; respetando al igual que ellos, la recopilación y producción de material para el uso en educación. Es preciso señalar que el conocimiento es social y, por lo tanto, es para usarlo; cuando se investiga especialmente en el campo de la educación se busca aportar a la formación de quienes necesitan adquirir el conocimiento. Se espera que este documento sea útil para todos, aprendices y lectores en general, que estén interesados en acercarse a asuntos básicos de las redes de datos.
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
