Foredrag fagdag 31. August
==========================

## Intro til CoffeeScript
- Hvorfor coffeescript?
  - Javascript har noen kinks, variabler lekker scope, masse bruk av anynome funksjoner.
  - Fikser disse tingene automatisk. (vise generert kode)
  - Enklere syntax
    - Indent-basert
    - Parentes, krøllparentes kan ofte droppes
    - Forenkler javascript best practices
  - Ekstra funksjonalitet (Array deconstruction)
- Gotchas, vanlige operasjoner (for-løkker osv., == vs ====)
  - https://gist.github.com/liaody/1598046
  - Implicit Scoping
- Stemning i miljøet (mange som disser coffeescript, Rails-miljøet digger det)
- ES6, Typescript, (Bailey)











### Objekter
harald =
  høyde: 175
  by: lyngdal
  erfaring: 2
  alder: 24

### Funksjoner
=>
->

### if, unless
if true then 'something' else 'somethingorother'

### for

### splats
race = (winner, runners...) ->
  alert runners

race 'harald', 'nico', 'geir', 'jonny'

### Finnes
alert "I knew it!" if elvis?

### Array comprehention

electric_mayhem = [ { name: "Doctor Teeth", instrument: "piano" },
                    { name: "Janice", instrument: "lead guitar" },
                    { name: "Sgt. Floyd Pepper", instrument: "bass" },
                    { name: "Zoot", instrument: "sax" },
                    { name: "Lips", instrument: "trumpet" },
                    { name: "Animal", instrument: "drums" } ]

names = (muppet.name for muppet in electric_mayhem)

alert names

























## Coffeescript server-side
- Node.js + Express
- Applikasjonsstruktur
- Coffeescript + node - steg for steg

## Coffeescript client-side
- Coffeescript-klasser (POJOs)
- Event-drevet programmering
- Grunt workflow
- Live-koding
- Demonstrere chatte-app

## Andre rammeverk sammen med Coffeescript
- React
- Polymer
- Socket.io
- Snap.svg