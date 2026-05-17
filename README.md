# Amenities Pack · Procediments d'Exportació

Plataforma interna del departament d'exportacions d'Amenities Pack. Recopila els procediments operatius per a exportacions a països fora de la UE, amb checklist interactiu, plantilles descarregables i contactes clau.

## 🌐 Accés a la web

La web està publicada a través de GitHub Pages. Pots accedir-hi des de qualsevol navegador, ordinador o mòbil sense necessitat d'instal·lar res.

## 📋 Què inclou

- **Procediments per país** — Regne Unit i Noruega (futurs països africans en preparació)
- **Checklist interactiu** — El teu progrés es guarda automàticament al navegador
- **Centre de recursos** — Totes les plantilles i cartes de duana centralitzades
- **Contactes clau** — Persones de referència per a cada operador logístic
- **Bones pràctiques** — Recomanacions extretes de l'experiència operativa

## 🗂️ Estructura del projecte

```
amp-procediments/
├── index.html          # Pàgina d'inici
├── uk.html             # Procediment Regne Unit (BUNZL UK)
├── noruega.html        # Procediment Noruega (MASKE)
├── recursos.html       # Centre documental
└── recursos/           # Plantilles i documents
    ├── plantilla-cudos.xlsx
    ├── carta-residus.docx
    ├── carta-doble-us.docx
    ├── carta-gases.docx
    ├── no-cites.docx
    └── pqp.docx
```

## 🛠️ Manteniment

Aquesta web és **estàtica** (HTML, CSS i JavaScript pur), sense backend ni base de dades. El manteniment consisteix bàsicament en dues operacions:

### Actualitzar plantilles o documents
Substitueix el fitxer corresponent dins de la carpeta `recursos/` mantenint el mateix nom. Els enllaços de descàrrega de tota la web apuntaran automàticament a la versió nova.

### Actualitzar contingut textual
Edita directament els fitxers HTML. Cada fitxer té el contingut comentat per facilitar trobar el que cal modificar.

## 🔒 Política de privadesa

Aquest repositori és públic. No s'inclouen credencials, dades personals sensibles ni informació confidencial al codi. Els emails de contactes professionals que apareixen són de domini públic empresarial.

## 📦 Tecnologies

- HTML5 + CSS3 + JavaScript ES6
- Sense dependències ni frameworks
- `localStorage` per al progrés del checklist (privat per a cada usuari)
- Tipografies via Google Fonts (Plus Jakarta Sans + Fraunces)

## ©️ Crèdits

Departament d'Exportacions · Amenities Pack
Versió 1.1 · Maig 2026
