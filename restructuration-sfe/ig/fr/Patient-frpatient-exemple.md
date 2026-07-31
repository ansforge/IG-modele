# frpatient-exemple - ANS IG Example v0.1.0

## Exemple Patient: frpatient-exemple

-------

**French**

-------

Profil: [Patient français](StructureDefinition-fr-patient.md)

JEANNE MARIE DARK Female, Date de Naissance :1939-08-13 ( urn:oid:1.2.250.1.213.1.4.8#239088815400243)

-------



## Resource Content

```json
{
  "resourceType" : "Patient",
  "id" : "frpatient-exemple",
  "meta" : {
    "profile" : ["https://interop.esante.gouv.fr/ig/fhir/modele/StructureDefinition/fr-patient"]
  },
  "identifier" : [{
    "system" : "urn:oid:1.2.250.1.213.1.4.8",
    "value" : "239088815400243"
  }],
  "name" : [{
    "family" : "DARK",
    "given" : ["JEANNE MARIE"]
  }],
  "gender" : "female",
  "birthDate" : "1939-08-13"
}

```
