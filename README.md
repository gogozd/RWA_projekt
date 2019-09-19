## Uvod

Praćenjem ponude poslova za web developera u gradu Zadru kroz proteklih godinu ili dvije, kao najtraženija tehnologija i programski jezik se pojavljivao JavaScript, React, Redux, Docker, MySQL, tako da sam odlučio pokušati napraviti zadatak koristeći te tehnologije uz pomoć raznih izvora sa interneta, točnije YouTube-a i Stackoverflow-a.

## Naučeno

Elemente koje sam naučio kroz ovaj zadatak mogu svesti na slijedeće:

- upoznao JavaScript i novije svojstvo arrow functiona
- const i env varijable
- React folder strukturu
- komponente koje rade sa HTTP-om (React Components)
- korištenje Postman-a za slanje requesta i testiranje backenda dok još nije razvijen frontend
- JSON server
- Materialize UI - css framework koji je sličan Bootstrapu

## Baza podataka

Za bazu podataka je korišten [JSON server](https://github.com/typicode/json-server) koji simulira REST API i može primati request-e. Nije vrsta servera koji se koristi u komercijalne svrhe već za brzu provjeru backenda. U ovom zadatku JSON server nije instaliran globalno, nego je stvoren db.json file koji se pokreće preko:

### `json-server --watch db.json`

koji je dodan pod "scripts" pod "json-server", a nalazi se u package.json

## Pokretanje aplikacije

Potrebno je kopirati repozitorij. Aplikacija se pokreće preko termninala npr. Visual Studio Code-a naredbom:

### `npm run dev`

Aplikacija treba raditi bez instaliranja dodatnih dev dependency-ja, testirano je na drugom računalu i radilo je bez problema.

Ukoliko ne bude aplikacija radila, a trebala bi, pomoću slijedećih naredbi se instaliraju dodatni dev dependency:

### `npm i -D json-server concurrently`

### `npm i materialize-css`

### `npm i redux react-redux redux-thunk redux-devtools-extension`
