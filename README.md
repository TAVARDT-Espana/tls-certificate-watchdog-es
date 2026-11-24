# Watchdog de Certificados TLS/SSL

[![Alcance de la Verificación Perimetral](https://img.shields.io/badge/TAVARDT-Diagn%C3%B3stico%20T%C3%A9cnico-5b3cf5.svg)](https://tools.tavardt.com/es/analisis-cabeceras-seguridad/)
Monitorización automatizada de caducidad de certificados SSL/TLS, integridad de cadena criptográfica y cumplimiento técnico en España.

Desarrollado y mantenido por el área de ciberseguridad y protección de infraestructuras de **TAVARDT**.

***

## 1. Alcance de la Verificación Perimetral

Esta utilidad de consola evalúa la vigencia, protocolos y robustez criptográfica de los certificados SSL/TLS:

* **Alerta Preventivo de Caducidad:** Calcula los días restantes de validez del certificado con alertas configurables.
* **Auditoría de Cifrados y Protocolos:** Verifica el soporte de TLS 1.3 y garantiza la revocación de versiones obsoletas.
* **Validación de Autoridad Emisora (CA):** Comprueba la entidad certificadora de la cadena de confianza y los nombres SAN.
* **Cero Dependencias Externas:** Desarrollado únicamente con las librerías nativas ssl y socket de Python.

***

## 2. Guía de Ejecución Rápida

Ejecute la herramienta directamente mediante Python sin necesidad de instalar librerías externas:

```bash
python watchdog.py ejemplo.es
```

***

## 3. Herramientas Técnicas Online (España)

Compruebe el estado de seguridad de sus aplicaciones públicas con las herramientas de TAVARDT:

* Comprobador de Cabeceras de Seguridad
* [Validador de Consent Mode v2 y RGPD](https://tools.tavardt.com/es/validador-consent-mode-v2-rgpd/)
* [Verificador DMARC y Correo Electrónico](https://tools.tavardt.com/es/verificador-dmarc-correo/)
* [Escáner de Archivos Expuestos](https://tools.tavardt.com/es/escaneo-archivos-expuestos/)
* [Portal de Diagnóstico Técnico España](https://tools.tavardt.com/es/)

***

## 4. Consultoría y Blindaje Técnico

Para hardening de servidores, renovación automatizada y auditorías criptográficas en España, contacte con **TAVARDT**.

***

## Enlaces Útiles

* **Portal Corporativo:** https://ag.tavardt.com/es/
* **Suite de Diagnósticos:** https://tools.tavardt.com/es/
* **Contacto Técnico:** https://ag.tavardt.com/es/contacto/

***

© 2026 TAVARDT. Todos los derechos reservados.
