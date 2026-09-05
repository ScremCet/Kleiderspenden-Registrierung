# Kleiderspenden-Registrierung

Eine Webanwendung zur Registrierung und Verwaltung von Kleiderspenden für Krisengebiete.

## Features

- **Registrierungsformular**: Benutzerfreundliches Formular für Spender zur Registrierung von Kleiderspenden
- **Standortbasierte Validierung**: Validierung von Abholadressen und Postleitzahlen gegen Geschäftsstellen
- **Mehrere Abholoptionen**: Unterstützung für persönliche Übergabe und Abholung durch Sammelfahrzeuge
- **Spendenverfolgung**: Kategorisierung von Spenden nach Kleidungstyp und Krisengebiet

## Schnellstart

Bitte stelle sicher, dass Node.js und npm auf deinem System installiert sind.

    npm install          # Abhängigkeiten installieren
    npm run dev          # Dev-Server starten auf localhost:4321
    npm run build        # Für Produktion bauen

## Projekt Struktur

    src/
    ├── components/       # Formular- und UI-Komponenten
    ├── layouts/          # Seiten-Layouts
    ├── pages/            # Route-Seiten (Registrierung, Bestätigung, Rechtliche Seiten)
    └── assets/           # Statische Assets

## Seiten

    / - Willkommensseite
    /registration - Kleiderspenden-Registrierungsformular
    /confirmation - Registrierungsbestätigung
    /impressum - Impressum
    /datenschutz - Datenschutzerklärung
    /nutzungsbedingungen - Nutzungsbedingungen