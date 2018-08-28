{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Effluent Charting and Reporting Summary Effluent Chart Service",
    "_postman_id": "9c551726-bae3-4b17-bad9-886b5f2d18a9",
    "description": "Summary of compliance status each outfall and parameter for one NPDES permit. Provides the current compliance status and overall compliance status for the date range of interest. This service supports the Summary Matrix on the Effluent Charts.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "fd82080a-657d-43df-b2fb-736a290e5155",
      "name": "downloads-tabular-discharge-monitoring-report-dmr-and-compliance-data-for-one-npdes-permit-as-a-csv-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/eff_rest_services.download_effluent_chart?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Downloads tabular Discharge Monitoring Report (DMR) and compliance data for one NPDES permit as a CSV."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "83f3f624-ab55-4757-82be-c589f54b720e"
        }
      ]
    },
    {
      "id": "532b5a91-8960-401b-abfd-b6b115fdea84",
      "name": "discharge-monitoring-report-dmr-data-supporting-each-effluent-chart-for-one-npdes-permit--includes-d",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/eff_rest_services.get_effluent_chart?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Discharge Monitoring Report (DMR) data supporting each effluent chart for one NPDES permit. Includes Discharge Monitoring Reports and NPDES Violations."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "67833df5-2757-4bac-acb9-2bebbbf71fed"
        }
      ]
    },
    {
      "id": "8aa6dae4-8a61-4ca0-9a7a-65af6c3ce42e",
      "name": "summary-of-compliance-status-each-outfall-and-parameter-for-one-npdes-permit--provides-the-current-c",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/eff_rest_services.get_summary_chart?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Summary of compliance status each outfall and parameter for one NPDES permit. Provides the current compliance status and overall compliance status for the date range of interest. This service supports the Summary Matrix on the Effluent Charts."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "17ebea11-c233-47a9-b876-fb5e2ffa0ce6"
        }
      ]
    }
  ]
}