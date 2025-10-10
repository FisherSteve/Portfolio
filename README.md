# Portfolio – Data Science & Actuarial Modeling (P&C Insurance)

Dieses Portfolio zeigt angewandte Modellierungsarbeit im Schnittfeld von **Wirtschaftsmathematik, Data Science und Aktuariat**, mit Fokus auf **Tarifierung, Risikomodellierung und generative Simulationen**.  
Alle Projekte sind eigenständig entwickelt, dokumentiert und reproduzierbar (Python/SQL, Jupyter, GitHub).

---

## 1. Kfz-Schadenfrequenz (freMTPL2) – GLM/GAM-Pricing
**Ziel:** Entwicklung eines interpretierbaren Basismodells zur Schadenfrequenzprognose (Poisson- und Tweedie-Verteilungen).  
**Ansatz:** Vergleich GLM vs. GAM mit Splines, Kreuzvalidierung und Exposure-Offset.  
**Ergebnis:** GAM reduzierte Poisson-Deviance um **6 %**, Gini-Koeffizient **+3 pp** ggü. GLM-Baseline.  
**Technologien:** Python (pandas, statsmodels, pyGAM), Power BI, Git.  
🔗 [GitHub-Link](https://github.com/FisherSteve/freMTPL2sev-pricing)

---

## 2. Generative Zeitreihenmodellierung (Schrödinger-Brücke)
**Ziel:** Untersuchung generativer Modelle für stochastische Prozesse und Finanzzeitreihen.  
**Ansatz:** Implementierung des Schrödinger-Bridge-Algorithmus mit Euler–Maruyama-Simulation.  
**Ergebnis:** Anwendung auf ARIMA, GARCH und Aktienrenditen zur Szenario-Generierung.  
**Nutzen:** Potenzial für **Stress- und What-if-Szenarien** in P&C-Frequenzmodellen.  
🔗 [GitHub-Link](https://github.com/FisherSteve/SchrodingerBridgeGenModel)

---

## 3. Instacart Reorder Prediction – Large-Scale Classification & ETL
**Ziel:** Nachbestellwahrscheinlichkeit als Proxy für Kundensegmentierung.  
**Ansatz:** Verarbeitung von > 3 Mio. Transaktionen, Feature Engineering, Training und Kalibrierung eines Klassifikationsmodells.  
**Ergebnis:** AUC = **0.84**, gute Kalibrierung. Übertragbar auf P&C-Kundendatenpools.  
**Technologien:** Python (pandas, scikit-learn), SQL.  
🔗 [GitHub-Link](https://github.com/FisherSteve/instacart-reorder-prediction)

---

## 4. Stochastische Analysis (Lehre & Dokumentation)
**Ziel:** Saubere Dokumentation und didaktische Aufbereitung stochastischer Grundlagen, SDEs und Simulationen.  
**Nutzen:** Unterstützung für Studierende und Einstieg in Aktuarsausbildung.  
🔗 [GitHub-Link](https://github.com/FisherSteve/Stochastische-Analysis)

---

## Fokusbereiche
GLM/GAM-Pricing (Poisson/Tweedie) | Exposure-Offset | Cross-Validation | Calibration | Time Series & SDEs | Model Interpretability (PDPs, Feature Importance) | Solvency II / IFRS 17 (Übersicht)

---

## Tech Stack
Python (pandas, statsmodels, pyGAM, scikit-learn) | SQL | Power BI | Git | Docker | LaTeX

---

**Aktuelles Ziel:** Einstieg als **Junior Pricing Actuary (P&C)** oder **Data Scientist im Versicherungsumfeld**, mit geplanter **DAV-Ausbildung**.  

**Kontakt:**  
[LinkedIn-Profil](https://www.linkedin.com//in/fischer-stephan/) | [GitHub-Hauptseite](https://github.com/FisherSteve) | 📧 [steph-fischer@gmx.de]
