<!-- Ce fichier contient les informations relatives à la première section "contexte métier". !-->

### Cas d'usages

*Détailler les cas d'usage à travers des exemples illustrés via des diagrammes de séquences.*

<figure style="text-align:center">
{% include spe-sequence.svg %}
<figcaption>diagramme de séquence du cas d'usage</figcaption>
</figure>

### Définitions et cadre juridique

*Définir le cadre juridique de l’étude. Mentionner les orientations organisationnelles et les moyens mis en œuvre pour rationaliser les processus.*

### Organisation du contexte métier

Définir le domaine développé dans le cadre du volet, ainsi que les groupes de processus et les processus collaboratifs.

<figure class="figure svg-wrap" style="width:100%;">
 <div class="btn-group-vertical position-absolute top-0 end-0 p-2 svg-controls">
 <button class="btn btn-light btn-sm svg-zoom-in">🔍+</button>
 <button class="btn btn-light btn-sm svg-zoom-out">🔍−</button>
 <button class="btn btn-light btn-sm svg-zoom-reset">↻</button>
 <button class="btn btn-light btn-sm svg-fullscreen">⛶</button>
 </div>
 <p style="margin: 0; padding: 0;">
    {% include spe-paquetage.svg %}
 </p>
<figcaption>Organisation du contexte métier du volet traité</figcaption>
</figure>

### Acteurs

{% sql {
  "query" : "
    SELECT
      Title,
      Description,
      REPLACE(Purpose, '**Exemples**', '') AS Purpose,
      Web
    FROM Resources
    WHERE Type = 'ActorDefinition'
    ORDER BY Title
  ",
  "class" : "lines",
  "columns" : [
    {
      "title" : "Acteur", "type" : "link", "source" : "Title", "target" : "Web" },
    {
      "title" : "Description", "type" : "markdown", "source" : "Description" },
    {
      "title" : "Exemples", "type" : "markdown", "source" : "Purpose" }
  ]
} %}

