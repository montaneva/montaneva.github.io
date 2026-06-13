# Cercador de RAM i Fàrmacs

Eina de consulta ràpida de termes mèdics en català, orientada a evitar
faltes ortogràfiques en redacció clínica i de farmacovigilància.

🔗 **[Accés a l'eina](https://montaneva.github.io/public_resources/cercador/)**

## Fonts de dades

Cerca termes de dues bases de dades diferenciades:

- **RAM** — Reaccions Adverses a Medicaments (`ramDescripcio.csv`)
- **Fàrmacs** — Noms de medicaments (`farmacs.csv`)

Les dades es descarreguen en temps real des d'aquest mateix repositori:
[montaneva/FVcsv](https://github.com/montaneva/FVcsv)

## Funcionalitats

- Cerca autocomplete amb coincidència parcial i insensible a accents
- Ressaltat de la paraula cercada als resultats del desplegable
- Còpia automàtica al porta-retalls en seleccionar un terme
- Commutador RAM / Fàrmacs per canviar de font de dades
- Etiqueta de font clicable que obre el fitxer CSV original en una nova finestra
- Comptador de termes carregats per a cada font
- Enllaços de traducció/consulta configurables (Google Traductor, Optimot,
  Termcat, Softcatalà...) que s'actualitzen dinàmicament amb el terme cercat
- Mode clar / fosc
- Disseny responsiu adaptat a mòbil i escriptori
- Notificacions toast lleugeres per a accions de l'usuari

## Dependències externes

| Llibreria | Versió |
|-----------|--------|
| jQuery | 3.7.1 |
| jQuery UI (Autocomplete) | 1.13.3 |
| Google Fonts — Outfit | — |

## Crèdits

Idea original i concepte: **@montaneva**  
Codificat al 100% per IA: **Anthropic Fable 5**
