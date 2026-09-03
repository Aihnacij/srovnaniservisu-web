# SrovnaniServisu — web

Statická stránka srovnání cen českých autoservisů a pneuservisů.
Běží na GitHub Pages, data má vložená přímo v `index.html`.

Generuje se z privátního repozitáře příkazem:

```bash
.venv/bin/python web/build.py
scripts/deploy.sh
```

Ceny pocházejí z veřejných ceníků jednotlivých servisů; u každé je odkaz
na zdroj. Adresář provozoven vychází mimo jiné z dat
© přispěvatelé OpenStreetMap (ODbL).
