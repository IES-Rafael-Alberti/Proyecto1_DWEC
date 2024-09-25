# Idea de la Aplicación
La idea de la aplicación es hacer una tienda online de ropa tanto masculina como femenina. Los usuarios se registrarían creando sus perfiles y de ésta manera accediendo al catálogo distribuido por tipos de prendas podrán realizar sus compras a través de un carrito, similar a otras tiendas online. respecto a las ventas, los artículos no serían de otras tiendas, sino que serían de diseño propio con su propia marca.

# Audiencia Objetivo
La aplicación va horientada a un público juvenil y adulto ya que no estaría centrada en ropa para niños y no se centrarían en un público en específico pero sí que ofrecería mas variedad de camisetas y chaquetas tanto de hombre como mujer. Lo que sí que busca son personas que busquen algo nuevo, como por ejemplo, cazadoras de cuero o polipiel de otro color que no sean negras o marrones.

# Análisis de Mercado
La aplicación sería similar a otras que hay tipo Zara, Springfield, Inside, etc, aunque en la mayoría de ellas veo que hay más variedad de ropa para mujer que para hombre sobretodo en temas de diseño y colores. La diferencia respecto a estas tiendas es dar no solo más variedad al público femenino sino también al masculino, como especifiqué antes, ofreciendo una variedad de colores más amplia en cazadoras de polipiel y chaquetas por ejemplo, así como camisetas con diseños propios de la marca.

# funcionalidades clave
Funcionalidades Frontend:
- *Visualizar la aplicación.* Es lo primero que verá el cliente, por lo que deberá ser atractiva, fácil de usar y personalizada (muestra productos vistos recientemente, los más visitados, los recomendados, etc...)
- *Presentar un catálogo.* Debe ser intuitivo y cómodo de usar, en este caso sería de dos niveles, primero dividido por género y segundo por tipo de ropa.
- *Presentar los productos.* Se muestran especificaciones del producto, imágenes, publicidad, valoraciones, opiniones de otros clientes, precio, gastos de envío, disponibilidad, etc...
- *Ofrecer un buscador.* El cliente podrá hacer una búsqueda del producto que le interesa y hacer filtros según sus preferencias.
- *Cesta de compra.* El cliente irá introduciendo los artículos en la cesta de compra y se le irá informando del precio tanto de los productos como el acumulado. Debe ser rápido, eficiente y fácil de usar.
- *Poder compartir.* Se podría compartir las redes sociales de la tienda, los productos o las transacciones realizadas.
- *Realizar pedidos.* Será por medio de registro mediante de un formulario sencillo sin pedir datos que no sean necesarios o identificación si ya está registrado o ha hecho compras previamente.
- *Realizar pagos.* sería por formas de pago que garanticen fiabilidad y seguridad como paypal o con tarjeta de crédito o débito.
- *Realizar seguimiento del pedido.* Se mostraría el estado del envío en todo momento.
- *Ofrecer atención al cliente.* Se le proporcionaría al cliente asistencia, ya sea por problemas o dudas relacionadas con la tienda

