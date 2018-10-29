# Special Requirements

> Status: Draft | [Please Provide Feedback via GitHub](https://github.com/emduk/special-requirements/issues)

## Status

This list is in a draft state, however every effort will be made in subsequent revisions to maintain the IDs associated with the concepts enumerated here.

EMD UK works as part of the [OpenActive Community Group](https://www.w3.org/community/openactive) to promote the usecases represented by this controlled vocabulary, with the intention of standardising it over time. As such, this location of this controlled vocabulary is subject to change.

## Documentation

This repository holds the [JSON-LD definition](https://data.emduk.org/special-requirements/special-requirements.jsonld) of the EMD UK Special Requirements controlled vocabulary.

This controlled vocabulary MUST be referenced within a `Concept` via `inScheme` using the URL `"https://data.emduk.org/special-requirements/special-requirements.jsonld"` (which will return the [JSON-LD definition](https://data.emduk.org/special-requirements/special-requirements.jsonld)).

Please raise requests for content or issues related to this controlled vocabulary via [GitHub](https://github.com/emduk/special-requirements/issues). 

## Example use

The example below illustrates an `"emduk:specialRequirements"` property for an `Event` that supports all defined special requirements.

```json
"emduk:specialRequirements": [
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#736f74df-0c3f-4314-9bd5-eec6b9c2f34f",
    "prefLabel": "Adult Education",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#e5db28d6-93ef-463e-8626-f143f55f619c",
    "prefLabel": "Autism",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#56ec6bb7-2272-4c7b-970f-d1af7bf94269",
    "prefLabel": "Back care",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#ba2291c0-252c-4616-a2a0-4863cb04cd25",
    "prefLabel": "Cancer support",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#15caac99-83b7-4963-8ec0-183050779a3d",
    "prefLabel": "Cardiac Rehabilitation",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#2fa48dbf-0165-433c-9b15-604afb5248b3",
    "prefLabel": "Chair based",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#20c1a0c6-cf75-4d6a-b7c3-3c083ec46ce0",
    "prefLabel": "Dementia",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#c4bceff4-39a5-4e39-b16a-873ed79bc498",
    "prefLabel": "GP Referral",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#135ff50d-c3af-4db2-a491-b68070874d21",
    "prefLabel": "Multiple Sclerosis",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#2eba5bcc-ac8b-4d1b-beeb-d62bb10e7a0d",
    "prefLabel": "Osteoporosis",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#f5c631fc-51d8-4252-89c4-e5a6e17bbfd9",
    "prefLabel": "Parkinsons",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#68dd5e97-baad-497f-8da4-4c3bcb8ca1a4",
    "prefLabel": "Post Breast Cancer",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#60bd020e-13a7-4e00-890e-89d6ad157083",
    "prefLabel": "Post Natal",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#88ce3d1a-b49c-4edc-a24e-8c3a29dbc4f3",
    "prefLabel": "Pregnancy",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#dbb8a138-3ce9-4298-9e51-9f9011d8f6e4",
    "prefLabel": "Residential Home / Day centre",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#54031d85-b037-477d-98c4-2739d0e6ef44",
    "prefLabel": "RNIB",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#b079c5db-44d9-4bf5-936d-8ac0b1ea31e7",
    "prefLabel": "Stroke",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  },
  {
    "type": "Concept",
    "id": "https://data.emduk.org/special-requirements#06b78897-6efa-431f-b76b-382de3a6b05f",
    "prefLabel": "Weight Management",
    "inScheme": "https://data.emduk.org/special-requirements/special-requirements.jsonld"
  }
]
```

## Concepts in this Vocabulary

- [Adult Education](https://data.emduk.org/special-requirements#736f74df-0c3f-4314-9bd5-eec6b9c2f34f)
- [Autism](https://data.emduk.org/special-requirements#e5db28d6-93ef-463e-8626-f143f55f619c)
- [Back care](https://data.emduk.org/special-requirements#56ec6bb7-2272-4c7b-970f-d1af7bf94269)
- [Cancer support](https://data.emduk.org/special-requirements#ba2291c0-252c-4616-a2a0-4863cb04cd25)
- [Cardiac Rehabilitation](https://data.emduk.org/special-requirements#15caac99-83b7-4963-8ec0-183050779a3d)
- [Chair based](https://data.emduk.org/special-requirements#2fa48dbf-0165-433c-9b15-604afb5248b3)
- [Dementia](https://data.emduk.org/special-requirements#20c1a0c6-cf75-4d6a-b7c3-3c083ec46ce0)
- [GP Referral](https://data.emduk.org/special-requirements#c4bceff4-39a5-4e39-b16a-873ed79bc498)
- [Multiple Sclerosis](https://data.emduk.org/special-requirements#135ff50d-c3af-4db2-a491-b68070874d21)
- [Osteoporosis](https://data.emduk.org/special-requirements#2eba5bcc-ac8b-4d1b-beeb-d62bb10e7a0d)
- [Parkinsons](https://data.emduk.org/special-requirements#f5c631fc-51d8-4252-89c4-e5a6e17bbfd9)
- [Post Breast Cancer](https://data.emduk.org/special-requirements#68dd5e97-baad-497f-8da4-4c3bcb8ca1a4)
- [Post Natal](https://data.emduk.org/special-requirements#60bd020e-13a7-4e00-890e-89d6ad157083)
- [Pregnancy](https://data.emduk.org/special-requirements#88ce3d1a-b49c-4edc-a24e-8c3a29dbc4f3)
- [Residential Home / Day centre](https://data.emduk.org/special-requirements#dbb8a138-3ce9-4298-9e51-9f9011d8f6e4)
- [RNIB](https://data.emduk.org/special-requirements#54031d85-b037-477d-98c4-2739d0e6ef44)
- [Stroke](https://data.emduk.org/special-requirements#b079c5db-44d9-4bf5-936d-8ac0b1ea31e7)
- [Weight Management](https://data.emduk.org/special-requirements#06b78897-6efa-431f-b76b-382de3a6b05f)


## Licence

The documentation and data in this repository is published under the [Creative Commons CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.

