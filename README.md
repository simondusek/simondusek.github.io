# ⚡ simondusek.com — Automated B2B Newsletter Engine

> **Pravidelná dávka technologické esence a B2B analytiky bez balastu a šumu.**

Tento repozitář obsahuje kompletní zdrojový kód pro osobní web **[simondusek.com](https://simondusek.com)** a **automatizovaný Python/AI konvertor**, který transformuje surové RSS feedy a přpisy světových přednášek (Stanford, MIT, Y Combinator) do responzivních HTML newsletterů pro Ecomail.

---

## 🎯 Architektura & Dva formáty

Projekt zajišťuje sběr, zpracování, kurátorství a generování e-mailových kampaní rozdělených do dvou doplňujících se formátů:

1. **Digest | simondusek.com** *(2×–3× týdně)*  
   * Rychlý 3minutový přehled klíčových událostí z AI, financí a české scény.  
   * Filtrováno přes chytré RSS AI agenty, vysvětlený žargon v závorce a vyhodnocený dopad `Why It Matters`.
2. **Deep Dive | simondusek.com** *(1× za 1–2 týdny)*  
   * Prémiová analytická esence z přednášek a vědeckých studií.  
   * Finanční a controllingový pohled na AI (Unit Economics, CapEx, OpEx) s konkrétním srovnáním *PŘED vs. PO* pro firmy.

---

## 🛠️ Součásti projektu a struktura

Repozitář kombinuje statický web na GitHub Pages s lokálním CLI nástrojem v Pythonu: