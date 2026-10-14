<h1 align="center">¡Hola! / Hi! I'm Cristóbal 👋</h1>

<p align="center">
  <strong>Desarrollador de Software · Software Developer</strong><br>
  📍 Quito, Ecuador 🇪🇨
</p>

<p align="center">
  <a href="https://github.com/cristobalmontenegro?tab=repositories"><img alt="Repositorios" src="https://img.shields.io/badge/Repositorios-13-181717?style=flat&logo=github"></a>
  <img alt="MantisBT" src="https://img.shields.io/badge/MantisBT-Plugins-8DB93E?style=flat">
  <img alt="NetSuite" src="https://img.shields.io/badge/NetSuite-SuiteScript%202.1-1F6FEB?style=flat">
  <img alt="PHP" src="https://img.shields.io/badge/PHP-7.4%2B-777BB4?style=flat&logo=php&logoColor=white">
  <img alt="License" src="https://img.shields.io/badge/Licencia-MIT%20%2F%20GPL-blue?style=flat">
</p>

---

## 🇪🇸 Español

Les comparto algunas de mis herramientas que resuelvan problemas reales: plugins para **MantisBT**, scripts y módulos para **NetSuite (SuiteScript 2.1)**, utilidades de administración para Windows y Linux, migradores de sitios y sistemas de reportería.

La mayoría de los proyectos están documentados en **español e inglés** y publicados en este perfil. Abajo encontrarás un **índice completo** de todo lo que he publicado, con un resumen y un enlace directo a cada repositorio y subproyecto.

Si alguno de mis proyectos te ha servido en tu día a día y quieres apoyar lo que hago, ¡te lo agradezco muchísimo! 👇

## 🇬🇧 English

