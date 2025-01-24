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
<img width="574" alt="Screenshot 2025-01-24 at 18 15 38" src="https://github.com/user-attachments/assets/8287cba7-c915-4a78-8698-30f2246bb0f7" />

Git clone nos permite clonar un repositorio al nuestro a partir de su URL.

### Git Status
<img width="553" alt="Screenshot 2025-01-24 at 18 16 04" src="https://github.com/user-attachments/assets/77d3f9c9-6ea7-4d3d-b598-92c88e56029f" />


Git Status muestra el estado actual del repositorio local, como:
	•	Cambios que aún no se han guardado (staged o unstaged).
	•	Archivos nuevos que no están siendo rastreados.
	•	La rama en la que estás trabajando.

### Git Add
<img width="534" alt="Screenshot 2025-01-24 at 18 17 35" src="https://github.com/user-attachments/assets/6eaabe4a-8cd4-4afc-8ecc-ee8e7b939d16" />


Git Add añade archivos al área de preparación (staging area). Esto prepara los archivos para ser incluidos en el próximo commit.

### Git Commit
<img width="351" alt="Screenshot 2025-01-24 at 18 18 30" src="https://github.com/user-attachments/assets/4b374df1-c9c9-49b4-954f-7546529ef94f" />


Git Commit guarda los cambios en el historial del repositorio. Un commit representa un punto de control en el desarrollo.

### Git Push
<img width="493" alt="Screenshot 2025-01-24 at 18 20 25" src="https://github.com/user-attachments/assets/722bc674-a7dd-4c18-a117-d1b0ba59589e" />


Git Push envía los commits locales al repositorio remoto, sincronizando los cambios.

### Git Checkout
<img width="364" alt="Screenshot 2025-01-24 at 18 20 41" src="https://github.com/user-attachments/assets/67700a1d-5e36-4460-9284-7c85a60c7c34" />


Git Checkout permite cambiar de rama o restaurar archivos. Con la flag -b creamos una nueva rama.
