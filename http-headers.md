Evaluación 4 HTTP HEADERS

HTTP HEADERS

1. ¿Qué son los Encabezados HTTP?

Respuesta:son bloques de informacion enviados de parte del cliente, en este caso un navegador y un servidor web existente para enviar datos importantes sobre la solicitud o la respuesta, como el tipo de autentificacion, contenido o la misma configuracion de seguridad.

2. ¿A qué se asemejan los encabezados HTTP en la analogía de la "casa"? (2 puntos)

Respuesta:Son como etiquetas en paquetes de correo, donde se remarca el remitente, destinatario , las instrucciones de manipulacion o cuidados y su respectivo contenido.

3. ¿Qué tipo de información se envía a los servidores web cuando se realiza un proceso de registro o inicio de sesión? (3 puntos)

Respuesta:La informacion puede ser como los nombres de usuarios y contraseñas,informacion delicada como correos personales o tockens de autenticacion.

4. ¿Qué son los "Response Headers"? (3 puntos)

Respuesta:Son cabeceras que contienen mas informacion sobre el contenido como su servidor o el origen.

5. ¿Cuál es la importancia de los "Response Headers"? (3 puntos)

Respuesta:Son muy importantes para definir como el cliente o usuario debe interpretarsu respuesta,como controlar o gestionar la seguridad y tener un buen rendimiento de la misma pagina web

6. ¿Qué es la "pestaña Network" en las herramientas para desarrolladores? (2 puntos)

Respuesta:Es una seccion rn las herramients para desarrolladores del navegador que nos permite monitorear las solicitudes y respuestas http, agregando encabezados, el tiempo de carga y los recursos utilizados.

7. ¿Cuál es el principal objetivo de los Encabezados HTTP en términos de seguridad? (3 puntos)

Respuesta:Proteger la infornacion y su integridad misma de la informacion transferida entre el o los clientes y los servidores, asi evitando ataques de terceros y la misma exposicion de la informacion sencible.

8. ¿Qué tipos de Encabezados HTTP existen para proteger la información? (3 puntos)

Respuesta:Los mas comunes son:
Strict-Transport-Security (HSTS)
Content-Security-Policy (CSP)
X-Content-Type-Options
X-Frame-Options

9. ¿Qué es la encriptación y cómo se relaciona con los Encabezados HTTP en la seguridad web? (3 puntos)

Respuesta:Es un mecanismo de seguridad que protege los datos de los robos o vulnerabilidades y estan enlazados con los encabezados http a travez de protocolos https.

10. ¿Cuál es el nombre de la página web oficial de Mozilla con documentación sobre Encabezados HTTP? (1 punto)

Respuesta:MDN o Mozilla Developer Network.

11. ¿Cuáles son algunos ejemplos de Encabezados HTTP utilizados para la autenticación? (3 puntos)

Respuesta:Authorization, WWW-Authenticate, Proxy-Authorization y Proxy-Authenticate.

12. ¿Qué son las cookies y qué función cumplen? (3 puntos)

Respuesta:Son arvivos de texto que los sitios web envian al navegador del usuario para guardar su informacion sobre sus visitas.

13. ¿Cuales son los 2 tipos de Encabezados HTTP se utilizan para la protección de contenido web? (3 puntos)

Respuesta:Content-Security-Policy (CSP) y Strict-Transport-Security (HSTS)

14. ¿Qué función cumple el Content Security Policy (CSP)? (3 puntos)

Respuesta:Es una funcion de seguridad que ayuda a evitar ataques de secuencias de comandos entre sitios (XSS)

15. ¿Qué es el "XSS" y cómo se relaciona con los Encabezados HTTP? (4 puntos)

Respuesta:Es un termino que se usa para describir una clase de ataques que permiten al atacante inyectar scripst de lado cliente a travez de los sitios webs.
16. (*) ¿Qué encabezado ayuda al rendimiento de una página web? (3 puntos)

Respuesta:Cache-control, nos permite especificar politicas de almacenamiento en cache, lo que reduce el tiempo de carga, lo que facilita y reduce el tiempo de carga

17. ¿Cómo se identifican los Encabezados HTTP antes del 2012? (2 puntos)

Respuesta:
18. (*) ¿Qué es SEO en el contexto de la web? (2 puntos)

Respuesta: En el contexto de la web, SEO (Search Engine Optimizacion, por sus siglas en ingles) es el conjunto de estrategias y tecnicas destinadas a mejorar la visibilidad y el posicionamiento de un sitio web en los resultados organicos de los motores de busqueda , ya sea Google, Bing o Yahoo.

19. ¿Cuál es el atajo del teclado (shortcut) para acceder al inspector de elementos en el navegador? (1 punto)

Respuesta.:En Window o Linux esta con Chrome o Firefox es Ctrl+Shift+I+F12
            Opera tiene Crtl+Shift+I
            Mac es Command (⌘)+Option(⌥)+I.
20. ¿Qué significa "HTTP" en las siglas de Encabezados HTTP? (1 punto)

Respuesta:Significa que los Protocolos De Transferencias de Hipertexto. Es el sistema que permite que los navegadores y los servidores web se comuniquen para transferir datos como paginas web, ya sea, imagenes o videos.

21. (*) ¿Cuál es la diferencia entre los encabezados HTTP y los encabezados HTTPS? (4 puntos)

Respuesta: La  diferencia es que entre los encabezados HTTP y los encabezados HTTPS no esta en su contenido, sino en como se transmiten debido al protocolo subyacente
            Los encabezados HTTP: son enviados en texto plano, lo que significa que pueden ser interceptados y leidos facilmente por 3°ros durante la transmision.
            Los encabezados HTTPS: son enviados cifrados, garantizan que los encabezados y el contenido de la solicitud y/o respuestas esten encriptados y protegidos contra accesos no autorizados.
22. (*) ¿Cuáles son los tipos de métodos HTTP qué mas se utilizan? (mencione al menos 5) (4 puntos)

Respuesta:
GET: Pide información al servidor (como cargar una página).
POST: Envía datos al servidor para crear o procesar información.
PUT: Actualiza o reemplaza datos existentes.
DELETE: Solicita eliminar datos del servidor.
HEAD: Similar a GET, pero solo devuelve los encabezados (sin el contenido).

23. (*) ¿Qué permiten hacer las herramientas de desarrollo del navegador con respecto a los encabezados HTTP? (4 puntos)

Respuesta:
Las herramientas de desarrollo de los navegadores permiten inspeccionar y analizar los encabezados HTTP para entender la comunicación entre el navegador y el servidor. Algunas funciones clave incluyen:

Ver encabezados de solicitudes y respuestas (como Content-Type y Cache-Control).
Depurar problemas como errores HTTP (p. ej., 404 o 500) y encabezados mal configurados.
Analizar cookies y políticas de seguridad, como Set-Cookie o Strict-Transport-Security.
Simular configuraciones para probar cambios en los encabezados.
Ver solicitudes de APIs y examinar su contenido, útil para aplicaciones web modernas.

24. (*) ¿Qué es un "Proxy" y cómo se relaciona con los Encabezados HTTP? (4 puntos)

Respuesta:

25. (*) ¿Cómo se pueden usar los Encabezados HTTP para optimizar el SEO de un sitio web? (4 puntos)

Respuesta:
