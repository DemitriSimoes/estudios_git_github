# Estudios Git y GitHub

Se trata del control de versiones de código

y<br>
repositorios remotos en GitHub

## Flujo de trabajo Git local

1. git checkout -b <nova branch><br>
2. crea o actualiza archivos<br>
3. git status<br>
4. git add <nombre del archivo o .><br>
5. git commit -m "<mensagem>"<br>
6. git checkout main<br>
7. git merge <nova branch><br>

## Flujo de trabajo GitHub <> local (tu propio proyecto o el proyecto de tu empresa)

1. git clone <dirección del proyecto><br>
2. git checkout -b <nueva branch><br>
3. cambios de archivo<br>
4. git status<br>
5. git add <archivos><br>
6. git status<br>
7. git commit -m "<mensagem>"<br>
8. git push origin <nombre de la nueva branch><br>
9. abrir pull request en GitHub para main
10. eliminar <nueva branch> orgin<br>
11. git checkout main<br>
12. git pull origin main<br>
13. git branch -D <nueva branch><br>

## Flujo de trabajo GitHub <> local (proyectos open source)

1. Fork del proyecto en tu propio GitHub<br>
2. git clone <sitio del proyecto fork><br>
3. git checkout -b <nueva branch><br>
4. cambios de archivo<br>
5. git status<br>
6. git add <archivos><br>
7. git status<br>
8. git commit -m "<mensagem>"<br>
9. git push origin <nombre de la nueva branch><br>
10. abrir pull request en GitHub de la branch fork para la main del proyecto original<br>
11. eliminar <nueva branch><br>
12. git checkout main<br>
13. git pull origin main<br>
14. git branch -D <nueva branch>

