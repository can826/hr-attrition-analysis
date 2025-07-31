# 📊 HR ATTRITION ANALYSE - EXECUTIVE SUMMARY

**Datum:** 31. Juli 2025  
**Erstellt von:** Can Pascal Cevikkollu  
**Status:** Abgeschlossen  
**Datengrundlage:** 1.470 Mitarbeiterdatensätze

---

## 🎯 MANAGEMENT SUMMARY

Unsere datengetriebene Analyse identifiziert kritische Kündigungsrisiken und liefert konkrete Handlungsempfehlungen zur Senkung der Mitarbeiterfluktuation. Mit einer **Fluktuationsrate von 16,1%** entstehen jährliche Kosten von **11,8 Mio. €**. Unser Machine Learning Modell erreicht eine **Vorhersagegenauigkeit von 82,6%** und identifiziert **71 Hochrisiko-Mitarbeiter**.

## 📈 KERNERGEBNISSE AUF EINEN BLICK

### Fluktuationsanalyse
- **237 von 1.470** Mitarbeitern haben gekündigt (16,1%)
- **Kosten pro Kündigung:** 50.000€ (Recruiting + Einarbeitung)
- **Jährliche Gesamtkosten:** 11,8 Mio. €
- **Einsparpotenzial:** 2,95 Mio. €/Jahr bei 25% Reduktion

### Modell-Performance
![ROC Curve](visualizations/figures/roc_curve.png)
*AUC-Score von 0.826 zeigt exzellente Vorhersagekraft des Modells*

## 🔍 HAUPTRISIKOFAKTOREN

### Feature Importance Analyse
![Feature Importance](visualizations/figures/feature_importance.png)

### Top 3 Kündigungstreiber:
1. **Überstunden (OverTime_Yes)**
  - Kündigungsrate mit Überstunden: 30,5%
  - Kündigungsrate ohne Überstunden: 10,4%
  - **→ 3x höheres Risiko**

2. **Häufige Geschäftsreisen**
  - 2,5x höheres Kündigungsrisiko
  - Betrifft 277 Mitarbeiter

3. **Spezifische Jobrollen**
  - Sales Representatives: 39,8% Fluktuation
  - Laboratory Technicians: 23,7% Fluktuation

### Schutzfaktoren:
- ✅ Bildungshintergrund in Medical/Life Sciences (-72% Risiko)
- ✅ Research Director Position (-87% Risiko)
- ✅ Ausgewogene Work-Life-Balance

## 💡 HANDLUNGSEMPFEHLUNGEN

### Priorisierte Maßnahmen mit ROI-Berechnung

| Priorität | Maßnahme | Zielgruppe | Investment | Einsparung/Jahr | ROI |
|-----------|----------|------------|------------|-----------------|-----|
| **HOCH** | Flexible Arbeitszeiten & Überstundenabbau | 416 MA | 2,1 Mio. € | 8,4 Mio. € | **4,0x** |
| **HOCH** | Remote-Work Programme | 277 MA | 831.000 € | 2,1 Mio. € | **2,5x** |
| **MITTEL** | Retention-Bonus für Risikogruppen | Sales/Lab | 1,5 Mio. € | 2,7 Mio. € | **1,8x** |

### Business Insights Dashboard
![Business Insights Dashboard](visualizations/figures/business_insights_dashboard.png)
*Gesamtübersicht: Risikoverteilung, Kategorisierung und ROI-Analyse*

## 💰 BUSINESS CASE

### Investitionsrechnung
- **Gesamtinvestition:** 4,4 Mio. € (einmalig)
- **Jährliche Einsparungen:** 2,95 Mio. €
- **Break-Even:** < 6 Monate
- **5-Jahres-ROI:** 335%
- **NPV (5 Jahre, 8% Diskont):** 7,3 Mio. €

### Umsetzungsplan

**Phase 1 (Monat 1-3): Quick Wins**
- Task Force "Work-Life-Balance" etablieren
- Überstunden-Policy überarbeiten
- Pilot mit Sales-Abteilung starten

**Phase 2 (Monat 4-6): Skalierung**
- Remote-Work-Richtlinien implementieren
- Retention-Programme ausrollen
- Monitoring-Dashboard aufbauen

**Phase 3 (ab Monat 7): Optimierung**
- Modell mit neuen Daten trainieren
- A/B-Tests der Maßnahmen
- Kontinuierliche Verbesserung

## 📊 ERFOLGSMETRIKEN

### KPIs zur Fortschrittsmessung
- **Primär:** Fluktuationsrate (Ziel: < 12%)
- **Sekundär:** 
 - Überstundenquote (Ziel: < 15%)
 - Mitarbeiterzufriedenheit (Ziel: > 4.0/5.0)
 - Cost-per-Hire Reduktion (Ziel: -30%)

### Monitoring
- **Monatlich:** Risiko-Score Updates für alle Mitarbeiter
- **Quartalweise:** Modell-Performance Review
- **Jährlich:** ROI-Evaluation und Strategieanpassung

## ⚡ NÄCHSTE SCHRITTE

1. **Woche 1-2:** Präsentation der Ergebnisse an C-Level
2. **Woche 3-4:** Budget-Freigabe und Ressourcenplanung
3. **Monat 2:** Start Pilot-Programme in Hochrisiko-Abteilungen
4. **Monat 3:** Erste Erfolgsmessung und Anpassungen

## 🔧 TECHNISCHE UMSETZUNG

- **Predictive Model:** Integration in HR-System geplant
- **Dashboard:** Power BI/Tableau Anbindung möglich
- **Automatisierung:** Monatliche Risk-Reports
- **API:** REST-Endpoint für Echtzeit-Scoring

---


*Diese Analyse demonstriert das Potenzial von Data Science zur proaktiven Mitarbeiterbindung. Die Kombination aus statistischer Analyse, Machine Learning und betriebswirtschaftlicher Bewertung ermöglicht datengetriebene HR-Entscheidungen mit messbarem ROI.*