Funcionalidades Backend:
- *Gestionar la información de la tienda.* El administrador podrá modificar cualquier descripción o dato de la tienda.
- *Gestionar el catálogo.* Es una de las partes más importantes de una tienda online. Se permitiría crear un árbol de categorías y ofrecer información de los productos así como imágenes o vídeos sobre éstos. Algo esencial es la descripción de los productos, que debe de ser atractivo y que diferencie de la competencia, además de información que ayude a la venta del mismo como opiniones de los usuarios.
- *Gestionar las relaciones en el catálogo*. Para permitir el Cross-selling o Up-selling se debe permitir el establecimiento de relaciones entre elementos de la jerarquía del catálogo. El Cross-selling o venta cruzada es una estrategia que busca crear interés para adquirir productos adicionales a su compra, y el Up-selling o venta complementaria es crear interés para adquirir productos que complementen a la compra principal.
- *Gestionar el Stock.* La información del stock en la página debe de ser coherente con el stock físico de la tienda.
- *Gestionar ofertas y descuentos.* Con ello se pretende aumentar la ventas de la tienda, no siguen un patrón, son especiales e inesperadas. Tiene implicación en Frontend, ya que se pretendería que sea una de las cosas que primero ve el cliente al entrar en la página o aplicación.
- *Gestionar productos destacados.* Se permite agregar o eliminar productos de la sección de destacados. Aparecen en la pantalla principal.
- *Gestionar clientes.* Los clientes deben poder registrarse y con ello poder acceder a su información y poder modificarlos o incluso darlos de baja.
- *Gestionar pedidos.* Se puede obtener información dobre los pedidos y actuar sobre ellos marcando su estado, por ejemplo para cuando se va a enviar podría poner envío en curso, en reparto o entregado y para el pago, esperando el pago, error al realizar el pago o pago realizado con éxito. El cliente debe recibir toda esta información, por ejemplo por correo electrónico.
- *Gestionar la comunicación con visitantes y clientes.* Una de las claves del éxito de una tienda online es ofrecer un buen servicio al cliente. La relación entre la tienda y el visitante comienza desde el instante en el que entra por lo que se debe de proporcionar un mecanismo de comunicación, como por ejemplo un chat en el que puede realizar preguntas sobre la tienda o los productos de la misma, así como resolver problemas que surjan con las compras. Es esencial mantener el contacto con el cliente incluso después de haber realizado la compra, enviádole información sobre nuevos productos y promociones y así evitar cerrar la relación con él.
- *Generar informes.* Se debe de saber el rendimiento de la página, por lo que sería necesario tener los datos de cuántos visitantes tiene, el número de compras, cuáles son los productos que mas se venden, etc... Ésta información es imprescindible para tomar decisiones que afecten al negocio o al diseño de la página y en base a esto, poner medidas para corregir o potenciar.

Referencia investigación del Frontend y Backend de la tienda: https://www.esi.uclm.es/www/jjcastro/coe/funcionalidades.html  
Referencia de definición Cross-selling y Up-selling: https://blog.hubspot.es/service/cross-selling-upselling#que-es-cross

# Modelos de Ejecución
*Modelo Cliente-Servidor:* es una de las arquitecturas más populares para la construcción de aplicaciones en la actualidad y se llama así a todo modelo que en la que participan dos componentes en el que uno sea el cliente, que solicita los servicios y el otro el servidor, el que ofrece esos servicios. Todas las aplicaciones web son modelo Cliente-Servidor, el cliente es el navegador, y el servidor es la máquina en la que están instaladas las aplicaciones, las bases de datos y otros recursos.

*Tipos modelo Cliente-Servidor:* principalmente existen dos tipos, arquitectura de dos niveles y de tres niveles.

- *Arquitectura de dos niveles:* es el modelo más habitual, en el que los clientes realizan solicitudes directas sobre el servidor sin la intervención de intermediarios.
- *Arquitectura de tres niveles: * se añade un intermediario entre el cliente y el servidor que normalmente se encarga de aplicar una capa de lógica de negocio. Aporta una separación mayor de la responsabilidad del software, por lo que da mayor mantenibilidad y escalabilidad a cambio de mayor complejidad.
- *Variantes: * aparte de modelos 2-Tier o 3-Tier, es decir, de dos o tres niveles, existen modelos n-Tier en el que se añaden capas adicionales para separar aún más la responsabilidad del software, como por ejemplo, aislar una capa de datos.
- *Alternativa: * la alternativa más frecuente al modelo Cliente-Servidor es lo que se llama software standalone. En este tipo de aplicaciones, se encarga de toda la operativa de la aplicación un único sistema. Éste modelo era el más popular hace unos años. Un ejemplo de standalone sería la antigua aplicación de Word, el cual se ejecutaba en el ordenador sin tener que estar conectado a internet ni tener que depender de un servidor externo. A nivel de red también existen alternativas a Cliente-Servidor como el Peer-to-Peer(P2P), en el que cada nodo u ordenador realiza las tareas de servidor y cliente simultáneamente.Uno de los ejemplos más famosos de un modelo P2P es Amazon, en el que no sólo ésta ofrece sus servicios, también otras empresas la usan para ofrecer los suyos a través de esta plataforma.

Algunos ejemplos de la arquitectura Cliente-Servidor son: Outlook, que es un cliente de correo para leer los correos de servicio hotmail, whatsapp, cliente de servicio de chat, vídeo y audio, Firefox, cliente web, 

Referencia Modelo Cliente-Servidor: https://www.arsys.es/blog/todo-sobre-la-arquitectura-cliente-servidor
