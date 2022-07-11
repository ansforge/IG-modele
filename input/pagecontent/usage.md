### Usage

L'implementation guide contient un package [téléchargeable ici](package.tgz) permettant de valider les instances par rapport aux profils qu'il contient.

Pour cela, il suffit de télécharger le [package.tgz](package.tgz) et l'importer dans un serveur, par exemple sur hapi en suivant ce [script python](https://github.com/nmdp-bioinformatics/igloader) open source.

Vous pourrez ensuite utiliser l'opération [$validate](https://www.hl7.org/fhir/resource-operation-validate.html) pour valider les instances de ressource contre un profil issu de cette spécification.