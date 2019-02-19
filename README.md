# Yannick Libert

Mon CV au format LaTeX. Utilise le template awesome-cv et quelques fonts disponibles dans le repo. 


Testé et compilé avec la version 1.07.0 de LuaTeX


Pour compiler sur un mac avec Sublime Text 2, installer d'abord LaTeX puis dans Sublime Text 2 : 

Tools > Build System > New Build System...

Copier Coller ce bout de code

```sh
{
    "cmd": ["/Library/TeX/texbin/lualatex","$file"],
    "selector": "text.tex.latex"
}
```

Et sauver le fichier sous le nom ```LaTeX.sublime-build```

Le raccourci Cmd+B lancera un build. 

Pour afficher le résultat, Skim est pratique car il recharche le pdf à chaque build.