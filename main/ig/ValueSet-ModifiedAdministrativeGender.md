# ModifiedAdministrativeGender - ANS IG Example v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ModifiedAdministrativeGender**

## ValueSet: ModifiedAdministrativeGender 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/[code]/ValueSet/ModifiedAdministrativeGender | *Version*:0.1.0 |
| Draft as of 2025-11-14 | *Computable Name*:ModifiedAdministrativeGender |

 
AdministrativeGender without unknown code 

 **References** 

* [Patient français](StructureDefinition-fr-patient.md)

### Logical Definition (CLD)

Ce jeu de valeur (ValueSet) inclut les codes selon les règles suivantes :

* Inclut tous les codes définis dans [`http://hl7.org/fhir/administrative-gender`](http://hl7.org/fhir/R4/codesystem-administrative-gender.html)version 📦4.0.1

Ce jeu de valeur (ValueSet) exclut les codes selon les règles suivantes :

* Exclude ce(s) code(s) tel quil(s) est (sont) défini(s) dans [`http://hl7.org/fhir/administrative-gender`](http://hl7.org/fhir/R4/codesystem-administrative-gender.html)version 📦4.0.1

 

### Expansion

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
  "id" : "ModifiedAdministrativeGender",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/[code]/ValueSet/ModifiedAdministrativeGender",
  "version" : "0.1.0",
  "name" : "ModifiedAdministrativeGender",
  "title" : "ModifiedAdministrativeGender",
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
  "description" : "AdministrativeGender without unknown code",
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
        "system" : "http://hl7.org/fhir/administrative-gender"
      }
    ],
    "exclude" : [
      {
        "system" : "http://hl7.org/fhir/administrative-gender",
        "concept" : [
          {
            "code" : "unknown"
          }
        ]
      }
    ]
  }
}

```
