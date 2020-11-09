# Apuntes_UF1_1

# TIPUS DE PROGRAMACIO

A continuació els tipus de programari d'acord a l'objectiu que té dins de el sistema informàtic:
```sh
   - De sistema (Sistema operatiu, drive
   - De aplicació (Suite ofimàtica, Navegador, Edició d'imatge, ...)
   - De desenvolupament (Editors, compiladors, intèrprets, ...)
   ```

# RELACIÓ HARDWARE-SOFTWARE

 [![N|Solid](https://1.bp.blogspot.com/-YrSDozngTPs/VZWbLsXekBI/AAAAAAAACmI/bw7ZIarNO3A/w1200-h630-p-k-no-nu/Hardware%2By%2BSoftware.jpg)

# CODIS FONT, OBJECTE I EXECUTABLE

| CODI | DESCRIPCIO |
| ------ | ------ |
| FONT | texto legible escrito en un lenguaje de programación.|
| OBJECTE | binario no ejecutable |
| EJECUTABLE | binario ejecutable. |

# DESENVOLUPAMENT DE SOFTWARE
   FASES PRINCIPALS

```sh
   - ANÀLISIS
   - DISSENY
   - CODIFICACIÓ
   - PROVES
   - MANTENIMENT
```

### ANALISIS

Extreure els requisits d'un producte de programari és la primera etapa per crear-lo. Mentre que els clients pensen que ells saben el que el programari ha de fer, es requereix d'habilitat i experiència en l'enginyeria de programari per reconèixer requisits incomplets, ambigus o contradictoris.


### DISSENY

Es refereix a determinar com funcionarà de forma general sense entrar en detalls. Consisteix a incorporar consideracions de la implementació tecnològica, com el maquinari, la xarxa, etc. Es defineixen els casos d'ús per a cobrir les funcions que realitzarà el sistema, i es transformen les entitats definides en l'anàlisi de requisits en classes de disseny, obtenint un model proper a la programació orientada a objectes.

Les activitats habituals són les següents:
- disseny arquitectònic
- disseny detallat
- Disseny de dades
- Disseny d'interfície

### CODIFICACIÓ
Reduir un disseny a codi pot ser la part més òbvia de la feina d'enginyeria de programari, però no és necessàriament la porció més llarga. La complexitat i la durada d'aquesta etapa està íntimament lligada a l'o als llenguatges de programació utilitzats.

### PROVES
Consisteix en comprovar que el programari realitzi correctament les tasques indicades en l'especificació. Una tècnica de prova és provar per separat cada mòdul del programari, i després provar de forma integral, per així arribar a l'objectiu.

### MANTENIMENT
Mantenir i millorar el programari per enfrontar errors descoberts i nous requisits. Això pot portar més temps fins i tot que el desenvolupament inicial de l'programari.

Tipus de manteniment:
- Correctiu: es corregeixen defectes.
- Perfectiu: es millora la funcionalitat.
- Evolutiu: s'afegeix funcionalitats noves.
- Adaptatiu: s'adapta a nous entorns.

## MODELOS DE DESARROLLO DE SOFTWARE

```sh
   - Models clàssics (predictius)
   - Model de construcció de prototips
   - Models evolutius o incrementals
```
### Models clàssics (predictius)
#### MODEL CASCADA
[![N|Solid](data:image/png;base64,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)
#### MODEL V
[![N|Solid](https://www.google.com/url?sa=i&url=https%3A%2F%2Fca.wikipedia.org%2Fwiki%2FModel_V&psig=AOvVaw0Wyy0mzscga7SbxR0bdb0j&ust=1605029782402000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCLjWtYKA9uwCFQAAAAAdAAAAABAD)





License
----

MIT


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
