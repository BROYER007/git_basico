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