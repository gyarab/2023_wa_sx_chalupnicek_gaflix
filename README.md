# 2023_wa_sx_chalupnicek_gaflix

## První spuštění projektu - instalace závislostí do venv

```
git clone git@github.com:gyarab/2023_wa_sx_chalupnicek_gaflix.git
cd 2023_wa_sx_chalupnicek_gaflix/
py -3 -m venv venv
source ./venv/Scripts/activate
pip install -r requirements.txt
```

## Spuštění projektu

```
./manage.py migrate
./manage.py runserver
```

## Vytvoření admin usera

```
./manage.py createsuperuser
```

## Po změně `models.py`

```
./manage.py makemigrations
./manage.py migrate
```
