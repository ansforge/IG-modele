# Numérotation Automatique - Guide d'utilisation rapide

Le fichier 'figure-caption.html' permet de numéroter automatiquement toutes les figures disposant d'une légende (<figcaption>).

## Pour ajouter une légende numérotée

### Étape 1 : Inclure le style (une fois en haut de la page)
```markdown
{% include figure-caption.html %}
```

### Étape 2 : Encapsuler l'image avec la balise figure et ajouter la balise <figcaption> contenant la légende de la figure
```markdown
<figure style="text-align:center">
{% include SVG.svg %}
<figcaption>légende de la figure</figcaption>
</figure>
```

La numérotation est incrémentée automatiquement pour chaque nouvelle balise <figure> contenant un <figcaption>.

## Exemple

Voir `input/pagecontent/contexte-metier.md` pour un exemple d'implémentation.