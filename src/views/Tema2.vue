<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 2
      h1 Configuración de la red
    p A continuación, se describen los principales dispositivos que permiten la configuración de la red.
    .separador
    #t_2_1.titulo-segundo
      h2 2.1. Configuración del router TPLINK con referencia TL-MR3220
    p Una interfaz es una herramienta que permite dar acceso directo a la configuración, sistema operativo y demás funcionalidades de cada dispositivo, generalmente se trata de una interfaz gráfica que por medio de un monitor, pantalla o terminal que da acceso a una serie de menús e iconos a utilizar por parte del usuario en la interacción con los dispositivos de la red que necesitan ser configurados o actualizados para su correcto funcionamiento dentro del sistema. Algunas de las características que posee una interfaz son:
    .row.align-items-center.p-5
      .col-lg-4.mx-auto
        img(src="@/assets/curso/t2/f1.svg", alt="Joven sentado sobre routers wifi").py-4
      .col-lg-6.mx-auto
        ul.lista-ul--separador
          li 
            i.fas.fa-play.texto-acento-contenido.me-4
            | Facilidad de uso, aprendizaje y comprensión.
          li 
            i.fas.fa-play.texto-acento-contenido.me-4
            | Representación fija y permanente del área de trabajo o fondo.
          li 
            i.fas.fa-play.texto-acento-contenido.me-4
            | Fácil identificación del objeto o dispositivo de interés.
          li 
            i.fas.fa-play.texto-acento-contenido.me-4
            | Diseño ergonómico con menús, barras de acción e iconos de fácil acceso.
          li 
            i.fas.fa-play.texto-acento-contenido.me-4
            | Operaciones rápidas, incrementales y reversibles, con efectos inmediatos.
          li 
            i.fas.fa-play.texto-acento-contenido.me-4
            | Variedad de herramientas de ayuda y consulta.
    p Los tipos de interfaz de usuario más conocidos son:
    .row.align-items-center
      .col-lg-8
        .tarjeta-avatar-b.mb-5
          img(src="@/assets/curso/t2/f2.svg", alt="icono laptop")
          .tarjeta.fondo-azul-clarito
            .p-4
              .h2 Interfaz GUI
              p Usadas para aplicaciones web, móviles, escritorio y juegos que permiten interacción al usuario.
        .tarjeta-avatar-b.mb-5
          img(src="@/assets/curso/t2/f3.svg", alt="icono tablet")
          .tarjeta.fondo-azul-clarito
            .p-4
              .h2 Interfaz de usuario de pantalla táctil
              p Diseñadas para pantallas táctiles, sin botones físicos, se encuentran en smartphone, tablets, cajeros automáticos, etc.
        .tarjeta-avatar-b.mb-5
          img(src="@/assets/curso/t2/f4.svg", alt="icono desktop")
          .tarjeta.fondo-azul-clarito
            .p-4
              .h2 Interfaz natural de usuario (NUI)
              p En estos casos se interactúa con un sistema, aplicación y demás, sin utilizar dispositivos de entrada como ratón, teclado y lápiz óptico, a cambio de estos se utilizan las manos o las yemas de los dedos.
      .col-lg-3.mx-auto
        img(src="@/assets/curso/t2/f5.svg", alt="persona con dispositivos")







</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
