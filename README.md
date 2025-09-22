<!-- HERO -->
<div align="center">
  <img src="brand_logo.png" width="140" alt="StegoSec logo"><br/>
  <h1>StegoSec</h1>
  <p><em>Protección digital con enfoque técnico y estratégico.</em></p>

  <!-- Badges -->
  <img alt="CTI" src="https://img.shields.io/badge/CTI-Threat%20Intel-111827?labelColor=0f172a&logo=protonvpn&logoColor=white&style=for-the-badge">
  <img alt="Pentesting" src="https://img.shields.io/badge/Pentesting-Offensive-111827?labelColor=0f172a&logo=apachekylin&logoColor=white&style=for-the-badge">
  <img alt="Vuln Management" src="https://img.shields.io/badge/Vuln%20Mgmt-Prioritization-111827?labelColor=0f172a&logo=datadog&logoColor=white&style=for-the-badge">
  <img alt="Hardening" src="https://img.shields.io/badge/Hardening-CIS%2FNIST-111827?labelColor=0f172a&logo=gnometerminal&logoColor=white&style=for-the-badge">
  <img alt="Automation" src="https://img.shields.io/badge/Automation-DevSecOps-111827?labelColor=0f172a&logo=githubactions&logoColor=white&style=for-the-badge">

  <br/><br/>
  <!-- CTAs -->
  <a href="https://github.com/stegosec"><b>GitHub</b></a> ·
  <a href="mailto:contacto@stegosec.com">contacto@stegosec.dev</a> ·
</div>

---

## 🚀 Qué hacemos (en 20 segundos)

- **Pentesting** (Web/API, móvil, infra, cloud) con metodología OWASP/PTES/NIST.  
- **Gestión de vulnerabilidades** con priorización **CVSS+EPSS** y contexto de negocio.  
- **Hardening & Config Audit** en firewalls, switches, WAFs y sistemas.  
- **CTI/ASM** para reducir superficie de ataque y detectar exposición.  
- **Automatización/DevSecOps**: controles en CI/CD y tareas repetibles de seguridad.

> Entregables: **reporte ejecutivo**, **reporte técnico reproducible**, **plan de remediación** y **validación de cierre**.

---

## 🦖 JurassicSec Suite (productos)

<div align="center">

<table>
<tr>
<td width="50%" valign="top">

### TriceraAudit **Lite**
**Auditoría offline** de configuraciones  
- **Fortinet `.conf` (backup)**  
- Reglas **baseline** + **PSIRT** (resumen corto)  
- UI con **candados PRO** visibles

<a href="https://github.com/stegosec/Tricera-lite">Repositorio →</a>

</td>
<td width="50%" valign="top">

### TriceraAudit **PRO**
Arquitectura **modular** por plugins (FW/SW/WAF)  
- Multi-vendor: Cisco, Palo Alto, Juniper, F5, NGINX/ModSec, **y más**  
- Multi-archivo, **API**, scheduling, reportes firmados  
- **CVE/PSIRT detallado**, licenciamiento por token, on-prem

<sub><i>Roadmap público en este repo</i></sub>

</td>
</tr>
</table>

</div>

<details>
<summary><b>¿Por qué un único producto multi-vendor?</b></summary>

- **Una marca / una UX** (menos fricción para clientes).  
- **Plugins por tipo/vendor** → ciclos de release independientes.  
- **Licenciamiento granular** (activar solo lo contratado).  
- **Aislamiento**: cada plugin corre en su contenedor (menos superficie de riesgo).
</details>

---

## 💼 Servicios (tarjetas rápidas)

<div align="center">

<table>
<tr>
<td width="33%" valign="top">

### 🔓 Pentesting
OWASP WSTG/ASVS/MSTG, PTES, NIST 800-115.  
**Web/API, móvil, cloud, red.**  
• AuthZ/IDOR • Inyección • SSRF • RCE • Lógica de negocio

</td>
<td width="33%" valign="top">

### 🛡️ Vulnerability Mgmt
Escaneo auth/no-auth, priorización **CVSS+EPSS**,  
**SLA/SLO** y remediación guiada.  
Integración con CI/CD y tickets.

</td>
<td width="33%" valign="top">

### 🧰 Hardening & Config
Baselines **CIS/NIST** y fabricante.  
Gaps, “quick wins” y **playbooks** claros.  
FW, **switches**, **WAFs**, sistemas.

</td>
</tr>
<tr>
<td width="33%" valign="top">

### 🛰️ CTI / ASM
Detección temprana, fugas de marca, exposición externa,  
apoyo a IR y Red Team.

</td>
<td width="33%" valign="top">

### ⚙️ DevSecOps
SAST/DAST/IaC en pipelines, artefactos firmados,  
**automatización** de tareas de seguridad.

</td>
<td width="33%" valign="top">

### 📊 Entregables
**Ejecutivo + Técnico**, plan de remediación,  
**validación de cierre** y sesión de debrief.

</td>
</tr>
</table>

</div>

---

## 🧩 Cómo funciona TriceraAudit (multi-vendor)

1. **Core** detecta tipo/vendor del archivo (p. ej., Fortinet backup `.conf`).  
2. Selecciona el **plugin** adecuado (FW/SW/WAF).  
3. Ejecuta reglas y **PSIRT/CVE** (Lite = resumen; PRO = detalle).  
4. Genera hallazgos con **prioridad**, contexto y remediaciones.

> **Lite hoy:** plugin **Fortinet** (.conf) + baseline + PSIRT corto.  
> **PRO:** + Cisco, Palo Alto, Juniper, F5, NGINX/ModSec, AWS WAFv2, etc.

---

## ⏱️ Empieza en 1 minuto (Lite)

```bash
git clone https://github.com/stegosec/Tricera-lite.git
cd Tricera-lite
docker compose up -d
# Abre http://localhost:8000 y sube un .conf de Fortinet
