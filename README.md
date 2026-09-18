# Cyklo vrstvy

Jednoduchá dvojjazyčná webová aplikácia, ktorá podľa teploty a podmienok odporučí cyklistické oblečenie a zobrazí presný vizuál vybranej zostavy.

## Spustenie

Web je statický a nemá žiadne závislosti. Na GitHube je produkčná verzia uložená priamo v koreňovom priečinku, takže ju možno nasadiť cez GitHub Pages. Lokálne ju spustíš napríklad:

```bash
python3 -m http.server 8080
```

Potom otvor `http://localhost:8080`.

Aktuálne počasie a vyhľadávanie miest používa verejné Open-Meteo API. Manuálny výber teploty funguje aj bez neho.
