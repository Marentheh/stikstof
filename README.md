# Stikstof Vingerafdruk Analyse

## Intro 
'Stikstof Vingerafdruk' is een project in het kader van het voormalige PAS (Programma Aanpak Stikstof). De scripts hebben als doel om een beter beeld te krijgen van de emissiebronnen die voor deposities zorgen in stikstofgevoelige N-2000 gebieden. 

## Contact
Via GitHub of via de mail: t.schouten@pzh.nl.

## Instructies
Het script is geschreven in Python v3.7 m.b.v. Jupyter notebook. De code en documentatie zijn zo op dezelfde locatie te vinden.

## Bestanden & Folders
bronnen-lokaliseren.ipynb -- Jupyter Notebook workflow
utils.py -- Helpfuncties om te communiceren met de AERIUS Connect API.
nox-env.yml -- Conda package file*

* via (mini)conda kan je een kopie maken van de environment met het volgende commando:

```
conda env create -f nox-env.yml -n nox-environment 
```

