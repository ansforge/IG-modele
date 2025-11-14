# Melting Pot Value Set - ANS IG Example v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Melting Pot Value Set**

## ValueSet: Melting Pot Value Set 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/[code]/ValueSet/MeltingPotVS | *Version*:0.1.0 |
| Draft as of 2025-11-14 | *Computable Name*:MeltingPotVS |

 
Melting Pot Value Set. 

 **References** 

Ce jeu de valeurs nest pas utilisé ici ; il peut être utilisé autre part (par exemple dans les spécifications et / ou implémentations qui utilisent ce contenu)

### Logical Definition (CLD)

Ce jeu de valeur (ValueSet) inclut les codes selon les règles suivantes :

* Inclut ce(s) code(s) tel quil(s) est (sont) défini(s) dans [`http://snomed.info/sct`](http://www.snomed.org/)version Not Stated (use latest from terminology server)
* Inclut ce(s) code(s) tel quil(s) est (sont) défini(s) dans [`https://interop.esante.gouv.fr/ig/fhir/[code]/CodeSystem/competence-code-system`](CodeSystem-competence-code-system.md)version 📦0.1.0 
* Inclut tous les codes définis dans [`https://interop.esante.gouv.fr/ig/fhir/[code]/CodeSystem/type-carte-code-system`](CodeSystem-type-carte-code-system.md)version 📦0.1.0

 

### Expansion

Expansion from smt.esante.gouv.fr based on:

* SNOMED CT 11000315107 edition 21-Jun 2025
* [codesystem Compétences CodeSystem v0.1.0 (CodeSystem)](CodeSystem-competence-code-system.md)
* [codesystem Type de carte v0.1.0 (CodeSystem)](CodeSystem-type-carte-code-system.md)

Ce jeu de valeur (ValueSet) contient 7 concepts

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
  "id" : "MeltingPotVS",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/[code]/ValueSet/MeltingPotVS",
  "version" : "0.1.0",
  "name" : "MeltingPotVS",
  "title" : "Melting Pot Value Set",
  "status" : "draft",
  "date" : "2025-11-14T15:31:38+00:00",
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
  "description" : "Melting Pot Value Set.",
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
            "display" : "Blue color (qualifier value)"
          },
          {
            "code" : "371254008"
          }
        ]
      },
      {
        "system" : "https://interop.esante.gouv.fr/ig/fhir/[code]/CodeSystem/competence-code-system",
        "concept" : [
          {
            "code" : "C01"
          }
        ]
      },
      {
        "system" : "https://interop.esante.gouv.fr/ig/fhir/[code]/CodeSystem/type-carte-code-system"
      }
    ]
  }
}

```
