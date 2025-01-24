# Práctica 1

Un repositorio para empezar a usar [git](https://git-scm.com/) y Github

## ¿Como probar en la nube?

[Github-Codespaces](https://github.com/features/codespaces)

## Comandos git básicos

```
git clone https://github.com/gitt-3-pat/p1
git status
git add .
git commit -m "TU MENSAJE"
git push

git checkout -b feature/1
git checkout main
```

## ¿Cómo escribir un README.md con formato?

[Github Markdown](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## Memoria práctica 1 - Lucas Carrasco

A continuación procedemos a explicar los diferentes comandos que utilizamos a lo largo de la practica:

### Git Clone
![alt text](<Screenshot 2025-01-24 at 18.15.38.png>)

Git clone nos permite clonar un repositorio al nuestro a partir de su URL.

### Git Status
![alt text](<Screenshot 2025-01-24 at 18.16.04.png>)

Git Status muestra el estado actual del repositorio local, como:
	•	Cambios que aún no se han guardado (staged o unstaged).
	•	Archivos nuevos que no están siendo rastreados.
	•	La rama en la que estás trabajando.

### Git Add
![alt text](<Screenshot 2025-01-24 at 18.17.35.png>)

Git Add añade archivos al área de preparación (staging area). Esto prepara los archivos para ser incluidos en el próximo commit.

### Git Commit
![alt text](<Screenshot 2025-01-24 at 18.18.30.png>)

Git Commit guarda los cambios en el historial del repositorio. Un commit representa un punto de control en el desarrollo.

### Git Push
![alt text](<Screenshot 2025-01-24 at 18.20.25.png>)

Git Push envía los commits locales al repositorio remoto, sincronizando los cambios.

### Git Checkout
![alt text](<Screenshot 2025-01-24 at 18.20.41.png>)

Git Checkout permite cambiar de rama o restaurar archivos. Con la flag -b creamos una nueva rama.
