# typescript-template GIT / WSL / VSC

* git init project-name
* cd project-name
* npm init
  * adopt package.json:
  * "main": "./dist/index.js",
  *   "scripts": { "start": "rm -Rf ./dist && npx tsc && node --experimental-modules --es-module-specifier-resolution=node ."
* VSC -> Datei -> Ordner öffnen... -> path/to/project-name -> OK
* VSC -> Arbeitsbereich speichern unter... -> OK
* zum Terminal
* wget https://github.com/AM2H-Development/typescript-template/blob/11a810540bbc390da651d2bbaa32929667f4e819/.gitignore
* npm install typescript --save-dev
* EITHER: npx tsc --init
  * adopt the path to ./src
* OR: wget https://github.com/AM2H-Development/typescript-template/blob/775306fb1ec48fe2a4f9f78f7ead102efdb2c113/tsconfig.json
