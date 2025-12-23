# Compétences CodeSystem - ANS IG Example v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Compétences CodeSystem**

## CodeSystem: Compétences CodeSystem 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/[code]/CodeSystem/competence-code-system | *Version*:0.1.0 |
| Draft as of 2025-12-23 | *Computable Name*:CompetenceCS |

 
Compétences des professionnels de santé. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* [MeltingPotVS](ValueSet-MeltingPotVS.md)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "competence-code-system",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/[code]/CodeSystem/competence-code-system",
  "version" : "0.1.0",
  "name" : "CompetenceCS",
  "title" : "Compétences CodeSystem",
  "status" : "draft",
  "date" : "2025-12-23T15:01:44+00:00",
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
  "description" : "Compétences des professionnels de santé.",
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
  "content" : "complete",
  "count" : 43,
  "concept" : [
    {
      "code" : "C01",
      "display" : "Anatomie et Cytologie pathologiques humaines",
      "definition" : "Anatomie, Cyto patho;Anatomie et Cytologie pathologiques humaines"
    },
    {
      "code" : "C03",
      "display" : "Anesthésie-réanimation",
      "definition" : "Anesthésie-réanim;Anesthésie-réanimation"
    },
    {
      "code" : "C05",
      "display" : "Médecine appliquée aux sports",
      "definition" : "Méd appliquée sports;Médecine appliquée aux sports"
    },
    {
      "code" : "C07",
      "display" : "Cardiologie",
      "definition" : "Cardiologie;Cardiologie"
    },
    {
      "code" : "C09",
      "display" : "Chirurgie plastique, reconstructrice et esthétique",
      "definition" : "Chir plast reco esth;Chirurgie plastique, reconstructrice et esthétique"
    },
    {
      "code" : "C10",
      "display" : "Chirurgie maxillo-faciale;Chirurgie maxillo-faciale;Chirurgie maxillo-faciale"
    },
    {
      "code" : "C11",
      "display" : "Chirurgie thoracique",
      "definition" : "Chirurgie thoracique;Chirurgie thoracique"
    },
    {
      "code" : "C12",
      "display" : "Chirurgie orthopédique",
      "definition" : "Chirurgie orthopédique;Chirurgie orthopédique"
    },
    {
      "code" : "C13",
      "display" : "Urologie",
      "definition" : "Urologie;Urologie"
    },
    {
      "code" : "C15",
      "display" : "Dermato-vénéréologie",
      "definition" : "Dermato-vénéréologie;Dermato-vénéréologie"
    },
    {
      "code" : "C20",
      "display" : "Hémobiologie",
      "definition" : "Hémobiologie;Hémobiologie"
    },
    {
      "code" : "C23",
      "display" : "Gynécologie médicale et Obstétrique",
      "definition" : "Gynéco-médicale, Obstétrique;Gynécologie médicale et Obstétrique"
    },
    {
      "code" : "C25",
      "display" : "Gynécologie médicale",
      "definition" : "Gynécologie médicale;Gynécologie médicale"
    },
    {
      "code" : "C27",
      "display" : "Obstétrique",
      "definition" : "Obstétrique;Obstétrique"
    },
    {
      "code" : "C29",
      "display" : "Maladies de l'appareil digestif",
      "definition" : "Maladies appareil digestif;Maladies de l'appareil digestif"
    },
    {
      "code" : "C30",
      "display" : "Néphrologie",
      "definition" : "Néphrologie;Néphrologie"
    },
    {
      "code" : "C31",
      "display" : "Médecine exotique",
      "definition" : "Médecine exotique;Médecine exotique"
    },
    {
      "code" : "C33",
      "display" : "Allergologie",
      "definition" : "Allergologie;Allergologie"
    },
    {
      "code" : "C34",
      "display" : "Angéiologie",
      "definition" : "Angéiologie;Angéiologie"
    },
    {
      "code" : "C35",
      "display" : "Cancérologie",
      "definition" : "Cancérologie;Cancérologie"
    },
    {
      "code" : "C36",
      "display" : "Diabétologie-nutrition",
      "definition" : "Diabéto-nutrition;Diabétologie-nutrition"
    },
    {
      "code" : "C37",
      "display" : "Endocrinologie",
      "definition" : "Endocrinologie;Endocrinologie"
    },
    {
      "code" : "C38",
      "display" : "Maladies du sang",
      "definition" : "Maladies du sang;Maladies du sang"
    },
    {
      "code" : "C39",
      "display" : "Réanimation",
      "definition" : "Réanimation;Réanimation"
    },
    {
      "code" : "C40",
      "display" : "Médecine légale",
      "definition" : "Médecine légale;Médecine légale"
    },
    {
      "code" : "C41",
      "display" : "Médecine du travail",
      "definition" : "Médecine du travail;Médecine du travail"
    },
    {
      "code" : "C43",
      "display" : "Neurologie",
      "definition" : "Neurologie;Neurologie"
    },
    {
      "code" : "C45",
      "display" : "Neuro-chirurgie",
      "definition" : "Neuro-chirurgie;Neuro-chirurgie"
    },
    {
      "code" : "C47",
      "display" : "Neuro-psychiatrie",
      "definition" : "Neuro-psychiatrie;Neuro-psychiatrie"
    },
    {
      "code" : "C51",
      "display" : "Pédiatrie",
      "definition" : "Pédiatrie;Pédiatrie"
    },
    {
      "code" : "C52",
      "display" : "Phoniatrie",
      "definition" : "Phoniatrie;Phoniatrie"
    },
    {
      "code" : "C54",
      "display" : "Pneumologie",
      "definition" : "Pneumologie;Pneumologie"
    },
    {
      "code" : "C57",
      "display" : "Psychiatrie",
      "definition" : "Psychiatrie;Psychiatrie"
    },
    {
      "code" : "C58",
      "display" : "Psychiatrie, option enfant et adolescent",
      "definition" : "Psychiatrie, opt enfant et ado;Psychiatrie, option enfant et adolescent"
    },
    {
      "code" : "C60",
      "display" : "Médecine physique et de réadaptation",
      "definition" : "Médecine physique, réadapt;Médecine physique et de réadaptation"
    },
    {
      "code" : "C62",
      "display" : "Rhumatologie",
      "definition" : "Rhumatologie;Rhumatologie"
    },
    {
      "code" : "C68",
      "display" : "Chirurgie pédiatrique",
      "definition" : "Chirurgie pédiatrique;Chirurgie pédiatrique"
    },
    {
      "code" : "C69",
      "display" : "Médecine nucléaire",
      "definition" : "Médecine nucléaire;Médecine nucléaire"
    },
    {
      "code" : "C71",
      "display" : "Médecine thermale",
      "definition" : "Médecine thermale;Médecine thermale"
    },
    {
      "code" : "C72",
      "display" : "Génétique médicale",
      "definition" : "Génétique médicale;Génétique médicale"
    },
    {
      "code" : "C75",
      "display" : "Endocrinologie et Maladies métaboliques",
      "definition" : "Endocrin, Maladies métaboliq;Endocrinologie et Maladies métaboliques"
    },
    {
      "code" : "C76",
      "display" : "Orthopédie dento-maxillo-faciale",
      "definition" : "Orthopédie dento-maxilo-fac;Orthopédie dento-maxillo-faciale"
    },
    {
      "code" : "C83",
      "display" : "Chirurgie de la face et du cou",
      "definition" : "Chirurgie face et cou;Chirurgie de la face et du cou"
    }
  ]
}

```
