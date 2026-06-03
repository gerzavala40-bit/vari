# VARI - Sistema Integral de Asistencia y Seguridad Ciudadana

VARI (inspirado en Álvaro y Clari) es un proyecto de software de arquitectura distribuida pensado como tesis final de carrera. El objetivo principal es resolver la exclusión digital de los adultos mayores, centralizando servicios esenciales sin distracciones, a la vez que funciona como una red de videovigilancia urbana autosustentable.

## 🚀 Componentes del Ecosistema
* **VARI Hogar:** Dispositivo doméstico compacto con interfaz táctil simplificada de alto contraste, enfocado en salud, comunicación familiar (llamadas/videollamadas) y validación de tarjeta SUBE por RFID/NFC de manera local.
* **VARI Urbano:** Tótems públicos antivandálicos instalados en postes de la vía pública (ej. paradas de colectivos) con conectividad a redes móviles o infraestructura municipal. Integra botones de emergencia, lector de huella dactilar (seguridad biométrica mediante cifrado hash) y cámaras de seguridad activas las 24 hs.

## 💰 Modelo de Negocio (Monetización Híbrida)
* **B2B (Empresas de Seguros):** Las aseguradoras pagan un abono mensual corporativo para acceder al archivo de video encriptado de las esquinas críticas, reduciendo el fraude en accidentes viales.
* **B2C (Consumidores Particulares):** Los ciudadanos particulares pueden solicitar fragmentos específicos de video mediante un sistema de "pago por evento" (pago único) tras un siniestro.

## 💾 Primer Esbozo de la Base de Datos (Estructura Conceptual)
El backend procesará los datos mediante las siguientes entidades principales conectadas:
1. `Usuarios`: Información básica del ciudadano y código hash de su huella.
2. `Ficha_Medica_Usuario`: Grupo sanguíneo, enfermedades crónicas, alergias y obras sociales para emergencias médicas.
3. `Contactos_Emergencia`: Agenda de familiares directos vinculados al usuario con orden de prioridad.
4. `Terminales_Urbana`: Registro, ubicación geográfica y telemetría de estado de cada tótem en la calle.
5. `Registro_Siniestros`: Control de videos bloqueados, fechas de eventos y estado de pagos de descargas.

---
*Desarrollado de a muy de a poquito. Cronograma estimado de finalización: 2028.*
