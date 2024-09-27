# Idea de la Aplicación
La idea de la aplicación es hacer una tienda online de ropa tanto masculina como femenina. Los usuarios se registrarían creando sus perfiles y de ésta manera accediendo al catálogo distribuido por tipos de prendas podrán realizar sus compras a través de un carrito, similar a otras tiendas online. respecto a las ventas, los artículos no serían de otras tiendas, sino que serían de diseño propio con su propia marca.

# Audiencia Objetivo
La aplicación va horientada a un público juvenil y adulto ya que no estaría centrada en ropa para niños y no se centrarían en un público en específico pero sí que ofrecería mas variedad de camisetas y chaquetas tanto de hombre como mujer. Lo que sí que busca son personas que busquen algo nuevo, como por ejemplo, cazadoras de cuero o polipiel de otro color que no sean negras o marrones.

# Análisis de Mercado
La aplicación sería similar a otras que hay tipo Zara, Springfield, Inside, etc, aunque en la mayoría de ellas veo que hay más variedad de ropa para mujer que para hombre sobretodo en temas de diseño y colores. La diferencia respecto a estas tiendas es dar no solo más variedad al público femenino sino también al masculino, como especifiqué antes, ofreciendo una variedad de colores más amplia en cazadoras de polipiel y chaquetas por ejemplo, así como camisetas con diseños propios de la marca.

# funcionalidades clave
Funcionalidades Frontend:
- **Visualizar la aplicación.** Es lo primero que verá el cliente, por lo que deberá ser atractiva, fácil de usar y personalizada (muestra productos vistos recientemente, los más visitados, los recomendados, etc...)
- **Presentar un catálogo.** Debe ser intuitivo y cómodo de usar, en este caso sería de dos niveles, primero dividido por género y segundo por tipo de ropa.
- **Presentar los productos.** Se muestran especificaciones del producto, imágenes, publicidad, valoraciones, opiniones de otros clientes, precio, gastos de envío, disponibilidad, etc...
- **Ofrecer un buscador.** El cliente podrá hacer una búsqueda del producto que le interesa y hacer filtros según sus preferencias.
- **Cesta de compra.** El cliente irá introduciendo los artículos en la cesta de compra y se le irá informando del precio tanto de los productos como el acumulado. Debe ser rápido, eficiente y fácil de usar.
- **Poder compartir.** Se podría compartir las redes sociales de la tienda, los productos o las transacciones realizadas.
- **Realizar pedidos.** Será por medio de registro mediante de un formulario sencillo sin pedir datos que no sean necesarios o identificación si ya está registrado o ha hecho compras previamente.
- **Realizar pagos.** sería por formas de pago que garanticen fiabilidad y seguridad como paypal o con tarjeta de crédito o débito.
- **Realizar seguimiento del pedido.** Se mostraría el estado del envío en todo momento.
- **Ofrecer atención al cliente.** Se le proporcionaría al cliente asistencia, ya sea por problemas o dudas relacionadas con la tienda

