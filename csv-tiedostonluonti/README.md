# kartta_plot.ipynb - Kartoitetut Kuvat ja Tunnistukset
kartta_plot.ipynb tiedostolla voi luoda kartan, joka näyttää kuvat tunnistuksilla käyttäen Folium-kirjastoa Pythonissa.

## Vaatimukset
- Python 3.10 tai uudempi
- Seuraavat Python-kirjastot:
    - pandas
    - folium
    - ast
    - pillow
Voit asentaa tarvittavat kirjastot seuraavilla komennoilla:
```bash
pip install pandas folium pillow
```

## CSV-tiedoston Rakenne
CSV-tiedoston updated_predictions.csv tulisi sisältää seuraavat sarakkeet:

- Latitude: Kuvan sijainnin leveysaste DMS-muodossa (Degrees, Minutes, Seconds)
- Longitude: Kuvan sijainnin pituusaste DMS-muodossa (Degrees, Minutes, Seconds)
- Image Name: Kuvan nimi
- Prediction: Tunnistuksen tulos

## csc-tiedostonluonti.ipynb - Kuvantunnistus ja Metadatan Päivitys CSV-tiedostoon
csc-tiedostonluonti.ipynb Python-skriptillä voi käsitellä kuvien metatietoja ja päivittää niitä CSV-tiedostoon. Skripti lukee kuvien GPS-koordinaatit ja lisää ne vastaaviin riveihin CSV-tiedostossa.

## Vaatimukset
- Python 3.10 tai uudempi
- Seuraavat Python-kirjastot:
    - pandas
    - pillow
    
Voit asentaa tarvittavat kirjastot seuraavalla komennolla:
```bash
pip install pandas pillow
```

# Tuloksia.ipynb - Kuvantunnistus ja Analysointi
Tuloksia.ipynb tiedostossa analysoidaan ja visualisoidaan YOLOv5-mallin tuottamia ennusteita sekä kuvia ja niiden metatietoja Pythonin ja erilaisten kirjastojen avulla.

## Asennus
Varmista, että seuraavat Python-kirjastot on asennettu:

- pandas
- pillow
- matplotlib
- seaborn
- ipywidgets

Voit asentaa ne pip-komennolla:

```bash
pip install pandas pillow matplotlib seaborn ipywidgets
```

