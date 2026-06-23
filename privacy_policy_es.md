# Política de Privacidad

**Fecha de Entrada en Vigor:** 15 de febrero de 2026
**Última Actualización:** 1 de mayo de 2026

## 1. Información sobre el Responsable del Tratamiento

**BeatLoop** (denominado «nosotros», «nos» o «nuestro») opera la aplicación móvil BeatLoop (la «App»).

**Responsable del Tratamiento:**
OnBeat HQ UG (haftungsbeschränkt)
Wichterichstraße 4
50937 Köln, Alemania
Correo electrónico: privacy@on-beat.de

Para todas las consultas relacionadas con la privacidad, solicitudes de protección de datos o el ejercicio de sus derechos en virtud de las leyes de protección de datos aplicables, póngase en contacto con nosotros en la dirección de correo electrónico anterior.

## 2. Introducción y Alcance

Esta Política de Privacidad explica cómo recopilamos, usamos, procesamos y protegemos sus datos personales cuando utiliza nuestra aplicación móvil BeatLoop. Esta política se aplica a todos los usuarios en todo el mundo y cumple con el Reglamento General de Protección de Datos de la UE (RGPD), la Ley de Privacidad del Consumidor de California (CCPA) y otras leyes de protección de datos aplicables.

**BeatLoop** es una aplicación de práctica musical diseñada para bailarines y músicos para crear bucles de audio, ajustar la velocidad de reproducción, grabar vídeo y gestionar sesiones de práctica. La App permite a los usuarios acceder a música desde el almacenamiento local del dispositivo, YouTube, Apple Music y Spotify, y mantiene cuentas de usuario para funciones premium y sincronización de sesiones.

## 3. Base Jurídica para el Tratamiento de Datos (Artículo 6 del RGPD)

Procesamos sus datos personales sobre la base de los siguientes fundamentos jurídicos:

- **Ejecución de un Contrato** (Artículo 6(1)(b)): Para proporcionar los servicios de la App, la gestión de cuentas y las funciones premium
- **Intereses Legítimos** (Artículo 6(1)(f)): Mejora de la App, seguridad, prevención del fraude y atención al cliente
- **Consentimiento** (Artículo 6(1)(a)): Comunicaciones de marketing, análisis opcionales y determinadas integraciones de terceros
- **Obligación Legal** (Artículo 6(1)(c)): Cumplimiento de las leyes aplicables, obligaciones fiscales y solicitudes legales

## 4. Información que Recopilamos

### 4.1 Información que Usted Proporciona Directamente

**Información de la Cuenta:**
- Dirección de correo electrónico (obligatoria para la creación de la cuenta)
- Credenciales de autenticación (al usar el inicio de sesión con correo electrónico/contraseña)
- Estado de la suscripción premium e información de pago
- Preferencias y configuración de la cuenta

**Contenido Generado por el Usuario:**
- Archivos de audio que importa desde el almacenamiento local de su dispositivo
- Música a la que se accede a través de integraciones de YouTube, Apple Music o Spotify (solo metadatos; véase la Sección 5)
- Grabaciones de vídeo de sesiones de práctica (almacenadas solo localmente)
- Metadatos de la sesión (marcadores, segmentos, bucles, notas de práctica)
- Datos de organización y nomenclatura de proyectos

**Comunicaciones:**
- Consultas de soporte y comentarios
- Correspondencia relativa a su cuenta o a la App

### 4.2 Información Recopilada Automáticamente

**Datos de Uso y Análisis:**
- Patrones de interacción con la App y uso de funciones
- Duración de la sesión y frecuencia de uso
- Métricas de rendimiento del dispositivo relacionadas con el procesamiento de audio/vídeo
- Informes de errores y registros de fallos (a través de Sentry)

**Información del Dispositivo y Técnica:**
- Modelo del dispositivo, sistema operativo y versión
- Versión de la App e identificador de instalación
- Dirección IP y ubicación general (nivel de país/región)
- Tipo de conexión de red

**Datos de Autenticación:**
- Marcas de tiempo de inicio de sesión y eventos de autenticación
- Tokens OAuth de Google y Apple (al usar el inicio de sesión social)
- Marcas de tiempo de creación de la cuenta y última actividad
- Marcas de tiempo de aceptación de las Condiciones del Servicio y la Política de Privacidad (almacenadas en nuestros sistemas backend para el cumplimiento legal)