Funcionalidades Backend:
- **Gestionar la información de la tienda.** El administrador podrá modificar cualquier descripción o dato de la tienda.
- **Gestionar el catálogo.** Es una de las partes más importantes de una tienda online. Se permitiría crear un árbol de categorías y ofrecer información de los productos así como imágenes o vídeos sobre éstos. Algo esencial es la descripción de los productos, que debe de ser atractivo y que diferencie de la competencia, además de información que ayude a la venta del mismo como opiniones de los usuarios.
- **Gestionar las relaciones en el catálogo**. Para permitir el Cross-selling o Up-selling se debe permitir el establecimiento de relaciones entre elementos de la jerarquía del catálogo. El Cross-selling o venta cruzada es una estrategia que busca crear interés para adquirir productos adicionales a su compra, y el Up-selling o venta complementaria es crear interés para adquirir productos que complementen a la compra principal.
- **Gestionar el Stock.** La información del stock en la página debe de ser coherente con el stock físico de la tienda.
- **Gestionar ofertas y descuentos.** Con ello se pretende aumentar la ventas de la tienda, no siguen un patrón, son especiales e inesperadas. Tiene implicación en Frontend, ya que se pretendería que sea una de las cosas que primero ve el cliente al entrar en la página o aplicación.
- **Gestionar productos destacados.** Se permite agregar o eliminar productos de la sección de destacados. Aparecen en la pantalla principal.
- **Gestionar clientes.** Los clientes deben poder registrarse y con ello poder acceder a su información y poder modificarlos o incluso darlos de baja.
- **Gestionar pedidos.** Se puede obtener información dobre los pedidos y actuar sobre ellos marcando su estado, por ejemplo para cuando se va a enviar podría poner envío en curso, en reparto o entregado y para el pago, esperando el pago, error al realizar el pago o pago realizado con éxito. El cliente debe recibir toda esta información, por ejemplo por correo electrónico.
- **Gestionar la comunicación con visitantes y clientes.** Una de las claves del éxito de una tienda online es ofrecer un buen servicio al cliente. La relación entre la tienda y el visitante comienza desde el instante en el que entra por lo que se debe de proporcionar un mecanismo de comunicación, como por ejemplo un chat en el que puede realizar preguntas sobre la tienda o los productos de la misma, así como resolver problemas que surjan con las compras. Es esencial mantener el contacto con el cliente incluso después de haber realizado la compra, enviádole información sobre nuevos productos y promociones y así evitar cerrar la relación con él.
- **Generar informes.** Se debe de saber el rendimiento de la página, por lo que sería necesario tener los datos de cuántos visitantes tiene, el número de compras, cuáles son los productos que mas se venden, etc... Ésta información es imprescindible para tomar decisiones que afecten al negocio o al diseño de la página y en base a esto, poner medidas para corregir o potenciar.

Referencia investigación del Frontend y Backend de la tienda: https://www.esi.uclm.es/www/jjcastro/coe/funcionalidades.html  
Referencia de definición Cross-selling y Up-selling: https://blog.hubspot.es/service/cross-selling-upselling#que-es-cross

# Modelos de Ejecución
**Modelo Cliente-Servidor:** es una de las arquitecturas más populares para la construcción de aplicaciones en la actualidad y se llama así a todo modelo que en la que participan dos componentes en el que uno sea el cliente, que solicita los servicios y el otro el servidor, el que ofrece esos servicios. Todas las aplicaciones web son modelo Cliente-Servidor, el cliente es el navegador, y el servidor es la máquina en la que están instaladas las aplicaciones, las bases de datos y otros recursos.

**Tipos modelo Cliente-Servidor:** principalmente existen dos tipos, arquitectura de dos niveles y de tres niveles.

- **Arquitectura de dos niveles:** es el modelo más habitual, en el que los clientes realizan solicitudes directas sobre el servidor sin la intervención de intermediarios.
- **Arquitectura de tres niveles:** se añade un intermediario entre el cliente y el servidor que normalmente se encarga de aplicar una capa de lógica de negocio. Aporta una separación mayor de la responsabilidad del software, por lo que da mayor mantenibilidad y escalabilidad a cambio de mayor complejidad.
- **Variantes:** aparte de modelos 2-Tier o 3-Tier, es decir, de dos o tres niveles, existen modelos n-Tier en el que se añaden capas adicionales para separar aún más la responsabilidad del software, como por ejemplo, aislar una capa de datos.
- **Alternativa:** la alternativa más frecuente al modelo Cliente-Servidor es lo que se llama software standalone. En este tipo de aplicaciones, se encarga de toda la operativa de la aplicación un único sistema. Éste modelo era el más popular hace unos años. Un ejemplo de standalone sería la antigua aplicación de Word, el cual se ejecutaba en el ordenador sin tener que estar conectado a internet ni tener que depender de un servidor externo. A nivel de red también existen alternativas a Cliente-Servidor como el Peer-to-Peer(P2P), en el que cada nodo u ordenador realiza las tareas de servidor y cliente simultáneamente.Uno de los ejemplos más famosos de un modelo P2P es Amazon, en el que no sólo ésta ofrece sus servicios, también otras empresas la usan para ofrecer los suyos a través de esta plataforma.

