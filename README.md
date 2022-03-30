[ARCHIVED]
# Nukkit-Dzialki

Plugin stworzony do Minecraft Education Edition, aby ułatwić prowadzenie eventu świątecznego dla dzieci.

## Wszystko czego potrzeba do stworzenia świata z działkami


1. Wszystkie jary trzeba przenieść do folderu z pluginami.
2. Odpalić server, zaczekać aż wszystkie pluginy się załadują.
3. W konsoli wpisać "mw create dzialki flat" aby stworzyć odrębny płaski świat od działek.
4. Następnie "setworldgamemode 1 dzialki", żeby ustawić tryb kreatywny na tym świecie.
5. W pliku nukkit.yml w polu worlds dopisać świat działki, aby był on domyślnie loadowany w taki sposób
* settings:
*  .
*  .
*  .
*     worlds:
*       dzialki:
*         gamemode: 1
6. Zamienić plik utworzony po pierwszym wczytaniu pluginu Residence znajdujący się w ./plugins/Residence/config.yml na config.yml z repozytorium.
7. Zresetować server po zmianach.


## Jak obsługiwać pluginy w grze

* Żeby przeteleportować się do świata działki
```
/mw tp dzialki
/mw tp <nazwa_swiata>
```

* Żeby wybrać obszar dookoła gracza, na którym chcemy stworzyć naszą działkę
```
/res select
```

* Następnie, żeby stworzyć we wskazanym miejscu działkę nazwaną naszym Nickiem wpisujemy:
```
/res create
```

* Żeby teleportować się prosto na naszą działkę wpisujemy:
```
/res tp <Nickname>
```

