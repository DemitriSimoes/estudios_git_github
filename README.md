# Estudios Git y GitHub

Se trata del control de versiones de código

y<br>
repositorios remotos en GitHub

## Flujo de trabajo Git local

1. git checkout -b <nova_branch>
2. crea o actualiza archivos
3. git status
4. git add <nombre_del_archivo o .>
5. git commit -m "mensagem"
6. git checkout main
7. git merge <nova_branch>

## Flujo de trabajo GitHub <br> local (tu propio proyecto o el proyecto de tu empresa)

1. git clone <dirección_del_proyecto>
2. git checkout -b <nueva_branch>
3. cambios de archivo
4. git status
5. git add <archivos>
6. git status
7. git commit -m "mensagem"
8. git push origin <nombre_de_la_nueva_branch>
9. abrir pull request en GitHub para main
10. eliminar <nueva_branch> orgin
11. git checkout main
12. git pull origin main
13. git branch -D <nueva_branch>

## Flujo de trabajo GitHub <br> local (proyectos open source)

1. Fork del proyecto en tu propio GitHub
2. git clone <sitio_del_proyecto_fork>
3. git checkout -b <nueva_branch>
4. cambios de archivo
5. git status
6. git add <archivos o .>
7. git status
8. git commit -m "mensagem"
9. git push origin <nombre_de_la_nueva_branch>
10. abrir pull request en GitHub de la branch fork para la main del proyecto original
11. eliminar <nueva_branch>
12. git checkout main
13. git pull origin main
14. git branch -D <nueva_branch>

