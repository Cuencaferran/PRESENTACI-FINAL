# 🌌 Portfoli Executiu i Defensa Final del Curs: La Saga EverPia & Projectes Tecnològics

---

## 👨‍💻 Consultor Tècnic Principal
* **Nom:** Ferran Cuenca Garcia
* **Equip de Treball / Cotutor:** Aran Pérez
* **Rol:** Tècnics Júnior d'Infraestructura, Ciberseguretat i Solucions Cloud
* **Empresa de Consultoria:** **EverPia Solutions** 🚀

> 💬 *“Mantingueu la calma, documenteu cada pas i recordeu: mai no feu rm -rf / ni tan sols de broma.”* — Llei de supervivència de l'administrador IT.

---

## 🧠 Introducció i Enfocament de la Defensa

Benvinguts a la documentació central i memòria de presentació final de tot el curs acadèmic. Aquest repositori recull la transformació professional de **júnior a tècnic de sistemes**, a través d'una simulació hyperrealista del mercat laboral actual: **"EverPia: Sobreviure en una empresa IT"**.

Davant l'augment de clients exigents, contractes crítics i servidors cremant, hem actuat com els **bombers digitals** del sector. Hem dissenyat infraestructures robustes, auditat la ciberseguretat de sistemes reals, automatitzat serveis de xarxa en entorns crítics i aplicat estrictes polítiques de **Green IT (Sostenibilitat i Economia Circular)**.

A continuació es presenta el **Full de Ruta Interactiu** amb l'accés directe a cadascun dels projectes de la nostra trajectòria corporativa.

---

## 📂 Índex Interactiu Global de Projectes (Estratègia 2-8)

Fes clic a qualsevol dels títols o enllaços per accedir directament a la carpeta de producció d'aquell bloc temàtic:

