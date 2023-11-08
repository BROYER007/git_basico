# GIT basico 

1 - crear el .gitingore y README.md
2- Iniciar el proyecto: 
git init
3 - Configuracion
git config user.name "nombre"
git congif ("global) user.email mi.email@ejemplo.com
git config --global core.autocrif true (win) o input (Mac - Linux)
git config -- global core.editor "code --wait"
git add .gitignore README.md
4- informacion del estado
git status
5- pasar al stage
git add .gitignore README.md
6- pasar al commit (version 1)
git commit -m "README hasta el punto 5"
git commit -a -m "README hasta el punto 6"




let array_1 = ["Anna", "Sara", "John"]
//console.log (typeof array_1);
let nombre = " Pep"
console.log(nombre.length); 3
console.log (array_1.length); 3

let array_frutas = ["Mango", "Pera", "Cereza", platano]
console.log(array_frutas[3]); platano
console.log (array_frutas.length); 5
console.log (array_frutas[array_frutas.length +1]); castaña
array_frutas[2] = "naranja"
console.log (array_frutas[2]); 

//array_frutas.push =(array_frutas_sum)
// console.log(array_frutas_fall);
let array_frutas_fall = ["Mango", "Pera", "Cereza", "castaña"] 
let array_unificado =  ["melocoton", "melon", "sandia"]

let  array_frutas_fal = array_unificado.concat(array_frutas_fall);
console.log(array_frutas_fal);