### 4.3 Información de Terceros

**Proveedores de Autenticación Social:**
- Google OAuth: Nombre, dirección de correo electrónico, foto de perfil (opcional)
- Apple Sign-In: Nombre, dirección de correo electrónico o correo electrónico de retransmisión privada

**Procesamiento de Pagos:**
- En iOS: Apple procesa la información de pago a través de Compras dentro de la Aplicación
- En Android: Google procesa la información de pago a través de Google Play Billing
- En la Web: Stripe procesa la información de pago para las suscripciones premium
- Solo recibimos confirmaciones de transacciones y el estado de la suscripción; no recopilamos ni almacenamos datos de tarjetas de pago a través de las aplicaciones móviles

## 5. Integraciones de Servicios de Música de Terceros

BeatLoop se integra con los siguientes servicios de música de terceros para permitir a los usuarios acceder a la música y practicar con ella. Cada integración implica una recopilación y un procesamiento de datos específicos:

### 5.1 YouTube (YouTube API Services)

BeatLoop utiliza YouTube API Services para permitir a los usuarios buscar y reproducir música de YouTube.

- **Datos recopilados:** Metadatos del vídeo (título, artista, duración), datos de interacción de reproducción
- **Datos NO recopilados:** BeatLoop NO descarga, almacena ni guarda en caché contenido de audio o vídeo de YouTube. Toda la reproducción se realiza a través de la API de YouTube.
- **Condiciones del Servicio de YouTube:** [https://www.youtube.com/t/terms](https://www.youtube.com/t/terms)
- **Política de Privacidad de Google:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

**Cumplimiento de la Política de Datos de Usuario de los Servicios de la API de Google:** El uso por parte de BeatLoop de la información recibida de YouTube API Services se ajustará a la [Política de Datos de Usuario de los Servicios de la API de Google](https://developers.google.com/terms/api-services-user-data-policy), incluidos los requisitos de Uso Limitado.

Los usuarios pueden revocar el acceso de BeatLoop a sus datos de YouTube a través de la página de configuración de seguridad de Google en [https://security.google.com/settings/security/permissions](https://security.google.com/settings/security/permissions).

### 5.2 Apple Music (MusicKit)

BeatLoop utiliza la API de Apple MusicKit para permitir a los usuarios buscar y transmitir música de Apple Music.

- **Datos recopilados:** Metadatos de la pista (título, artista, álbum, duración), acceso a la biblioteca (con permiso del usuario)
- **Datos NO recopilados:** BeatLoop NO descarga, almacena ni guarda en caché contenido de audio de Apple Music. El audio se transmite a través de Apple Music.
- **Requisito:** Los usuarios deben tener una suscripción activa de Apple Music para usar esta función.
- **Términos y Condiciones de los Servicios de Medios de Apple:** [https://www.apple.com/legal/internet-services/itunes/](https://www.apple.com/legal/internet-services/itunes/)

### 5.3 Spotify (Spotify Web API)

BeatLoop utiliza la Spotify Web API para permitir a los usuarios buscar y reproducir música de Spotify.

- **Datos recopilados:** Metadatos de la pista (título, artista, álbum, duración), estado de reproducción
- **Datos NO recopilados:** BeatLoop NO descarga, almacena ni guarda en caché contenido de audio de Spotify. El audio se transmite a través de Spotify.
- **Requisito:** Los usuarios deben tener una cuenta activa de Spotify para usar esta función.
- **Condiciones de Uso de Spotify:** [https://www.spotify.com/legal/end-user-agreement/](https://www.spotify.com/legal/end-user-agreement/)
- **Política de Privacidad de Spotify:** [https://www.spotify.com/legal/privacy-policy/](https://www.spotify.com/legal/privacy-policy/)

### 5.4 Archivos Locales

Los usuarios pueden importar archivos de audio desde el almacenamiento local de su dispositivo.

- Los archivos locales se procesan íntegramente en el dispositivo y nunca se cargan en nuestros servidores.
- BeatLoop no supervisa, escanea ni valida el contenido o el estado de los derechos de autor de los archivos locales.

### 5.5 Google Drive

BeatLoop permite a los usuarios importar archivos de audio desde su Google Drive.

- **Tipo de Acceso:** Acceso de solo lectura a los archivos que el usuario selecciona explícitamente a través del Google Picker
- **Datos Recopilados:** Metadatos del archivo (nombre, tipo, tamaño) y contenido del archivo de audio para la reproducción
- **Almacenamiento de Datos:** El audio importado se procesa y almacena únicamente de forma local en el dispositivo del usuario. BeatLoop NO carga, guarda en caché ni almacena archivos de Google Drive en sus servidores
- **Intercambio de Datos:** Los datos de los archivos de Google Drive no se comparten con ningún tercero
- **Revocación:** Los usuarios pueden revocar el acceso de BeatLoop en cualquier momento a través de [https://myaccount.google.com/permissions](https://myaccount.google.com/permissions)
- **Cumplimiento de la Política de Datos de Usuario de los Servicios de la API de Google:** El uso por parte de BeatLoop de la información recibida de las API de Google se ajustará a la [Política de Datos de Usuario de los Servicios de la API de Google](https://developers.google.com/terms/api-services-user-data-policy), incluidos los requisitos de Uso Limitado.
- **Condiciones del Servicio de Google:** [https://developers.google.com/terms](https://developers.google.com/terms)

### 5.6 Almacenamiento de Metadatos

Los metadatos de la música en streaming (título de la canción, artista, marcadores de tempo, puntos de bucle) pueden almacenarse localmente en su dispositivo con fines de gestión de la sesión. El contenido de audio real de los servicios de streaming NO es almacenado por BeatLoop.

## 6. Cómo Usamos Su Información

### 6.1 Funcionalidad Principal de la App
- Creación de cuentas, autenticación y gestión de accesos
- Activación de funciones premium y seguimiento de uso
- Procesamiento de audio local, creación de bucles, ajuste de velocidad y gestión de sesiones
- Grabación de vídeo sincronizada con la reproducción de audio
- Sincronización de sesiones entre dispositivos (solo metadatos)
- Atención al cliente y asistencia técnica

### 6.2 Mejora del Servicio
- Optimización del rendimiento de la App y corrección de errores
- Desarrollo de funciones basado en patrones de uso
- Supervisión de seguridad y prevención del fraude
- Garantía de calidad y pruebas

### 6.3 Comunicaciones
- Notificaciones y actualizaciones relacionadas con el servicio
- Gestión de suscripciones premium
- Respuesta a consultas de soporte
- Cambios importantes en las políticas o el servicio (cuando lo exija la ley)

### 6.4 Análisis y Operaciones Comerciales
- Métricas de Usuarios Activos Mensuales (MAU) y análisis de la interacción
- Análisis de conversión y retención de suscripciones
- Estadísticas generales de uso para la planificación empresarial
- Cumplimiento de obligaciones legales y requisitos fiscales

## 7. Contenido del Usuario y Responsabilidad sobre los Derechos de Autor

### 7.1 Responsabilidad del Usuario sobre el Contenido

**IMPORTANTE:** BeatLoop es una herramienta que permite a los usuarios acceder a música de múltiples fuentes (archivos locales, YouTube, Apple Music, Spotify) con fines de práctica. Al usar la App, usted reconoce y acepta que:

1. **Usted es el único responsable** de todos los archivos de audio, música y otros contenidos que importe, acceda o cree usando BeatLoop
2. **Usted garantiza** que posee u ha obtenido todos los derechos, licencias y permisos necesarios para usar cualquier material protegido por derechos de autor en su contenido
3. **Usted indemniza y exime de responsabilidad** a OnBeat HQ UG (haftungsbeschränkt), sus filiales y proveedores de servicios de cualquier reclamación, daño o responsabilidad derivada de su uso de contenido protegido por derechos de autor o de otro modo
4. **El contenido al que se accede a través de servicios de streaming** (YouTube, Apple Music, Spotify) sigue estando sujeto a los respectivos términos de licencia de esas plataformas y a sus acuerdos de suscripción con ellas

### 7.2 Cumplimiento de los Derechos de Autor

- BeatLoop **no** proporciona, aloja, guarda en caché ni redistribuye música, pistas de audio ni contenido protegido por derechos de autor
- BeatLoop **no** supervisa, revisa ni valida el estado de los derechos de autor del contenido del usuario
- El contenido de los servicios de streaming se reproduce a través de las API oficiales de esos servicios y BeatLoop no lo descarga ni almacena
- Los usuarios deben cumplir con todas las leyes de derechos de autor aplicables en su jurisdicción
- BeatLoop se reserva el derecho de cancelar las cuentas que infrinjan repetidamente las políticas de derechos de autor

### 7.3 Cumplimiento de la Ley de Derechos de Autor de la Era Digital (DMCA)

Si cree que algún contenido de BeatLoop infringe sus derechos de autor, póngase en contacto con nosotros en support@on-beat.de con:
- Su información de contacto y firma electrónica
- Identificación de la obra protegida por derechos de autor cuya infracción se alega
- Identificación del material presuntamente infractor
- Una declaración de buena fe de que el uso no está autorizado
- Una declaración de que la información es exacta y de que usted está autorizado para actuar

### 7.4 Ausencia de Responsabilidad por el Contenido del Usuario

**BeatLoop renuncia expresamente a toda responsabilidad** por:
- La infracción de derechos de autor por parte de los usuarios
- El uso no autorizado de contenido de audio o vídeo protegido
- Cualquier reclamación legal derivada del contenido generado por el usuario
- Los daños resultantes del incumplimiento por parte de los usuarios de la obtención de las licencias adecuadas
- Las reclamaciones de derechos de autor derivadas de los vídeos grabados y compartidos por los usuarios

## 8. Almacenamiento y Seguridad de los Datos

### 8.1 Almacenamiento Local de Datos
- **Los archivos de audio y vídeo** importados desde el almacenamiento local se almacenan exclusivamente en su dispositivo
- **El contenido en streaming** de YouTube, Apple Music y Spotify NO se almacena en su dispositivo ni en nuestros servidores
- **Las sesiones de práctica y los proyectos** permanecen locales en su dispositivo
- **Ningún contenido del usuario** se carga en nuestros servidores sin una acción explícita

### 8.2 Almacenamiento de Datos en la Nube
- **La información de la cuenta** se almacena de forma segura utilizando la infraestructura de Supabase
- **Los metadatos de la sesión** (marcadores, marcas de tiempo, puntos de bucle, nombres de proyectos) pueden sincronizarse
- **Los tokens de autenticación** se cifran y almacenan de forma segura
- **La información de pago** es procesada y almacenada por Apple (iOS), Google (Android) o Stripe (web), no por BeatLoop

### 8.3 Medidas de Seguridad
- Cifrado estándar del sector para la transmisión de datos (TLS/HTTPS)
- Protocolos de autenticación seguros y gestión de tokens
- Evaluaciones de seguridad periódicas y supervisión de vulnerabilidades
- Controles de acceso y registros de auditoría para funciones administrativas
- Procedimientos de respuesta a violaciones de datos y protocolos de notificación a los usuarios

## 9. Transferencias Internacionales de Datos

BeatLoop opera a nivel mundial y puede transferir sus datos personales fuera de su país de residencia, incluso a países que pueden no proporcionar el mismo nivel de protección de datos que su país de origen.

### 9.1 Proveedores de Servicios de Terceros

Los siguientes servicios pueden procesar sus datos fuera de la UE:

**Supabase (Base de Datos y Autenticación):**
- Ubicación de los datos: Región de la UE (Fráncfort/Londres) o EE. UU. con Cláusulas Contractuales Tipo
- Finalidad: Gestión de cuentas y autenticación
- Salvaguardias: Alojamiento conforme al RGPD y acuerdos de tratamiento de datos

**HubSpot (Gestión de Relaciones con los Clientes):**
- Ubicación de los datos: Estados Unidos
- Finalidad: Atención al cliente, gestión de relaciones y seguimiento de la comunicación con el usuario
- Datos procesados: Direcciones de correo electrónico, interacciones de soporte, métricas de interacción del usuario y preferencias de comunicación
- Salvaguardias: Cláusulas Contractuales Tipo y marcos sucesores del Privacy Shield
- Nota: HubSpot procesa la información de contacto y el historial de interacciones para proporcionar soporte personalizado y gestionar las relaciones con los clientes

**Apple (Compras dentro de la Aplicación y MusicKit):**
- Ubicación de los datos: Estados Unidos y UE
- Finalidad: Procesamiento de pagos (iOS) e integración con Apple Music
- Salvaguardias: Los compromisos de privacidad de Apple y los acuerdos de tratamiento de datos

**Google (Play Billing, YouTube API y Google Drive):**
- Ubicación de los datos: Estados Unidos y UE
- Finalidad: Procesamiento de pagos (Android), integración con YouTube e importación de archivos de audio seleccionados por el usuario a través de Google Drive
- Datos (Drive): Metadatos del archivo y contenido de audio (solo lectura, procesamiento local únicamente)
- Salvaguardias: Cláusulas Contractuales Tipo y las condiciones de tratamiento de datos de Google

**Spotify (Spotify Web API):**
- Ubicación de los datos: Estados Unidos y UE
- Finalidad: Integración de streaming de música
- Salvaguardias: Cláusulas Contractuales Tipo y los acuerdos de tratamiento de datos de Spotify

**Stripe (Procesamiento de Pagos):**
- Ubicación de los datos: Estados Unidos y UE
- Finalidad: Pagos de suscripciones premium (web)
- Salvaguardias: Cumplimiento de PCI DSS, Cláusulas Contractuales Tipo

**Resend (Comunicaciones por Correo Electrónico):**
- Ubicación de los datos: Estados Unidos
- Finalidad: Entrega de correos electrónicos transaccionales
- Salvaguardias: Cláusulas Contractuales Tipo y medidas de cumplimiento del RGPD

**Sentry (Informes de Fallos y Errores):**
- **Ubicación de los datos:** Unión Europea (Frankfurt am Main)
- **Operador:** Sentry GmbH, Krausenstraße 9-10, 10117 Berlín, Alemania (empresa matriz: Functional Software, Inc., 45 Fremont Street, 8th Floor, San Francisco, CA 94105, EE. UU.)
- **Finalidad:** Detección y resolución de errores y fallos de la aplicación para mejorar la estabilidad
- **Datos procesados:** Mensajes de error, trazas de pila, versión de la app, tipo de dispositivo, versión del sistema operativo. La información de identificación personal (direcciones de correo electrónico, ID de usuario, rutas de archivos) se elimina antes de la transmisión mediante salvaguardias técnicas (depuración de PII).
- **Base jurídica:** Art. 6(1)(f) del RGPD (interés legítimo en la estabilidad y el funcionamiento sin errores de nuestra aplicación)
- **Período de conservación:** 90 días
- **Salvaguardias:** Acuerdo de Tratamiento de Datos (DPA) firmado de conformidad con el Art. 28 del RGPD, incluidas las Cláusulas Contractuales Tipo
- **Política de Privacidad de Sentry:** [https://sentry.io/privacy/](https://sentry.io/privacy/)
- **Lista de Subencargados del Tratamiento:** [https://sentry.io/legal/subprocessor-list/](https://sentry.io/legal/subprocessor-list/)

### 9.2 Salvaguardias Legales
Todas las transferencias internacionales de datos están protegidas por salvaguardias adecuadas, entre ellas:
- Cláusulas Contractuales Tipo aprobadas por la Comisión Europea
- Decisiones de adecuación cuando corresponda
- Normas Corporativas Vinculantes para proveedores de servicios multinacionales
- Medidas técnicas y organizativas adicionales según sea necesario

## 10. Intercambio y Divulgación de Datos

### 10.1 No Vendemos Datos Personales
BeatLoop no vende, alquila ni comercia con su información personal a terceros con fines de marketing.

### 10.2 Intercambio Limitado de Datos
Podemos compartir su información únicamente en las siguientes circunstancias:

**Proveedores de Servicios:** Con proveedores de servicios de terceros de confianza que ayudan a operar nuestra App, procesar pagos o proporcionar atención al cliente, bajo estrictos acuerdos de confidencialidad.

**Requisitos Legales:** Cuando lo exija la ley, un proceso legal o una solicitud gubernamental, o cuando creamos que la divulgación es necesaria para proteger nuestros derechos, propiedad o seguridad, o los de nuestros usuarios o el público.

**Transferencias Comerciales:** En relación con cualquier fusión, adquisición o venta de activos de la empresa, donde los datos personales puedan transferirse como parte de los activos comerciales.

**Consentimiento:** Con su consentimiento explícito para fines específicos no cubiertos por esta política.

### 10.3 Protección de Datos en el Intercambio
Todos los acuerdos de intercambio de datos incluyen:
- Obligaciones contractuales de protección de datos
- Limitación de la finalidad y restricciones de uso
- Requisitos de seguridad y confidencialidad
- Mecanismos de preservación de los derechos del usuario

## 11. Sus Derechos en virtud de las Leyes de Protección de Datos

### 11.1 Derechos del RGPD (Usuarios de la UE)

Usted tiene los siguientes derechos con respecto a sus datos personales:

**Derecho de Acceso (Artículo 15):** Solicitar una copia de los datos personales que tenemos sobre usted
**Derecho de Rectificación (Artículo 16):** Corregir datos inexactos o incompletos
**Derecho de Supresión (Artículo 17):** Solicitar la eliminación de sus datos personales («derecho al olvido»)
**Derecho a la Limitación del Tratamiento (Artículo 18):** Limitar cómo usamos sus datos
**Derecho a la Portabilidad de los Datos (Artículo 20):** Recibir sus datos en un formato portátil
**Derecho de Oposición (Artículo 21):** Oponerse al tratamiento basado en intereses legítimos
**Derecho a Retirar el Consentimiento:** Cuando el tratamiento se base en el consentimiento

### 11.2 Derechos de la CCPA (Usuarios de California)

Los residentes de California tienen derechos adicionales, entre ellos:
- Derecho a saber qué información personal se recopila
- Derecho a eliminar la información personal
- Derecho a optar por no participar en la venta de información personal (Nota: No vendemos información personal)
- Derecho a la no discriminación por ejercer los derechos de privacidad

### 11.3 Ejercicio de Sus Derechos

Para ejercer sus derechos de privacidad:

**En la App:** Utilice la configuración de la cuenta y los controles de privacidad dentro de la app BeatLoop
**Eliminación de la Cuenta:** Para eliminar sus datos personales, elimine su cuenta a través de la configuración de la cuenta de la app. Esto eliminará permanentemente toda su información personal de nuestros sistemas en un plazo de 30 días
**Correo electrónico:** Póngase en contacto con privacy@on-beat.de con su solicitud
**Verificación de Identidad:** Podemos requerir la verificación de su identidad por motivos de seguridad
**Tiempo de Respuesta:** Responderemos en un plazo de 30 días (RGPD) o 45 días (CCPA)
**Sin Coste:** Las solicitudes de ejercicio de derechos se procesan generalmente de forma gratuita

### 11.4 Derecho a Presentar una Reclamación

Si cree que no hemos abordado adecuadamente sus inquietudes sobre la privacidad, tiene derecho a presentar una reclamación ante su autoridad local de protección de datos. Los usuarios de la UE pueden encontrar su autoridad local en: https://edpb.europa.eu/about-edpb/about-edpb/members_en

## 12. Conservación de Datos

### 12.1 Datos de la Cuenta
- **Cuentas activas:** Conservados durante la duración de su cuenta más 30 días
- **Cuentas inactivas:** Eliminadas automáticamente después de 24 meses de inactividad
- **Cuentas eliminadas:** Eliminadas permanentemente en un plazo de 30 días desde la solicitud de eliminación

### 12.2 Datos de Uso y Análisis
- **Registros de inicio de sesión:** Conservados durante 12 meses por motivos de seguridad
- **Análisis de uso:** Datos agregados conservados indefinidamente, datos individuales durante 24 meses
- **Registros de errores:** Conservados durante 12 meses para la depuración y la mejora

### 12.3 Datos Legales y de Cumplimiento
- **Registros de pagos:** Conservados durante 7 años para cumplir con los requisitos fiscales y contables
- **Correspondencia legal:** Conservada durante el tiempo necesario para fines legales
- **Avisos de la DMCA:** Conservados durante 3 años según lo exige la ley

### 12.4 Contenido del Usuario
- **Archivos locales:** Bajo su control completo en su dispositivo
- **Metadatos de la sesión:** Conservados mientras la cuenta esté activa, eliminados con la eliminación de la cuenta
- **Comunicaciones de soporte:** Conservadas durante 3 años con fines de calidad y formación

## 13. Cookies y Tecnologías de Seguimiento

### 13.1 Uso Actual
BeatLoop actualmente utiliza tecnologías de seguimiento mínimas:
- **Tokens de autenticación:** Para un inicio de sesión seguro y la gestión de sesiones
- **Preferencias de la App:** Almacenadas localmente para recordar su configuración
- **Seguimiento de errores:** Informes básicos de fallos para la estabilidad de la app

### 13.2 Futura Implementación de Análisis
Planeamos implementar análisis de Usuarios Activos Mensuales (MAU) y podemos usar:
- **Cookies de análisis:** Para comprender los patrones de uso de la app
- **Supervisión del rendimiento:** Para optimizar la funcionalidad de la app
- **Herramientas de pruebas A/B:** Para mejorar la experiencia del usuario

### 13.3 Su Control
- **Configuración de cookies:** Puede gestionarse a través de la configuración de su dispositivo
- **Exclusión de análisis:** Estará disponible en la configuración de la app cuando se implemente
- **Seguimiento de terceros:** No utilizamos píxeles de seguimiento de publicidad ni de redes sociales

## 14. Privacidad de los Menores

### 14.1 Restricción de Edad
BeatLoop no está destinado a usuarios menores de 16 años. No recopilamos a sabiendas información personal de menores de 16 años. Si es menor de 16 años, no utilice BeatLoop ni proporcione ninguna información personal.

### 14.2 Aviso a los Padres
Si tenemos conocimiento de que hemos recopilado información personal de un menor de 16 años sin el consentimiento parental verificado, tomaremos medidas para eliminar esa información de inmediato.

### 14.3 Derechos de los Padres
Los padres que crean que su hijo menor de 16 años ha proporcionado información personal a BeatLoop pueden ponerse en contacto con nosotros en privacy@on-beat.de para solicitar la eliminación de dicha información.

## 15. Cambios en esta Política de Privacidad

### 15.1 Actualizaciones de la Política
Podemos actualizar esta Política de Privacidad de vez en cuando para reflejar cambios en nuestras prácticas, tecnología, requisitos legales u otros factores.

### 15.2 Notificación de Cambios
**Cambios menores:** Fecha de «Última Actualización» actualizada en la parte superior de esta política
**Cambios sustanciales:** Notificación por correo electrónico a los usuarios registrados y notificación dentro de la app
**Uso Continuado:** Su uso continuado de BeatLoop después de los cambios constituye una aceptación

### 15.3 Historial de Cambios
Mantenemos un registro de los cambios significativos en la política con fines de transparencia y cumplimiento.

## 16. Información de Contacto

### 16.1 Consultas sobre Privacidad
Para preguntas sobre esta Política de Privacidad o nuestras prácticas de datos:

**Correo electrónico:** privacy@on-beat.de
**Dirección Postal:**
OnBeat HQ UG (haftungsbeschränkt)
Wichterichstraße 4
50937 Köln, Alemania

### 16.2 Solicitudes de Protección de Datos
Para ejercer sus derechos de protección de datos, utilice el correo electrónico anterior e incluya:
- Su nombre completo y la dirección de correo electrónico asociada a su cuenta
- El derecho específico que desea ejercer
- Cualquier información adicional necesaria para verificar su identidad

### 16.3 Compromiso de Respuesta
Nos comprometemos a responder a las consultas sobre privacidad de manera rápida y profesional. Normalmente respondemos en un plazo de 3 a 5 días hábiles para consultas generales y dentro de los plazos legalmente requeridos para las solicitudes formales de ejercicio de derechos.

## 17. Información Legal Adicional

### 17.1 Ley Aplicable
Esta Política de Privacidad se rige por las leyes de Alemania y la Unión Europea. Cualquier disputa que surja de esta política estará sujeta a la jurisdicción de los tribunales alemanes.

### 17.2 Divisibilidad
Si alguna disposición de esta Política de Privacidad se considera inaplicable o inválida, dicha disposición se limitará o eliminará en la medida mínima necesaria para que la Política de Privacidad permanezca por lo demás en pleno vigor y efecto.

### 17.3 Idioma
Esta Política de Privacidad está redactada en inglés. En caso de cualquier discrepancia entre las diferentes versiones lingüísticas, prevalecerá la versión en inglés.

---

**Esta Política de Privacidad se actualizó por última vez el 1 de mayo de 2026 y entra en vigor inmediatamente después de su publicación.**

Para obtener la versión más actual de nuestra Política de Privacidad, consulte este documento periódicamente o póngase en contacto con nosotros en privacy@on-beat.de.
