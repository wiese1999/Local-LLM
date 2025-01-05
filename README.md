# Lokale Risikoanalyse für Sprachmodelle (LLMs)

Dieses Projekt führt eine praktische Risikoanalyse von großen Sprachmodellen (LLMs) durch, basierend auf dem Modell **Flan-T5-base**. Ziel ist es, potenzielle Schwachstellen wie Datenlecks, Bias oder Halluzinationen in einer lokalen Umgebung zu testen.

## Projektziel

- Validierung theoretisch identifizierter Risiken durch praktische Tests.
- Analyse von Modellausgaben in Bezug auf Sicherheit, Bias und Robustheit.
- Erstellung einer Grundlage für die Entwicklung von Gegenmaßnahmen.

## Nutzung

1. Abhängigkeiten installieren:
   ```bash
   pip install -r requirements.txt
   ```
2. Testskript ausführen:
   ```bash
   python LocalLLMSetup.py
   ```
3. Ergebnisse werden in der Konsole und in der Datei `test_results.csv` ausgegeben.

## Getestete Risiken

- Datenlecks
- Bias
- Adversariale Angriffe
- Prompt-Injektionen
- Halluzinationen
