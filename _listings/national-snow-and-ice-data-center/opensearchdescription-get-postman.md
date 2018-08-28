{
  "info": {
    "name": "NSIDC Web Service Documentation Index Describes the web interface of NSIDC's data search engine",
    "_postman_id": "94ec97b6-eefc-43c6-80d6-c5d0967eaea1",
    "description": "Describes the web interface of NSIDC's data search engine",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Environment",
      "item": [
        {
          "id": "3c3bc267-a78b-48c3-85f2-f689cd4bf35f",
          "name": "facets",
          "request": {
            "url": "http://nsidc.org/api/dataset/2/Facets?count=%7B%7D&endDate=%7B%7D&facetFilters=%7B%7D&searchTerms=%7B%7D&sortKeys=%7B%7D&source=%7B%7D&spatial=%7B%7D&startDate=%7B%7D&startIndex=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "In the NSIDC Search and Arctic Data Explorer interfaces, this endpoint is used in conjunction with /OpenSearch whenever a user submits a new search. Consequently, it has the same parameters as /OpenSearch."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "526b2d6f-f324-41eb-bd1c-daee46e6fb89"
            }
          ]
        },
        {
          "id": "53582b0b-c57f-4a3d-acd1-be7b9ae473ad",
          "name": "OpenSearch.get",
          "request": {
            "url": "http://nsidc.org/api/dataset/2/OpenSearch?count=%7B%7D&endDate=%7B%7D&facetFilters=%7B%7D&searchTerms=%7B%7D&sortKeys=%7B%7D&source=%7B%7D&spatial=%7B%7D&startDate=%7B%7D&startIndex=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint uses parameters from the OpenSearch 1.1 specification, as well as parameters from the OpenSearch Geo (1.0) and SRU (1.0) extensions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6a580e64-807b-493b-8a4b-990bdfc31ab3"
            }
          ]
        },
        {
          "id": "f606df60-658f-4c7a-9e78-3cc3ac09fd18",
          "name": "OpenSearchDescription.get",
          "request": {
            "url": "http://nsidc.org/api/dataset/2/OpenSearchDescription",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the web interface of NSIDC's data search engine"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d2e237e2-75f5-48ce-aa0f-cffcf7e70e9a"
            }
          ]
        }
      ]
    }
  ]
}