# Requisitos

# Práctica: Estudiar las Cookies y las Sessions en ExpressJS

Estudie las cookies y las sessions en ExpressJS. Puede hacer uso de estos u otros recursos:

* [Repositorio con ejemplos de uso de Cookies, Sesiones y Autenticación en NodeJS en GitHub](https://github.com/ULL-ESIT-DSI-1617/express-cookies-examples)

* [HTTP cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)at MDN

* [set-cookie](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Set-Cookie)at MDN

* [Wikipedia: Query String](https://en.wikipedia.org/wiki/Query_string)

* [cookie module](https://www.npmjs.com/package/cookie)

* [Cookie Management in Express](https://www.codementor.io/noddy/cookie-management-in-express-js-du107rmna)

* [A very basic session auth in node.js with express.js](http://www.codexpedia.com/node-js/a-very-basic-session-auth-in-node-js-with-express-js/)

Elabore a partir de ellas un libro GitBook con sus notas explicando e ilustrando con códigos de ejemplo el uso de las distintos conceptos y tecnologías.

El repo debe tener un directorio docs/ con los MarkDown del libro y un directorio src/ con los códigos fuentes de los ejemplos.

Despliegue el libro en las plataformas que hemos visto en las prácticas anteriores Incorpore los apuntes elaborados en las prácticas anteriores a este En el directorio src/ deberá de disponer de un gulpfile.js con tareas para la ejecución de los códigos fuentes de ejemplo

# 

# 

# ¿Que es una Cookie?

### Definición:

Una **galleta**,**galleta informática **o **cookie **es una pequeña información enviada por un sitio web y almacenada en el navegador del usuario, de manera que el sitio web puede consultar la actividad previa del usuario.

Sus principales funciones son:

* Llevar el control de usuarios: cuando un usuario introduce su nombre de usuario y contraseña, se almacena una galleta para que no tenga que estar introduciéndolas para cada página del servidor. Sin embargo, una galleta no identifica a una persona, sino a una combinación de computadora de la clase de computacion-navegador-usuario.

* Conseguir información sobre los hábitos de navegación del usuario, e intentos de \(programas espía\), por parte de agencias de publicidad y otros.

## ¿Cómo funcionan?

Una cookie consiste en una cadena de texto \(string\) con varios pares`key=value`cada uno separado por`;`:

Desde el servidor, las cookies son creadas mediante la cabecera de respuesta`HTTP Set-Cookie`

### Limitaciones

En total, cada cookie puede tener un tamaño máximo de 4.096 bytes, se permiten hasta 50 cookies por dominio y 3000 cookies por navegador/dispositivo.

## La propiedad`document.cookie`

La propiedad`document.cookie`es todo lo que se necesita para trabajar con cookies client-side desde JavaScript. A través de ella podemos crear, leer, modificar y eliminar cookies. Veamos cada uno de los casos.





# express-session

Existen dos formas generales de implementar sesiones en Express: utilizar cookies y utilizar un almacén de sesiones en el backend. Ambos añaden un nuevo objeto en el objeto request denominado session, que contiene las variables de sesión. 

No importa el método que utilice, Express proporciona una interfaz coherente para trabajar con los datos de la sesión.





