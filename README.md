# Office Energy Consumption Predictor ⚡🧠

Un modello di regressione lineare costruito con **PyTorch** per prevedere il consumo energetico (kWh) di un ufficio basandosi su variabili ambientali e operative.

## 📋 Descrizione del Progetto
Il progetto utilizza una rete neurale semplice per stimare il costo energetico giornaliero. Il dataset (generato sinteticamente) tiene conto di:
* **Temperatura esterna**: Influenza l'uso del condizionatore/riscaldamento.
* **PC Accesi**: Carico di lavoro elettronico.
* **Tipo di Giorno**: Differenza tra giorni feriali e weekend.

Il modello impara la relazione matematica tra queste variabili e il costo finale in Euro.

## 🛠️ Tecnologie Utilizzate
* **Python 3.x**
* **PyTorch**: Per la creazione e l'addestramento della rete neurale.
* **Pandas & NumPy**: Per la manipolazione dei dati e la generazione del dataset.
* **Scikit-learn**: Per la suddivisione dei dati in Training e Test set.
* **Matplotlib**: Per la visualizzazione dei risultati.

## 📈 Risultati
Dopo 3000 epoche di addestramento, il modello ha raggiunto una **Loss (MSE)** estremamente bassa, dimostrando un'alta precisione nelle predizioni.

**Esempio di output:**
- Predizione: 61 €
- Consumo Reale: 61 €