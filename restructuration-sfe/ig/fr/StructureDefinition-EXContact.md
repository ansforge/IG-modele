# EX Contact - ANS IG Example v0.1.0

## Modèle logique: EX Contact 

 
Exemple concept métier contact 

Le flag Must Support est ici utilisé sur les modèles logiques afin d'indiquer les attributs effectivement utilisés dans le cadre du cas d'usage du présent volet.

## Vue logique du concept

🔍+
🔍−
↻
⛶

  

**Utilisations:**

* Ce Modèle logique n'est utilisé par aucun autre profil dans ce guide d'implémentation

Vous pouvez également vérifier [les usages dans le FHIR IG Statistics](https://packages2.fhir.org/xig/ans.fhir.fr.modele|current/StructureDefinition/EXContact)

### Vues formelles du contenu du profil

 [Description des profils, des différentiels, des instantanés et de leurs représentations](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

*  [Tableau différentiel (differential)](#tabs-diff) 
*  [Tableau récapitulatif (snapshot)](#tabs-snap) 
*  [Statistiques/Références](#tabs-summ) 
*  [Tous](#tabs-all) 

Cette structure est dérivée de [Contact](https://interop.esante.gouv.fr/ig/mos/0.1.0-ballot/StructureDefinition-Contact.html) 

#### Bindings terminologiques

Cette structure est dérivée de [Contact](https://interop.esante.gouv.fr/ig/mos/0.1.0-ballot/StructureDefinition-Contact.html) 

** Résumé **

Must-Support : 1 élément

 **Vue différentielle** 

Cette structure est dérivée de [Contact](https://interop.esante.gouv.fr/ig/mos/0.1.0-ballot/StructureDefinition-Contact.html) 

 **Vue d'ensembleView** 

#### Bindings terminologiques

Cette structure est dérivée de [Contact](https://interop.esante.gouv.fr/ig/mos/0.1.0-ballot/StructureDefinition-Contact.html) 

** Résumé **

Must-Support : 1 élément

 

Autres représentations du profil : [CSV](../StructureDefinition-EXContact.csv), [Excel](../StructureDefinition-EXContact.xlsx) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "EXContact",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/modele/StructureDefinition/EXContact",
  "version" : "0.1.0",
  "name" : "EXContact",
  "title" : "EX Contact",
  "status" : "draft",
  "date" : "2026-07-31T12:42:16+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "contact" : [{
    "name" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
    "telecom" : [{
      "system" : "url",
      "value" : "https://esante.gouv.fr"
    }]
  }],
  "description" : "Exemple concept métier contact",
  "jurisdiction" : [{
    "coding" : [{
      "system" : "urn:iso:std:iso:3166",
      "code" : "FR",
      "display" : "France (la)"
    }]
  }],
  "fhirVersion" : "4.0.1",
  "kind" : "logical",
  "abstract" : false,
  "type" : "https://interop.esante.gouv.fr/ig/fhir/modele/StructureDefinition/EXContact",
  "baseDefinition" : "https://interop.esante.gouv.fr/ig/mos/StructureDefinition/Contact|0.1.0-ballot",
  "derivation" : "specialization",
  "differential" : {
    "element" : [{
      "id" : "EXContact",
      "path" : "EXContact",
      "short" : "EX Contact",
      "definition" : "Exemple concept métier contact"
    },
    {
      "id" : "EXContact.role",
      "path" : "EXContact.role",
      "mustSupport" : true
    }]
  }
}

```
