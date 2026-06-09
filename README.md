# Crude Oil Price Analysis (1983–2026)

## Project Overview

This project analyzes more than four decades of monthly crude oil prices, covering the period from March 1983 to June 2026.

The objective is to understand long-term market behavior, identify major price cycles, investigate periods of market volatility, and examine the impact of significant economic and geopolitical events on crude oil prices.

The analysis combines exploratory data analysis (EDA), time-series analysis, market cycle detection, and event-driven market investigations to provide a comprehensive view of the global oil market.

---

## Dataset

The dataset contains:

- 520 monthly observations
- Period: March 1983 – June 2026
- Variables:
  - Date
  - Oil Price (USD/Bbl)
  - Monthly Price Change
  - Monthly Percentage Change

---

## Project Objectives

The main goals of this project are:

- Understand long-term oil price behavior
- Identify major market cycles
- Measure market volatility
- Detect historical turning points
- Investigate the impact of economic crises and geopolitical events
- Extract business-oriented insights from historical data

---

## Methodology

### 1. Data Preparation

- Data cleaning
- Date conversion
- Feature engineering
- Creation of year, month, quarter, and decade variables

### 2. Exploratory Data Analysis (EDA)

- Distribution analysis
- Outlier detection
- Skewness and kurtosis analysis
- Correlation analysis

### 3. Time Series Analysis

- Long-term trend analysis
- Moving averages (12 and 24 months)
- Rolling volatility
- Bull and bear market detection
- Decade comparison

### 4. Historical Event Analysis

The following events were investigated:

- 1986 Oil Price Collapse
- Gulf War (1990)
- Asian Financial Crisis (1997)
- Global Financial Crisis (2008)
- COVID-19 Pandemic (2020)
- Russia–Ukraine Energy Crisis (2022)

### 5. Executive Insights

- Market cycle analysis
- Price regime classification
- Long-term market interpretation
- Business-focused conclusions

---

## Key Findings

### Long-Term Market Cycles

Crude oil prices do not follow a continuous upward trend. Instead, the market moves through recurring cycles of expansion, correction, recovery, and stabilization.

### Most Volatile Decade

The 2000s experienced the highest volatility, driven by rapid demand growth, the oil price bubble, and the Global Financial Crisis.

### Highest Recorded Price

- June 2008
- 140 USD/Bbl

### Largest Monthly Decline

- March 2020
- -54.25%

### Market Recovery

Despite severe downturns, the oil market has historically demonstrated a strong ability to recover after major disruptions.

### Price Regimes

| Regime | Months |
|---------|---------|
| Low Price (<30 USD/Bbl) | 222 |
| Medium Price (30–80 USD/Bbl) | 212 |
| High Price (>80 USD/Bbl) | 86 |

Most of the study period occurred within low and medium price environments.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Project Structure

```text
oil-price-analysis/
│
├── data/
│   └── crude-oil-price.csv
│
├── notebooks/
│   └── oil_price_analysis.ipynb
│
├── images/
│
├── presentation/
│
├── README.md
│
└── requirements.txt
```

---

## Conclusion

The analysis demonstrates that crude oil prices are primarily influenced by long-term economic cycles, geopolitical developments, and structural changes in global energy markets.

While short-term price movements can be highly unpredictable, long-term patterns provide valuable insight into how the oil market responds to periods of growth, uncertainty, and disruption.

---

# Rohölpreisanalyse (1983–2026)

## Projektübersicht

Dieses Projekt analysiert mehr als vier Jahrzehnte monatlicher Rohölpreise im Zeitraum von März 1983 bis Juni 2026.

Ziel der Analyse ist es, langfristige Marktbewegungen zu verstehen, wichtige Preiszyklen zu identifizieren, Phasen hoher Volatilität zu untersuchen und den Einfluss bedeutender wirtschaftlicher sowie geopolitischer Ereignisse auf den Ölmarkt zu analysieren.

Die Untersuchung kombiniert explorative Datenanalyse (EDA), Zeitreihenanalyse, Marktzyklenerkennung und ereignisbasierte Marktanalysen.

---

## Datensatz

Der Datensatz umfasst:

- 520 monatliche Beobachtungen
- Zeitraum: März 1983 bis Juni 2026
- Variablen:
  - Datum
  - Ölpreis (USD/Bbl)
  - Monatliche Preisänderung
  - Monatliche prozentuale Preisänderung

---

## Projektziele

- Langfristiges Verhalten des Ölmarktes verstehen
- Marktzyklen identifizieren
- Marktvolatilität messen
- Historische Wendepunkte erkennen
- Auswirkungen wirtschaftlicher Krisen und geopolitischer Ereignisse untersuchen
- Geschäftsrelevante Erkenntnisse aus historischen Daten ableiten

---

## Wichtigste Erkenntnisse

### Langfristige Marktzyklen

Der Ölmarkt folgt keinem konstanten Aufwärtstrend. Stattdessen bewegt er sich in wiederkehrenden Phasen von Wachstum, Korrektur, Erholung und Stabilisierung.

### Volatilstes Jahrzehnt

Die 2000er Jahre zeigten die höchste Volatilität, insbesondere aufgrund der starken Nachfrageentwicklung, der Ölpreisblase und der globalen Finanzkrise.

### Höchster Ölpreis

- Juni 2008
- 140 USD/Bbl

### Größter monatlicher Preisrückgang

- März 2020
- -54,25 %

### Markterholung

Trotz erheblicher Einbrüche zeigte der Ölmarkt historisch eine bemerkenswerte Fähigkeit zur Erholung nach Krisen.

### Preisregime

| Preisniveau | Monate |
|-------------|---------|
| Niedrig (<30 USD/Bbl) | 222 |
| Mittel (30–80 USD/Bbl) | 212 |
| Hoch (>80 USD/Bbl) | 86 |

Der größte Teil des Untersuchungszeitraums lag im niedrigen oder mittleren Preisbereich.

---

## Fazit

Die Analyse zeigt, dass Rohölpreise hauptsächlich durch langfristige Wirtschaftszyklen, geopolitische Entwicklungen und strukturelle Veränderungen der globalen Energiemärkte beeinflusst werden.

Obwohl kurzfristige Preisbewegungen oft schwer vorhersehbar sind, liefern langfristige Muster wertvolle Erkenntnisse über das Verhalten des Ölmarktes in Zeiten von Wachstum, Unsicherheit und Krisen.
