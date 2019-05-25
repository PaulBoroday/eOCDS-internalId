# eOCDS-internalId

Extension to cover existing requirement to have an ability to use an internal identifier for different data entities.

This extension is adding `internalId` attribute for `tender`, `lot`, `item`, `award` and `contract`

```
{
  "ocid":"",
  "tender": {
    "id": "",
    "internalId": "",
    "lots": [
      {
        "id": "",
        "internalId": ""
      }
    ],
    "items": [
      {
        "id": "",
        "internalId": ""
      }
    ]
  },
  "awards": [
    {
      "id": "",
      "internalId": ""
    }
  ],
  "contracts": [
    {
      "id": "",
      "internalId": ""
    }
  ]
}
```
