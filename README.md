<div align="center">
  <img src="brand_logo.png" width="140" alt="StegoSec logo"><br>
  <h1>StegoSec</h1>
  <p><em>Protección digital con enfoque técnico y estratégico.</em></p>

  <a href="https://github.com/stegosec">
    <img alt="GitHub followers" src="https://img.shields.io/github/followers/stegosec?label=Follow&style=for-the-badge">
  </a>
  <a href="#">
    <img alt="Made with love" src="https://img.shields.io/badge/Made%20with-%E2%9D%A4-ff69b4?style=for-the-badge">
  </a>
</div>

---

## ¿Quiénes somos?

**StegoSec** es una **empresa de ciberseguridad** especializada en **Threat Intelligence (CTI)**, **pentesting**, **análisis/gestión de vulnerabilidades**, **hardening** y **automatización**. Diseñamos soluciones y servicios para equipos técnicos con un enfoque práctico y medible (ROI técnico y de riesgo).

Este es el repositorio principal de la empresa: concentramos enlaces a proyectos, documentación y nuestro **roadmap público**.

---

## Portafolio de servicios

### 1) Pentesting (caja gris/negra/blanca)
- **Web / API** (REST/GraphQL), **móvil** (iOS/Android), **infra/red**, **cloud** (AWS/Azure/GCP), **wireless**.
- Cobertura: autenticación/autorización, lógica de negocio, exposición de datos, configuración insegura, deserialización, inyección, RCE, SSRF, IDOR, etc.
- **Metodologías:** OWASP WSTG/MSTG/ASVS, PTES, NIST SP 800-115, MITRE ATT&CK.

### 2) Análisis y gestión de vulnerabilidades
- Escaneo autenticado y no autenticado, priorización **CVSS/EPSS** y contexto de negocio.
- Ciclo **VM**: descubrimiento → análisis → priorización → **plan de remediación** → **validación de cierre**.
- Integración opcional con CI/CD, tickets y métricas (SLA/SLO).

### 3) Auditoría de configuración y hardening
- Firewalls (p. ej., **Fortinet**), WAFs, switches y sistemas.
- Baselines: **CIS Benchmarks**, NIST, mejores prácticas del fabricante.
- Evidencia de gaps y “quick wins” con recomendaciones prácticas.

### 4) CTI / ASM (Attack Surface Management)
- Recolección y enriquecimiento de indicadores, monitoreo de superficie expuesta, fugas de credenciales/marca.
- Casos de uso: **detección temprana**, reducción de **exposición externa**, soporte a IR y Red Team.

### 5) Automatización y DevSecOps
- Integración de **SAST/DAST/IaC** en pipelines, controles de calidad de seguridad, firmas y artefactos reproducibles.
- Flujos de **orquestación** para tareas repetitivas de seguridad.

> **Entregables estándar (por servicio):**
> - **Reporte ejecutivo** (riesgo, impacto, priorización).
> - **Reporte técnico** con evidencias reproducibles.
> - **Plan de remediación** priorizado y **validación de cierre**.
> - Sesión de **debriefing** técnico.

---

## Productos (JurassicSec Suite)

- **TriceraAudit Lite** — Auditor de backups **Fortinet `.conf`** (un solo archivo).  
  Reglas YAML baseline y **PSIRT (resumen corto)** por versión/rama.  
  Repo: https://github.com/stegosec/Tricera-lite
- **TriceraAudit PRO** *(en roadmap)* — Web/API, multi-upload, tokens/licencias, reportes firmados, CVE/PSIRT detallado, scheduling y on-prem.
- **raptorscan** *(roadmap)* — Descubrimiento de activos / ASM.
- **velociparser** *(roadmap)* — Parsers para switches/WAFs.
- **eggwatcher** *(roadmap)* — Auditorías periódicas vía API/scheduler.
- **dinoeye** *(roadmap)* — Dashboard multi-firewall y alertas.
- **t-rexhunter** *(roadmap)* — Threat hunting basado en logs/IA.

---

## Metodologías y estándares

- **OWASP** (WSTG, ASVS, MSTG), **PTES**, **NIST SP 800-115**, **MITRE ATT&CK**, **CIS Benchmarks**.
- Evidencias reproducibles, enfoque “risk-based” y trazabilidad de hallazgos → remediación.

---

## Repos destacados

| Proyecto | Descripción | Estado |
|---|---|---|
| **TriceraAudit Lite** | Auditoría de `.conf` Fortinet (single-file), reglas baseline y PSIRT corto. | ✅ Público |
| **falconspy** | Plataforma de **CTI/ASM** (inteligencia de amenazas). | 🚧 |
| **blockspy** | Blog/Docs y laboratorio de pruebas. | 🚧 |
| **riskx** | Scanner de riesgo de IP/servicios (enterprise). | 🔒 Privado |
| **tool-templates** | Plantillas de arranque para nuevos proyectos. | ✅ Público |

---

## Cómo trabajamos

1. **Kickoff** y definición de alcance/activos/objetivos.
2. **Ejecución** con comunicación continua (canal dedicado).
3. **Entrega**: reporte ejecutivo/técnico, plan de remediación.
4. **Validación** de correcciones y cierre.
5. Opcional: **acompañamiento** trimestral y métricas (SLA/SLO).

**Para cotización rápida de pentest**, comparte:
- Tipo (Web/API/Móvil/Infra/Cloud), ambientes y autenticación/roles.
- Nº aproximado de endpoints/microservicios y dependencias externas.
- Ventanas de ejecución, restricciones y objetivos de negocio.

---

## Privacidad y cumplimiento

- **NDA** y acuerdos de tratamiento de datos bajo solicitud.
- Evidencias mínimas y **cifrado en reposo**.
- Para herramientas **Lite**: todo se procesa localmente; no se ejecuta código de clientes; solo análisis estático.

---

## Roadmap público

- Ampliar reglas y PSIRT en **TriceraAudit Lite**.
- Lanzamiento **TriceraAudit PRO** (MVP comercial).
- Módulos de **ASM**, **hardening multi-vendor** y **automatización**.

---

## Soporte y contacto

- Dudas técnicas y bugs: abre un **Issue** en el repositorio correspondiente.
- Consultas comerciales / servicios: *(añade aquí tu correo o formulario oficial; p. ej. sales@stegosec…)*

---

<div align="center">
  <sub>© StegoSec. Todos los derechos reservados.</sub>
</div>