Algunos ejemplos de la arquitectura Cliente-Servidor son: Outlook, que es un cliente de correo para leer los correos de servicio hotmail, whatsapp, cliente de servicio de chat, vídeo y audio, Firefox, cliente web.

Referencia Modelo Cliente-Servidor: https://www.arsys.es/blog/todo-sobre-la-arquitectura-cliente-servidor

# Lenguajes de Programación Web
## Javascript 
Es uno de los más usados actualmente y permite a los desarrolladores crear páginas dinámicas y aplicaciones web interactivas que mejoran la experiencia de los usuarios.  

### Ventajas
- **Interactividad en tiempo real.** Es una de las características más valiosas de Javascript. Es la capacidad de responder y adaptarse a las acciones del usuario en el mismo tiempo en el que ocurren, sin necesidad de recargar la página, por lo que crea una experiencia más dinámica, fluida y atractiva.
- **Detección y respuesta de eventos.** Son las acciones que ocurren en la página web. Puede servir para mostrar información adicional al pasar el ratón sobre algún elemento de la página o para ejecutar una acción al hacer click.
- **Manipulación sencilla del DOM.** Document Object Model, es una representación de la memoria de la estructura y el contenido de una página web. Javascript agiliza tanto el acceso como la manipulación de los elementos del DOM (cambiar el contenido, estilo y atributos de los elementos de las respuesta a los eventos).
- **Creación de formularios interactivos.** Puede mejorar la interacción con formularios al validar los datos ingresados por el usuario, por lo que se mostarán mensajes de error instantáneos cuando existan campos erróneos o incompletos.
- **Innovación en la carga de contenido dinámico.** Con AJAX (Asynchronous JavaScript and XML), carga y muestra contenido adicional sin recurrir a una recarga.
- **Animación y efectos visuales.** Puede crear animaciones y efectos visuales en una página web (hacer que los elementos se muevan, cambien de tamaño, etc...).
- **Desarrollo de juegos y aplicaciones interactivas.** Es una plataforma perfecta para crear juegos y aplicaciones interactivas en navegadores. Se utiliza en muchos juegos en línea simuladores y apps educativas.
- **Comunicación inmediata entre cliente y servidor.** Con tecnologías como WebSockets, esta herramienta permite establecer conexiones de comunicación bidireccional entre el cliente y el servidor. Es esencial para aplicaciones en teimpo real, como chats en línea.
- **Amplia adopción en el desarrollo web.** Tiene una gran cantidad de recursos , tutoriales y comunidades en línea dismponible.
- **Ejecución constante en el lado del cliente.** Puede realizar acciones sin comunicarse de manera constante con els ervidor, por lo que ayuda a reducir la carga en el servidor y mejorar la eficiencia de las aplicaciones.
- **Comunicación asíncrona con el servidor.** Los datos pueden cargarse y enviarse als ervidor en segundo plano a través de tecnologías como AJAX.
- **Uso versátil para desarrolladores.** Con Node.js, Javascript se puede utilizar también en el lado del servidor.
- **Amplio repertorio de bibliotecas y frameworks.** Existen bibliotecas y frameworks como JQery, React, Angular y Vue.js, que simplifican las tareas comunes como el desarrollo de las interfaces de usuario o la manipulación del DOM.
- **Facilidad de aprendizaje.** Es sencillo de aprender ya que cuenta con una sintaxis clara y flexible.
- **Evolución contínua en cada nueva versión.** Este lenguaje evoluciona y se mejora de manera constante, por lo que las nuevas versiones permiten escribir un código más limpio y eficiente.
- **Compatibilidad con múltiples navegadores.** Los navegadores modernos han mejorado de manera significativa en términos de soporte para el JavaScript estándar, lo que facilita la creación de aplicaciones consistentes en diferentes plataformas.   

