# Preguntas práctica - parte 1
### ¿Qué comando utilizaste en el paso 11? ¿Por qué?
```git reset --hard HEAD~1```

Porque de esta forma deshago el último commit y lo que había en mi working copy, todo queda como estaba antes.

### ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
```git reflog```

Para ver todo lo ocurrido en nuestro repositorio y así ver los commits por los que hemos ido pasando, en qué orden y poder acceder a ellos a través de su id.

```git reset --hard id```

Me muevo al commit anterior a través de su id y así recupero el trabajo.

### El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No, crea un merge con fast forward, las ramas forman una lista, da un aviso "already up to date" que indica que la rama styled no tiene nada de lo que hacer merge.

### El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Sí, tenemos dos archivos de mismo nombre con distinto contenido en las mismas líneas y se nos pide que resolvamos el conflicto eligiendo el contenido con el que deseamos quedarnos.

### El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No, hace un merge fast-fordward ya que la rama master absorbe styled sin problemas.

### ¿Qué comando o comandos utilizaste en el paso 25?
```git log --graph```

### El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Sí, no se crearía un commit nuevo, el puntero apuntaría directamente al último commit realizado en la rama title, pero ésta pasaría a ser absorbida por master.

### ¿Qué comando o comandos utilizaste en el paso 27?
```git reset HEAD~1```

### ¿Qué comando o comandos utilizaste en el paso 28?
```git checkout -- git-nuestro.md```

### ¿Qué comando o comandos utilizaste en el paso 29?
```git branch -D title```

###¿Qué comando o comandos utilizaste en el paso 30?
```git reset --hard 5c21107```

5c21107 -> id del merge para volver a recuperarlo

### ¿Qué comando o comandos usaste en el paso 32?
```git reflog```

```git reset --hard b9044fe```

b9044fe -> id del commit en el que se creó el poema

### ¿Qué comando o comandos usaste en el punto 33?
```git reflog```

```git reset --hard 67e05d2``

67e05d2 -> id del commit en el que puse el título al poema
