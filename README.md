<h1 align="center">¡Hola! / Hi! I'm Cristóbal 👋</h1>

<p align="center">
  <strong>Desarrollador de Software · Software Developer</strong><br>
  📍 Quito, Ecuador 🇪🇨
</p>

<p align="center">
  <a href="https://github.com/cristobalmontenegro?tab=repositories"><img alt="Repositorios" src="https://img.shields.io/badge/Repositorios-10-181717?style=flat&logo=github"></a>
  <img alt="MantisBT" src="https://img.shields.io/badge/MantisBT-Plugins-8DB93E?style=flat">
  <img alt="NetSuite" src="https://img.shields.io/badge/NetSuite-SuiteScript%202.1-1F6FEB?style=flat">
  <img alt="PHP" src="https://img.shields.io/badge/PHP-7.4%2B-777BB4?style=flat&logo=php&logoColor=white">
  <img alt="License" src="https://img.shields.io/badge/Licencia-MIT%20%2F%20GPL-blue?style=flat">
</p>

---

## 🇪🇸 Español

Soy desarrollador de software en **Quito, Ecuador**. Me apasiona el **open source** y crear herramientas que resuelvan problemas reales: plugins para **MantisBT**, scripts y módulos para **NetSuite (SuiteScript 2.1)**, utilidades de administración para Windows y Linux, migradores de sitios y sistemas de reportería.

La mayoría de mis proyectos están documentados en **español e inglés** y publicados en este perfil. Abajo encontrarás un **índice completo** de todo lo que he publicado, con un resumen y un enlace directo a cada repositorio y subproyecto.

Si alguno de mis proyectos te ha servido en tu día a día y quieres apoyar lo que hago, ¡te lo agradezco muchísimo! 👇

## 🇬🇧 English

I'm a software developer from **Quito, Ecuador**. I'm passionate about **open source** and building tools that solve real problems: plugins for **MantisBT**, **NetSuite** scripts and modules (SuiteScript 2.1), Windows and Linux administration utilities, website migrators, and reporting systems.

Most of my projects are documented in **both Spanish and English** and are published on this profile. Below you'll find a **complete index** of everything I've published, with a summary and a direct link to each repository and subproject.

If any of my projects has helped you in your daily work and you'd like to support what I do, I'd really appreciate it! 👇

<br>

<p align="center">
  <a href="https://ko-fi.com/cristobalmontenegro" target="_blank" id="support-button">
    <img height="36" style="border:0px;height:36px;" src="https://storage.ko-fi.com/cdn/kofi6.png?v=6" border="0" alt="Buy Me a Coffee at ko-fi.com" />
  </a>
</p>

---

<h2 id="indice">🗂️ Índice / Index</h2>

