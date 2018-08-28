{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case Search Enforcement Case Map Service",
    "_postman_id": "eee08193-77d9-4428-81cc-58298d8d0f1a",
    "description": "The purpose of the GET_MAP service is to display facility coordinates and facility clusters related to a get_cases query. Currently, the maximum number of coordinates returned is 500. GET_MAP performs automatic clustering at the state, county, and zip code levels to maximize the number of coordinates returned.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "aea91aab-5193-48d2-8847-d409b0d23181",
      "name": "the-get-case-report-service-endpoint-returns-a-complex-object-of-civil-enforcement-case-details-base",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/case_rest_services.get_case_report?No Name=%7B%7D&output=%7B%7D&p_id=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "The get_case_report service endpoint returns a complex object of civil enforcement case details based on the provided case id."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "b2684b75-a9bd-4257-87fb-d0a3a6fa8e78"
        }
      ]
    },
    {
      "id": "a7a46447-199c-4cb8-94ce-eda91b429566",
      "name": "the-get-cases-service-end-point-searches-for-civil-enforcement-and-criminal-cases-based-on-the-provi",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/case_rest_services.get_cases?No Name=%7B%7D&output=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "The get_cases service end point searches for civil enforcement and criminal cases based on the provided selection criteria."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "e8fca2ff-549c-48e8-889f-92d7084a011b"
        }
      ]
    },
    {
      "id": "e62b5887-58c0-4a6e-9ba4-ae7e21d42d89",
      "name": "the-get-crcase-report-service-end-point-returns-a-complex-object-of-criminal-case-detials-based-on-t",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/case_rest_services.get_crcase_report?No Name=%7B%7D&output=%7B%7D&p_id=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "The get_crcase_report service end point returns a complex object of criminal case detials based on the provided criminal case id."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "67743401-7d58-4c5e-b663-9bfd5540eb9c"
        }
      ]
    },
    {
      "id": "9dfe4794-6825-4227-a7b6-b7dcbe957e1a",
      "name": "based-on-the-qid-obtained-from-a-get-cases-query-return-a-comma-sepated-vaule-csv-file-of-the-cases-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/case_rest_services.get_download?No Name=%7B%7D&output=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Based on the QID obtained from a get_cases query, return a comma sepated vaule (CSV) file of the cases found."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "4b67f35a-775d-41f3-ae95-0b7d08d3a796"
        }
      ]
    },
    {
      "id": "6e6e4489-8647-4a3a-8afa-b9bc7b5aeedc",
      "name": "the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/case_rest_services.get_map?No Name=%7B%7D&output=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "The purpose of the GET_MAP service is to display facility coordinates and facility clusters related to a get_cases query. Currently, the maximum number of coordinates returned is 500. GET_MAP performs automatic clustering at the state, county, and zip code levels to maximize the number of coordinates returned."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "8174aa5d-d4fc-4212-bee6-e8107e3e7985"
        }
      ]
    }
  ]
}