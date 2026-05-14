# Progetto 3 - Classificazione del dataset Wine con PCA

## Obiettivo del progetto

L’obiettivo di questo progetto è confrontare due algoritmi di classificazione supervisionata:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

utilizzando il dataset Wine disponibile nella libreria Scikit-learn.

Prima dell’addestramento dei modelli è stata applicata la PCA (Principal Component Analysis) per ridurre la dimensionalità del dataset a 2 componenti principali, così da poter visualizzare meglio i dati e i decision boundary dei modelli.

---

## Dataset utilizzato

Il dataset Wine contiene diverse caratteristiche chimiche relative a differenti tipologie di vino.

Il dataset è stato caricato tramite:

```python
from sklearn.datasets import load_wine