| # | Proyecto / Project | Descripción |
|:-:|:---|:---|
| 1 | [🐛 Mantis — Plugins para MantisBT](#-mantis) | 7 plugins para el gestor de incidencias MantisBT |
| 2 | [🚀 Netsuite — NetSuite Excellence Suite](#-netsuite) | 8 módulos SuiteScript 2.1 (móvil, inventario, finanzas, RFM, respaldos) |
| 3 | [🧰 Tools — Utilidades variadas](#-tools) | Suite de administración Windows, lector de retenciones SRI y visor de PDF |
| 4 | [🇪🇨 Dimm-Linux](#-dimm-linux) | DIMM del SRI de Ecuador corriendo en Linux moderno |
| 5 | [📊 WebReporter](#-webreporter) | Sistema de reportería y dashboards en PHP + MySQL |
| 6 | [🌐 WordPress-Migrator](#-wordpress-migrator) | Migrador interactivo de WordPress entre dominios y hostings |
| 7 | [🔱 Forks y contribuciones](#-forks-y-contribuciones--forks--contributions) | Mejoras a proyectos de terceros |

---

<a id="-mantis"></a>
## 🐛 Mantis

**[github.com/cristobalmontenegro/Mantis](https://github.com/cristobalmontenegro/Mantis)** — *MantisBT 2.X · PHP 7.4+*

**ES:** Repositorio de plugins personalizados para [MantisBT](https://www.mantisbt.org/), el sistema de seguimiento de incidencias. Cada plugin se instala copiando su carpeta a `mantis/plugins/` e instalándolo desde *Manage Plugins*.

**EN:** A collection of custom plugins for [MantisBT](https://www.mantisbt.org/), the issue tracking system. Each plugin is installed by copying its folder into `mantis/plugins/` and enabling it from *Manage Plugins*.

| Plugin | Versión | Descripción (ES / EN) |
|:---|:---:|:---|
| [**Attachments**](https://github.com/cristobalmontenegro/Mantis/tree/main/plugins/Attachments) | 3.2 | Formulario de adjuntos dedicado, con fecha de subida y modo solo-PDF. / Dedicated attachment upload form with upload date and PDF-only mode. |
| [**BugRelationPriority**](https://github.com/cristobalmontenegro/Mantis/tree/main/plugins/BugRelationPriority) | 3.0.0 | Columnas configurables (prioridad, resolución, campos personalizados) en la tabla de relaciones. / Configurable columns in the bug relations table. |
| [**CustomReports**](https://github.com/cristobalmontenegro/Mantis/tree/main/plugins/CustomReports) | 2.1.0 | Interfaz para crear y ejecutar reportes SQL personalizados (solo SELECT, con filtros y export CSV). / Interface to build and run custom SQL reports. |
| [**ReminderManager**](https://github.com/cristobalmontenegro/Mantis/tree/main/plugins/ReminderManager) | 2.1.3 | Recordatorios automáticos por correo basados en campos de fecha, con plantillas y placeholders. / Automated email reminders driven by custom date fields. |
| [**ResolutionAccess**](https://github.com/cristobalmontenegro/Mantis/tree/main/plugins/ResolutionAccess) | 1.0 | Restringe quién puede modificar el campo Resolución (bloqueo visual y en servidor). / Restricts who can change the Resolution field. |
| [**SuspendToggle**](https://github.com/cristobalmontenegro/Mantis/tree/main/plugins/SuspendToggle) | 1.1 | Alterna la resolución del caso entre Abierto (10) y Suspendido (80) sin cambiar el estado. / Toggles case resolution between Open and Suspended. |
| [**TOTP**](https://github.com/cristobalmontenegro/Mantis/tree/main/plugins/TOTP) | 1.1.0 | Autenticación de doble factor (2FA) con códigos TOTP y QR. / Two-factor authentication (2FA) with TOTP codes and QR. |

---

<a id="-netsuite"></a>
## 🚀 Netsuite

**[github.com/cristobalmontenegro/Netsuite](https://github.com/cristobalmontenegro/Netsuite)** — *NetSuite · SuiteScript 2.1*

**ES:** *NetSuite Excellence Suite (Edición Comunitaria)* — colección de scripts y módulos de grado profesional para extender NetSuite más allá de sus límites estándar. Cada módulo es independiente y desplegable por separado.

**EN:** *NetSuite Excellence Suite (Community Edition)* — a curated collection of professional-grade scripts and modules that extend NetSuite beyond standard limits. Each module is independent and deployable on its own.

| Módulo | Tecnología | Descripción (ES / EN) |
|:---|:---|:---|
| [**Mobile_Suite**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Mobile_Suite) | Suitelet | UI móvil para fuerza de ventas: visitas, pedidos, portal, stock, casos y aging. / Mobile field-force UI: visits, orders, portal, stock, cases and aging. |
| [**SFTP_Foundation**](https://github.com/cristobalmontenegro/Netsuite/tree/main/SFTP_Foundation) | RESTlet + Python | Respaldo y sincronización del File Cabinet a servidores externos (recuperación ante desastres). / File Cabinet backup & sync to external servers. |
| [**RFM_Engine**](https://github.com/cristobalmontenegro/Netsuite/tree/main/RFM_Engine) | Scheduled + SuiteQL | Segmentación de clientes por Recencia, Frecuencia y Monto, con ranking 1–5. / Customer segmentation by Recency, Frequency and Monetary value. |
| [**Kardex_Optimizado**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Kardex_Optimizado) | Scheduled + Suitelet | Libro auxiliar de inventarios en tiempo real con indexación avanzada. / Real-time inventory ledger with advanced indexing. |
| [**Inventory_Reports**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Inventory_Reports) | PDF/XML | Impresiones PDF personalizadas para operaciones de almacén. / Custom PDF printouts for warehouse operations. |
| [**Accounting_Vouchers**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Accounting_Vouchers) | PDF | Comprobantes imprimibles (asientos, pagos, facturas) para cumplimiento contable. / Printable financial vouchers for accounting compliance. |
| [**Fichas_PDF**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Fichas_PDF) | Suitelet | Fichas técnicas 360° de Artículos y Clientes en PDF. / 360° Item & Customer PDF data sheets. |
| [**Inventory_Utilities**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Inventory_Utilities) | Suitelet | Herramientas de mantenimiento, p. ej. corrección de lotes negativos. / Maintenance tools, e.g. negative lot correction. |

---

<a id="-tools"></a>
## 🧰 Tools

**[github.com/cristobalmontenegro/Tools](https://github.com/cristobalmontenegro/Tools)** — *PowerShell · HTML/JS · Bash*

**ES:** Utilidades variadas del día a día, agrupadas en un solo repositorio.

**EN:** A grab-bag of everyday utilities, grouped in a single repository.

| Proyecto | Tecnología | Descripción (ES / EN) |
|:---|:---|:---|
| [**SuperScriptcmc**](https://github.com/cristobalmontenegro/Tools/tree/main/SuperScriptcmc) | PowerShell | Suite interactiva para Windows: gestión de usuarios, debloat, despliegue de software con GUI (Chocolatey), tareas programadas y configuración de red. / Interactive Windows admin suite: users, debloat, GUI software deployment, scheduled tasks and network setup. |
| [**LectorRetenciones**](https://github.com/cristobalmontenegro/Tools/tree/main/LectorRetenciones) | HTML | Lector de comprobantes de retención (SRI Ecuador) en una página web. / Web-based reader for withholding tax receipts (SRI Ecuador). |
| [**FlippingBook**](https://github.com/cristobalmontenegro/Tools/tree/main/FlippingBook) | HTML/JS | Visor de PDF con efecto de libro de páginas (basado en turn.js y pdf.js). / PDF viewer with a page-flip book effect (turn.js + pdf.js). |
| [**actualizar.sh**](https://github.com/cristobalmontenegro/Tools/blob/main/actualizar.sh) | Bash | Script de actualización integral del sistema (APT, Snap, Flatpak, firmware y herramientas). / One-shot system update script (APT, Snap, Flatpak, firmware and tools). |

---

<a id="-dimm-linux"></a>
## 🇪🇨 Dimm-Linux

**[github.com/cristobalmontenegro/Dimm-Linux](https://github.com/cristobalmontenegro/Dimm-Linux)** — *Eclipse RCP · Java 21 · SWT/GTK*

**ES:** Migración completa de **DIMM** (*Declaración de Impuestos y Manejo de Módulos*), el software de declaración de impuestos del **SRI de Ecuador**, para que funcione en **Linux moderno**. Resuelve la incompatibilidad de la aplicación Eclipse 3.3 (2007) con Java 21, los fallos de SWT/GTK y reimplementa el sitio de actualizaciones caído del SRI para instalar plugins (ATS, RDEP, ICE, ADI y más) por Internet.

**EN:** A full port of **DIMM**, the tax filing software of Ecuador's **SRI**, so it runs on **modern Linux**. It solves the incompatibilities of the 2007 Eclipse 3.3 application with Java 21 and SWT/GTK, and re-implements the now-defunct SRI update site so that plugins (ATS, RDEP, ICE, ADI, etc.) can be installed over the Internet.

---

<a id="-webreporter"></a>
## 📊 WebReporter

**[github.com/cristobalmontenegro/WebReporter](https://github.com/cristobalmontenegro/WebReporter)** — *PHP 7.4+ · MySQL/MariaDB*

**ES:** Sistema de reportería ligero y universal que convierte datos de MySQL/MariaDB en tablas y gráficas interactivas. Incluye dashboard personalizable, gestión de usuarios (Admin/Usuario), filtros, exportación a Excel/impresión y protección CSRF/XSS.

**EN:** A lightweight, universal reporting system that turns MySQL/MariaDB data into interactive tables and charts. Includes a customizable dashboard, user management (Admin/User), filtering, Excel export/print and CSRF/XSS protection.

---

<a id="-wordpress-migrator"></a>
## 🌐 WordPress-Migrator

**[github.com/cristobalmontenegro/WordPress-Migrator](https://github.com/cristobalmontenegro/WordPress-Migrator)** — *Python 3*

**ES:** Asistente interactivo para migrar sitios WordPress entre dominios y hostings. Reemplaza URLs respetando la serialización de PHP (Elementor y plugins complejos), evita bloqueos de hostings restringidos mediante túnel PHP/SFTP, soporta reanudación y actualiza `wp-config.php` automáticamente.

**EN:** An interactive assistant to migrate WordPress sites between domains and hosts. It replaces URLs safely (serialization-aware), bypasses restricted-hosting blocks with a PHP/SFTP tunnel, supports resume and updates `wp-config.php` automatically.

---

<a id="-forks-y-contribuciones--forks--contributions"></a>
## 🔱 Forks y contribuciones / Forks & Contributions

**ES:** Mejoras y adaptaciones sobre proyectos de terceros, con crédito a sus autores originales.

**EN:** Improvements and adaptations built on top of third-party projects, with credit to the original authors.

| Repositorio | Autor original | Descripción (ES / EN) |
|:---|:---|:---|
| [**netsuite-field-explorer-plus**](https://github.com/cristobalmontenegro/netsuite-field-explorer-plus) | Michoel Chaikin | Extensión de Chrome para descubrir los nombres de campo de NetSuite; agrega expandir/colapsar y copiar JSON, y es compatible con Manifest V3. / Chrome extension to discover NetSuite field names, with expand/collapse, JSON copy and Manifest V3 support. |
| [**hp42**](https://github.com/cristobalmontenegro/hp42) | richmit | Colección de programas para calculadoras HP-42S, Free42 y DM42. / A collection of programs for HP-42S, Free42 and DM42 calculators. |

---

## ☕ Apóyame / Support me

**ES:** Si alguno de estos proyectos te resultó útil, puedes invitarme un café. ¡Gracias por el apoyo!

**EN:** If any of these projects was useful to you, you can buy me a coffee. Thanks for the support!

<p align="center">
  <a href="https://ko-fi.com/cristobalmontenegro" target="_blank">
    <img height="36" style="border:0px;height:36px;" src="https://storage.ko-fi.com/cdn/kofi6.png?v=6" border="0" alt="Buy Me a Coffee at ko-fi.com" />
  </a>
</p>

<meta name="google-site-verification" content="IHHqRg-yt7K-NvhsAk2NEfonN49Ypb2DZpWoKYgNyQ8" />
