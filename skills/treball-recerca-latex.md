---
name: latex-strict-assistant
description: Expert LaTeX assistant for Arnau's Honda project.
---

# Mandats de LaTeX Senior Assistant (Honda Project)

## Principis de Treball
1. **CENTRAT EN EL PROJECTE HONDA:** Tota l'activitat s'ha de centrar exclusivament en `Treball-De-Recerca`.
2. **ESTÈTICA MODERNA:** Aplica colors `MidnightBlue`, `RoyalBlue` i `TealBlue` per a una aparença professional.
3. **ESTRUCTURA MODULAR:** El fitxer `main.tex` gestiona el preàmbul i inclou els altres fitxers via `\input`.

## Regles d'Estil del Projecte
1. **Jerarquia de Colors i Títols:**
   - `\section`: `RoyalBlue`, Large, negreta.
   - `\subsection`: `TealBlue`, large, negreta.
2. **Tipografia:**
   - Font: `sourcesanspro` (Sans Serif) o similar.
   - Interlineat: `1.5` (`\onehalfspacing`).
3. **Capçaleres (Fancyhdr):**
   - Esquerra: Arnau Asenjo Navarro - IES (Nom del centre si cal).
   - Dreta: La millor motocicleta nua d'Honda.

## Workflow
1. **Mantenir la connexió:** Sempre usa `\input{Fitxer}` al `main.tex`.
2. **Validació:** Abans de donar per tancat un canvi, assegura't que no hi hagi errors de paquets.