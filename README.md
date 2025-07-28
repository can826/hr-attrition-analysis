# 📊 HR Attrition Analyse

Eine datengetriebene Analyse zur Vorhersage und Reduzierung von Mitarbeiterfluktuation mit Python und Machine Learning.

## 🎯 Projektziel

Entwicklung eines Vorhersagemodells zur Identifikation von Kündigungsrisiken bei Mitarbeitern, um HR-Abteilungen bei der proaktiven Mitarbeiterbindung zu unterstützen.

## 📈 Wichtigste Ergebnisse

- **Fluktuationsrate:** 16,1% (237 von 1.470 Mitarbeitern)
- **Modell-Performance:** 82,6% AUC-Score
- **Hauptrisikofaktor:** Überstunden (3x höheres Kündigungsrisiko)
- **ROI der Maßnahmen:** 4,0x bei Überstunden-Intervention

## 🔍 Kernerkenntnisse

### Top-Risikofaktoren:
1. **Überstunden** - Mitarbeiter mit Überstunden haben eine 30,5% Kündigungsrate (vs. 10,4%)
2. **Häufige Geschäftsreisen** - 2,5x höheres Risiko
3. **Bestimmte Jobrollen** - Sales Representatives und Lab Technicians besonders betroffen

### Schutzfaktoren:
- Höhere Bildungsabschlüsse (Medical, Life Sciences)
- Research Director Positionen
- Ausgewogene Work-Life-Balance

## 💼 Business Impact

- **Jährliche Fluktuationskosten:** 11,8 Mio. $
- **Potenzielle Einsparungen:** 2,95 Mio. $/Jahr (bei 25% Reduktion)
- **Break-Even:** < 6 Monate nach Implementierung

## 🛠️ Verwendete Technologien

- **Python 3.8+**
- **Datenanalyse:** Pandas, NumPy
- **Visualisierung:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Statistik:** SciPy, Statsmodels

## 📁 Projektstruktur
hr_attrition_project/
├── data/
│   └── HR_data.csv              # Rohdatensatz
├── notebooks/
│   └── HR_Attrition_Analysis.ipynb  # Hauptanalyse
├── reports/
│   └── executive_summary.md     # Management Summary
├── visualizations/              # Generierte Grafiken
├── .gitignore
├── README.md
└── requirements.txt

## 🚀 Installation & Ausführung

### Voraussetzungen
- Python 3.8 oder höher
- Jupyter Notebook

### Setup

```bash
# Repository klonen
git clone https://github.com/can826/hr-attrition-analysis.git
cd hr-attrition-analysis

# Virtuelle Umgebung erstellen (optional)
python -m venv venv
source venv/bin/activate  # Auf Windows: venv\Scripts\activate

# Abhängigkeiten installieren
pip install -r requirements.txt

# Jupyter Notebook starten
jupyter notebook
