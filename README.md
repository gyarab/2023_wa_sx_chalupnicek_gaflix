# 2023_wa_sx_chalupnicek_gaflix

## První spuštění projektu - instalace závislostí do venv

```
git clone git@github.com:gyarab/2023_wa_sx_chalupnicek_gaflix.git
cd 2023_wa_sx_chalupnicek_gaflix/
py -3 -m venv venv
source ./venv/Scripts/activate
pip install -r requirements.txt
./manage.py migrate
./manage.py createsuperuser
./manage.py runserver
```

## Spuštění projektu

```
git pull
source ./venv/Scripts/activate
./manage.py migrate
./manage.py runserver
```

## Po změně `models.py`

```
./manage.py makemigrations
./manage.py migrate
```