### Desventajas 
- **Falta de compatibilidad con navegadores.** A pesar de que la compatibilidad entre navegadores ha mejorado, todavía puede haber diferencias en la manera en la que interpretan y ejecutan el código de Javascript, por lo que puede requerir pruebas y ajustes adicionalespara garantizar un buen funcionamiento.
- **Nivel de seguridad deficiente.** Como su código se ejecuta en el navegador del usuario, existe el riesgo de que algunos exploten sus vulnerabilidades para llevar a cabo ataques.
- **Bajo rendimiento en aplicaciones complejas.** Javascript es un lenguaje interpretado, por lo que puede afectar al rendimiento en comparación a lenguajes compilados.
- **Funcionalidad sujeta al uso del cliente.** Si un usuario deshabilita este recurso en su navegador o este no lo admite, la funcionalidad de la aplicación puede verse afectada.
- **Dificultad para indexar en motores de búsqueda.** Los motores de búsqueda suelen tener dificultades para indexar contenido generado dinámicamente por este lenguaje de programación.
- **Mantenimiento y legibilidad complicados.** A medida que las aplicaciones web se tornan más complejas o grandes, el código JavaScript puede volverse difícil de mantener y entender, por lo que puede generar problemas de legibilidad y errores.
- **Carga inicial prolongada y rendimiento deficiente en dispositivos móviles.** Si no se optimiza de manera adecuada, los códigos creados con este lenguaje pueden aumentar los tiempos de carga de la página, afectando la experiencia del usuario.
- **Obsolescencia de las versiones antiguas.** Algunas características de las versiones antiguas de JavaScript pueden volverse obsoletas o no recomendadas, por lo que puede ocasinar problemas de compatibilidad o dificultades de migración del código.  

## TypeScript 
Es un lenguaje de programación libre y de código abierto y es desarrollado y mantenido por Microsoft. Es un superconjunto de JavaScript, añade tipado estático opcional y funciones avanzadas de JavaScript. se usa para para desarrollar aplicaciones JavaScript tanto para el lado del cliente como del servidor. Además ofrece POO (Programación Orientada a Objetos) como clases, interfaces y herencia, permitiendo un código estructurado y organizado.  

### Ventajas
- **Detecta errores en una fase temprana.** A medida que se va escribiendo el código, TypeScript proporciona un reporte con errores o mejoras que se pueden realizar.
- **Amplía la funcionalidad de JavaScript.** Permite usar conceptos de programación avanzados como clases e interfaces.
- **Proporciona una mejor experiencia de desarrollo para grandes proyectos.** Es especialmente útil para proyectos grandes con muchos desarrolladores, ya que ayuda a mantener el código bien organizado.
- **Integración con librerías y frameworks.** Es compatible con muchas librerías y frameworks de JavaScript, por lo que ofrece una mayor integración.  

### Desventajas
- **La curva de aprendizaje.** Ofrece características adicionales a JavaScript, por lo que si el desarrollador no está familiarizado con TypeScript, deberá aprender los conceptos antes de poder trabajar con esta herramient.
- **Tiempo adicional para definir tipos.** Añadir tipos estáticos puede llevar más tiempo en comparación a hacerlo simplemente con JavaScript debido a que requiere definir los tipos correctamente.

Referencia JavaScript: https://blog.hubspot.es/website/ventajas-y-desventajas-de-javascript  
Referencia TypeScript: https://medium.com/@alejodev95/introducci%C3%B3n-a-typescript-9740a71aaaee  

