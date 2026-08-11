# Comment utiliser la fonctionnalité SVG Interactif

## Description
Cette fonctionnalité ajoute des contrôles de zoom, pan (déplacement) et plein écran à vos SVG.

## Utilisation dans vos pages markdown

### 1. Inclure les styles (une seule fois par page)
En haut de votre fichier markdown, ajoutez :
```markdown
{% include svg-interactive-styles.html %}
```

### 2. Wrapper votre SVG
Enveloppez votre SVG avec la structure suivante :

```markdown
<div class="figure svg-wrap" style="width:100%; overflow-x:auto;">
  <div class="btn-group-vertical position-absolute top-0 end-0 p-2 svg-controls">
    <button class="btn btn-light btn-sm svg-zoom-in" title="Zoom avant">🔍+</button>
    <button class="btn btn-light btn-sm svg-zoom-out" title="Zoom arrière">🔍−</button>
    <button class="btn btn-light btn-sm svg-zoom-reset" title="Réinitialiser">↻</button>
    <button class="btn btn-light btn-sm svg-fullscreen" title="Plein écran">⛶</button>
  </div>
  <p style="margin: 0; padding: 0;">
    {% include votre-fichier.svg %}
  </p>
</div>
```

### 3. Inclure le script (une seule fois à la fin de la page)
À la fin de votre fichier markdown, ajoutez :
```markdown
{% include svg-interactive-script.html %}
```

## Exemple complet

Voir le fichier `input/pagecontent/professionnel.md` pour un exemple d'utilisation complète.

## Fonctionnalités disponibles

- **Zoom avant/arrière** : Boutons + / - ou molette de la souris
- **Réinitialiser** : Bouton ↻
- **Plein écran** : Bouton ⛶
- **Pan (déplacement)** : Clic gauche + glisser
- **Zoom tactile** : Pinch zoom sur mobile
- **Les liens restent cliquables** : Les liens dans le SVG fonctionnent normalement

## Notes techniques

- Le script s'initialise automatiquement pour tous les éléments avec la classe `svg-wrap`
- Vous pouvez avoir plusieurs SVG interactifs sur la même page
- Le CSS et le JavaScript sont isolés et n'interfèrent pas avec le reste de la page
