# Clase 05 - Git

## Para crear un repositorio de GIT

```sh
git init
```

## Ver en que estado están los archivos y en que área

```sh
git status
```

## Areas del repositorio de GIT

3 Áreas

# Agrego al área de confirmación el archivo/archivos

```sh
git add <nombre-archivo>
git add <nombre-archivo> <nombre-archivo> <nombre-arhivo>
git add . #Agrega todos los archivos
```

# Persistimos los cambios agregados al área de confirmación en un commit

```sh
git commit -m "mensaje descriptivo de lo que tiene el commit"
```

# Corregir el mensaje del commit

```sh
git commit --amend -m "el mensaje corregido"
```

