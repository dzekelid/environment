{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case Search Enforcement Case Paginated Results Service",
    "_postman_id": "6f57b39d-8e8b-45fa-bb71-eef4f0a1d415",
    "description": "GET_QID is passed with a query ID corresponding to a previously run get_cases query. It then returns a CASES object containing all matching cases. The main purpose of GET_QID is for large querysets that contain multiple pages (responsesets) of output. GET_QID allows for pagination and for the selection and sorting of columns.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "34e5ad6b-9219-4c67-affa-fc31e46878c9",
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
          "id": "ea46e2f5-5d1b-4a82-902b-d252efcad1e3"
        }
      ]
    },
    {
      "id": "ff9fb25e-0b43-4f6a-80fa-5ba39b10787b",
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
          "id": "bec9ec05-8e67-418d-83bf-3232d60f7adf"
        }
      ]
    },
    {
      "id": "5d3e543a-b9dc-4096-a9f8-e4de1228d73a",
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
          "id": "1e537587-a47b-4db2-80c1-cd0c75602b11"
        }
      ]
    },
    {
      "id": "5e9d343e-c844-4536-92cb-b3c80799f46b",
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
          "id": "36a2af6c-f7de-4669-948f-f4dfe3105ddd"
        }
      ]
    },
    {
      "id": "8f28dee5-2de5-4279-90df-1c414e8873b2",
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
          "id": "dbeabb6b-e18d-4b40-b226-06d0e8f33cc7"
        }
      ]
    },
    {
      "id": "050e2ea5-e2f4-4123-a4ed-a8da1f09b012",
      "name": "get-qid-is-passed-with-a-query-id-corresponding-to-a-previously-run-get-cases-query--it-then-returns",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/case_rest_services.get_qid?No Name=%7B%7D&output=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "GET_QID is passed with a query ID corresponding to a previously run get_cases query. It then returns a CASES object containing all matching cases. The main purpose of GET_QID is for large querysets that contain multiple pages (responsesets) of output. GET_QID allows for pagination and for the selection and sorting of columns."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "a310bdec-b81e-4261-a6bb-91768d08c782"
        }
      ]
    }
  ]
}