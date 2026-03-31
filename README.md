# Happiness Analysis: Fixed Effects Panelanalyse 🌍

**World Happiness Report 2011-2024: Between vs Within Effekte**

## 📊 Hauptbefunde

**BETWEEN-Effekte (zwischen Ländern):**
| Variable | Effekt | p-Wert | R² |
|----------|--------|--------|-----|
| **BIP pro Kopf** | +0.27 pro 10k USD | **p<0.001*** | **0.63** |
| **Demokratie** | +0.011 | **p<0.001*** | |

**WITHIN-Effekte (innerhalb Länder):**  
- BIP: Positiver Trend, aber n.s. (**p=0.090**)  
- Demokratie: n.s. (p=0.323)  
- **R²=0.91** (hauptsächlich Länder-FE)

**Frauenrechte-Index:** Kein signifikanter Effekt (between+within)

## 🔬 Methodik
✅ Fixed Effects (Länder-FE)
✅ Cluster-robust SE
✅ Between/Within-Dekomposition
✅ OWID World Happiness Daten


## 💡 Interpretation
> **Global:** Wirtschaft + Demokratie erklären Glücksunterschiede.  
> **Innerhalb Länder:** Geringe Within-Varianz der Prädiktoren.

**Live Notebook:** [Analyse öffnen] (./Analyse.ipynb)
