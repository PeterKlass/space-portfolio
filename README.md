# 🌌 Space Portfolio
Dieses Projekt ist ein modernes und visuell beeindruckendes Portfolio, das mit Next.js und einer Vielzahl moderner Technologien entwickelt wurde. Es bietet ein immersives Design mit 3D-Effekten und interaktiven Animationen, um Skills und Projekte auf kreative Weise zu präsentieren.

## 🎯 Ziel des Projekts
- Präsentation von Projekten und Skills in einem einzigartigen Design.
- Schaffung eines immersiven Erlebnisses durch 3D-Hintergründe und Animationen.
- Benutzerfreundlichkeit durch ein einfaches und responsives Layout.

## 🌟 Features
- Interaktiver Sternenhintergrund: Erstellt mit React Three Fiber für ein realistisches und animiertes Erlebnis.
- Responsives Layout: Optimiert für Mobilgeräte, Tablets und Desktops.
- Animierte Sektionen: Mit Framer Motion für flüssige Übergänge und Interaktivität.
- Videohintergründe: Hinzugefügt für mehr Tiefe und visuelle Attraktivität.
- Projekte und Skills: In strukturierten Abschnitten mit klaren Erklärungen und Bildern dargestellt.
- Soziale Links und Footer: Einfacher Zugriff auf wichtige Plattformen.

## 📂 Projektstruktur
```
/
├── app/                           # Hauptstruktur von Next.js
│   ├── globals.css                # Globales Styling
│   ├── layout.tsx                 # Seitenlayout
│   ├── page.tsx                   # Startseite
├── components/                    # Wiederverwendbare Komponenten
│   ├── main/                      # Hauptkomponenten (Hero, Footer, Skills, etc.)
│   ├── sub/                       # Sub-Komponenten (HeroContent, SkillDataProvider)
├── constants/                     # Konstante Werte für Social Media Links und Skills
├── public/                        # Statische Dateien (Bilder, Videos, Icons)
├── utils/                         # Utility-Funktionen (Animationslogik)
│   └── motion.ts                  # Animationskonfiguration für Framer Motion
└── package.json                   # Abhängigkeiten und Skripte
```

## 🚀 Technologien
- Next.js: Framework für Server-Side-Rendering und statische Webseiten.
- TailwindCSS: Utility-First-Framework für das Styling.
- Framer Motion: Für beeindruckende Animationen und Seitenübergänge.
- React Three Fiber: Für die Integration von 3D-Elementen wie den Sternenhintergrund.
- Heroicons: Für Icons und visuelle Elemente.
- React Intersection Observer: Für inhaltsgesteuerte Animationen.

## 📝 Lernpunkte
Während der Erstellung dieses Projekts habe ich folgende Themen und Technologien vertieft:

- Verwendung von Framer Motion: Animationen für Übergänge und visuelle Interaktivität.
- Komplexe Layouts mit TailwindCSS: Effizientes Styling von responsiven Komponenten.
- Integration von Videos: Hinzufügen von immersiven Video-Hintergründen für visuelle Tiefe.

## ⚙️ Installation und Verwendung
### 1. Repository klonen:
```
git clone https://github.com/PeterKlass/space-portfolio.git
cd space-portfolio
```

### 2. Abhängigkeiten installieren:
```
npm install
```

### 3. Entwicklungsserver starten:
```
npm run dev
```

### 4. Öffne die App im Browser:
```
http://localhost:3000
```

### 5. Produktions-Build erstellen:
```
npm run build
```

## 🖥️ Live-Demo
Die Live-Version dieses Portfolios ist hier verfügbar: https://space-portfolio-ten-chi.vercel.app/

## 🔗 Weitere Projekte
Weitere meiner Projekte findest du hier: https://github.com/PeterKlass