I share with you some of my tools that solve real problems: plugins for **MantisBT**, **NetSuite** scripts and modules (SuiteScript 2.1), Windows and Linux administration utilities, website migrators, and reporting systems.

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
| 2 | [🚀 Netsuite — NetSuite Excellence Suite](#-netsuite) | 16 módulos SuiteScript 2.1 (móvil, inventario, finanzas, RFM, auditoría, controles, respaldos) |
| 3 | [🧰 Tools — Utilidades variadas](#-tools) | Suite de administración Windows, lector de retenciones SRI y visor de PDF |
| 4 | [🖥️ Action1 Scripts](#-action1) | 14 scripts PowerShell para automatización y gestión de endpoints Windows con Action1 (RMM) |
| 5 | [🇪🇨 Dimm-Linux](#-dimm-linux) | DIMM del SRI de Ecuador corriendo en Linux moderno |
| 6 | [✍️ FirmadorSRI](#-firmadorsri) | Servidor propio de firmado XAdES-BES para el SRI Ecuador (Python + FastAPI + Docker) |
| 7 | [📊 WebReporter](#-webreporter) | Sistema de reportería y dashboards en PHP + MySQL |
| 8 | [🌐 WordPress-Migrator](#-wordpress-migrator) | Migrador interactivo de WordPress entre dominios y hostings |
| 9 | [🧩 Apps y utilidades](#apps-utilidades) | Firmador portable, gestor de música MP3, sistema de respaldo a Blu-ray/DVD/CD y juegos HTML |
| 10 | [🔱 Forks y contribuciones](#-forks-y-contribuciones--forks--contributions) | Mejoras a proyectos de terceros |

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

**ES:** *NetSuite Excellence Suite (Edición Comunitaria)* — colección de scripts y módulos de grado profesional para extender NetSuite más allá de sus límites estándar. Son **16 módulos independientes**, cada uno desplegable por separado y con su propio README y **guía de implementación paso a paso**.

**EN:** *NetSuite Excellence Suite (Community Edition)* — a curated collection of professional-grade scripts and modules that extend NetSuite beyond standard limits. **16 independent modules**, each deployable on its own and shipping with its own README and **step-by-step implementation guide**.

| Módulo | Tecnología | Descripción (ES / EN) |
|:---|:---|:---|
| [**RFM_Engine**](https://github.com/cristobalmontenegro/Netsuite/tree/main/RFM_Engine) | Scheduled (3) | Segmentación de clientes por **7 variables de comportamiento** (R·F·M·P·Z·G·D) con puntaje 0–100, índice DuPont y calificación por letras. / Customer segmentation by **7 behaviour variables** (R·F·M·P·Z·G·D) with a 0–100 score, DuPont index and letter rating. |
| [**Kardex_Optimizado**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Kardex_Optimizado) | Scheduled + Suitelet | Libro auxiliar de inventarios en tiempo real con indexación avanzada. / Real-time inventory ledger with advanced indexing. |
| [**Deployment_Audit**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Deployment_Audit) | Suitelet + SuiteQL | Audita todos los Script Deployments: creador, audiencia, allroles y estado. / Audits every Script Deployment: creator, audience, allroles and state. |
| [**Committed_Stock_Monitor**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Committed_Stock_Monitor) | Suitelet | Encuentra qué bloquea el inventario (cantidades comprometidas) en vivo. / Finds what is blocking inventory (committed quantities) in real time. |
| [**Mobile_Suite**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Mobile_Suite) | Suitelet (8) | UI móvil para fuerza de ventas: visitas, pedidos, portal, stock, casos y aging. / Mobile field-force UI: visits, orders, portal, stock, cases and aging. |
| [**SFTP_Foundation**](https://github.com/cristobalmontenegro/Netsuite/tree/main/SFTP_Foundation) | RESTlet + Python | Respaldo y sincronización del File Cabinet a servidores externos (recuperación ante desastres). / File Cabinet backup & sync to external servers (disaster recovery). |
| [**Fichas_PDF**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Fichas_PDF) | Suitelet | Fichas técnicas 360° de Artículos y Clientes en PDF. / 360° Item & Customer PDF data sheets. |
| [**Inventory_Reports**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Inventory_Reports) | PDF/XML | Impresiones PDF personalizadas para operaciones de almacén. / Custom PDF printouts for warehouse operations. |
| [**Accounting_Vouchers**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Accounting_Vouchers) | PDF | Comprobantes imprimibles (asientos, pagos, facturas) para cumplimiento contable. / Printable financial vouchers for accounting compliance. |
| [**Text_Sanitizer**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Text_Sanitizer) | User Event | Normaliza descripciones y direcciones al guardar (seguro para facturación electrónica). / Normalizes descriptions & addresses on save (e-invoicing safe). |
| [**Reopen_Transaction**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Reopen_Transaction) | User Event + Suitelet | Reabre transacciones cerradas que la UI bloquea. / Reopens closed transactions the UI blocks. |
| [**Lock_Units_Field**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Lock_Units_Field) | Client Script | Vuelve de solo lectura el campo "Unidades" de la línea. / Makes the line "Units" field read-only. |
| [**Inbound_Shipment_Gate**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Inbound_Shipment_Gate) | User Event + Client | Exige "costos completos" antes de recibir un Inbound Shipment. / Requires "costs complete" before receiving an Inbound Shipment. |
| [**Sales_Budget_Guard**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Sales_Budget_Guard) | User Event | Bloquea presupuestos duplicados Vendedor + Período + Clasificación. / Blocks duplicate Seller + Period + Classification budgets. |
| [**Purchase_Invoice_Comparator**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Purchase_Invoice_Comparator) | Suitelet | Concilia el TXT de facturas recibidas vs Vendor Bills (clave de acceso). / Reconciles received-invoice TXT vs Vendor Bills (access key). |
| [**Inventory_Utilities**](https://github.com/cristobalmontenegro/Netsuite/tree/main/Inventory_Utilities) | Suitelet | Herramientas de mantenimiento, p. ej. corrección de lotes negativos. / Maintenance tools, e.g. negative lot correction. |

### 🧩 Herramienta relacionada / Related tool

**ES:** Extensión de navegador para trabajar con NetSuite (fork con mejoras sobre el proyecto original). **EN:** A browser extension for working with NetSuite (fork with enhancements over the original project).

| Repositorio | Autor original | Descripción (ES / EN) |
|:---|:---|:---|
| [**netsuite-field-explorer-plus**](https://github.com/cristobalmontenegro/netsuite-field-explorer-plus) | Michoel Chaikin | Extensión de Chrome para descubrir los nombres de campo de NetSuite; agrega expandir/colapsar y copiar JSON, y es compatible con Manifest V3. / Chrome extension to discover NetSuite field names, with expand/collapse, JSON copy and Manifest V3 support. |

---

<a id="-tools"></a>
## 🧰 Tools

**[github.com/cristobalmontenegro/Tools](https://github.com/cristobalmontenegro/Tools)** — *PowerShell · HTML/JS · Bash*

**ES:** Utilidades variadas del día a día, agrupadas en un solo repositorio.

**EN:** A grab-bag of everyday utilities, grouped in a single repository.

| Proyecto | Tecnología | Descripción (ES / EN) |
|:---|:---|:---|
| [**SuperScriptcmc**](https://github.com/cristobalmontenegro/Tools/tree/main/SuperScriptcmc) | PowerShell | Suite interactiva para Windows (v11.0): gestión de usuarios, debloat, despliegue de software con GUI (Chocolatey), tareas programadas, formato regional/idioma es-EC y configuración de red. / Interactive Windows admin suite (v11.0): users, debloat, GUI software deployment, scheduled tasks, es-EC region/language setup and network config. |
| [**LectorRetenciones**](https://github.com/cristobalmontenegro/Tools/tree/main/LectorRetenciones) | HTML | Lector de comprobantes de retención (SRI Ecuador) en una página web. / Web-based reader for withholding tax receipts (SRI Ecuador). |
| [**FlippingBook**](https://github.com/cristobalmontenegro/Tools/tree/main/FlippingBook) | HTML/JS | Visor de PDF con efecto de libro de páginas (basado en turn.js y pdf.js). / PDF viewer with a page-flip book effect (turn.js + pdf.js). |
| [**actualizar.sh**](https://github.com/cristobalmontenegro/Tools/blob/main/actualizar.sh) | Bash | Script de actualización integral del sistema (APT, Snap, Flatpak, firmware y herramientas). / One-shot system update script (APT, Snap, Flatpak, firmware and tools). |

---

<a id="-action1"></a>
## 🖥️ Action1 Scripts

**[github.com/cristobalmontenegro/Action1](https://github.com/cristobalmontenegro/Action1)** — *PowerShell · Action1 RMM*

**ES:** Colección de **14 scripts PowerShell** para automatización, mantenimiento y gestión de endpoints Windows con **Action1** (RMM). Cada script vive en su propia subcarpeta con un **README bilingüe** que documenta qué hace, sus parámetros, sus códigos de salida y sus riesgos. Ideal para despliegues masivos de limpieza, reparación del sistema, software y políticas de Windows.

**EN:** A collection of **14 PowerShell scripts** for Windows endpoint automation, maintenance and management with **Action1** (RMM). Each script lives in its own subfolder with a **bilingual README** documenting what it does, its parameters, its exit codes and its risks. Great for fleet-wide rollouts of cleanup, system repair, software and Windows policies.

| Categoría | Scripts | Descripción (ES / EN) |
|:---|:---:|:---|
| 🔧 **maintenance** | 4 | Limpieza, diagnóstico y reparación del sistema (temporales, `.lnk` rotos, CHKDSK, SFC, DISM). / Cleanup, diagnostics and system repair (temp files, broken `.lnk`, CHKDSK, SFC, DISM). |
| 🍫 **chocolatey** | 2 | Actualización masiva con `choco upgrade all` y atributo personalizado de inventario. / Mass upgrade with `choco upgrade all` and an inventory custom attribute. |
| 📦 **installers** | 3 | Instalación/actualización de FluentCleaner (WinGet), FluentTweaker (GitHub) y FirmaEC. / Install/update of FluentCleaner (WinGet), FluentTweaker (GitHub) and FirmaEC. |
| 🛡️ **policies** | 2 | Bloqueo de cuentas Microsoft + OneDrive y desactivación de OOBE/SCOOBE. / Block Microsoft accounts + OneDrive and disable OOBE/SCOOBE. |
| 🚀 **boot** | 2 | Control del arranque: Modo Seguro con red (persistente) y menú F8 heredado. / Boot control: Safe Mode with networking (persistent) and the legacy F8 menu. |
| 💾 **reporting** | 1 | Atributo personalizado `LowDisk` para alertas de poco espacio en disco. / `LowDisk` custom attribute for low-disk warnings. |

> **Nota / Note (ES):** los 14 scripts están publicados directamente en la raíz del repo (estructura plana, sin carpeta `scripts/` intermedia). El README raíz lista todos con tabla de descripción, parámetros y reinicio. **(EN):** all 14 scripts live directly in the repo root (flat structure, no intermediate `scripts/` folder). The root README lists them all with a description / parameters / reboot table.

---

<a id="-dimm-linux"></a>
## 🇪🇨 Dimm-Linux

**[github.com/cristobalmontenegro/Dimm-Linux](https://github.com/cristobalmontenegro/Dimm-Linux)** — *Eclipse RCP · Java 21 · SWT/GTK*

**ES:** Migración completa de **DIMM** (*Declaración de Impuestos y Manejo de Módulos*), el software de declaración de impuestos del **SRI de Ecuador**, para que funcione en **Linux moderno**. Resuelve la incompatibilidad de la aplicación Eclipse 3.3 (2007) con Java 21, los fallos de SWT/GTK y reimplementa el sitio de actualizaciones caído del SRI para instalar plugins (ATS, RDEP, ICE, ADI y más) por Internet.

**EN:** A full port of **DIMM**, the tax filing software of Ecuador's **SRI**, so it runs on **modern Linux**. It solves the incompatibilities of the 2007 Eclipse 3.3 application with Java 21 and SWT/GTK, and re-implements the now-defunct SRI update site so that plugins (ATS, RDEP, ICE, ADI, etc.) can be installed over the Internet.

---

<a id="-firmadorsri"></a>
## ✍️ FirmadorSRI

**[github.com/cristobalmontenegro/FirmadorSRI](https://github.com/cristobalmontenegro/FirmadorSRI)** — *Python 3.12 · FastAPI · Docker · XAdES-BES*

**ES:** Servidor propio de **firmado electrónico XAdES-BES** para los comprobantes del **SRI Ecuador** (facturas, notas de crédito/débito, guías de remisión, retenciones y liquidaciones de compra). Es **autocontenido y agnóstico** del sistema que lo consume: cualquier ERP o backend le envía el XML en Base64 y recibe el documento firmado, listo para el SRI. Incluye validación XSD opcional con los esquemas oficiales, dos modos de certificado, Docker y una suite de verificación criptográfica.

**EN:** A self-hosted **XAdES-BES signing server** for Ecuador's **SRI** e-invoices (invoices, credit/debit notes, waybills, withholding receipts and purchase settlements). It is **self-contained and agnostic** to the consuming system: any ERP or backend posts the Base64 XML and gets the signed document back, ready for the SRI. Includes optional XSD validation with the official schemas, two certificate modes, Docker and a cryptographic verification suite.

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

<a id="apps-utilidades"></a>
## 🧩 Apps y utilidades / Apps & Utilities

**ES:** Aplicaciones y utilidades independientes, listas para usar.

**EN:** Standalone, ready-to-use apps and utilities.

### ✍️ [FirmaEcmc](https://github.com/cristobalmontenegro/FirmaEcmc) — *Java 8 · Windows / Linux / macOS*

**ES:** Paquete **portable** del firmador de documentos electrónicos de Ecuador (FirmaEC), con **JRE embebido** y lanzadores para Windows y Linux/macOS, para firmar **sin instalar Java**. Su gran diferencia: **permite firmar con una fecha y hora personalizadas, incluso anteriores a hoy**. Fork y reempaquetado del firmador original, con crédito a su autor.

**EN:** A **portable** package of Ecuador's electronic document signer (FirmaEC), with an **embedded JRE** and launchers for Windows and Linux/macOS, so you can sign **without installing Java**. Its big difference: **you can sign with a custom date and time, including dates earlier than today**. A fork/repackaging of the original signer, crediting its author.

### 🎵 [music-manager](https://github.com/cristobalmontenegro/music-manager) — *Bash · Python*

**ES:** Suite de scripts para **descargar, organizar, renombrar y depurar** tu biblioteca musical MP3 desde Spotify. Incluye detección perceptual de duplicados (Chromaprint/AcoustID), metadatos con `eyeD3` y menú interactivo.

**EN:** A Bash/Python suite to **download, organize, rename and clean up** your MP3 music library from Spotify. Includes perceptual duplicate detection (Chromaprint/AcoustID), `eyeD3` tag handling and an interactive menu.

### 💾 [organizar-backups](https://github.com/cristobalmontenegro/organizar-backups) — *Bash*

**ES:** Sistema de respaldo, compresión, verificación y quema a discos (Blu-ray/DVD/CD) desde la terminal. Sustituye ~26 scripts sueltos por un único `backup.sh` con menú, perfiles, filtros, *pull* por SSH, empaquetado `rar`/`7z`, verificación `sha256`, ejecución en segundo plano y avisos por correo.

**EN:** A terminal backup, compression, verification and optical-disc burning system (Blu-ray/DVD/CD). It replaces ~26 loose scripts with a single `backup.sh` featuring a menu, profiles, filters, SSH pull, `rar`/`7z` packing, `sha256` verification, background jobs and email alerts.

### 🎮 [JuegosHTML](https://github.com/cristobalmontenegro/JuegosHTML) — *HTML5 · CSS3 · JavaScript*

**ES:** Colección de juegos clásicos en HTML/CSS/JS puro que corren directo en el navegador: Space Invaders, Moon Patrol, Tetris, Nonogramas, FreeCell, Sumplete y Pixel Flow.

**EN:** A collection of classic games in plain HTML/CSS/JS that run straight in the browser: Space Invaders, Moon Patrol, Tetris, Nonograms, FreeCell, Sumplete and Pixel Flow.

---

<a id="-forks-y-contribuciones--forks--contributions"></a>
## 🔱 Forks y contribuciones / Forks & Contributions

**ES:** Mejoras y adaptaciones sobre proyectos de terceros, con crédito a sus autores originales.

**EN:** Improvements and adaptations built on top of third-party projects, with credit to the original authors.

| Repositorio | Autor original | Descripción (ES / EN) |
|:---|:---|:---|
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

---

## 👤 Author / Autoría

**Cristóbal Montenegro**  
GitHub: [@cristobalmontenegro](https://github.com/cristobalmontenegro)

---

## 📜 License / Licencia

MIT — see [`LICENSE`](./LICENSE).
