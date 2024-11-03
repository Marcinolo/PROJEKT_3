# Aplikacja FastAPI do Predykcji Rezygnacji Klienta

## Opis projektu

Aplikacja FastAPI, która przewiduje prawdopodobieństwo rezygnacji klienta na podstawie danych o subskrypcji i historii użytkowania. Wyniki wyświetlane są na podstawie modelu uczenia maszynowego, wczytanego z pliku `model_random_forest.pkl`.

## Wymagania

- Python 3.7 lub nowszy
- FastAPI
- Uvicorn
- scikit-learn
- joblib
- numpy
- pandas
- jinja2 (do szablonów HTML)

## Instalacja

1. Sklonuj repozytorium:

   ```bash
   git clone https://github.com/Marcinolo/PROJEKT_3.git
   cd PROJEKT_3
   ```

2. Zainstaluj wymagane pakiety:

   ```bash
   pip install -r requirements.txt
   ```

3. Umieść model `model_random_forest.pkl` w katalogu projektu. Plik ten powinien zawierać wytrenowany model Random Forest oraz skaler, zapisany w formacie:

   ```python
   {'model': trained_model, 'scaler': scaler}
   ```

4. Upewnij się, że plik `.env` zawiera wymagane zmienne środowiskowe
