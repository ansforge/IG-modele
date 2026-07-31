# EyeColor Value Set - ANS IG Example v0.1.0

## ValueSet: EyeColor Value Set 

 
Different eye colors. 

 **References** 

* [EyeColor](StructureDefinition-EyeColor.md)

### Définition logique (CLD)

 

### Expansion

-------

 [Description du (des) tableau(x) ci-dessus](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "ValueSet",
  "id" : "EyeColorVS",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/modele/ValueSet/EyeColorVS",
  "version" : "0.1.0",
  "name" : "EyeColorVS",
  "title" : "EyeColor Value Set",
  "status" : "draft",
  "date" : "2026-07-31T07:50:12+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "contact" : [{
    "name" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
    "telecom" : [{
      "system" : "url",
      "value" : "https://esante.gouv.fr"
    }]
  }],
  "description" : "Different eye colors.",
  "jurisdiction" : [{
    "coding" : [{
      "system" : "urn:iso:std:iso:3166",
      "code" : "FR",
      "display" : "France (la)"
    }]
  }],
  "compose" : {
    "include" : [{
      "system" : "http://snomed.info/sct",
      "concept" : [{
        "code" : "405738005",
        "display" : "Blue color"
      },
      {
        "code" : "371254008",
        "display" : "Brown color"
      },
      {
        "code" : "54662009",
        "display" : "Green color"
      }]
    }]
  }
}

```
