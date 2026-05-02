# 🩺 Aprenentatge automàtic per al diagnòstic precoç de la Diabetis Mellitus tipus II

Aquest projecte presenta una solució integral d'anàlisi predictiva per al diagnòstic precoç de la diabetis. Mitjançant tècniques avançades de **Machine Learning** i **Intel·ligència Artificial Explicable (XAI)**, el sistema no només prediu el risc d'un pacient, sinó que explica els motius clínics darrere de cada predicció per facilitar la presa de decisions mèdiques.

## 🚀 Característiques del Projecte

- **Processament de Dades Clíniques:** Neteja i unificació de datasets, tractament de valors nuls i enginyeria de variables (símptomes i dades biomètriques).
- **Estratègia Anti-Biaix:** Selecció rigorosa de la *primera prova* registrada per cada pacient per evitar el "biaix de tractament" i capturar l'estat metabòlic original.
- **Models Predictius:** Comparativa de rendiment entre Regressió Logística, XGBoost i Xarxes Neuronals Artificials (MLP).
- **Explicabilitat (SHAP):** Implementació de valors SHAP per desxifrar la "caixa negra" dels models i entendre l'impacte de variables com la Hb-Glicosilada o l'HDL-Colesterol.
- **Dashboard de Suport Clínic:** Quadre de comandament interactiu a Power BI per a la gestió poblacional i el diagnòstic individualitzat.

## 🛠️ Stack Tecnològic

- **Llenguatge:** Python 3.x
- **Llibreries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn i SHAP.
- **Visualització:** Power BI Desktop (Data Modeling, DAX, Power Query).
- **Entorn:** Jupyter Notebook / Google Colab.

## 📊 Resultats Destacats

- **Model Guanyador:** XGBoost.
- **Mètrica Clau:** Sensibilitat (Recall) > 90%, garantint una detecció mínima de falsos negatius en entorns de salut.
- **Factors de Risc Identificats:** L'anàlisi SHAP confirma la Hb-Glicosilada, l'obesitat o l'edat com els principals predictors de la malaltia.

## 📂 Estructura del Repositori

- `/data`: Fitxers CSV de dades original.
- `/notebooks`: Jupyter Notebooks amb tot el procés d'EDA, preprocessament i entrenament.
- `/dashboard`: Arxiu `.pbix` de Power BI i captures de pantalla de la interfície.

## 📈 Dashboard de Power BI

El dashboard inclou dues vistes principals:
1. **Gestió Poblacional:** Visió macro dels pacients en risc per rang d'edat i perfil de salut.
2. **Perfil Individual:** "Semàfor" de risc i explicació en cascada de les variables que afecten el pacient seleccionat.

## 📝 Conclusions

Aquest projecte demostra com la integració de models predictius i eines de BI pot transformar la gestió sanitària, passant d'un model reactiu a un proactiu de diagnòstic precoç.

---
**Autor:** Ari Pidevall 
**Projecte realitzat per al Treball Final de Màster de Ciència de dades de la UOC**
