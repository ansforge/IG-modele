# EX Concept Metier - ANS IG Example v0.1.0

## Logical Model: EX Concept Metier 

 
Exemple concept métier 

**Usages:**

* This Logical Model is not used by any profiles in this Specification

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/resource/ans.fhir.fr.modele|current/StructureDefinition/StructureDefinition-EXConceptMetier.json)

### Formal Views of Profile Content

 [Description Differentials, Snapshots, and other representations](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](../StructureDefinition-EXConceptMetier.csv), [Excel](../StructureDefinition-EXConceptMetier.xlsx) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "EXConceptMetier",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/modele/StructureDefinition/EXConceptMetier",
  "version" : "0.1.0",
  "name" : "EXConceptMetier",
  "title" : "EX Concept Metier",
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
  "description" : "Exemple concept métier",
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
  "type" : "https://interop.esante.gouv.fr/ig/fhir/modele/StructureDefinition/EXConceptMetier",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/Base|4.0.1",
  "derivation" : "specialization",
  "differential" : {
    "element" : [{
      "id" : "EXConceptMetier",
      "path" : "EXConceptMetier",
      "short" : "EX Concept Metier",
      "definition" : "Exemple concept métier"
    }]
  }
}

```
