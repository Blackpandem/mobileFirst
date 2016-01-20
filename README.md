# Mobile First

Liste des branches
```git branch ```

Basculer sur une branche
```git checkout gh-pages```

```git merge master```

```git checkout master```

Mettre à jour sur une branche
```git checkout gh-pages```

```git merge master```

```git pull```

```git add --all```

```git commit -a```


```git push```

#Preprocesseur CSS


SASS

LESS - lesscss.org

Permet de créer des variables - plus rapide

DRY : Don't Repeat Yourself

Exemple:

##AVANT
```

.titre{
color: #f00;
}
.link{
color: #f00;
}

```

##APRES
```

@color-primary: #f00;

.titre{
color: @color-primary;
}
.link{
color: @color-primary;
}

```
