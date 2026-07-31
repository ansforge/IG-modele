# Type Carte Value Set - ANS IG Example v0.1.0

## ValueSet: Type Carte Value Set 

 
Type Carte Value Set. 

 **References** 

Ce jeu de valeurs n'est pas utilisé ici ; il peut être utilisé autre part (par exemple dans les spécifications et / ou implémentations qui utilisent ce contenu)

### Définition logique (CLD)

 

### Expansion

-------

 [Description du (des) tableau(x) ci-dessus](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "ValueSet",
  "id" : "TypeCarteVS",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/modele/ValueSet/TypeCarteVS",
  "version" : "0.1.0",
  "name" : "TypeCarteVS",
  "title" : "Type Carte Value Set",
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
  "description" : "Type Carte Value Set.",
  "jurisdiction" : [{
    "coding" : [{
      "system" : "urn:iso:std:iso:3166",
      "code" : "FR",
      "display" : "France (la)"
    }]
  }],
  "compose" : {
    "include" : [{
      "system" : "https://interop.esante.gouv.fr/ig/fhir/modele/CodeSystem/type-carte-code-system",
      "version" : "0.1.0"
    }]
  }
}

```
