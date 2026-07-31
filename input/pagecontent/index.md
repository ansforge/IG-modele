{% include figure-caption.html %}
{% include svg-interactive-styles.html %}

<p style="padding: 5px; border-radius: 5px; border: 2px solid maroon; background: #ffffe6; width: 65%">
<b>Brief description of this Implementation Guide</b><br>
[Add a brief description of this IG in English]
</p>

{% if site.data.info.releaselabel == 'ci-build' %}
<div style="width: 65%">
    <blockquote class="stu-note">
    <p>Cet Implementation Guide n'est pas la version courante, il s'agit de la version en intégration continue soumise à des changements fréquents uniquement destinée à suivre les travaux en cours. La version courante sera accessible via l'URL canonique suite à la première release : http://interop.esante.gouv.fr/ig/fhir/[code - ig]</p>
    </blockquote>
</div>
{% endif %}


{% if site.data.info.releaselabel == 'public-comment' %}
<div style="width: 65%">
<blockquote class="stu-note">
<p>
  <b>Attention !</b>
  <br>
 Cet Implementation Guide est actuellement en concertation. La version courante est accessible à l'adresse : http://interop.esante.gouv.fr/ig/fhir/[code - ig]
</p>
</blockquote>
</div>
{% endif %}


<!--  A décommenter si CI-SIS
<div class="figure">
    <img src="ci-sis-logo.png" alt="CI-SIS" title="Logo du CI-SIS" style="width:100%;">
</div>
-->

*Définir ici le sujet traité dans l'IG (En termes non expert, compréhensible par tout profil de lecteur).*

Le guide d'implementation suit cette structure :

<div style="background-color: #e8f4f8; border-left: 4px solid #0077be; padding: 15px; margin: 20px 0;color: #333333; font-size: 14px;">
<strong>Contexte métier</strong>
<ul style="margin: 10px 0 0 0;">
Le contexte métier permet de présenter les <a href="#cas-dusages">cas d'usages</a> les <a href="#définitions-et-cadre-juridique"> définitions et le cadre juridique</a>, l'<a href="#organisation-du-contexte-métier">organisation des processus collaboratifs</a> et les <a href="#acteurs">acteurs impliqués</a>
</ul>
</div>

<div style="background-color: #e9edfa; border-left: 4px solid #94aef7; padding: 15px; margin: 20px 0;color: #333333; font-size: 14px;">
<strong>Spécifications</strong>
<ul style="margin: 10px 0 0 0;">

<p>La section <a href="specifications.html">spécifications</a> présente l'étude fonctionnelle et les spécifications techniques associées à chaque processus collaboratif.</p>

<p>L'<strong>étude fonctionnelle</strong> contient notamment la description des activités liées au flux ainsi que les concepts métiers véhiculés.</p>

<p>Les <strong>spécifications techniques</strong> décrivent l'implémentation des flux nécessaires à l'implémentation du cas d'usage.</p>
<p><i>Présenter brièvement le standard retenu.</i></p>
<p>Une <a href="spe-synthese.html">synthèse des flux et des ressources profilées</a> dans ce volet est également disponible.</p>
</ul>
</div>

<div style="background-color: #f7f2ff; border-left: 4px solid #bd90f8; padding: 15px; margin: 20px 0;color: #333333; font-size: 14px;">
<strong>Ressources de conformité, Tests et Annexes</strong>
<ul style="margin: 10px 0 0 0;">
<p>La section <a href="artifacts.html">Ressources de conformité</a> liste les différents artéfacts supportant les spécifications fonctionnelles et techniques.</p>
<p>La section <a href="tests.html">Tests</a> permet d'accéder aux solutions de tests disponibles pour ce volet.</p>
<p>La section <a href="annexes.html">Annexes</a> permet d'accéder à des ressources complémentaires relatives à la sécurité, aux téléchargements, à la traduction ou à tout autre documentation utile à ce volet.</p>
</ul>
</div>

Les spécifications d'interopérabilité présentées dans ce volet ne présagent pas des conditions de leur mise en œuvre dans le cadre d'un système d'information partagé. Il appartient à tout responsable de traitement de s'assurer que les services utilisant ces spécifications respectent les cadres et bonnes pratiques applicables à ce genre de service (ex : cadre juridique, bonnes pratiques de sécurité, ergonomie, accessibilité...).

Il est à noter que les contraintes de sécurité concernant les flux échangés ne sont pas traitées dans ce document. Celles-ci sont du ressort de chaque responsable de l’implémentation du mécanisme qui est dans l’obligation de se conformer au cadre juridique en la matière. L’ANS propose des référentiels dédiés à la politique de sécurité (la [PGSSI-S](https://esante.gouv.fr/produits-services/pgssi-s)) et des mécanismes de sécurisation sont définis dans les volets de la [couche Transport](https://esante.gouv.fr/services/referentiels/ci-sis/espace-publication/couche-transport) du Cadre d’Interopérabilité des systèmes d’information de santé (CI- SIS).

{% include contexte-metier.md %}

### Auteurs et contributeurs (optionnel)

| Role  | Nom | Organisation | Contact |
| --- | --- | --- | --- |
| **Primary Editor** | Prenom Nom | Agence du Numérique en Santé | prenom.nom@address.email |

### Dépendances

{% lang-fragment dependency-table.xhtml %}

### Propriété intellectuelle

{% lang-fragment ip-statements.xhtml %}

{% include svg-interactive-script.html %}