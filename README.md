# Bestandsabfage der Judaica von Compact Memory in der Deutschen Nationalbibltiohek

(C) 2024 Benjamin Schnabel

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)


## Einleitung
Dieses Projekt dient dazu, die Judaica von Compact Memory in der Deutschen Nationalbibliothek zu erfassen. Die Daten werden in einer CSV-Datei gespeichert.

Alle Daten wurden mit Hilfe verschiedener Jupyter Notebooks generiert.

## Vorraussetzungen
Die benötigten Bibliotheken finden sich in der Datei: `requirements.txt`.
Das Projekt wurde mit python3.11 gebaut und getestet.
Um die generierten RDF-Daten in einen Graphen zu laden wird [Apache Jena Fuseki](https://jena.apache.org/documentation/fuseki2/) benötigt.
Die benötigten Metadaten finden sich [hier](https://web.judaicalink.org/fulltexts/metadata/).

## Dateien
### Jupyter Notebooks
* [Metadata.ipynb]() - Extrahiert die Metadaten und bereite sie auf.
* [Bestandsabfage.ipynb](https://github.com/bsesic/DNB/blob/master/Bestandsabfrage.ipynb) - Führt die Bestandsabfage durch.
* [Ontology.ipynb](https://github.com/bsesic/DNB/blob/master/Ontology.ipynb) - Erstellt die Ontologie.
* [Judaica.ipynb](https://github.com/bsesic/DNB/blob/master/Judaica.ipynb) - Führt eine Bestandsabfrage auf alle Judaica durch.
* [Projekte.ipynb](https://github.com/bsesic/DNB/blob/master/Projekte.ipynb) - Führt eine Abfrage auf alle Projekte durch.
* [Request DNB.ipynb](https://github.com/bsesic/DNB/blob/master/Request%20DNB.ipynb) - Führt eine Abfrage auf die Deutsche Nationalbibliothek von Compact Memory durch.


### Generierte Dateien
* ontology.ttl - Turtle 
* final_data.csv - CSV-Datei
* final_data.xlsx - Excel Tabelle

## Ergebnisse


## Workflow


## Weitere Informationen
Die genaue Beschreibung des Projekts, sowie die Dokumentation der einzelnen Schritte des Workflows finden sich in einem Abschlussbericht.


