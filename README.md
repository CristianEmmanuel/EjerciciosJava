# EjerciciosJava

## Como vincular un proyecto que ya tengo en mi compu, con un repo github

1) Entrar desde la consola hasta la carpeta donde tengo mi codigo
2) Iniciamos un repositorio en esa carpeta
		git init
2) Añadimos el repositorio remoto a nuestro repo local
		git remote add https://github.com/CristianEmmanuel/EjerciciosJava.git

3) Ahora hacemos lo de siempre 
		git add .
		git commit -m "First commit"
		git pull origin master
		git push origin master
