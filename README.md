# Histaminscanner

Ein kostenloses, browserbasiertes Tool zur Einschätzung von Zutatenlisten bei Histaminintoleranz (HIT).

## Was macht das Tool?

Der Histaminscanner analysiert die Zutatenliste eines Lebensmittels und ordnet jede Zutat einer von vier Kategorien zu:

- 🔴 **Histaminreich** – enthält direkt Histamin oder biogene Amine in relevanter Menge
- 🟠 **Liberator** – regt die körpereigene Histaminfreisetzung aus Mastzellen an
- ⚠️ **DAO-hemmend** – blockiert das Enzym, das Histamin im Körper abbaut
- ✅ **Unbedenklich** – in der Regel gut verträglich

Zusätzlich wird jede Zutat nach dem SIGHI-Stufenmodell (S0–S3) eingeordnet, und das Produkt erhält eine Gesamtbewertung.

## Funktionsweise

1. Zutatenliste eines Produkts (z. B. vom Verpackungsfoto) eingeben oder einfügen
2. Der Scanner zerlegt den Text, löst Klammern und Verbundzutaten auf und normalisiert Schreibweisen (z. B. E-Nummern, Synonyme, Tippfehler-Toleranz)
3. Jede Zutat wird gegen eine lokale Datenbank abgeglichen
4. Optional: Zutaten, die nicht in der lokalen Datenbank stehen, können per KI (Mistral oder Claude, eigener API-Key erforderlich) eingeschätzt werden

## Verwendung

Einfach `histaminscanner.html` im Browser öffnen – keine Installation, kein Server nötig. Die App läuft vollständig lokal (Single-File HTML/JS), optional als GitHub Pages gehostet.

## Hinweis

Dieses Tool ersetzt keine ärztliche Diagnose oder Ernährungsberatung. Die Einstufungen basieren auf SIGHI-Listen und gängigen Quellen zur Histaminintoleranz, erheben aber keinen Anspruch auf Vollständigkeit oder individuelle Verträglichkeit. Im Zweifel immer Rücksprache mit Arzt oder Ernährungsberater halten.

## Stand

Aktuelle Version: siehe Einstellungen in der App.
