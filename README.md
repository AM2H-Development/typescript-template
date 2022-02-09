# typescript-template for local server app
* clone this template
* ... todo ...


OLD: start from scratch:
* git init project-name
* cd project-name
* npm init
  * adopt package.json:
  * "main": "./dist/index.js",
  * "type": "module",
  *   "scripts": { "start": "rm -Rf ./dist && npx tsc && node --experimental-modules --es-module-specifier-resolution=node ."
* VSC -> Datei -> Ordner öffnen... -> path/to/project-name -> OK
* VSC -> Arbeitsbereich speichern unter... -> OK
* zum Terminal
* wget https://raw.githubusercontent.com/AM2H-Development/typescript-template/main/.gitignore
* npm i --save-dev typescript 
* npm i --save-dev @types/node
* EITHER: npx tsc --init
  * adopt the path to ./src
* OR: wget https://raw.githubusercontent.com/AM2H-Development/typescript-template/main/tsconfig.json
* mkdir src src/app
* touch 
