# Type de carte - ANS IG Example v0.1.0

## CodeSystem: Type de carte 

 
Type de carte professionnelle et personnelle. 

Ce système de codes est référencé dans la définition des ensembles de valeurs suivants :

* [MeltingPotVS](ValueSet-MeltingPotVS.md)
* [TypeCarteVS](ValueSet-TypeCarteVS.md)

-------

 [Description du (des) tableau(x) ci-dessus](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "type-carte-code-system",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/modele/CodeSystem/type-carte-code-system",
  "version" : "0.1.0",
  "name" : "TypeCarteCS",
  "title" : "Type de carte",
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
  "description" : "Type de carte professionnelle et personnelle.",
  "jurisdiction" : [{
    "coding" : [{
      "system" : "urn:iso:std:iso:3166",
      "code" : "FR",
      "display" : "France (la)"
    }]
  }],
  "content" : "complete",
  "count" : 4,
  "concept" : [{
    "code" : "CPA",
    "display" : "Carte de Personnel Autorisé",
    "definition" : "La carte d'un personnel autorisé (CDA/CPA)"
  },
  {
    "code" : "CPE",
    "display" : "Carte de Personnel d'Etablissement",
    "definition" : "La Carte de Personnel d'Etablissement de santé (CDE/CPE)."
  },
  {
    "code" : "CPF",
    "display" : "Carte de Professionnel de Santé en Formation",
    "definition" : "La Carte de Professionnel de Santé en Formation (CPF)."
  },
  {
    "code" : "CPS",
    "display" : "Carte de Professionnel de Santé",
    "definition" : "La Carte de Professionnel de Santé (CPS)."
  }]
}

```
