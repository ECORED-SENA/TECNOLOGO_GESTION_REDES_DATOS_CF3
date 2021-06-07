<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 Introducción a las redes inalámbricas
    #t_1_1.titulo-segundo
      h2 1.1 Clasificación de redes inalámbricas
    p Según Andreu (2011) las redes inalámbricas se clasifican en los siguientes grupos:
    TabsC.color-acento-contenido
      .py-3.py-md-4(titulo="Red WBAN")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            img(src="@/assets/curso/t1/f1.svg", alt="Ilustración red WBAN").p-4
          .col-md-6.mb-4.mb-md-0
            h5 Redes inalámbricas de área corporal o WBAN 
            p (Wireless Body Area Network) con cobertura entre 1 a 2 metros.
      .py-3.py-md-4(titulo="Red WPAN")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            img(src="@/assets/curso/t1/f2.svg", alt="Ilustración red WPAN").p-4
          .col-md-6.mb-4.mb-md-0
            h5 Redes inalámbricas de área personal o WPAN
            p (Wireless Personal Área Network). Su alcance es por debajo de los 10 metros, usadas para para comunicar dispositivos de un usuario como, por ejemplo, el PC y la impresora, ya sea por uso de bluetooth o de IEEE 802.15.
      .py-3.py-md-4(titulo="Red WLAN")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            img(src="@/assets/curso/t1/f3.svg", alt="Ilustración red WLAN").p-4
          .col-md-6.mb-4.mb-md-0
            h5 Redes inalámbricas de área local o WLAN
            p (Wireless Local Area Network). Tienen un alcance de cientos de metros, utilizadas para comunicar dispositivos ubicados en un mismo edificio o grupos de edificios como, por ejemplo, HomeRF o wifi.
      .py-3.py-md-4(titulo="Red WMAN")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            img(src="@/assets/curso/t1/f4.svg", alt="Ilustración red WMAN").px-5
          .col-md-6.mb-4.mb-md-0
            h5 Redes inalámbricas de área metropolitana o WMAN
            p (Wireless Metropolitan Area Network). Tienen como función cubrir una ciudad, utilizando protocolo LMDS (Local Multipoint Distribution Service) o MMDS (Multichannel Multipoint Distribution Service).
      .py-3.py-md-4(titulo="Red WBAN")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            img(src="@/assets/curso/t1/f5.svg", alt="Ilustración red WWAN").p-4
          .col-md-6.mb-4.mb-md-0
            h5 Redes inalámbricas de área extensa o WWAN
            p (Wireless Wide Area Network). Conocidas también como de área global o WGAN, tienen cobertura de una gran región, país o grupo de países, basadas en tecnología celular, y son consideradas como la evolución de las redes de voz.
    .separador
    #t_1_2.titulo-segundo
      h2 1.2 Funcionamiento de las redes inalámbricas
    .row.align-items-center.fondo-azul-clarito.p-5
      .col-lg-4.mx-auto
        img(src="@/assets/curso/t1/f6.svg", alt="Persona inspeccionando elementos").py-4
      .col-lg-8.mx-auto
        p Para el funcionamiento de las redes inalámbricas es relevante diferenciar algunas características como la frecuencia de trabajo, velocidad de transmisión y cobertura, para lo cual se utilizan ondas de radio que llevan la información hacia el destino. Las ondas de radio se refieren a portadoras que transportan la información, llevan la energía a un receptor remoto, y los datos que se envían se superponen a la portadora de radio y, finalmente se deben extraer en el receptor. A este proceso nombrado anteriormente se le conoce como modulación de la portadora, si las ondas se transmiten con frecuencias diferentes pueden existir envíos al mismo tiempo y espacio sin que haya interferencia. 
        p En las redes inalámbricas WLAN se presentan dos formas de funcionamiento que son:
        ul.lista-ul
          li 
            i.lista-ul__vineta
            p <b>Ad-hoc (IBSS).</b> Aquí cada equipo de la red se conecta con los demás, es considerado cliente y punto de acceso, pero con un máximo de nueve clientes.
          li 
            i.lista-ul__vineta
            p.mb-0 <b>Infraestructura (BSS).</b> Para este caso la conexión se hace utilizando un AP (punto de acceso), el cual permite que la red inalámbrica acceda la red cableada, dicho AP trabaja como puerta de entrada a la red inalámbrica con una cobertura determinada y en un lugar específico para los dispositivos que necesiten acceder.
    .separador
    #t_1_3.titulo-segundo
      h2 1.3 Ventajas y desventajas
    p De acuerdo con Andreu (2011) las principales ventajas de utilizar una red inalámbrica son:
    .col-lg-11.mx-auto.mb-4
      .row.align-items-center
        .col-lg-6
          ul.lista-ul--separador
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              |	Permiten una amplia libertad de movimientos.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Facilitan reubicar las estaciones de trabajo.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Evitan establecer cableado.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Rapidez en la instalación de la red.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | De menor costo.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Tienen mayor cobertura en puntos de difícil acceso con cables.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Permiten la ampliación de redes locales cableadas.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Poseen facilidad de expansión o limitación de usuarios en la red con solo añadir o quitar módulos.
        .col-lg-6
          img(src="@/assets/curso/t1/f7.svg", alt="Router wifi").py-4
    p Y sus desventajas son:
    .col-lg-11.mx-auto.mb-4
      .row.align-items-center
        .col-lg-6
          img(src="@/assets/curso/t1/f8.svg", alt="Servidores").py-4
        .col-lg-6
          ul.lista-ul--separador
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Menor ancho de banda que las redes cableadas.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Las redes que usan señales infrarrojas deben estar perfectamente alineadas, y no pueden atravesar obstáculos como paredes, árboles, etc.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Son inseguras puesto que cualquiera puede acceder a la red inalámbrica.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Poseen un menor ancho de banda que las redes que se unen mediante cables.
    .separador
    #t_1_4.titulo-segundo
      h2 1.4 Componentes de las redes inalámbricas
    p Se encuentran integradas por los siguientes dispositivos:
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f9.svg' alt='Icono antena')
      .tarjeta.fondo-casi-blanco
        .p-4
          .h2 Antena
          p Elemento que permite transmitir y recibir ondas de radio por medio de una comunicación natural como el aire o el espacio libre.
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f10.svg' alt='Icono punto de acceso')
      .tarjeta.fondo-casi-blanco
        .p-4
          .h2 Punto de acceso
          p Dispositivo de capa 2, por medio del cual las estaciones wireless pueden integrarse rápida y fácilmente a cualquier red cableada, actuando como núcleo de la red inalámbrica y puente de conexión entre redes inalámbricas y cableadas. El punto de acceso se conecta a un router, switch o hub con un cable Ethernet y radia la señal wifi en un área específica, como ejemplo, si desea habilitar el acceso wifi en el área de recepción de una empresa, pero no existe un router que pueda cubrirla, se instala un punto de acceso cerca de la recepción y se conecta con un cable hacia el salón de equipos donde está el servidor.
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f11.svg' alt='Icono puente inalámbrico')
      .tarjeta.fondo-casi-blanco
        .p-4
          .h2 Bridge inalámbrico
          p Dispositivo que permite conectar dos o más redes ubicadas en diferentes edificios, proporcionando más velocidad de transmisión de datos, además conecta sitios difíciles de cablear, pisos no contiguos, instalaciones de campus de escuelas o empresas, etc.
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f12.svg' alt='Icono enrutador inalábrico')
      .tarjeta.fondo-casi-blanco
        .p-4
          .h2 Router inalámbrico
          p Es el que permite la conexión de redes inalámbricas, enrutar los paquetes de datos hacia la red correcta de destino y facilita la conexión a la WLAN de dispositivos inalámbricos; es la tecnología de comunicación de ondas de radio que admite la conexión ADSL para el manejo de Internet de banda ancha y que se distribuya hacia otros computadores.
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f13.svg' alt='Icono adaptador')
      .tarjeta.fondo-casi-blanco
        .p-4
          .h2 Adaptadores
          p Son tarjetas para expandir la capacidad de conexión, envían y reciben datos sin necesidad de cables en las redes WLAN, poseen una antena para la recepción y envío de datos, y están diseñados para algunos estándares de redes inalámbricas.
    .separador
    #t_1_5.titulo-segundo
      h2 1.5 Modos de operación
    .bloque-texto-a.color-acento-contenido.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-3.mb-4.mb-lg-0
          img(src='@/assets/curso/t1/f14.svg' alt='Imagen 4 computadores')
        .col-lg-9
          .bloque-texto-a__texto.p-5
            p Para el estándar 802.11 es importante tener en cuenta dos modos fundamentales de uso para este tipo de redes, el modo ad-hoc y el modo infraestructura BSS, los cuales se detallarán a continuación.
    .row.align-items-center.justify-content-between.mb-4
      .col-lg-6
        h3 Modo ad-hoc.
        p Se conoce también como punto a punto, en este método los clientes inalámbricos establecen comunicación directa entre sí, por tanto, no es necesario un punto de acceso o AP; cada terminal inalámbrica en una red ad- hoc configura el adaptador inalámbrico en este modo, y debe usar el mismo SSID y canal dentro de la red. Este método limita el número de dispositivos, y si estos aumentan, el rendimiento de la red disminuye, además la conexión ad-hoc es temporal entre dispositivos para un mismo fin, por ejemplo, compartir impresoras, archivos o juegos en la red.
        .cajon.color-acento-contenido.p-4.mb-4
          p.mb-0 La conexión de los equipos se realiza por medio de los adaptadores de red sin necesidad de un punto de acceso. Una infraestructura ad-hoc tendría mínimo 2 computadores, tarjetas de red inalámbrica y, de hecho, los drivers de tarjetas de red. 
        p De manera que en la tabla que aparece a continuación puede consultar tanto las ventajas como desventajas del modo ad-hoc.
      .col-lg-6
        img(src='@/assets/curso/t1/f15.svg' alt='Ilustración modo ad-hoc')
    .titulo-quinto.color-acento-contenido
      h4 Ventajas y desventajas modo ad-hoc
    .tabla-a.color-acento-botones.mb-5 
      table
        caption Leyenda de la tabla
        thead
          tr
            th.texto-acento-contenido Ventajas
            th.texto-acento-contenido Desventajas
        tbody
          tr
            td No necesita conexión a Internet.
            td Compatibilidad de tarjetas de red para conexión en modo ad–hoc.
          tr
            td Hay acceso a los datos de los dispositivos conectados a la red.
            td Es necesario configurar cada vez que se va a usar.
          tr
            td Realiza el envío directo de información.
            td No conecta dispositivos ubicados dentro del área de cobertura.
          tr
            td Tiene gestión no centralizada.
            td En la transmisión entre dos o más nodos simultáneos se presenta interferencia y competencia para acceder al medio.
          tr
            td La configuración es mínima.
            td 
    h3 Modo infraestructura BSS.







</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
