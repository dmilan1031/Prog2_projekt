# Prog2_projekt

A projektem célja egy légnemű közeg szimulálása, bizonyos testekkel való kölcsönhatásának vizsgálata, ezen hatások (pl.: légörvények, légnyomás különbségek) vizualizációja. Ezt egy klasszikus mechanikán alapuló részecskeszimulációval fogom megvalósítani.

## Első lépések

Elsősorban egy 'proof of concept' programot készítek. Ez a szimuláció működőképes állapotba való hozatalát jelenti, továbbá a szimuláció optimalizálását, mivel a későbbiekben a vizualizáció alapjául szolgáló adatok előállításához sok iteráción keresztül sok részecskét kell szimulálni. Miután a fizikai modell kellő hatékonysággal működik, megkezdem a további funkciók hozzáadását.

## A jövőben

Egyelőre ezeket a fő funkciókat tervezem hozzáadni a programhoz

- OpenGL megjelenítő: A szimulációból kinyert adatok, fizikai mennyiségek 3D-s (az előbb említett teszt jellegű program csak 2D-ben működik) megjelenítése akár mozgóképként, GUI elskészítése.
- 3D-s objektumok imprtálása: Elterjedt fájltípusok (.obj, .stl) olvasása, ezen modellek alapvető manipulációja.
