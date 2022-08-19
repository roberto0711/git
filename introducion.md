# **CONCEPTOS**
# Sistemas de control de versiones distribuidos:
- Git
- Mercurial
-Bazar
# Forma de compartir mi repositorio:
1ro- Comprimir carpeta repositorio y enviarla 
2da- A travez de Servidor
    a. Monto un servidor
    b. Uso una herramienta app para crear repos
- Github (de microsoft)
- gitLab.org
- bitbucket
- source forge (tiene un DS)

# Uso de GitHub:
*Public:* da acceso a todos los usuarios que tengan cuenta de git 
*Private:* no puede tener acceso nadie aquien no le autorización
Elegir una licencia: para crear proyectos open source una suegrida (MIT)
*creando un repo git local 1*
- mkdir app
- touch LICENSE
- echo "Documentacion" > Readme.md
- git init . (crea un repositorio en el directorio actual )
- ls -altr (muestra el fichero .git)
- git log muestra los cambios 
- git add . (añade todos los cambios)
- git config (cambia configuracion de git)
- git config --system --> modigica a nivel codigo
- git config --global --> modifica ficheros de usuario
- git config --local ---> modifica ficheros locales en mi directorio que me encuentro
# PARA VER LA CONFIGURACION ACTUAL
git config --list --system

# CREAR UN REPO LOCAL SOLO DIRECTORIO EN MI APP 
git init .
git add .
git commit -am "version actual"
git log
# CREAR UNA REPO LOCAL EN MI PC
- git init --bare miapp
ruta del repo en mi pc
 git clone /home/roberto/repositories/miapp