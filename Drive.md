# Maqueen gaat rijden!

## Introductie @showdialog

In deze tutorial ga jij Maqueen laten rondrijden. 
Je gaat er zelfs voor zorgen dat die nergens tegenaan gaat botsen!

## Stap 1
In de werkruimte zie je weer de twee containerblokken 
``||basic:on start||`` en ``||basic:forever||`` staan. 
Klik nu in de **blokkenlade** op de categorie ``||maqueen:Maqueen||``. 
*In deze categorie staan de blokken die speciaal voor de Maqueen robot zijn.*
Sleep hieruit het blok ``||maqueen: motor ... move at speed ...||`` en 
plaats die in het ``||basic:on start||`` blok.

```blocks
maqueen.motorRun(maqueen.Motors.All, maqueen.Dir.CW, 100)
```