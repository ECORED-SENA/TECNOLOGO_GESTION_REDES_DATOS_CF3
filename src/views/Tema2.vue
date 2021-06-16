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
      h2 2.1 Configuración del router TPLINK con referencia TL-MR3220
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
          .tarjeta.fondo-casi-blanco
            .p-4
              .h2 Interfaz GUI
              p Usadas para aplicaciones web, móviles, escritorio y juegos que permiten interacción al usuario.
        .tarjeta-avatar-b.mb-5
          img(src="@/assets/curso/t2/f3.svg", alt="icono tablet")
          .tarjeta.fondo-casi-blanco
            .p-4
              .h2 Interfaz de usuario de pantalla táctil
              p Diseñadas para pantallas táctiles, sin botones físicos, se encuentran en smartphone, tablets, cajeros automáticos, etc.
        .tarjeta-avatar-b.mb-5
          img(src="@/assets/curso/t2/f4.svg", alt="icono desktop")
          .tarjeta.fondo-casi-blanco
            .p-4
              .h2 Interfaz natural de usuario (NUI)
              p En estos casos se interactúa con un sistema, aplicación y demás, sin utilizar dispositivos de entrada como ratón, teclado y lápiz óptico, a cambio de estos se utilizan las manos o las yemas de los dedos.
      .col-lg-3.mx-auto
        img(src="@/assets/curso/t2/f5.svg", alt="persona con dispositivos")
    p En el siguiente video se explicará la configuración del router TPLINK con referencia TL-MR3220.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video
    h3 Protección de la red inalámbrica
    .row.align-items-center.justify-content-between.mb-5
      .col-lg-6
        img(src='@/assets/curso/t2/f6.svg' alt='Personas conectadas a dispositivos')
      .col-lg-6
        p Una red inalámbrica es más vulnerable, pues la señal se difunde en el espacio libre, permitiendo que los usuarios con equipos cercanos puedan acceder a la información almacenada en los equipos de la red y usar la conexión a Internet.
        .cajon.color-acento-contenido.p-4.mb-4
          p.mb-0 Se debe cambiar el nombre de usuario, contraseña y SSID predeterminados para proteger el enrutador. Es importante configurar una contraseña para la red inalámbrica, dependiendo del tipo de protección deseada por parte del usuario, para ello existen entre otros tres tipos de seguridad o protección en el menú wireless security que son: 
        .col-lg-8.mx-auto
          ul.lista-ul--separador
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | WPA/WPA2 personal
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | WPA/WPA2 enterprise
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | WEP
    h3 Autenticación
    p La autenticación de sistema abierto consta de dos comunicaciones:
    .row.align-items-center.mb-4
      .col-lg-6
        img(src='@/assets/curso/t2/f6_5.svg' alt='En primer lugar, se envía una solicitud de autenticación desde el dispositivo móvil que contiene el ID de la estación (normalmente la dirección MAC). A continuación, una respuesta de autenticación del PA/enrutador con un mensaje de éxito o de fallo.').mb-4
        p Con la autenticación de clave compartida o frase de contraseña se configura manualmente tanto en el dispositivo móvil como en el PA/enrutador.
      .col-lg-4.mx-auto
        img(src='@/assets/curso/t2/f7.svg' alt='Personas conectadas a dispositivos')
    .separador
    #t_2_2.titulo-segundo
      h2 2.2	Seguridad, <i>firewall</i>, filtros, aplicaciones
    .bloque-texto-a.color-acento-contenido.p-md-4.mb-5 
      .row.m-0.align-items-center.justify-content-between.p-4
        .col-lg-4.mb-4.mb-lg-0
          img(src='@/assets/curso/t2/f8.svg' alt='ilustración servidores')
        .col-lg-8
          .bloque-texto-a__texto.p-5
            p Se debe tener en cuenta que son muchos los ataques que pueden existir para una red inalámbrica y gran cantidad de puertos se deben bloquear para minimizar estos riesgos, con la ayuda de normativas, protocolos, estándares y demás medidas que sean necesarias. Un firewall o cortafuegos permite proteger un dispositivo o una red completa de las intrusiones que provienen de una red exterior como el caso de Internet, usar un firewall también permite filtrar los paquetes de datos que circulan por la red, además un firewall puede ser de tipo software o de tipo hardware.
    .row.align-items-center.mb-4
      .col-lg-6
        p Un <i>firewall</i> funciona como una barrera entre Internet u otras redes públicas y los dispositivos. Todo el tipo de tráfico que no esté en la lista permitida por el firewall no entra ni sale de los dispositivos de la red, para ello contiene un conjunto de reglas predefinidas que permiten:
        .col-lg-8.mx-auto
          ul.lista-ul--separador
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Autorizar una conexión (allow).
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Bloquear una conexión (deny).
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Redireccionar un pedido de conexión sin avisar al emisor (drop).
      .col-lg-4.mx-auto
        img(src='@/assets/curso/t2/f9.svg' alt='Ilustración conexión segura').py-4
    .row.align-items-center.mb-4
      .col-lg-4.mx-auto
        img(src='@/assets/curso/t2/f10.svg' alt='Ilustración firewall').py-4
      .col-lg-6
        p También existe el <i>firewall</i> de software que se puede instalar y utilizar libremente o con licencia en los dispositivos de la red o con acceso a redes que se encarga de monitorear y bloquear, siempre que sea necesario, el tráfico sospechoso o de Internet. Sus características son:
        .col-lg-8.mx-auto
          ul.lista-ul--separador
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Los gratuitos se incluyen con el sistema operativo y normalmente son para uso personal.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Facilita la integración con otros productos de seguridad.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | No es necesario hardware para su instalación.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Un firewall comercial incluye protecciones extra, más control sobre su configuración y funcionamiento.
    .cajon.color-acento-contenido.p-4.mb-5
      p.mb-0 Por el contrario, un <i>firewall</i> por <i>hardware</i> viene normalmente instalado en los router que se utilizan para acceder a Internet, por tanto, todos los dispositivos que se conecten a un <i>router</i> estarán protegidos por un <i>firewall</i> que está incluido en el <i>router</i>, como se muestra en la siguiente figura.
    SlyderC.mb-5(:datos="datosSlider1")
    p El acceso inalámbrico puede filtrarse también con el uso de direcciones MAC (Media Access Control) de los dispositivos inalámbricos que transmiten dentro del radio de su red, permitiendo o restringiendo el acceso de dispositivos inalámbricos específicos a la red inalámbrica.
    p Para configurar el filtro MAC es necesario, entre otras cosas, identificar todas las direcciones MAC que se desean filtrar, y conectar los dispositivos inalámbricos al router para que tengan acceso a la red, como se muestra en la figura <i>Seguridad wireless</i>.
    .separador
    #t_2_3.titulo-segundo
      h2 2.3	Características adicionales de las redes
    p Las redes inalámbricas tienen diversas características dependiendo del rango de frecuencias, el medio y la velocidad de transmisión, entre las cuales están:
    TabsC.color-acento-contenido.mb-5
      .py-3.py-md-4(titulo="Ondas de radio")
        .row.align-items-center
          .col-lg-4.mx-auto
            img(src="@/assets/curso/t2/f11.svg", alt="Ilustración ondas de radio").py-4
          .col-lg-6
            .h2 Ondas de radio
            p Las ondas electromagnéticas (combinación de campos eléctricos y magnéticos oscilantes, que se propagan a través del espacio transportando energía de un lugar a otro) son omnidireccionales, así que no son necesarias antenas parabólicas. La transmisión no es sensible a las atenuaciones producidas por la lluvia, ya que se opera a frecuencias que no son demasiado elevadas.
      .py-3.py-md-4(titulo="Microondas por satélite")
        .row.align-items-center
          .col-lg-4.mx-auto
            img(src="@/assets/curso/t2/f12.svg", alt="Ilustración ondas por satelite").py-4
          .col-lg-6
            .h2 Microondas por satélite
            p Se hacen enlaces de dos o más estaciones terrestres que se les denomina estaciones base. El satélite recibe la señal (denominada señal ascendente) en una banda de frecuencia, la amplifica y la retransmite en otra banda (señal descendente); cada satélite opera en unas bandas concretas. Las fronteras frecuenciales de las microondas, tanto terrestres como por satélite, con los infrarrojos y las ondas de radio de alta frecuencia se mezclan bastante, así que puede haber interferencias con las comunicaciones en determinadas frecuencias.
      .py-3.py-md-4(titulo="Infrarrojos")
        .row.align-items-center
          .col-lg-4.mx-auto
            img(src="@/assets/curso/t2/f13.svg", alt="Ilustración infrarojos").py-4
          .col-lg-6
            .h2 Infrarrojos
            p Hay enlaces de transmisores y receptores que modulan la luz infrarroja no coherente. Deben estar alineados directamente o con una reflexión en una superficie. Las señales infrarrojas trabajan en la banda de 300 GHz hasta 384 THz.
      .py-3.py-md-4(titulo="Microondas terrestres")
        .row.align-items-center
          .col-lg-4.mx-auto
            img(src="@/assets/curso/t2/f14.svg", alt="Ilustración microondas terrestres").py-4
          .col-lg-6
            .h2 Microondas terrestres
            p Estas se utilizan en antenas parabólicas con un diámetro aproximado de unos tres metros. Tienen una cobertura de kilómetros, pero con el inconveniente de que el emisor y el receptor deben estar perfectamente alineados, por eso, se les denomina enlaces punto a punto en distancias cortas.
    .bloque-texto-a.color-acento-contenido.p-md-4.mb-5 
      .row.m-0.align-items-center.justify-content-between.p-4
        .col-lg-4.mb-4.mb-lg-0
          img(src='@/assets/curso/t2/f15.svg' alt='ilustración servidores')
        .col-lg-8
          .bloque-texto-a__texto.p-5
            p En concreto, dentro de las características adicionales se encuentra el control parental que se realiza para impedir, o limitar el acceso al manejo de dispositivos destinados a la reproducción o recepción de imágenes e información de determinados contenidos para los menores de edad, determinando con exactitud los dispositivos que se deben bloquear o proteger. Dado que el acceso a Internet de los menores hoy en día es increíblemente fácil y cada vez se produce a edades más tempranas, debido a que se pone al alcance de los dispositivos multimedia como smartphones o tablets, es imprescindible una buena educación digital. Como segundo apoyo, el uso de filtros y herramientas de control parental que les protejan de sitios y contenidos inseguros e inapropiados para estas edades. Por lo tanto, servirá para limitar el acceso de los pequeños a cierto contenido en Internet, limitar el tiempo que pasan los pequeños navegando o intercambiando información por Internet, como se muestra en la siguiente figura.
    .titulo-quinto.color-acento-contenido
      h4 Configuración control parental
    img(src='@/assets/curso/imagenes/cp.png' alt='Imagen control parental')
    p Como se indicó, se puede modificar los DNS de un equipo para que se filtre la información a través de ellos y llegue de manera segura, pero como alternativa a ello, hay otros métodos para instaurar un sistema de control parental cuando se tienen computadores que usan Windows como sistema operativo.
    .cajon.color-acento-contenido.p-4.mb-4
      .row.align-items-center
        .col-lg-3.mx-auto
          img(src='@/assets/curso/t2/f16.svg' alt='figura relacionada')
        .col-lg-8  
          p Si se utiliza Windows 10 hay que saber que tiene su propio sistema de control parental, al cual se puede acceder desde la configuración, y también desde una cuenta Microsoft a través de cualquier navegador. La idea es asignar a cada menor de la casa una cuenta de Windows y arrancar el computador desde esa cuenta. Las cuentas de adultos o sin restricciones se protegen mediante una contraseña alfanumérica y, las cuentas de los menores estarán protegidas a través de un PIN de 4 dígitos.
          p.mb-0 En el siguiente video se explicará la configuración del control parental.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video
    .row.align-items-center
      .col-lg-7
        p Por otro lado, toda la información registrada en la última semana, incluyendo el tiempo de conexión, los programas y web visitados podrán bloquear cualquier programa o web desde este mismo punto. Como es de esperar, este tipo de sistema de control parental de Windows 10 solo funciona en navegadores Microsoft Edge y Explorer; para evitar el uso de otro navegador se puede bloquear como se mencionó antes, o bien, instalar el control parental del que también disponen Google Chrome o Mozilla Firefox. 
        .cajon.color-acento-contenido.p-4.mb-4
          p La opción que ofrece el control parental de Windows 10 es la de configuración de acceso a contenidos multimedia, aplicaciones y juegos. Todos los contenidos multimedia como canales de televisión, películas, etc., tienen una clasificación de edad para su visionado, así como los juegos tienen su propio sistema de clasificación por edad en cada país, en España, por ejemplo, es el Sistema PEGI, esta es la clasificación a la que atenderá el filtro para permitir o denegar el acceso de cada cuenta a este tipo de contenidos. 
      .col-lg-3.mx-auto
        img(src="@/assets/curso/t2/f17.svg", alt="Ilustración persona y laptop").py-4
    p Se introduce el límite de edad y el explorador solo mostrará contenidos hasta esa edad, para edades mayores se mostrará el mensaje de bloqueo por control parental y el menor no podrá acceder a ellos. Otro dato importante es que se puede usar también este tipo de control en consolas XBOX, ya que pertenecen también a este gigante tecnológico, se puede bloquear el uso de la consola a ciertas horas, establecer una cuota de tiempo de uso o incluso, una franja horaria de funcionamiento.
    .row.align-items-center
      .col-lg-5.mx-auto
        img(src="@/assets/curso/t2/f18.svg", alt="Ilustración servidores").py-4
      .col-lg-7
        p De la mano de este filtro se puede también controlar el dinero que gasta el menor desde su cuenta en la tienda   Microsoft, este tipo de cuentas son débito, se ingresa una cantidad en la cuenta del menor de la que él dispondrá para gastarla, tanto en la consola como en el computador, y en los contenidos que se hayan permitido en los pasos previos que se han explicado, teniendo en cuenta la multitud de contenidos gratuitos este sistema de control parental también da la opción de restringir el tipo de transacciones.
        .cajon.color-acento-contenido.p-4.mb-4
          p Sin duda si se dispone de un equipo con Windows 10, el control parental que ha desarrollado Microsoft es de lo mejor y más completo que se puede encontrar en el mercado, y de manera gratuita, ya que viene de serie con la licencia de Windows 10. Si no utiliza Windows 10 o quiere alternativas al control parental de Microsoft, la opción más clara es usar programas o aplicaciones específicamente diseñados para este fin, existe una herramienta para instalar en el computador que se llama Qustodio, está disponible tanto para Windows, MacOS, Android y iOS, dispone de dos versiones, una gratuita y otra de pago, ya que viene diseñada tanto para ámbitos familiares como escolares. 
    p Esta herramienta dará la posibilidad de controlar el tiempo de conexión del menor, filtros de contenido prohibido e inapropiado, incluso, cuenta con  algo que no todos los sistemas de control parental han tenido en cuenta, la restricción de palabras.
    .cajon.color-acento-contenido.p-4.mb-4
      p.mb-0 Se pueden personalizar filtros de contenido y ver la actividad del computador que se quiera, y para ampliar la versión de pago ofrece informes mucho más detallados, bloqueo total de pornografía, bloqueo de aplicaciones, juegos y contenidos, monitorización de YouTube, seguimiento en redes sociales, control de llamadas y SMS, geolocalización por GPS y un botón de pánico instalable en el smartphone del menor que podrá usar en cualquier momento para pedir ayuda.
    .separador
    #t_2_4.titulo-segundo
      h2 2.4	Red wifi para invitados
    .bloque-texto-a.color-acento-contenido.p-md-4.mb-5 
      .row.m-0.align-items-center.justify-content-between.p-4
        .col-lg-4.mb-4.mb-lg-0
          img(src='@/assets/curso/t2/f19.svg' alt='ilustración wifi')
        .col-lg-8
          .bloque-texto-a__texto.p-5
            p Seguro que en más de una ocasión se ha encontrado en la situación de que amigos o familiares piden la clave del wifi; hay una visita para comer, por ejemplo, y se quieren conectar a la red, ahora bien, en ocasiones puede ser un problema, puede ocurrir que simplemente no recuerde la clave, también es probable que se quiera mantener la seguridad de la red o que incluso poner cierto límite y que no se consuma todo el ancho de banda. Esto último especialmente es interesante en conexiones más lentas, como puede ser ADSL, en la que los recursos son más limitados.
    p Lo primero que hay que tener en cuenta es que no en todos los router es igual, aunque sí es una función similar, en la mayoría de los dispositivos modernos está disponible. Ya se sabe que evitar la pérdida de señal wifi es vital.
    p En el siguiente video se explicará la configuración de wifi para invitados.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video
    .cajon.color-acento-contenido.p-4.mb-4
      p.mb-0 Pero seguro que, si se realiza una prueba de velocidad con una conexión ADSL en la que se tiene a toda la familia conectada y viendo videos de YouTube, los datos no son los que se desearían. En algunos modelos incluso se puede limitar el ancho de banda, por ejemplo, asignar que únicamente el 20% del total de la red (o lo que se quiera) esté disponible en la red wifi para invitados. De esta manera se puede crear una red wifi para invitados, una forma interesante para que las visitas se puedan conectar a la red sin revelar la clave principal, ni poner en peligro el resto de los equipos conectados a la red.
    .separador
    #t_2_5.titulo-segundo
      h2 2.5	Prioridad de medios
    p Cambie la prioridad de los adaptadores de red en Windows 10 desde el centro de redes de este sistema operativo. Lo primero que se debe hacer es abrir el centro de redes y recursos compartidos, para ello, en el siguiente video se explicará la configuración de la prioridad de medios.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video
    .separador
    #t_2_6.titulo-segundo
      h2 2.6	Reenvío de puertos
    .bloque-texto-a.color-acento-contenido.p-md-4.mb-5 
      .row.m-0.align-items-center.justify-content-between.p-4
        .col-lg-4.mb-4.mb-lg-0
          img(src='@/assets/curso/t2/f20.svg' alt='ilustración internet')
        .col-lg-8
          .bloque-texto-a__texto.p-5
            p Es posible que una aplicación determinada o, por ejemplo, un juego en un momento concreto pida algo denominado reenvío de puertos, sin ese reenvío de puertos no podría haber conexión entre la aplicación o juego y el tráfico entrante o datos ingresados en Internet. No se puede hacer uso de determinadas funciones con las que cuenta un <i>software</i> determinado.
            br
            p Este problema se puede solucionar si se configura el reenvío de puertos en Windows 10; es un proceso sencillo y simplemente hay que llevar a cabo una serie de pasos que se van a explicar en el siguiente video.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video
    p Cuando se haya creado la regla se unirá a todas las que ya estaban presentes. Se puede modificar, hacer que se aplique solo a unos determinados programas o servicios, etc. En definitiva, siguiendo estos pasos que se han mencionado se pueden reenviar puertos en Windows 10 en caso de que una aplicación o servicio pida hacerlo.
    .cajon.color-acento-contenido.p-4.mb-4
      p.mb-0 Finalmente, todo lo indicado anteriormente es un proceso sencillo, rápido y que se puede lograr a través de la propia configuración del sistema operativo, sin tener que instalar nada adicional. Por otra parte, es necesario recordar la importancia de contar con herramientas de seguridad; un buen antivirus y firewall pueden evitar la entrada de amenazas. En este sentido, se tiene la posibilidad de hacer uso de Windows Defender, que está disponible en el sistema operativo de Microsoft de forma gratuita.


</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    datosSlider1: [
      {
        titulo: 'Firewall por hardware',
        texto: '',
        imagen: require('@/assets/curso/imagenes/sb.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Seguridad Wireless',
        texto: '',
        imagen: require('@/assets/curso/imagenes/sw.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
    ],
  }),
}
</script>

<style lang="sass" scoped></style>
