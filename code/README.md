# code/ipywidgetz.ipynb - Kuvantunnistus ipywidgetseillä 
Tämä osio kuvaa kuvantunnistussovelluksen, joka käyttää ipywidgets-pakettia interaktiivisen käyttöliittymän luomiseen.

## Tunnistussovelluksen Toiminta

Tämä sovellus havaitsee kuvissa kohteita käyttämällä YOLOv5-mallia ja ipywidgets-pakettia interaktiivisen käyttöliittymän luomiseen. Sovelluksessa voit valita kuvan indeksin syöttämällä sen tekstikenttään ja painamalla "detect"-painiketta.

Kun "detect"-painiketta painetaan, sovellus suorittaa seuraavat vaiheet:
1. Valitsee kuvan, jonka indeksi on syötetty tekstikenttään.
2. Käyttää YOLOv5-mallia tunnistamaan kohteet valitussa kuvassa.
3. Näyttää tunnistetut kohteet kuvassa.
4. Tallentaa tunnistetun kuvan `../images/exp/`-kansioon.

## Vaatimukset

- Python 3.10 tai uudempi
- ipywidgets-paketti

## Asennus

Asenna ipywidgets-paketti pipillä komennolla:

```bash
pip install ipywidgets
```