# Tecnologías a utilizar
Teniendo en cuenta toda la investigación, la parte del cliente sería realizada en:  

## Lenguajes:
- JavaScript, ya que permite crear experiencias dinámicas como añadir los productos al carrito o actualización de productos sin necesidad de actualizar la página.
- Utilizaría también HTML, para crear la estructura básica de la tienda (los productos, categorías, los formularios, etc...)
- CSS, para el diseño y las presentación visual, ya que se puede hacer que la tienda sea atractiva y que responda bien, incluso se podría hacer que responda bien en dispositivos móviles.

## Frameworks:
- React, Ideal para construir interfaces de usuario. Su modelo de componentes permite desarrollar aplicaciones modulares y reutilizables.
- Vue.js: Similar a React, es fácil de integrar y también ofrece un enfoque basado en componentes. Es ligero y se puede aprender rápidamente.
- Node.js: Para el backend. Permite construir aplicaciones escalables y utilizar JavaScript en el servidor. Es ideal para manejar múltiples conexiones y proporciona un entorno eficiente para el desarrollo.
- Express.js: Un framework para Node.js que facilita la creación de APIs y manejar rutas, middleware y servidores.

La razón de mi elección de estas tecnologías es porque son populares y ampliamente soportadas, por lo que existe bastante documentación y comunidades activas para resolver problemas. además Javascript tanto para el frontend como para el backend (con Node.js) permite un flujo de trabajo más simplificado.

## Integración de los Lenguajes de Marcas con los Lenguajes de Programación  
HTML se utilizaría para estructurar el contenido de la tienda, mientras que JavaScript se encargaría de la interactividad. Por ejemplo:  
- Manipulación del DOM: JavaScript piuede acceder y modificar el contenido HTML utilizando el DOM (Document Object Model), por lo que, como mecioné antes, permite agregar productos dinámicamente, actualizar la cesta de la compra, validar formularios, etc...
- Eventos: como por ejemplo los botones. en HTML se pueden desencadenar funciones en JavaScript, por ejemplo, al hacer click en "añadir al carrito", se podría ejecutar una función que actualiza la lista de los productos.

## Herramientas de Desarrollo  

### Editor de Código  
Utilizaría Visual Studio Code en principio. Es muy utilizado y soporta una amplia variedad de extensiones y herramientas. Ofrece funciones como autocompletado, depuración y control de versiones entre otras.  

## Otros Frameworks y Bibliotecas
- Bootstrap: es un framwork de css que proporciona estilos diseñados y componentes que responden a una acción. Acelera el desarrollo y asegura que la tienda se vea bien en cualquier dispositivo.
- Axios: es una biblioteca para hacer peticiones HTTP desde el frontend. Permie comunicarse fácilmente con el backend para procesar pedidos.
- Redux: una biblioteca de JavaScript para gestionar el estado de la aplicación de forma más predecible. Para manejar la autentificación del usuario por ejemplo.

Fuentes para la decisión de las tecnologías a utilizar:  
https://developer.mozilla.org/es/docs/Web/HTML  
https://developer.mozilla.org/es/docs/Web/CSS  
https://developer.mozilla.org/es/docs/Web/JavaScript  
https://www.tithink.com/es/2018/11/14/7-razones-para-utilizar-react/  
https://www.godaddy.com/resources/es/crearweb/vue-framework-js-que-es  
https://www.lucushost.com/blog/que-es-node-js/#:~:text=entorno%2C%20%C2%BFverdad%3F-,Node.,cuando%20las%20conexiones%20se%20multiplican.  
https://kinsta.com/es/base-de-conocimiento/que-es-express/  
https://immune.institute/blog/razones-usar-bootstrap-web/  
https://www.meltstudio.co/post/por-que-los-desarrolladores-adoran-axios  
https://oxygenacademy.es/que-es-redux-y-por-que-deberias-implementarlo-en-tus-aplicaciones-react/  

# Compatibilidad en Navegadores
