# 🎙️ FarmacoCasts

> *Aprèn farmacologia escoltant!*

FarmacoCasts és una **Aplicació Web Progressiva (PWA)** dissenyada per a dispositius mòbils, concebuda com a complement didàctic auditiu per a estudiants de Farmacologia Clínica. Ofereix una biblioteca de pòdcasts educatius allotjats a Google Drive, amb cerca integrada, que permet als estudiants repassar els continguts del curs en qualsevol lloc i moment: durant els desplaçaments, en els descansos o en sessions de repàs.

El projecte es troba actualment en fase **Beta** i està destinat principalment als estudiants de la [Universitat Autònoma de Barcelona (UAB)](https://www.uab.cat), on els pòdcasts segueixen el temari oficial de Farmacologia Clínica.

---

## 🌐 Aplicació en línia

**[https://montaneva.github.io/podcasts/](https://montaneva.github.io/podcasts/)**

També podeu escanejar el codi QR inclòs a la secció "Compartir" de l'app per instal·lar-la directament al vostre mòbil.

---

## ✨ Funcionalitats principals

### 🎧 Biblioteca de pòdcasts
Una llista estructurada i renderitzada dinàmicament d'episodis d'àudio, cadascun associat a:
- **Títol** — el tema tractat a l'episodi.
- **Etiqueta de tema** — la unitat del curs corresponent (p. ex. *Tema 1*, *Tema 8*).
- **Etiqueta de professor/a** — el/la docent responsable del contingut.
- **Etiqueta de data** — data de publicació, amb el distintiu **"Nou!"** destacat per als episodis publicats durant el mes en curs.

Els episodis s'obren directament en el reproductor d'àudio de Google Drive en una nova pestanya, mantenint la interfície principal neta i lleugera.

### 🔍 Cerca en temps real
Una barra de cerca filtra la llista de pòdcasts a l'instant per títol o paraules clau associades a mesura que l'usuari escriu, amb un botó per esborrar la cerca amb un sol clic.

### 📲 PWA — Instal·lable al mòbil
FarmacoCasts és una Aplicació Web Progressiva completa. Els usuaris poden instal·lar-la a la pantalla d'inici tant a **Android** (via Chrome o Firefox) com a **iOS** (via el menú Compartir de Safari), oferint una experiència similar a una app nativa amb:
- Icona i pantalla de càrrega personalitzades.
- Compatibilitat total amb els marges de zona segura en dispositius amb retall (iPhone, etc.).
- Un **avís d'instal·lació contextual** dins de l'app que recorda si l'usuari ja l'ha descartat.
- Un **Service Worker** (`sw.js`) registrat per a funcionament sense connexió i temps de càrrega ràpids.

### ℹ️ Panell d'informació
Una secció d'informació amb pestanyes a la part inferior de l'app inclou quatre panells:
- **Advertiment** — aclareix que els pòdcasts són un recurs complementari i que les diapositives oficials de classe continuen sent el material d'estudi de referència.
- **Compartir** — instruccions pas a pas per instal·lar la PWA a Android i iOS, més un codi QR.
- **Copyright** — el contingut està llicenciat sota **CC BY-NC-SA 4.0**, que permet compartir i adaptar lliurement el material per a usos no comercials amb atribució.
- **Contacte** — un enllaç mailto a l'autora, ofuscat contra robots de recollida de dades mitjançant la inversió de la cadena de text.

---

## 🤖 Projecte generat amb IA

FarmacoCasts és un projecte generat íntegrament amb intel·ligència artificial:

| Component | Eina |
|---|---|
| Disseny i programació de la webapp | **Anthropic Claude Sonnet** |
| Generació dels pòdcasts educatius | **Google NotebookLM** |

---

## 🛠️ Tecnologies utilitzades

FarmacoCasts és intencionadament senzill: una aplicació web estàtica d'un sol fitxer, sense pas de compilació ni dependències externes, la qual cosa facilita enormement el seu allotjament a GitHub Pages.

- **HTML, CSS i JavaScript purs** — sense frameworks ni llibreries.
- **APIs PWA** — Service Worker, Web App Manifest, event `beforeinstallprompt`.
- **Google Drive** — utilitzat com a backend d'allotjament d'àudio per als fitxers de pòdcast.
- **GitHub Pages** — allotjament estàtic.

---

## ⚖️ Llicència

El contingut es publica sota **Creative Commons BY-NC-SA 4.0**.  
Sou lliures de compartir i adaptar el material per a usos no comercials, sempre que es faci la corresponent atribució i es distribueixi sota la mateixa llicència.

Consulteu la llicència completa a [creativecommons.org/licenses/by-nc-sa/4.0/deed.ca](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ca).

---

## 👩 Autora

**Eva Montané** — [eva.montane@uab.cat](mailto:eva.montane@uab.cat)
