{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Safe Drinking Water Act Safe Drinking Water Act (SDWA) Paginated Results Service",
    "_postman_id": "296e7f4d-4a36-44ce-9b69-c1a323220611",
    "description": "GET_QID is passed with a query ID corresponding to a previously run get_systems query. It then returns a Systems object containing all matching water systems. The main purpose of GET_QID is for large querysets that contain multiple pages (responsesets) of output. GET_QID allows for pagination and for the selection and sorting of columns.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "2d286dcf-f8b6-4bd5-a0c7-c8f0fa20657c",
      "name": "based-on-the-qid-obtained-from-a-get-systems-query-return-a-comma-sepated-vaule-csv-file-of-the-wate",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/sdw_rest_services.get_download?No Name=%7B%7D&output=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Based on the QID obtained from a get_systems query, return a comma sepated vaule (CSV) file of the water systems found."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "c8058ff1-5a22-4254-82af-1dd7bf5a2efd"
        }
      ]
    },
    {
      "id": "a44a2572-e0bf-40d6-a9ad-c6b138ad38e1",
      "name": "get-qid-is-passed-with-a-query-id-corresponding-to-a-previously-run-get-systems-query--it-then-retur",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/sdw_rest_services.get_qid?No Name=%7B%7D&output=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "GET_QID is passed with a query ID corresponding to a previously run get_systems query. It then returns a Systems object containing all matching water systems. The main purpose of GET_QID is for large querysets that contain multiple pages (responsesets) of output. GET_QID allows for pagination and for the selection and sorting of columns."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f1f21d96-b2b5-4c0e-9934-5ac5c8e9b5a6"
        }
      ]
    }
  ]
}