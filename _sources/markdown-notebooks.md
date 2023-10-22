---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# COMANDOS GIT BASICOS

Aquí hay algunos comandos básicos de GIT que debes conocer:

## git init 
creará un nuevo repositorio local GIT. El siguiente comando de Git creará un repositorio en el directorio actual:
```
   git init 
```
Como alternativa, puedes crear un repositorio dentro de un nuevo directorio especificando el nombre del proyecto:
```
   git init [nombre del proyecto]
```

## git clone 
se usa para copiar un repositorio. Si el repositorio está en un servidor remoto, usa:
```
git clone nombredeusuario@host:/path/to/repository
```
A la inversa, ejecuta el siguiente comando básico para copiar un repositorio local:
```
git clone /path/to/repository
```
# git add 
se usa para agregar archivos al área de preparación. Por ejemplo, el siguiente comando de Git básico indexará el archivo temp.txt:
```
git add <temp.txt>
```
# git commit 
creará una instantánea de los cambios y la guardará en el directorio git.
```
git commit –m “El mensaje que acompaña al commit va aquí”
```

Revisar [Detalles de mas comandos para Git](https://www.hostinger.es/tutoriales/comandos-de-git)

