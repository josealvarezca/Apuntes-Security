Objetivo: "Explicar los vectores de amenazas comunes y las superficies de ataque"

1. Comprender los vectores de amenazas comunes
Un vector de amenaza es un método o camino utilizado por un atacante para ganar acceso o infectar su objetivo. Son las técnicas mediante las cuales los atacantes ingresan al sistema y pueden causar daños. Existen diversos tipos de vectores de amenazas que los profesionales de la seguridad deben identificar y proteger.

Tipos de vectores de amenazas comunes:
- A. Vectores basados en mensajes
  - Correo electrónico y SMS: Los correos electrónicos y mensajes de texto maliciosos son uno de los vectores más comunes y exitosos. Los atacantes suelen utilizar phishing y malware para infectar los sistemas.
  - Phishing: El atacante envía correos o mensajes que parecen ser de una fuente confiable para engañar al usuario y robar información confidencial.
  - Adjuntos maliciosos: Los archivos adjuntos (por ejemplo, documentos PDF, Excel) pueden contener malware.
  - Ingeniería social: Técnicas de manipulación psicológica para engañar a las víctimas (por ejemplo, estafas).

- B. Vectores basados en imágenes
  - Las imágenes pueden ocultar código malicioso que es difícil de identificar a simple vista.
  - Formatos de imagen: Algunos formatos, como SVG (basado en XML), pueden contener amenazas.
  - Inyección HTML/JavaScript: El código malicioso puede estar oculto dentro del contenido de una imagen o de una página web.

- C. Vectores basados en archivos
  - Archivos ejecutables (EXE): Son un vector común para distribuir malware.
  - PDF, ZIP/RAR: Los atacantes pueden usar formatos de archivo comprimido o documentos para ocultar malware o exploits.
  - Microsoft Office: Los archivos de Office pueden contener macros maliciosas o complementos.

- D. Vectores de llamadas de voz
  - Vishing: El phishing a través de llamadas telefónicas, donde el atacante se hace pasar por una entidad confiable para robar información.
  - Spam sobre IP: Llamadas de spam masivas utilizando VoIP.
  - War dialing: Técnica para marcar números de teléfono aleatorios en busca de sistemas vulnerables.
  - Manipulación de llamadas: Interrupción o alteración de las llamadas (DoS en llamadas de voz).

- E. Vectores de dispositivos removibles
  - Malware en USB: El uso de dispositivos USB para introducir malware en redes seguras o sistemas aislados (por ejemplo, redes air-gapped).
  - Exfiltración de datos: Los dispositivos USB pueden permitir la salida de grandes cantidades de datos sin necesidad de usar la red.

- F. Vectores de software vulnerable
  - Cliente basado: Software malicioso que explota vulnerabilidades conocidas o desconocidas.
  - Sin agente (Agentless): Ataques que no requieren un ejecutable instalado en el cliente, como cuando el software de un servidor comprometido afecta a todos los usuarios.

- G. Vectores de sistemas no soportados
  - Sistemas desactualizados: Los sistemas que no reciben actualizaciones de seguridad pueden ser vulnerables a ataques, ya que algunos no pueden ser parchados debido a su antigüedad.

- H. Vectores de redes inseguras
  - Redes inalámbricas: Protocolos desactualizados, redes abiertas o redes no autorizadas pueden ser un punto de entrada para los atacantes.
  - Redes cableadas: Interfaces inseguras, falta de autenticación (por ejemplo, 802.1X).
  - Bluetooth: Reconocimiento de dispositivos vulnerables, implementación incorrecta de protocolos.

- I. Puertos de servicio abiertos
  - Puertos abiertos: Cualquier puerto abierto en una red es una oportunidad para los atacantes. Los servicios de red se comunican a través de puertos TCP o UDP, y los atacantes pueden intentar aprovechar los puertos abiertos.

- J. Credenciales por defecto
  - Muchos dispositivos vienen con credenciales predeterminadas (como contraseñas), que deben cambiarse inmediatamente para evitar el acceso no autorizado.

- K. Vectores de la cadena de suministro
  - Manipulación de la infraestructura: Los atacantes pueden comprometer proveedores de servicios gestionados o cadenas de suministro para obtener acceso a las redes de muchas organizaciones.
  - Ejemplo: El breach de Target en 2013, donde los atacantes accedieron a la red de Target a través de un proveedor externo.
  - Equipos falsificados: Los atacantes pueden instalar puertas traseras en equipos de red falsificados, comprometiendo el sistema.

2. Phishing y sus variantes

- El phishing es un tipo de ingeniería social en el que los atacantes intentan engañar a las víctimas para que entreguen información confidencial. Aquí algunas variantes importantes:
  - Vishing: Phishing a través de llamadas telefónicas, a menudo con suplantación de identidad.
  - Smishing: Phishing a través de SMS (mensajes de texto), comúnmente usado para fraudes como el rastreo de envíos.
  - Business Email Compromise (BEC): Los atacantes suplantan a un empleado de confianza o a una figura importante de la organización para obtener información financiera o realizar fraudes.

3. Impersonación (Suplantación de identidad)
- Reconocimiento previo: Los atacantes usan información obtenida sobre la víctima para ganarse su confianza (por ejemplo, actuar como una persona de rango superior).
- El objetivo: Extraer información confidencial o realizar fraudes.

4. Watering Hole Attacks
En este tipo de ataque, los atacantes comprometen un sitio web o servicio que es frecuentado por sus víctimas. Los atacantes esperan a que las víctimas visiten el sitio comprometido para infectarlas con malware.

<img src=https://i.imgur.com/z64FJSK.png />
5. Otros ataques de ingeniería social
  - Desinformación/Misinformación: Los atacantes pueden usar las redes sociales para difundir información incorrecta con el fin de causar confusión o manipular la opinión pública.
  - Imitación de marca: Creación de sitios web o contenido falso que imita una marca conocida para infectar a los usuarios.
