# Elaboración de documentación técnica y uso de aplicaciones de propósito general

Marcos Martinez Cossio

Desarrollo de Aplicaciones Web

15/05/2026

[**1\. Análisis de Necesidades	3**](#análisis-de-necesidades)

[¿Qué problema de la empresa resolvemos con Guacamole y Docker?	3](#¿qué-problema-de-la-empresa-resolvemos-con-guacamole-y-docker?)

1. #  Análisis de Necesidades {#análisis-de-necesidades}

   ## ¿Qué problema de la empresa resolvemos con Guacamole y Docker? {#¿qué-problema-de-la-empresa-resolvemos-con-guacamole-y-docker?}

   La solución de Apache Guacamole aborda un problema muy común en empresas: la complejidad en la gestión de accesos remotos seguros. En muchas organizaciones, administrar múltiples herramientas de acceso remoto es complicado. Cada herramienta tiene sus propios requisitos, protocolos y configuraciones, lo que genera dificultades y riesgos de seguridad. Guacamole resuelve este problema proporcionando un acceso unificado a escritorios remotos mediante una interfaz web. Esta interfaz es accesible desde cualquier navegador moderno y no requiere instalar software adicional en los equipos cliente.  
   La instalación de Guacamole puede ser un poco complicada. Requiere compilar librerías y dependencias, y configurar un servidor de aplicaciones como Apache Tomcat. Esto incluye la instalación de componentes como guacd y la configuración de conectores para protocolos como RDP, VNC o SSH. Aunque esto puede ser laborioso, ofrece un control total sobre cada módulo y permite adaptar la solución a las necesidades específicas de la infraestructura.  
   Una de las ventajas de Guacamole es que no necesita agentes instalados en las máquinas a las que se desea acceder. Esto significa que los servidores o equipos remotos no requieren software adicional. Esto reduce la carga administrativa, evita problemas de compatibilidad y disminuye la superficie de ataque. No se añaden componentes externos que deban mantenerse o actualizarse.  
   El acceso a Guacamole se realiza desde un navegador, lo que lo convierte en una herramienta especialmente útil para entornos donde se utilizan múltiples dispositivos. El usuario puede conectarse a sus recursos corporativos de forma segura, centralizada y consistente, sin depender de configuraciones locales ni de la instalación de clientes pesados. En conjunto, Guacamole ofrece una solución robusta, flexible y moderna para la gestión de accesos remotos en infraestructuras profesionales.

 ## 2. Estimación de Costes de Infraestructura

<img width="903" height="326" alt="image" src="https://github.com/user-attachments/assets/c8b1c597-02f7-48d0-966e-e34782a243a2" />

## 3. Estrategia de Despliegue y Comunicación.

   - Para lanzar nuestra aplicacion en produccion, hemos elegido SFTP ya que es un sistemas que nos sentimos bastante seguro a la hora de trabjar con ellosy ademas tiene un cifrado para tranferir los archivos del             ordenador al servidor. Funciona sobre SSH, por lo que permite que tanto las credenciales y como la informacion esten protegidas con el cifrado tan bueno que realizan, gracias a eso, podemos evitar los riesgo de            seguridad y accesos que no queramos como puede ser los no deseados.

   - No utilizaremos el FTP porque los trasmite en texto plano y eso hace que sea muy vulnerable, tambien podemos utilizar GitHub actions o google cloud.

   - El proceso sera conectar muestro ordenador al servidor mediante visual code con SSH por ejemplo. Una vez que esten conectado, se sube un archivo a la aplicacion y lo configuramos

## Mensajería:
   - Para que la comunicacion interna de nuestro equipo vamos a usar Microdoft Teams, es la herramienta que va a ser compartir las incidencias tecnica que nos ocurran, tambien las videollamadas y alertas del servidor    º      cuando tenga un problema de caidas, historial de mensajes y coordinacion del proyecto.

## 4. Justificación Científica.
   - Se aborda la problemática actual de la microempresa del sector tecnológico seleccionada en la cual todos los procesos se los lleva sin el uso de programas o sistemas informáticos que agiliten y reduzcan el trabajo,       asimismo se presenta la implementación de la herramienta de planificación de recursos empresariales (ERP) Open Source Odoo 9, que permita contar con información oportuna y a tiempo, como soporte a la toma de               decisiones y    automatizar los procesos, mejorando la productividad y control como propuesta de solución a los inconvenientes existentes en cada área.
     
## Referencias:

F. Freire, Lenin, Director, "Implementación del ERP Open Source Odoo en una PYME", Freire, Lenin, Director, . [Online]. Available: https://www.dspace.espol.edu.ec/handle/123456789/38698. [Accessed: 05-22-2026].
