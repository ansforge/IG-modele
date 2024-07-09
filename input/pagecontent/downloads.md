### Téléchargement

L'implementation guide contient un package [téléchargeable ici](package.tgz) permettant de valider les instances par rapport aux profils qu'il contient.

Pour cela, il suffit de télécharger le [package.tgz](package.tgz) et l'importer dans un serveur, par exemple sur hapi en suivant ce [script python](https://github.com/nmdp-bioinformatics/igloader) open source.

Ensemble des ressources téléchargeables :

* [L'ensemble de la specification (zip)](full-ig.zip)
* [Package (tgz)](package.tgz)

#### Définitions

* [Définitions JSON (zip)](definitions.json.zip)
* [Définitions XML (zip)](definitions.xml.zip)
* [Définitions Turtle (zip)](definitions.ttl.zip)

#### Exemples

* [Exemples XML (zip)](examples.xml.zip)
* [Exemples JSON (zip)](examples.json.zip)
* [Exemples Turtle (zip)](examples.ttl.zip)

### Usage

Ce guide d'implémentation contient les profils qui définissent la structure des instances FHIR attendues.

Les serveurs ainsi que les clients qui envoient de la donnée aux serveurs devront s'assurer de la conformité des ressources envoyées par rapport aux profils indiqués dans le guide ainsi qu'à la spécification FHIR de base. Pour cela, il est possible d'utiliser le validateur officiel [FHIR Validator](https://confluence.hl7.org/display/FHIR/Using+the+FHIR+Validator) qui est également accessible [en ligne](https://validator.fhir.org/).

Pour plus d'information sur la validation des instances de ressource contre un profil issu de cette spécification, consulter la documentation de l'opération [$validate](https://www.hl7.org/fhir/resource-operation-validate.html) et la [documentation de l'ANS](https://interop.esante.gouv.fr/ig/documentation/valider_res.html).
