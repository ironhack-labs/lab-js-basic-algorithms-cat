![logo_ironhack_blau 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | Algoritmes bàsics JS

Benvingut al teu primer exercici de bootcamp a Ironhack!

L'objectiu d'aquest exercici és familiaritzar-vos amb les estructures de dades primitives en JavaScript, que acabem de tractar a la classe. No dubteu a fer referència als materials de la lliçó i no us limiteu, però tingueu curiositat i utilitzeu Google per explorar diverses solucions.

Preparat?

<br>

![qrjeCm](https://user-images.githubusercontent.com/76580/167263489-bd345c02-6c3b-425e-9a9c-96390dea9ba6.gif)

<br>

## Introducció

Per a aquesta activitat __de programació en parella__ farem que les dues persones de la parella treballin en els seus propis repositoris. Al final de l'exercici, els dos estudiants haurien de tenir el mateix codi en els seus respectius repositoris.

Preparat per començar?

## Requisits

- Bifurca aquest repo
- Clona aquest repo
- Escriu-ho a la _pestanya Fitxer_ (tauler esquerre)

  ```javascript
   console.log("I'm ready!");
  ```

- Desa
- Obriu un terminal i navegueu fins al directori on hi ha el fitxer d'script i, a continuació, emeteu el següent `node js/index.js`
- Si podeu veure el missatge al panell del terminal (a sota), esteu realment preparats!

- __Després de la primera iteració, o més tard en qualsevol moment, o un cop hàgiu acabat, seguiu els passos per a l'enviament.__

## Submissió

En finalitzar, executeu les ordres següents:

```shell
$ git add .
$ git commit -m "done"
$ git push origin master
```

Creeu Pull Request perquè els vostres TA puguin comprovar el vostre treball.

_Hauríeu de fer un PR (significa Pull Request) tan aviat com feu un canvi significatiu. No hauríeu d'esperar fins que acabeu completament amb aquest o qualsevol altre exercici per fer el PR. Després de fer el primer PR, en qualsevol altre moment que premeu els canvis (seguint els tres passos anteriors), el vostre canvi apareixerà automàticament al PR i els vostres TA podran comprovar-ho._

## Instruccions

### Iteració 1: noms i entrada

1.1 Creeu una variable `hacker1` amb el nom del controlador.<br/>
1.2 Imprimeix `"The driver's name is XXXX"` .<br/>
1.3 Creeu una variable `hacker2` amb el nom del navegador.<br/>
1.4 Imprimeix `"The navigator's name is YYYY"` .

### Iteració 2: condicionals

2.1. Segons quin nom [sigui més llarg](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/length) , imprimiu:<br/>
  - `The driver has the longest name, it has XX characters.` o<br/>
  - `It seems that the navigator has the longest name, it has XX characters.` o<br/>
  - `Wow, you both have equally long names, XX characters!` .

### Iteració 3: bucles

3.1 Imprimeix tots els caràcters del nom del conductor, separats per un espai i [en majúscules,](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toUpperCase) és a dir `"JOHN"`

3.2 Imprimeix tots els caràcters del nom del navegador, en ordre invers. és a dir, `"nhoJ"`

3.3 Segons l' [ordre lexicogràfic](https://en.wikipedia.org/wiki/Lexicographical_order) de les cadenes, imprimiu:<br/>
  - `The driver's name goes first.`<br/>
  - `Yo, the navigator goes first definitely.`<br/>
  - `What?! You both have the same name?`

### Temps de bonificació!

#### Bonificació 1:

Aneu al [generador de lorem ipsum](http://www.lipsum.com/) i:

- Genera 3 paràgrafs. Emmagatzema el text en un tipus de cadena variable.
- Feu que el vostre programa compti el nombre de paraules de la cadena.
- Feu que el vostre programa compti el nombre de vegades que apareix la paraula llatina [`et`](https://en.wiktionary.org/wiki/et#Latin) .

#### Bonificació 2:

Creeu una nova variable `phraseToCheck` i feu que contingui algun valor de cadena. Escriu un codi que comprovarà si el valor que hem assignat a aquesta variable és un [Palíndrom](https://en.wikipedia.org/wiki/Palindrome) . Aquests són alguns exemples de palíndroms:

- "A man, a plan, a canal, Panama!"
- "Amor, Roma"
- "race car"
- "stack cats"
- "step on no pets"
- "taco cat"
- "put it up"
- "Was it a car or a cat I saw?" and "No 'x' in Nixon".


__Suggeriment__ : si utilitzeu Google per ajudar-vos a trobar una solució a aquesta iteració, és possible que trobeu algunes solucions que utilitzen mètodes avançats de cadena o matriu (com ara _join()_ , _reverse()_ , etc.). Tanmateix, proveu d'aplicar els coneixements que teniu actualment, ja que podeu crear una solució força agradable amb només fer servir declaracions `for` , `if-else` amb una `break` i `continue` ... Simplement dient :smiley :

## Recursos addicionals

- [String - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
- [if - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
- [while - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while)
- [for - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)

__Feliç codificació!__ :heart: