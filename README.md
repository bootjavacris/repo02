## ex2
1. remoto
2. git clone https://github.com/bootjavacris/repo02.git
3. git add ., git git commit
4. 
# Comandos Principales de Git

## Configuración Inicial

- **Configurar el nombre de usuario**:
  ```sh
  git config --global user.name "Tu Nombre"
  ```

- **Configurar el correo**:
    ```sh
    git config --global user.email "ejemplo@gmail.com"
    ```

## Comando básicos

- **Inicializar un repo**:
  ```sh
  git init
  ```
- **Clonar un repositorio**:
    ```sh
    git clone https://github.com/usuario/repositorio.git
    ```
- **Ver el estado del repositorio:**:
  ```sh
    git status
  ```

- **Añadir archivos a Staging area:**:
  ```sh
    git add .
  ```
  añade todos los archivos, podemos sustituir el . por el nombre del archivo

- **Confirmar Cambios:**:
  ```sh
    git commit -m "Primer commit"
  ```

  - **Historial de cambios:**:
  ```sh
    git log
  ```