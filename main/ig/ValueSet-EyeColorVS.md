# EyeColor Value Set - ANS IG Example v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **EyeColor Value Set**

## ValueSet: EyeColor Value Set 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/[code]/ValueSet/EyeColorVS | *Version*:0.1.0 |
| Draft as of 2025-12-03 | *Computable Name*:EyeColorVS |

 
Different eye colors. 

 **References** 

* [EyeColor](StructureDefinition-EyeColor.md)

### Définition logique (CLD)

* Include ce(s) code(s) tel quil(s) est (sont) défini(s) dans [`http://snomed.info/sct`](http://www.snomed.org/)version Non précisé (utilise la dernière version provenant du serveur de terminologie)

 

### Expansion

Expansion de smt.esante.gouv.fr basée sur SNOMED CT édition 11000315107 21-Jun 2025

Ce jeu de valeur (ValueSet) contient 3 concepts

-------

 Explanation of the columns that may appear on this page: 

| | |
| :--- | :--- |
| Level | A few code lists that FHIR defines are hierarchical - each code is assigned a level. In this scheme, some codes are under other codes, and imply that the code they are under also applies |
| System | The source of the definition of the code (when the value set draws in codes defined elsewhere) |
| Code | The code (used as the code in the resource instance) |
| Display | The display (used in the*display*element of a[Coding](http://hl7.org/fhir/R4/datatypes.html#Coding)). If there is no display, implementers should not simply display the code, but map the concept into their application |
| Definition | An explanation of the meaning of the concept |
| Comments | Additional notes about how to use the code |



## Resource Content

```json
{
  "resourceType" : "ValueSet",
  "id" : "EyeColorVS",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/[code]/ValueSet/EyeColorVS",
  "version" : "0.1.0",
  "name" : "EyeColorVS",
  "title" : "EyeColor Value Set",
  "status" : "draft",
  "date" : "2025-12-03T08:52:56+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "contact" : [
    {
      "name" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
      "telecom" : [
        {
          "system" : "url",
          "value" : "https://esante.gouv.fr"
        }
      ]
    }
  ],
  "description" : "Different eye colors.",
  "jurisdiction" : [
    {
      "coding" : [
        {
          "system" : "urn:iso:std:iso:3166",
          "code" : "FR",
          "display" : "FRANCE"
        }
      ]
    }
  ],
  "compose" : {
    "include" : [
      {
        "system" : "http://snomed.info/sct",
        "concept" : [
          {
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
          }
        ]
      }
    ]
  }
}

```
