{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case Search Enforcement Case Metadata Service",
    "_postman_id": "476e14dd-6588-41f5-bb1e-8b91b84dc787",
    "description": "Returns the JSON Object Name and ColumnId for usage with the qcolumns parameter for get_cases endpoint.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "fdffb95e-5d5c-4eeb-a188-9368dce98aca",
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
          "id": "7f2cfa11-6add-4d23-8dfd-baccf0c10847"
        }
      ]
    },
    {
      "id": "159d4697-c9e8-40c3-ac51-790fecf06ae0",
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
          "id": "c641f14e-5d69-4eaf-9c4a-0508466e2bc7"
        }
      ]
    },
    {
      "id": "dd7f950d-814b-439d-8eb1-1f50164f562a",
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
          "id": "2b2e8b6c-5b04-4227-b512-20e70cb7aa50"
        }
      ]
    },
    {
      "id": "7c7f10f3-0bbb-426d-8295-45c9039848cb",
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
          "id": "3d8dd035-8e8e-4fc2-8704-a59d4bdbae3a"
        }
      ]
    },
    {
      "id": "b6e4d400-1e9a-42e0-882a-23dd5b93d3b2",
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
          "id": "c70c8368-1da7-4fb6-9cb1-7806aee057c0"
        }
      ]
    },
    {
      "id": "a5066f46-d0ce-420a-bb47-0f771df2d088",
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
          "id": "f1509c11-3e76-4a00-bdec-6b53caa04cc3"
        }
      ]
    },
    {
      "id": "a0d3fe4d-5332-4d54-a032-08ebbcbad499",
      "name": "returns-the-json-object-name-and-columnid-for-usage-with-the-qcolumns-parameter-for-get-cases-endpoi",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/case_rest_services.metadata?No Name=%7B%7D&output=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Returns the JSON Object Name and ColumnId for usage with the qcolumns parameter for get_cases endpoint."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "b5a358e8-c651-41b8-a160-df822fa13e83"
        }
      ]
    }
  ]
}