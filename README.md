# Kombinált ciklusú erőmű teljesítménybecslése

Ez a projekt különböző gépi tanulási módszerekkel becsli meg egy gázturbinás erőmű teljes elektromos teljesítményét.
A bemeneti adatok több környezeti és üzemi paramétert tartalmaznak (AT, V, AP, RH), a cél pedig a PE (Power Output) predikciója.

## Tartalom

- Adattisztítás és vizualizáció
- Outlier detektálás (IQR)
- Ferdeségvizsgálat és transzformáció (Yeo–Johnson)
- Több modell összehasonlítása GridSearchCV-vel
- PCA és Feature Subset kiválasztás
- Validáció a belső és külső (real) tesztadathalmazon
- Eredmények értékelése és összevetése szakirodalmi modellel

## Fájlok

- `Train.xlsx` – tanító adat
- `Test.xlsx` – különálló validációs adat
- `Article.pdf` – hivatkozott tanulmány
- `eda_and_regression.ipynb` – a teljes megoldás lépésről lépésre

## Használat

A notebook (`eda_and_regression.ipynb`) futtatható Jupyterben vagy VSCode-ban.
Minden szükséges kód, modell és magyarázat megtalálható a fájlban.
