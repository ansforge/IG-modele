# Patient français - ANS IG Example v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Patient français**

## Resource Profile: Patient français 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/[code]/StructureDefinition/fr-patient | *Version*:0.1.0 |
| Draft as of 2025-12-19 | *Computable Name*:FrPatient |

 
Description du patient français 

**Utilisations:**

* Exemples pour ce Profil: [Patient/frpatient-exemple](Patient-frpatient-exemple.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/ans.fhir.fr.[code]|current/StructureDefinition/fr-patient)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-fr-patient.csv), [Excel](StructureDefinition-fr-patient.xlsx), [Schematron](StructureDefinition-fr-patient.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "fr-patient",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/[code]/StructureDefinition/fr-patient",
  "version" : "0.1.0",
  "name" : "FrPatient",
  "title" : "Patient français",
  "status" : "draft",
  "date" : "2025-12-19T08:24:59+00:00",
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
  "description" : "Description du patient français",
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
  "fhirVersion" : "4.0.1",
  "mapping" : [
    {
      "identity" : "rim",
      "uri" : "http://hl7.org/v3",
      "name" : "RIM Mapping"
    },
    {
      "identity" : "cda",
      "uri" : "http://hl7.org/v3/cda",
      "name" : "CDA (R2)"
    },
    {
      "identity" : "w5",
      "uri" : "http://hl7.org/fhir/fivews",
      "name" : "FiveWs Pattern Mapping"
    },
    {
      "identity" : "v2",
      "uri" : "http://hl7.org/v2",
      "name" : "HL7 v2 Mapping"
    },
    {
      "identity" : "loinc",
      "uri" : "http://loinc.org",
      "name" : "LOINC code for the element"
    }
  ],
  "kind" : "resource",
  "abstract" : false,
  "type" : "Patient",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/Patient|4.0.1",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Patient",
        "path" : "Patient"
      },
      {
        "id" : "Patient.extension",
        "path" : "Patient.extension",
        "slicing" : {
          "discriminator" : [
            {
              "type" : "value",
              "path" : "url"
            }
          ],
          "ordered" : false,
          "rules" : "open"
        }
      },
      {
        "id" : "Patient.extension:eyecolor",
        "path" : "Patient.extension",
        "sliceName" : "eyecolor",
        "short" : "Eye color of the patient",
        "min" : 0,
        "max" : "1",
        "type" : [
          {
            "code" : "Extension",
            "profile" : [
              "https://interop.esante.gouv.fr/ig/fhir/[code]/StructureDefinition/EyeColor|0.1.0"
            ]
          }
        ],
        "mustSupport" : true
      },
      {
        "id" : "Patient.identifier",
        "path" : "Patient.identifier",
        "slicing" : {
          "discriminator" : [
            {
              "type" : "pattern",
              "path" : "system"
            }
          ],
          "description" : "Slice based on the identifier.system pattern",
          "ordered" : false,
          "rules" : "open"
        },
        "min" : 1
      },
      {
        "id" : "Patient.identifier:INS",
        "path" : "Patient.identifier",
        "sliceName" : "INS",
        "min" : 1,
        "max" : "1",
        "mustSupport" : true
      },
      {
        "id" : "Patient.identifier:INS.system",
        "path" : "Patient.identifier.system",
        "min" : 1,
        "patternUri" : "urn:oid:1.2.250.1.213.1.4.8"
      },
      {
        "id" : "Patient.gender",
        "path" : "Patient.gender",
        "short" : "male | female | other",
        "binding" : {
          "strength" : "required",
          "valueSet" : "https://interop.esante.gouv.fr/ig/fhir/[code]/ValueSet/ModifiedAdministrativeGender|0.1.0"
        }
      }
    ]
  }
}

```
