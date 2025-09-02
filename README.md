# Convolutional Neural Networks (CNNs)

Dieses Repository enthält ein Jupyter Notebook zur Demonstration und Umsetzung von **Convolutional Neural Networks (CNNs)**.  
Es dient als Lern- und Experimentierumgebung für Deep-Learning-Techniken im Bereich der Bildverarbeitung.

## Motivation

Klassische **Neuronale Netze (NNs)** haben den Nachteil, dass sie **nicht translationsinvariant** sind:  
Ein trainiertes Netz erkennt ein Muster (z. B. eine Ziffer) nur an der Position, an der es im Training gesehen wurde.  
Wenn dasselbe Muster verschoben wird, muss das Netz es neu lernen.  

**Convolutional Neural Networks (CNNs)** lösen dieses Problem:  
- Durch **Faltungsoperationen (Convolutions)** werden lokale Merkmale (Kanten, Formen, Texturen) extrahiert.  
- Diese Merkmale sind **unabhängig von der Position im Bild** – das sorgt für **Translationsinvarianz**.  
- Zusätzlich reduzieren CNNs die Anzahl der benötigten Parameter (im Vergleich zu voll verbundenen Schichten), was Training effizienter macht.  

Dadurch eignen sich CNNs besonders gut für:
- Bilderkennung (z. B. MNIST, CIFAR-10, ImageNet)  
- Objekterkennung  
- Computer Vision im Allgemeinen  

## Inhalt
- Einführung in CNNs und Vergleich mit klassischen NNs
- Aufbau und Training eines CNNs
- Evaluation und Visualisierung der Ergebnisse
- Beispiele mit gängigen Datensätzen (z. B. MNIST, CIFAR-10)

## Voraussetzungen
Um das Notebook auszuführen, werden folgende Tools benötigt:

- [Python 3.x](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- Typische Python-Bibliotheken für Machine Learning, z. B.:
  - `numpy`
  - `matplotlib`
  - `tensorflow` oder `pytorch` (abhängig von der Implementierung)
  - `scikit-learn`

Installation der Abhängigkeiten (Beispiel):
```bash
pip install -r requirements.txt
