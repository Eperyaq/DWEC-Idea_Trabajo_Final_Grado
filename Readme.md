## Propuesta inicial para la aplicación web como proyecto final de ciclo. **`Eliaser Pérez Yaque`** 

## 1. **Idea de la aplicación**: 
   - La página está pensada para ser una web de un estudio de tatuajes y piercings, unos de sus principales usos es que sirva para tomar citas para obtener alguno de sus servicios.
  
   - La idea es que un cliente se adentre en la página web y solicite algún servicio que esta tenga para que el servidor le proporcione los servicios requeridos ya que la idea es hacer una página web cuyo modelo sea el cliente-servidor.

## 2. **Audiencia objetivo**:
   - La página está dirigida a un cliente mayor de edad el cual quiera probar a hacerse un tatuaje o un piercing nuevo, mayoritariamente a gente extranjera ya que el establecimiento se encuentra en un lugar cuya fuente de ingresos mayoritaria son los turistas.

## 3. **Analisis de mercado**:
   - He encontrado esta página que se asemeja a la idea que tengo:
[Estudio de tatuaje - SKULLZYKLOM](https://skullzyklom.com/) .

   - Es una página bastante completa, me gusta todos los apartados que tiene pero he notado que le falta algo de movimiento a la página, algo de dinamismo.  
   Por tanto en mi página, jugaría con el Css para que sea más dinámica y aparte pondría un apartado, un link o algunas imágenes con algunos ejemplos de los diseños que puedes realizarte.  
   Lo Mismo con los piercings, un pequeño album con los piercings que se pueden hacer y los resultados en otras personas.

## 4. **Funcionalidades clave**:
   - Primeramente deberás iniciar sesión, así introducimos un poco la base de datos para guardar los datos de la sesión.
   - La página tendrá diferentes apartados, links a otros apartados de la misma página web como por ejemplo: 
      * Apartado para tomar una cita así metemos más base de datos.
      * Apartado para ver un álbum con algunas ideas para hacerte un tatuaje.
      * En el mismo apartado anterior un apartado para los piercings, para ver el precio, una foto de como quedan etc...
      * Información sobre las personas que van a dar cada servicio.
      * Un  Footer con la información de las redes sociales, un numero de contacto, un gmail…
      * Un mapa con la dirección del establecimiento junto a la dirección escrita a parte.

## 5. **Modelos de ejecucion**
   - Modelo de ejecución cliente:
      - Fijandome en [Arsys](https://www.arsys.es/blog/todo-sobre-la-arquitectura-cliente-servidor), he descubierto que:

      - El cliente es el que realiza las peticiones de los servicios que ofrezca el servidor usando la red como comunicación, gracias a los formularios y distintos tipos de desplegables o cuestionarios.

      - Y el servidor es el componente que entrega el servicio a los clientes, este siempre será un sistema que esperará lo que el cliente necesite para procesarlas y entregarle una respuesta.

## 6. **Lenguajes de programación web**

   - Basándome en unas páginas web que he visitado como [Hubspot](
https://blog.hubspot.es/website/que-es-desarrollo-web#lenguajes) He llegado a la conclusión de que los lenguajes de programación más usados para la programación web enfocado al cliente son:

      1. **HTML**: Es uno de los lenguajes de programación más utilizados en el front end.
      - Sus ventajas son:
         - Permite describir hipertexto.
         - Tiene un despliegue rápido.
         - Lo reconoce y admite cualquier navegador.
      -  Desventajas:
         - el diseño es más lento.
         - tiene un lenguaje estático.
         - etiquetas limitadas.
         ---
      2. **CSS**:  Este es un lenguaje de programación que trabaja en perfecta armonía con el HTML en el frontend.  
       Le sirve al programador para amoldar la página y darle el aspecto que busca el cliente.  
      - Sus ventajas son las siguientes:
         - Control del diseño.
         - Mejora en la consistencia.
         - Eficiencia en el mantenimiento.
      - Desventajas:
         - Curva de aprendizaje para técnicas avanzadas.
         - Inconsistencia entre navegadores.
         - Sobrecarga de estilos.
         ---
      3. **JavaScript**: Es uno de los lenguajes más apreciados ya que con el se facilita la interactividad con el cliente y el dinamismo de la página.
      - Sus ventajas son: 
         - Comunicación inmediata entre el cliente y el servidor.
         - Creación de formularios interactivos.
         - Interactividad en tiempo real.
      - Y sus desventajas:
         - Falta de compatibilidad entre navegadores.
         - Bajo rendimiento en aplicaciones complejas.
         - Obsolescencia de las versiones antiguas.
       ---
       4. **TypeScript**: Es un lenguaje de programación desarrollado por Microsoft, que se basa en JavaScript aunque este también comparte similitudes con JavaScript, su característica más destacada es su sistema de tipado estático.  
       - Sus ventajas son: 
         - Tipado estático.
         - Mantenimiento simplificado.
         - Legibilidad mejorada del código.
      - Sus desventajas:
         - Documentación limitada.
         - Curva de aprendizaje.
         - Necesidad de compilación.

## 7. **Tecnologías a utilizar**

Los lenguajes de programación a utilizar son: **Html, Css, JavaScript, Java y React**

- **Html**: Usaré html5 ya que este facilita la integración con CSS y javascript, permitiendo crear aplicaciones web interactivas. Ademas de su compatibilidad con diferentes APIs de Javascript, como la api de Geolocalización que le viene genial a la idea de mi página web.

- **CSS**: Esta le dará un diseño profesional a la interfaz de usuario ya que introduce funcionalidades como grid y flexbox que la hacen una página responsiva.

- **JavaScript**: Este será el lenguaje de programación para la interacción del cliente. Este es compatible con todos los navegadores y hace dinámica la pagina web, por eso mi elección.

- **Java**: Usaría Java principalmente para el lado del servidor, para manejar todo lo que es el back-end y poder acceder a la base de datos.

- **React**: Usaría React como framework principal, lo elegiría porque permite la creación de interfaces dinámicas mediante el uso de un modelo de componentes.

###  Evaluación de los mecanismos de integración de lenguajes de marcas con lenguajes de programación de clientes web.
- Por ejemplo, al hacer un formulario en HTML, JavaScript puede validar si los datos introducidos son correctos antes de enviarlos al servidor, además de que javaScript interactúa directamente con el cliente.

###  Evaluacion de herramientas de programación para clientes web.

- El IDE principal que usaría sería VisualStudio Code ya que es el que más conozco y estoy familiarizado con el y con sus extensiones, a parte de ser extremadamente poderoso ya que ofrece soporte nativo para JavaScript HTML y CSS
       
## 8. Estudio de compatibilidad con los navegadores.

- La compatibilidad de JavaScript se distingue en dos áreas, con los que  tiene compatibilidad general y con los que tiene problemas de compatibilidad común.    

   En el siguiente enlace podemos encontrar con más precisión cuales son todos las APIs de JavaScript y su compatibilidad con los navegadores:

    [Compatibilidad de APIs de JavaScript con navegadores](https://developer.mozilla.org/es/docs/Mozilla/Add-ons/WebExtensions/Browser_support_for_JavaScript_APIs).

   Aunque resumidamente, Chrome Firefox Edge y Safari son algunos de los navegadores modernos que menos problemas tienen con las APIs de JavaScript.    

   En cambio navegadores como opera, Internet Explorer y ese tipo de navegador tienen problemas con las APIs de javascript ya que o son antiguos o no están hechos para tener paginas que usen un moderno JavaScript.




## Bibliografía
### Punto 6: 
- [Ventajas y desventajas de Html5](https://bannersbanners.es/ventajas-y-desventajas-de-html5-para-creacion-de-web/)
- [Ventajas y desventajas de CSS3](https://www.dongee.com/tutoriales/ventajas-y-desventajas-de-html-y-css/)
- [Ventajas y desventajas de JavaScript](https://blog.hubspot.es/website/ventajas-y-desventajas-de-javascript)

### Punto 7: 
- [Tecnologías para desarrollar una aplicación web](https://mentorday.es/wikitips/tecnologia-mejor-desarrollar-aplicacion-web-medida/)

