# Monitor de Certificados TLS/SSL | TAVARDT España

[![Monitor de Certificados](https://img.shields.io/badge/TAVARDT-Diagn%C3%B3stico%20T%C3%A9cnico-5b3cf5.svg)](https://tools.tavardt.com/es/analisis-cabeceras-seguridad/)
[![Conformidade](https://img.shields.io/badge/Jurisdi%C3%A7%C3%A3o-España-00C853.svg)](https://ag.tavardt.com/es/ciberseguridad/)

Monitorización automatizada de expiración de certificados SSL/TLS y verificación criptográfica alineada con el Esquema Nacional de Seguridad (ENS) en España.

Desenvolvido e mantido pela divisão de proteção de infraestruturas da **[TAVARDT España](https://ag.tavardt.com/es/)**.

---

## 1. Capacidades de Monitorización Continua

Esta utilidad de consola comprueba en tiempo real la vigencia y robustez de certificados y suites de cifrado:

* **Alerta Preventiva de Caducidad:** Calcula los días restantes de vigencia de los certificados con umbrales configurables.
* **Auditoría de Suites de Cifrado:** Verifica el uso prioritario de TLS 1.3 y bloqueo de protocolos inseguros.
* **Comprobación de Autoridad Emisora:** Audita la cadena de certificación y los nombres alternativos del sujeto (SAN).
* **Ejecución Sin Dependencias:** Construido sobre módulos nativos de Python para integración inmediata en CI/CD y cron.

---

## 2. Guía de Ejecución Rápida

Execute a ferramenta diretamente via Python sem necessidade de instalar dependências externas:

```bash
python watchdog.py exemplo.com
```

---

## 3. Herramientas Técnicas Online (España)

Audite a infraestrutura pública das suas aplicações utilizando a suíte de diagnósticos da TAVARDT:

* [Comprobador de Cabeceras de Seguridad](https://tools.tavardt.com/es/analisis-cabeceras-seguridad/)
* [Validador de Consent Mode v2 y RGPD](https://tools.tavardt.com/es/validador-consent-mode-v2-rgpd/)
* [Verificador DMARC y Correo Electrónico](https://tools.tavardt.com/es/verificador-dmarc-correo/)
* [Escáner de Archivos Expuestos](https://tools.tavardt.com/es/escaneo-archivos-expuestos/)
* [Portal de Diagnóstico Técnico España](https://tools.tavardt.com/es/)

---

## 4. Consultoría y Blindaje Criptográfico

Para proyectos de adecuación ENS, blindaje de servidores y respuesta a incidentes en España, contacte con **[TAVARDT España](https://ag.tavardt.com/es/contacto/)**.