### 📁 Bloc 1: Organització, Hosting i Seguretat Inicial (Projecte 2 i 3)
* 📐 **[Projecte 2-1: Índex General d'Infraestructura](./PROJECTE2-1/)**
  * *Organització de l'equip de treball, gestió de repositoris amb Git/GitHub i disseny de la primera metodologia de treball.*
* ☁️ **[Projecte 3-1: Serveis de Xarxa i Primers Laboratoris](./PROJECTE3-1/)**
  * *Control de fluxos mitjançant Kanban, publicació de configuracions DNS directes a producció, i anàlisi de rendiment d'emmagatzematge lògic (LVM vs Storage Spaces).*

### 📁 Bloc 2: La Transformació Integral — "La Incubadora" (Projecte 5)
* 🌱 **[Projecte 5: Cas d'Èxit "La Incubadora" — Índex General](./PROJECTE5-CUENCAFERRAN/)**
  * *Unificació d'infraestructures tecnològiques.*
  * **[T01: Disseny Integrat](./T01%20Disseny%20de%20la%20Soluci%C3%B3%20T%C3%A8cnica%20Integrada/)** / **[T03: Servidors Segurs SFTP](./T03%20Serveis%20de%20transfer%C3%A8ncia%20de%20fitxers/)**
  * **[T05 i T06: Controlador de Domini i Active Directory en Windows Server](./T05%20Instal·lació%20del%20domini/)**
  * **[T08 i T09: Operació Ciberseguretat Activa contra Malware i Vulnerabilitats](./T08%20Seguretat%20protegint-nos%20contra%20el%20malware/)**

### 📁 Bloc 3: Desplegament Avançat i Auditories d'E-Learning (Projecte Nexus / 6)
* 🎓 **[Projecte 6: Infraestructura Educativa Nexus](./projecte6/)**
  * *Desenvolupament i optimització d'una arquitectura web d'alt rendiment per a entorns de formació tècnica.*
  * **[P01: Memòria de la Proposta](./P01%20Producte%20final%20memòria%20tècnica%20de%20la%20proposta/)**
  * **[T02 i T03: Duel de Titans — Apache vs Nginx](./T02%20Missió%20Apache%20Desplegament%20Multidomini%20i%20segur/)** *(Mètriques, consum de CPU/RAM i tria de producció).*
  * **[T06: Implantació de PKI i Signatura Digital Corporativa](./T06%20Projecte%20Nexus.%20Implantació%20de%20PKI%20i%20Signatura%20Digital%20Corporativa/)**
  * **[T12: Comparativa de Plataformes Funcions — Moodle vs Canvas LMS](./T12%20Comparativa%20Moodle%20vs%20Canvas%20LMS/)**

### 📁 Bloc 4: Modernització Logística i Cloud (Projecte FoodLogistic / 7)
* 🚛 **[Projecte 7: Cas Real FoodLogistic S.A.](./projecte7/)**
  * *Reestructuració i protecció de dades d'una gran empresa nacional amb 35 treballadors.*
  * **[T03 i T04: Centralització de Fitxers i Impressió de Xarxa](./T03%20Servidor%20de%20fitxers/)**
  * **[T06: Operació Escut Digital (Legalització Web i LOPD)](./T06%20Operació%20Escut%20Digital%20Fent%20100%25%20legal%20la%20web%20de%20FoodLogístic%20S.A/)**
  * **[T09: Planificació de Projectes — Diagrama de Gantt Professional](./T09%20Estimació%20temporal%20de%20projecte%20%28Diagrama%20de%20Gantt%20professional%29/)**

### 📁 Bloc 5: Connecta't al Futur (Projecte 8)
* 🌍 **[Projecte 8: El Repte de la Digitalització Real de PIMEs](./projecte8/)**
  * *Consultoria i auditoria per a negocis locals combinant solucions al núvol amb polítiques ecològiques actives.*

---

## 🛠️ Resum de Fites Tècniques Defensades (Casos Clínics)

Al llarg del tribunal d'avui, es defensaran decisions crítiques preses de manera autònoma basant-nos en dades empíriques i laboratoris PoC:

### 1. 🛡️ Còpies de Seguretat i Recuperació (Estratègia 3-2-1)
Implementació de solucions automatitzades multiplataforma:
* **A Windows:** Desplegament de **Duplicati** integrant un disc local secundari d'automatització horària coordinat amb una replicació al núvol (**Google Drive**).
* **A Linux:** Creació d'scripts automatitzats en Bash (`fullbackup.sh` i `incrementalbackup.sh`) enllaçats a tasques programades de **Cron**, assegurant que la unitat externa en format **XFS** es munti i es desmunti exclusivament durant el procés de còpia per evitar atacs de *Ransomware*.

### 🌐 2. Serveis de Directori Centralitzats (OpenLDAP)
Resolució del caos operatiu de la startup *Innovatech*. Instal·lació i disseny complet d'un arbre d'Unitats Organitzatives (`OU`), injecció d'usuaris mitjançant fitxers de càrrega estructurada `.ldif` i configuració de mòduls PAM/NSS en clients Linux per passar d'autenticacions locals a un ecosistema centralitzat.

### 🔌 3. Auditoria de Diagnosi de Xarxa i Resolució DNS
Auditoria CLI contra servidors lents utilitzant eines avançades de diagnosi. Anàlisi en profunditat de respostes autoritatives, registres clau (`A`, `NS`, `MX`, `SOA`), controls de propagació (`TTL`) i validacions mitjançant mode interactiu de `nslookup` i ordres complexes de `dig` (com resolucions inverses `-x`).

### 📂 4. Emmagatzematge Compartit en Xarxa Nativa Linux (NFSv3)
Desplegament i anàlisi de polítiques d'exportació a `/etc/exports` per a l'empresa *DevOptimize Solutions*. Demostració pràctica de les limitacions reals d'identitats de seguretat (`UID`/`GID`) en entorns sense autenticació centralitzada, gestionant opcions com `root_squash` i permisos estrictes del sistema de fitxers.

---

## 🧰 Stack Tecnològic i Eines de Gestió Utilitzades

| Àrea | Eines i Tecnologies Utilitzades |
| :--- | :--- |
| **Sistemes Operatius** | Windows Server 2025, Ubuntu Server, Zorin OS, Windows 11 Pro |
| **Hipervisors** | Oracle VM VirtualBox / VMware Workstation |
| **Serveis Core** | OpenLDAP, BIND9, NFS, CUPS, ProFTPd/sFTP, Apache, Nginx |
| **Còpies i Clons** | Duplicity (Linux), Duplicati (Windows), Rescuezilla |
| **Plataformes Web / LMS** | WordPress, Moodle, Canvas LMS |
| **Disseny i Gestió Agil** | Figma (UI/UX), GitHub Classroom, Microsoft Planner (Kanban), Gantt |

---

## 💚 Sostenibilitat i Qualitat Professional (Green IT)

Aquest portfoli demostra que el nostre rol no s'ha limitat a fer funcionar la tecnologia, sinó a aplicar **criteris de Sostenibilitat i Informàtica Verda**. Cada decisió (com triar Nginx pel seu baix consum, ajustar mètriques de rendiment, implementar l'economia circular o auditar segons la LOPD) s'ha realitzat minimitzant la petjada de carboni de la infraestructura dels nostres clients.

---
🚀 **L'equip de consultoria d'EverPia està llest per a la defensa final davant la junta directiva.**# PRESENTACIÓ-FINAL
