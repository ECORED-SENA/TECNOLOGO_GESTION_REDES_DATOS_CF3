<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 Introducción a las redes inalámbricas
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
      .py-3.py-md-4(titulo="Red WWAN")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            img(src="@/assets/curso/t1/f5.svg", alt="Ilustración red WWAN").p-4
          .col-md-6.mb-4.mb-md-0
            h5 Redes inalámbricas de área extensa o WWAN
            p (Wireless Wide Area Network). Conocidas también como de área global o WGAN, tienen cobertura de una gran región, país o grupo de países, basadas en tecnología celular, y son consideradas como la evolución de las redes de voz.
    Separador
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
    Separador
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
    Separador
    #t_1_4.titulo-segundo
      h2 1.4 Componentes de las redes inalámbricas
    p Se encuentran integradas por los siguientes dispositivos:
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f9.svg' alt='Icono antena')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 Antena
          p Elemento que permite transmitir y recibir ondas de radio por medio de una comunicación natural como el aire o el espacio libre.
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f10.svg' alt='Icono punto de acceso')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 Punto de acceso
          p Dispositivo de capa 2, por medio del cual las estaciones wireless pueden integrarse rápida y fácilmente a cualquier red cableada, actuando como núcleo de la red inalámbrica y puente de conexión entre redes inalámbricas y cableadas. El punto de acceso se conecta a un router, switch o hub con un cable Ethernet y radia la señal wifi en un área específica, como ejemplo, si desea habilitar el acceso wifi en el área de recepción de una empresa, pero no existe un router que pueda cubrirla, se instala un punto de acceso cerca de la recepción y se conecta con un cable hacia el salón de equipos donde está el servidor.
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f11.svg' alt='Icono puente inalámbrico')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 Bridge inalámbrico
          p Dispositivo que permite conectar dos o más redes ubicadas en diferentes edificios, proporcionando más velocidad de transmisión de datos, además conecta sitios difíciles de cablear, pisos no contiguos, instalaciones de campus de escuelas o empresas, etc.
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f12.svg' alt='Icono enrutador inalábrico')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 Router inalámbrico
          p Es el que permite la conexión de redes inalámbricas, enrutar los paquetes de datos hacia la red correcta de destino y facilita la conexión a la WLAN de dispositivos inalámbricos; es la tecnología de comunicación de ondas de radio que admite la conexión ADSL para el manejo de Internet de banda ancha y que se distribuya hacia otros computadores.
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f13.svg' alt='Icono adaptador')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 Adaptadores
          p Son tarjetas para expandir la capacidad de conexión, envían y reciben datos sin necesidad de cables en las redes WLAN, poseen una antena para la recepción y envío de datos, y están diseñados para algunos estándares de redes inalámbricas.
    Separador
    #t_1_5.titulo-segundo
      h2 1.5 Modos de operación
    .bloque-texto-a.color-acento-contenido.p-md-4.mb-5 
      .row.m-0.align-items-center.justify-content-between.p-4
        .col-lg-3.mb-4.mb-lg-0
          img(src='@/assets/curso/t1/f14.svg' alt='Imagen 4 computadores')
        .col-lg-9
          .bloque-texto-a__texto.p-5
            p Para el estándar 802.11 es importante tener en cuenta dos modos fundamentales de uso para este tipo de redes, el modo ad-hoc y el modo infraestructura BSS, los cuales se detallarán a continuación.
    .row.align-items-center.justify-content-between.mb-5
      .col-lg-6
        h3 Modo ad-hoc.
        p Se conoce también como punto a punto, en este método los clientes inalámbricos establecen comunicación directa entre sí, por tanto, no es necesario un punto de acceso o AP; cada terminal inalámbrica en una red ad-hoc configura el adaptador inalámbrico en este modo, y debe usar el mismo SSID y canal dentro de la red. Este método limita el número de dispositivos, y si estos aumentan, el rendimiento de la red disminuye, además la conexión ad-hoc es temporal entre dispositivos para un mismo fin, por ejemplo, compartir impresoras, archivos o juegos en la red.
        .cajon.color-acento-contenido.p-4.mb-4
          p.mb-0 La conexión de los equipos se realiza por medio de los adaptadores de red sin necesidad de un punto de acceso. Una infraestructura ad-hoc tendría mínimo 2 computadores, tarjetas de red inalámbrica y, de hecho, los drivers de tarjetas de red. 
        p De manera que en la tabla que aparece a continuación puede consultar tanto las ventajas como desventajas del modo ad-hoc.
      .col-lg-6
        img(src='@/assets/curso/t1/f15.svg' alt='Ilustración modo ad-hoc')
    .titulo-quinto.color-acento-contenido.pt-5
      h4 Ventajas y desventajas modo ad-hoc
    .tabla-a.color-primario.mb-5 
      table
        caption
        thead
          tr
            th.texto-acento-contenido.text-center Ventajas
            th.texto-acento-contenido.text-center Desventajas
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
    h3 Modo infraestructura BSS
    .row.align-items-center.justify-content-between.mb-5
      .col-lg-6
        img(src='@/assets/curso/t1/f16.svg' alt='Ilustración modo BSS')
      .col-lg-6
        p Para las redes que trabajan con el estándar IEEE 802.11 el modo de infraestructura se conoce como Conjunto de Servicios Básicos (BSS – Basic Service Set) y las denominan también cliente – servidor o maestro - esclavo. Para este modo de infraestructura existe un dispositivo central que corresponde al punto de acceso o estación base, que generalmente se conecta a una red Ethernet cableada, y así los clientes inalámbricos pueden acceder a la red fija por medio del punto de acceso. En el proceso de interconexión de los dispositivos inalámbricos hacia los puntos de acceso se debe configurar con el mismo SSID, lo que garantiza optimizar la capacidad total de la red.
        p Para este caso se pueden encontrar varias formas de distribuir los elementos conectados a la red, las cuales se presentan en la siguiente tabla.
    .titulo-quinto.color-acento-contenido.pt-5
      h4 Tipos de infraestructuras inalámbricas BSS
    TabsA.color-acento-contenido.mb-5
      .tarjeta.color-acento-contenido--borde.fcb.p-4(titulo="Tipo 1")
        h4 Estrella
        img(src='@/assets/curso/t1/f17.svg', alt='Figura estrella')
      .tarjeta.color-acento-contenido--borde.fcb.p-4(titulo="Tipo 2")
        h4 Punto a punto
        img(src='@/assets/curso/t1/f18.svg', alt='Figura punto a punto')
      .tarjeta.color-acento-contenido--borde.fcb.p-4(titulo="Tipo 3")
        h4 Con repetidores
        img(src='@/assets/curso/t1/f19.svg', alt='Figura con repetidores')
      .tarjeta.color-acento-contenido--borde.fcb.p-4(titulo="Tipo 4")
        h4 Malla
        img(src='@/assets/curso/t1/f20.svg', alt='Figura malla')
    
    Separador
    #t_1_6.titulo-segundo
      h2 1.6 Tecnologías de redes inalámbricas
    p Actualmente existen dos tipos de redes inalámbricas, para exteriores e interiores; en los sistemas para exteriores el sistema de posicionamiento global conocido como GPS por sus siglas en inglés (Global Positioning System), es el estándar de referencia por la precisión que consigue el receptor en línea directa con varios satélites de forma simultánea.
    .bloque-texto-a.color-acento-contenido.p-md-4.mb-5 
      .row.m-0.align-items-center.justify-content-between.p-4
        .col-lg-3.mb-4.mb-lg-0
          img(src='@/assets/curso/t1/f21.svg' alt='Ilustración redes inalámbricas')
        .col-lg-9
          .bloque-texto-a__texto.p-5
            p Para interiores este estándar no sirve, pues tantas paredes, techos y demás obstáculos apantallan la señal y el receptor no puede sincronizarse a algún satélite, impidiendo dar su localización, entonces, estas tecnologías a utilizar dependen de los requisitos necesarios para acceder a una u otra aplicación o servicio. También es importante tener presente para la tecnología a escoger, el consumo de energía, precio, ancho de banda y velocidad, entre otros factores. En el siguiente gráfico se describen brevemente las diferentes tecnologías utilizadas para redes inalámbricas.
    PasosA.color-primario.mb-5(tipo="n")
      .row
        img(src='@/assets/curso/iconos/1.svg' alt='1').figpasos
        h4 Bluetooth
        p Es la tecnología inalámbrica más utilizada para transmitir datos entre dispositivos cercanos, basada en radiofrecuencia, en la banda libre de 2.4 GHz y 3 Mbps de velocidad máxima; es muy frecuente su uso para pasar fotos y música entre teléfonos móviles. Los autos disponen del sistema bluetooth para atender llamadas telefónicas con manos libres al estar conduciendo, en los dispositivos domésticos es más frecuente como en el mouse, los auriculares, entre otros.
      .row
        img(src='@/assets/curso/iconos/2.svg' alt='2').figpasod
        h4 European Installation Bus
        p Usado para interconectar redes eléctricas inteligentes.
      .row
        img(src='@/assets/curso/iconos/3.svg' alt='3').figpasoi
        h4 HomePlug
        p Protocolo utilizado para tender cableado doméstico de energía eléctrica.
      .row
        img(src='@/assets/curso/iconos/4.svg' alt='4').figpasod
        h4 IrDA
        p Estándar físico para la transmisión y recepción de datos por rayos; el espectro infrarrojo sirve para la comunicación bidireccional entre dos extremos con velocidades que oscilan entre  9.600 bps y 4 Mbps.
      .row
        img(src='@/assets/curso/iconos/5.svg' alt='5').figpasoi
        h4 INSTEON
        p Red que trabaja en dos bandas de frecuencia, integrando comunicaciones por   radiofrecuencia (RF) con tendido doméstico para energía eléctrica HomePlug.
      .row
        img(src='@/assets/curso/iconos/6.svg' alt='6').figpasod
        h4 nanoNET
        p Se trata de protocolos inalámbricos tipo propietario creados para sensores, como competencia de la tecnología ZigBee.
      .row
        img(src='@/assets/curso/iconos/7.svg' alt='7').figpasoi
        h4 OBEX
        p Abreviatura de Object EXchange o intercambio de datos, este protocolo fue creado para facilitar el intercambio de información binaria entre dispositivos.
      .row
        img(src='@/assets/curso/iconos/8.svg' alt='8').figpasod
        h4 RadioRa
        p Protocolo de tipo propietario desarrollado por Lutron para radiofrecuencia (RF) doble vía, usado en el control de iluminación residencial.
      .row
        img(src='@/assets/curso/iconos/9.svg' alt='9').figpasoi
        h4 Topdog
        p Protocolo tipo propietario inalámbrico, utilizado en el control de iluminación comercial y residencial.
      .row
        img(src='@/assets/curso/iconos/10.svg' alt='10').figpasod
        h4 UPB
        p Protocolo desarrollado para mejorar el desempeño y confiabilidad en cableados de energía eléctrica.
      .row
        img(src='@/assets/curso/iconos/11.svg' alt='11').figpasoi
        h4 Wifi
        p Sigla usada para el término en inglés Wireless Fidelity (wifi), tecnología para redes del tipo WLAN Wireless Local Area Network, basada en el estándar IEEE 802.11. Permite realizar la transmisión de información con señales de radiofrecuencia, conectar en una misma red diferentes dispositivos como celulares, PC, blu-ray e impresoras que estén ubicados dentro del radio de cobertura wifi.
      .row
        img(src='@/assets/curso/iconos/12.svg' alt='12').figpasod
        h4 Wi-Max
        p Tecnología para red inalámbrica de área metropolitana con un alcance de 50 Km, velocidad de transmisión de hasta 70 Mbps, basada en el estándar 802.16, que opera en el rango de frecuencias de 10 GHz a 66 GHz con línea de vista, con el estándar 802.16a, opera entre los 2 y 11 GHz y sin línea de vista, puede usarse para receptores en vehículos móviles siempre que no superen 100 Km/h de velocidad, se creó como competencia para la tecnología xDSL y el acceso por cable módem.
      .row
        img(src='@/assets/curso/iconos/13.svg' alt='13').figpasoi
        h4 Wireless USB
        p Wireless Universal Serial Bus (WUSB) en inglés, hace referencia a una conexión de alta velocidad, eficaz y sin cables, basada en la tecnología USB usada para PC.
      .row
        img(src='@/assets/curso/iconos/14.svg' alt='14').figpasod
        h4 Z-wave
        p Protocolo tipo propietario usado en redes inalámbricas de control de hogares.
      .row
        img(src='@/assets/curso/iconos/15.svg' alt='15').figpasos
        h4 ZigBee
        p Especificación global creada para sistemas de control inalámbrico llamados ZigBee Alliance, se basa en el estándar IEEE 802.15.4, usado para radios digitales de baja frecuencia, con velocidad de transmisión 250 Kbps, y limitado a controladores de 8 bits.
    Separador
    #t_1_7.titulo-segundo
      h2 1.7 Radio, elementos y frecuencias del espectro
    p Actualmente el espectro radioeléctrico es utilizado de forma ineficiente, debido a que las bandas de frecuencia para su uso se realizan de manera fija, para ello surge una tecnología novedosa que es la radio cognitiva, la cual trae consigo varias funcionalidades que garanticen el acceso dinámico al usar el espectro, aquí se nombran  las cuatro más importantes: identificar la oportunidad de acceso al espectro, seleccionar las bandas de frecuencia a usar, coordinar el acceso al espectro entre usuarios, y movilidad espectral. 
    p Los dos tipos más usados de radio cognitiva son:
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f22.svg' alt='Icono punto de acceso')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 Radio cognitiva completa ("radio de mitola")
          p Aquí cualquier aspecto que se observe en un nodo inalámbrico será tenido en cuenta para la toma de decisiones en el cambio de parámetros de transmisión y/o recepción.
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f23.svg' alt='Icono punto de acceso')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 Radio cognitiva detectora del espectro
          p Para este caso, las decisiones se toman basadas solo en el estado del espectro de radiofrecuencia.
    p Igualmente, de acuerdo con las bandas del espectro disponibles para la radio cognitiva se tiene también:
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f24.svg' alt='Icono punto de acceso')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 Con licencia
          p Se utilizan bandas asignadas a usuarios bajo licencia, e incluso se usan bandas libres como la banda UNII o la ISM.
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f25.svg' alt='Icono punto de acceso')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 De acceso libre
          p Aquí la radio cognitiva solo puede hacer uso de bandas libres del espectro de radiofrecuencia.
    Separador
    #t_1_8.titulo-segundo
      h2 1.8 Diseño e instalación de red
    p Para el diseño de una red inalámbrica no solo se debe realizar la distribución de los dispositivos activos y pasivos, sino que es pertinente definir protocolos, estándares, normas y demás regulaciones necesarias para cumplir con los requerimientos establecidos. En la planeación de un diseño de red se deben tener en cuenta varios aspectos, entre los cuales se nombran los siguientes pasos que ayudan a optimizar el diseño de la red solicitada:
    TabsC.color-acento-contenido.mb-5
      .py-3.py-md-4(titulo="Recolección de información")
        .row.align-items-center
          .col-lg-6
            img(src="@/assets/curso/t1/f26.svg", alt="Figura relacionada").py-4
          .col-lg-6
            h3 Recolección de información
            ul.lista-ul--separador
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Analizar requerimientos solicitados.
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Establecer el tipo de servicios a utilizar. 
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Definir el tipo de dispositivos inalámbricos a conectar en la red (PC portátiles, de oficina, smartphone y tablets).
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Estudiar características y ubicación de los dispositivos activos para la red wifi.
      .py-3.py-md-4(titulo="Revisión de las instalaciones")
        .row.align-items-center
          .col-lg-6
            img(src="@/assets/curso/t1/f27.svg", alt="Figura relacionada").py-4
          .col-lg-6
            h3 Revisión de las instalaciones
            ul.lista-ul--separador
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Definir el tipo de instalación del punto de acceso en cada zona. 
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Determinar canalizaciones del cableado hasta cada punto de acceso.
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Comprobar los obstáculos existentes que degraden el rendimiento de la red.
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Ubicación de los terminales usuario, equipos de red, como switches, routers y servidores.
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Realizar el plano de la planta, basado en el espacio disponible, la alimentación, la seguridad y el sistema de aire acondicionado del lugar.
      .py-3.py-md-4(titulo="Elección de dispositivos")
        .row.align-items-center
          .col-lg-6
            img(src="@/assets/curso/t1/f28.svg", alt="Figura relacionada").py-4
          .col-lg-6
            h3 Elección de dispositivos
            ul.lista-ul--separador
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Determinar las características de las antenas y que cumplan con los requerimientos solicitados.
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Definir el tipo de radio a utilizar de acuerdo con la tecnología y estándar de acceso seleccionado.
      .py-3.py-md-4(titulo="Diseño preliminar")
        .row.align-items-center
          .col-lg-6
            img(src="@/assets/curso/t1/f29.svg", alt="Figura relacionada").py-4
          .col-lg-6
            h3 Diseño preliminar
            ul.lista-ul--separador
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Escoger una herramienta digital para realizar el diseño, por ejemplo, Xiro-online.
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Realizar el diseño basado en cobertura, con un equipo principal o central cubrir la mayor área posible.
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Realizar el diseño basado en capacidad, lo cual permite mejor capacidad, más puntos de acceso y contar con ajustes de la potencia transmitida, que permita calcular posibles interferencias conjuntas con la misma red u otras redes.
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Definir la ubicación de los equipos y analizar la precisión de los niveles de cobertura.
      .py-3.py-md-4(titulo="Diseño definitivo")
        .row.align-items-center
          .col-lg-6
            img(src="@/assets/curso/t1/f30.svg", alt="Figura relacionada").py-4
          .col-lg-6
            h3 Diseño definitivo
            ul.lista-ul--separador
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Realizar site survey de la red diseñada para confirmar el cumplimiento de los requerimientos.
              li 
                i.fas.fa-play.texto-acento-contenido.me-4
                | Ejecutar la simulación real del rendimiento, ubicando los puntos de acceso definidos por medio del software elegido.
    p.mb-5 Para el caso del diseño de una red inalámbrica se realizará una videoclase o web conference que permita explicar el procedimiento de simulación profesional de cobertura radioeléctrica online, a través de la herramienta de planificación radioeléctrica Xirio-Online para un caso específico de red. Las figuras siguientes muestran la interfaz principal y la de planificación de redes radioeléctricas de la herramienta Xirio-Online, la cual tiene acceso de forma tanto gratuita como con pago.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video
    h3 Topología de la red
    p Escoger la topología inicial de la red depende esencialmente de varios aspectos como:
    .row.align-items-center.mb-5
      .col-lg-5.mx-auto
        img(src="@/assets/curso/t1/f31.svg", alt="Persona manejando servidores").py-4
      .col-lg-6
        ul.lista-ul--separador
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Requerimientos del cliente.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Cantidad y ubicación de usuarios. 
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Crecimiento esperado de la red.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Estándares inalámbricos y de cableado.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Capacidad de expansión de la red.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Entorno de la red.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Dispositivos y servicios requeridos por la red.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Desempeño deseado.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Elegir recorrido simple desde el nodo y demás componentes para minimizar costos.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Facilitar detección de fallas.
            li 
              i.fas.fa-play.texto-acento-contenido.me-4
              | Optimizar instalación y reconfiguración de la red.
    .row.align-items-center.justify-content-between.my-5.pt-5
      .col-lg-7
        h3 Servicios
        p El DHCP es una extensión del protocolo Bootstrap (BOOTP) desarrollado en 1985 para conectar dispositivos como terminales y estaciones de trabajo sin disco duro con un bootserver, del cual reciben su sistema operativo. 
        .cajon.color-acento-contenido.p-4.mb-4
          p.mb-0 El DHCP se desarrolló como solución para redes de gran envergadura y computadores portátiles, por ello complementa a BOOTP, entre otras cosas, por su capacidad para asignar automáticamente direcciones de red reutilizables y por la existencia de posibilidades de configuración adicionales.
      .col-lg-5.mx-auto
        img(src='@/assets/curso/t1/f32.svg' alt='Wifi')
    p.mb-5 Para asignar direcciones con DHCP se toma el modelo cliente-servidor, donde el terminal o usuario solicita la configuración IP al servidor DHCP, que es quien asigna la respectiva dirección IP acompañada de la máscara de subred, puerta de enlace predeterminada, servidor DNS, y configuración proxy por WPAD (Web Proxy Auto-Discovery Protocol) necesarios para poder acceder a los servicios. La asignación de esta dirección dinámica es de carácter temporal mientras dura la conexión con el servicio solicitado, una vez se termina la conexión, esta dirección es liberada para ser asignada a otro usuario.
    h4 El servidor DHCP informa al Domain Name System
    p.mb-5 El servidor DHCP es el encargado de enviar la información al DNS al asignar una nueva dirección IP, la cual se asocia con su nombre de dominio correspondiente. El DHCP no es muy seguro, pues es de fácil manipulación por parte de atacantes a la red que desean apropiarse de la información sensible de sus usuarios.
    h4 Servidor NAT
    .bloque-texto-a.color-acento-contenido.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-between.p-4
        .col-lg-3.mb-4.mb-lg-0
          img(src='@/assets/curso/t1/f33.svg' alt='Persona conectando servidores')
        .col-lg-9
          .bloque-texto-a__texto.p-5
            p Este servidor surge a raíz del crecimiento exponencial de terminales que día a día acceden a Internet, se usa para Traducción de Direcciones de Red con su sigla en inglés NAT o <i>Network Address Translation</i>, y con ello, permitir que los dispositivos de una red utilicen un rango de direcciones especiales (IP privadas) y para conectarse a Internet utilicen una dirección IP única (IP pública). Se trata de una mejora o actualización en la que las redes grandes solo usarían una dirección IP y no gran cantidad de ellas.
            br
            p.mb-0 En la siguiente figura podrá observar el funcionamiento de este servidor.
    .titulo-quinto.color-acento-contenido
      h4 Funcionamiento Servidor NAT
    .col-lg-10.mx-auto.mb-5
      img(src='@/assets/curso/t1/f34.svg' alt='Funcionamiento servidor NAT').mb-4
      figcaption Nota. Página web Profesional review (s.f.).
    h4.pt-5 Modos de funcionamiento para NAT
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f35.svg' alt='Icono estática')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 Estática
          p La dirección IP privada siempre se traduce en la misma dirección IP pública. Cualquier host dentro de la red será así visible desde Internet. 
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f36.svg' alt='Icono dinámica')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 Dinámica
          p A cada dirección IP privada le corresponde al menos una dirección IP pública de las que posee el router, así, cuando un host requiera una conexión a Internet el router asignará la dirección IP pública que no esté siendo usada. De este modo hay más seguridad.
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f37.svg' alt='Icono sobrecarga')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 Sobrecarga
          p Aquí se mapean varias direcciones IP privadas por medio de una dirección IP pública, evitando así contratar más de una dirección IP pública, y se ahorran direcciones IPv4. Se le denomina también PAT (Port Address Translation) y es la más usada en los hogares.
    .tarjeta-avatar-b.mb-5
      img(src='@/assets/curso/t1/f38.svg' alt='Icono solapamiento')
      .tarjeta.fondo-casi-blanco
        .p-4
          h3 Solapamiento
          p Para evitar el conflicto de direcciones, si hay una dirección IP privada de una red es igual a una dirección IP pública que está en uso, el router reemplaza dicha dirección IP por otra.
    p.mb-5 De manera que en la siguiente tabla se muestran las ventajas y desventajas que tiene el Servidor NAT.
    .titulo-quinto.color-acento-contenido
      h4 Ventajas y desventajas del Servidor NAT
    .tabla-a.color-primario.mb-5 
      table
        thead
          tr
            th.texto-acento-contenido.text-center Ventajas
            th.texto-acento-contenido Desventajas
        tbody
          tr
            td Ahorro de direcciones IPv4 al conectarse múltiples máquinas de una red a Internet, con una única dirección IP pública.
            td Mayor potencia de computación en el router para recalcular el Checksum TCP y UDP de cada paquete modificado. 
          tr
            td Seguridad, pues las máquinas conectadas a la red mediante NAT no son visibles desde el exterior.
            td Incompatibilidad de NAT con varias aplicaciones y protocolos que no permiten al router modificar los paquetes.
          tr
            td Mientras se llevan a cabo tareas de mantenimiento de la red solo es necesario modificar la tabla de reenvío de un router para desviar todo el tráfico.
            td 
    .row.align-items-center.justify-content-between.mb-4
      .col-lg-7
        h3 Instalación
        p Para realizar la correcta instalación de la red inalámbrica es vital realizar un aprestamiento o verificación del entorno, los componentes y herramientas necesarios, aplicando una lista de chequeo que verifique la disponibilidad, estado y características de estos, con la debida antelación (4 a 8 días) para poder tomar los correctivos a los que haya lugar. Igualmente, al menos un día antes o el mismo día muy temprano se debe realizar el alistamiento de los elementos, materiales, herramientas necesarias para la instalación de todos y cada uno de los dispositivos como antenas, repetidores adaptadores, routers y puntos de acceso.
        .cajon.color-acento-contenido.p-4.mb-4
          p.mb-0  Una vez cumplidos los anteriores aspectos se procede a realizar la instalación de los componentes de la red inalámbrica por parte del personal idóneo, que cumpla con todos los requisitos y normas vigentes para dicha labor.
      .col-lg-4.mx-auto
        img(src='@/assets/curso/t1/f39.svg' alt='Computador portátil')
    h3 Antenas
    .row.align-items-start.justify-content-between.mb-4
      .col-lg-6
        p Una antena es un sistema conductor metálico con capacidad de radiar y recibir ondas electromagnéticas del espacio, estos dispositivos adaptan ondas guiadas desde conductores o guías al espacio libre. En la siguiente figura se puede ver un ejemplo.
        .titulo-quinto.color-acento-contenido
          h4 Representación de una antena
        img(src='@/assets/curso/t1/f40.svg' alt='Representación de una antena').mb-5
        p Existen varios tipos de antenas, entre ellos:
        ul.lista-ul--separador
          li 
            i.fas.fa-play.texto-acento-contenido.me-4
            p <b>Direccionales:</b> aquellas que orientan la señal en una determinada dirección, con un haz estrecho de largo alcance.
          li 
            i.fas.fa-play.texto-acento-contenido.me-4
            p <b>Omnidireccionales:</b> este tipo de antenas radian la señal con un haz amplio, de corto alcance y dirigido hacia todas direcciones.
          li 
            i.fas.fa-play.texto-acento-contenido.me-4
            p <b>Sectoriales:</b> radian la señal con un haz más amplio que las direccionales, se consideran la unión de una antena omni y de una direccional.
      .col-lg-6
        p La ganancia de una antena es la relación entre la densidad de potencia radiada en una dirección y la densidad de potencia que radia una antena isotrópica, en la misma distancia y potencia entregadas a la antena. La antena isotrópica es una antena puntual que no se puede realizar en la práctica y que radia de igual manera en todas las direcciones, la ganancia se mide en dBi (decibeles isotrópicos).
        p A continuación, puede ver un ejemplo de antena isotrópica.
        .titulo-quinto.color-acento-contenido
          h4 Antena isotrópica
        .col-lg-5.mx-auto
          img(src='@/assets/curso/t1/f41.svg' alt='Antena isotrópica').mb-5
        p La pérdida de la señal puede ser ocasionada por varios motivos, entre los cuales se puede enumerar los siguientes: 
        ul.lista-ul--separador
          li 
            i.fas.fa-play.texto-acento-contenido.me-4
            p Cable o guía de onda roto o desconectado.
          li 
            i.fas.fa-play.texto-acento-contenido.me-4
            p El equipo de transmisión o amplificador de la señal no envía la potencia por daño o se encuentra apagado.
          li 
            i.fas.fa-play.texto-acento-contenido.me-4
            p Antena descompuesta, rota o deteriorada.
    h3 Instalación de los adaptadores y el router
    p.mb-5 Un adaptador o tarjeta de red se requiere para conectar una terminal a Internet. La mayoría de las computadoras tienen conexión de red inalámbrica incorporada. Los equipos más antiguos pueden necesitar que se les adicione un adaptador de red para tener acceso a lnternet.
    h4.pt-5 Pasos para instalar el adaptador de red USB:
    PasosA.color-primario.mb-5(tipo="n")
      .row
        img(src='@/assets/curso/t1/f42.svg' alt='paso 1').figpasos
        h4 Paso 1
        p Conectar el adaptador de red USB a un puerto USB que esté disponible, sin necesidad de apagar el computador.
      .row
        img(src='@/assets/curso/t1/f43.svg' alt='paso 2').figpasod
        h4 Paso 2
        p Encender el computador e instalar los controladores (drivers) de la tarjeta de red. Si el sistema operativo es Windows, este reconocerá el hardware recién agregado y abrirá una ventana de diálogo «nuevo hardware encontrado», el cual se debe completar. Luego, insertar el CD de configuración y seguir el asistente para terminar la instalación. El software/drivers de la tarjeta de red USB se puede descargar desde el sitio web del fabricante.
      .row
        img(src='@/assets/curso/t1/f44.svg' alt='paso 3').figpasoi
        h4 Paso 3
        p Una vez que la tarjeta de red se ha instalado con éxito se deben establecer los valores de configuración de la tarjeta como dirección IP, máscara de subred, puerta de enlace o gateway, y servidores DNS (se recomienda ponerse en contacto con el administrador de red para comprobar los valores de configuración).
      .row
        img(src='@/assets/curso/t1/f45.svg' alt='paso 4').figpasoe
        h4 Paso 4
        p Reiniciar el equipo si es necesario o en su defecto verificar si el adaptador de red está listo para su uso.
    h3 Instalación del <b>router</b>
    p Este dispositivo posee puertos RJ45 para red LAN, en los cuales se deben conectar los cables patch cord hacia los dispositivos cableados y red WAN, donde se debe colocar el cable patch cord de alimentación a Internet del ISP, igualmente, se debe colocar la antena para acceso inalámbrico de los dispositivos a la red WLAN.  Por tratarse de un dispositivo activo se debe conectar el respectivo cable o adaptador de alimentación para su funcionamiento y, proceder a configurar las características básicas y necesarias como elemento de la red.
    p.mb-5 En el siguiente video podrá observar el procedimiento para la configuración de dispositivos.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video

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
