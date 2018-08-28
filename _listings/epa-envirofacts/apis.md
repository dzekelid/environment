---
name: EPA Envirofacts
x-slug: epa-envirofacts
description: 'EPAs purpose is to ensure that:    -  all Americans are protected from
  significant risks to human health and the environment where they live, learn and
  work;    -  national efforts to reduce environmental risk are based on the best
  available scientifi...'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
x-kinRank: "8"
x-alexaRank: "5166"
tags: Environment
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/apis.md
specificationVersion: "0.14"
apis:
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - All Data - Combined
    ECHO Metadata Service
  x-api-slug: echo-rest-services-metadata-get
  description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
    parameter for get_qid, get_facility_info and other service endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-metadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-metadata-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - All Data - Combined
    ECHO Paginated Results Service
  x-api-slug: echo-rest-services-get-qid-get
  description: GET_QID is passed with a query ID corresponding to a previously run
    get_facilities query. It then returns a Facility object containing all matching
    facilities. The main purpose of GET_QID is for large querysets that contain multiple
    pages (responsesets) of output. GET_QID allows for pagination and for the selection
    and sorting of columns.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-qid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-qid-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - All Data - Combined
    ECHO Map Service
  x-api-slug: echo-rest-services-get-map-get
  description: The purpose of the GET_MAP service is to display facility coordinates
    and facility clusters related to a get_facilities facility query. Currently, the
    maximum number of coordinates returned is 500. GET_MAP performs automatic clustering
    at the state, county, and zip code levels to maximize the number of coordinates
    returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-map-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-map-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - All Data - Combined
    ECHO Info Clusters Service
  x-api-slug: echo-rest-services-get-info-clusters-get
  description: Based on the QID obtained from a clustered get_facility_info query,
    download cluster facility information as either a CSV or GEOJSON file.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-info-clusters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-info-clusters-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - All Data - Combined
    ECHO GeoJSON Service
  x-api-slug: echo-rest-services-get-geojson-get
  description: Based on the QID obtained from a get_facilities or get_facility_info
    query, return GeoJSON of the facilities found.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-geojson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-geojson-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - All Data - Combined
    ECHO Facility Enhanced Search Service
  x-api-slug: echo-rest-services-get-facility-info-get
  description: Returns either an array of Facilities or an array of Clusters that
    meet the specified search criteria.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-facility-info-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-facility-info-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - All Data - Combined
    ECHO Facility Search Service
  x-api-slug: echo-rest-services-get-facilities-get
  description: Validates query search parameters and returns query identifier.  Use
    the responseset parameter to set the page size
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-facilities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-facilities-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - All Data - Combined
    ECHO Download Data Service
  x-api-slug: echo-rest-services-get-download-get
  description: Based on the QID obtained from a get_facilities or get_facility_info
    query, return a comma sepated vaule (CSV) file of the facilities found.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-download-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/echo-rest-services-get-download-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Air Act
    - Clean Air Act Metadata Service
  x-api-slug: air-rest-services-metadata-get
  description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
    parameter for get_qid, get_facility_info and other service endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-metadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-metadata-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Air Act
    - Clean Air Act Search by Query ID
  x-api-slug: air-rest-services-get-qid-get
  description: GET_QID is passed with a query ID corresponding to a previously run
    get_facilities query. It then returns a Facility object containing all matching
    facilities. The main purpose of GET_QID is for large querysets that contain multiple
    pages (responsesets) of output. GET_QID allows for pagination and for the selection
    and sorting of columns.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-qid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-qid-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Air Act
    - Clean Air Act Map Service
  x-api-slug: air-rest-services-get-map-get
  description: The purpose of the GET_MAP service is to display facility coordinates
    and facility clusters related to a get_facilities facility query. Currently, the
    maximum number of coordinates returned is 500. GET_MAP performs automatic clustering
    at the state, county, and zip code levels to maximize the number of coordinates
    returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-map-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-map-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Air Act
    - Clean Air Act Info Clusters Service
  x-api-slug: air-rest-services-get-info-clusters-get
  description: Based on the QID obtained from a clustered get_facility_info query,
    download cluster facility information as either a CSV or GEOJSON file.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-info-clusters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-info-clusters-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Air Act
    - Clean Air Act GeoJSON Service
  x-api-slug: air-rest-services-get-geojson-get
  description: Based on the QID obtained from a get_facilities or get_facility_info
    query, return GeoJSON of the facilities found.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-geojson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-geojson-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Air Act
    - Clean Air Act Facility Enhanced Search
  x-api-slug: air-rest-services-get-facility-info-get
  description: Returns either an array of Facilities or an array of Clusters that
    meet the specified search criteria.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-facility-info-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-facility-info-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Air Act
    - Clean Air Act Facility Search
  x-api-slug: air-rest-services-get-facilities-get
  description: Validates query search parameters and returns query identifier.  Use
    the responseset parameter to set the page size
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-facilities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-facilities-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Air Act
    - Clean Air Act Download Data Service
  x-api-slug: air-rest-services-get-download-get
  description: Based on the QID obtained from a get_facilities or get_facility_info
    query, return a comma sepated vaule (CSV) file of the facilities found.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-download-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/air-rest-services-get-download-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - ECHO WBD Name Lookup Service
  x-api-slug: rest-lookups-wbd-name-lu-get
  description: USGS Watershed Boundary Dataset (WBD) Code lookup based on a supplied
    WBD Name and Watershed Level
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-wbd-name-lu-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-wbd-name-lu-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - ECHO WBD Code Lookup Service
  x-api-slug: rest-lookups-wbd-code-lu-get
  description: USGS Watershed Boundary Dataset (WBD) Name lookup based on a supplied
    WBD Code and Watershed Level
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-wbd-code-lu-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-wbd-code-lu-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - ECHO NPDES Parameters Lookup Service
  x-api-slug: rest-lookups-npdes-parameters-get
  description: ICIS Limit Parameter Code and Name lookup based on the supply of a
    partial parameter name. (NPDES = National Pollutant Discharge Elimination System)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-npdes-parameters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-npdes-parameters-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - ECHO NAICS Codes Lookup Service
  x-api-slug: rest-lookups-naics-codes-get
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-naics-codes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-naics-codes-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - ECHO ICIS Law Sections Lookup Service
  x-api-slug: rest-lookups-icis-law-sections-get
  description: Returns the ICIS Law Section Descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-icis-law-sections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-icis-law-sections-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - ECHO ICIS NPDES Inspection Types Lookup Service
  x-api-slug: rest-lookups-icis-inspection-types-get
  description: Returns the ICIS NPDES Compliance Monitoring Type Code and Description.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-icis-inspection-types-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-icis-inspection-types-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - ECHO Federal Agency Lookup Service
  x-api-slug: rest-lookups-federal-agencies-get
  description: Look up Federal Agency Code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-federal-agencies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-federal-agencies-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - ECHO CWA Pollutants Lookup Service
  x-api-slug: rest-lookups-cwa-pollutants-get
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-cwa-pollutants-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-cwa-pollutants-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - ECHO CWA Parameter Lookup Service
  x-api-slug: rest-lookups-cwa-parameters-get
  description: Look up Clean Water Act parameter codes and descriptions in the Integrated
    Compliance Information System - National Pollutant Discharge Elimination System
    (ICIS-NPDES) by code or term.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-cwa-parameters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-cwa-parameters-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - ECHO BP Tribes Lookup Service
  x-api-slug: rest-lookups-bp-tribes-get
  description: Returns the EPA Standard Indian Tribes and Native Alaskan Villages
    tribal_id and tribe_name.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-bp-tribes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-bp-tribes-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - Clean Water Act (CWA) Metadata Service
  x-api-slug: cwa-rest-services-metadata-get
  description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
    parameter for get_qid, get_facility_info and other service endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-metadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-metadata-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - Clean Water Act (CWA) Paginated Results Service
  x-api-slug: cwa-rest-services-get-qid-get
  description: GET_QID is passed with a query ID corresponding to a previously run
    get_facilities query. It then returns a Facility object containing all matching
    facilities. The main purpose of GET_QID is for large querysets that contain multiple
    pages (responsesets) of output. GET_QID allows for pagination and for the selection
    and sorting of columns.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-qid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-qid-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - Clean Water Act (CWA) Map Service
  x-api-slug: cwa-rest-services-get-map-get
  description: The purpose of the GET_MAP service is to display facility coordinates
    and facility clusters related to a get_facilities facility query. Currently, the
    maximum number of coordinates returned is 500. GET_MAP performs automatic clustering
    at the state, county, and zip code levels to maximize the number of coordinates
    returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-map-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-map-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - Clean Water Act (CWA) Info Clusters Service
  x-api-slug: cwa-rest-services-get-info-clusters-get
  description: Based on the QID obtained from a clustered get_facility_info query,
    download cluster facility information as either a CSV or GEOJSON file.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-info-clusters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-info-clusters-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - Clean Water Act (CWA) Download Data Service
  x-api-slug: cwa-rest-services-get-geojson-get
  description: Based on the QID obtained from a get_facilities or get_facility_info
    query, return a comma sepated vaule (CSV) file of the facilities found.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-geojson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-geojson-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - Clean Water Act (CWA) Facility Enhanced Search Service
  x-api-slug: cwa-rest-services-get-facility-info-get
  description: Returns either an array of Facilities or an array of Clusters that
    meet the specified search criteria.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-facility-info-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-facility-info-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - Clean Water Act (CWA) Facility Search Service
  x-api-slug: cwa-rest-services-get-facilities-get
  description: Validates query search parameters and returns query identifier.  Use
    the responseset parameter to set the page size
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-facilities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-facilities-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services - Clean Water Act (CWA) GeoJSON Service
  x-api-slug: cwa-rest-services-get-download-get
  description: Based on the QID obtained from a get_facilities or get_facility_info
    query, return GeoJSON of the facilities found.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-download-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/cwa-rest-services-get-download-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Water Quality Service
  x-api-slug: dfr-rest-services-get-water-quality-get
  description: This procedure obtains data for the Water Quality section of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-water-quality-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-water-quality-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Tribes Service
  x-api-slug: dfr-rest-services-get-tribes-get
  description: This procedure obtains data for the Tribes and Reservations section
    of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-tribes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-tribes-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report TRI Releases Service
  x-api-slug: dfr-rest-services-get-tri-releases-get
  description: This procedrue obtains data for the TRI Releases section of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-tri-releases-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-tri-releases-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report TRI History Service
  x-api-slug: dfr-rest-services-get-tri-history-get
  description: This procedure obtains data for the TRI History section of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-tri-history-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-tri-history-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Spatial Metadata Service
  x-api-slug: dfr-rest-services-get-spatial-metadata-get
  description: Returns an object with the facility coordinate spatial metadata.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-spatial-metadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-spatial-metadata-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report SIC Code Service
  x-api-slug: dfr-rest-services-get-sic-codes-get
  description: This procedure obtains data for the Facility SIC Codes section in Facility/System
    Characteristics of the Detailed Facility Report.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-sic-codes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-sic-codes-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report SDWIS Compliance Service
  x-api-slug: dfr-rest-services-get-sdwis-compliance-get
  description: This procedure obtains data for the SDWA Compliance section of the
    DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-sdwis-compliance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-sdwis-compliance-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report SDWA Violations Service
  x-api-slug: dfr-rest-services-get-sdwa-violations-get
  description: This procedure obtains data for the SDWA Violations section of the
    DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-sdwa-violations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-sdwa-violations-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report SDWA Sanitary Site Visits Service
  x-api-slug: dfr-rest-services-get-sdwa-site-visits-get
  description: This procedure obtains data for the SDWA, Sanitary Site Visits section
    of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-sdwa-site-visits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-sdwa-site-visits-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report SDWA Sanitary Surveys Service
  x-api-slug: dfr-rest-services-get-sdwa-sanitary-surveys-get
  description: This procedure obtains data for the SDWA, Sanitary Surveys section
    of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-sdwa-sanitary-surveys-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-sdwa-sanitary-surveys-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report SDWA Lead and Copper Service
  x-api-slug: dfr-rest-services-get-sdwa-lead-and-copper-get
  description: This procedure obtains data for the SDWA, Lead and Copper Rule section
    of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-sdwa-lead-and-copper-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-sdwa-lead-and-copper-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report RCRA Compliance Service
  x-api-slug: dfr-rest-services-get-rcra-compliance-get
  description: This procedure obtains data for the RCRA Compliance section of the
    DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-rcra-compliance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-rcra-compliance-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Permits Service
  x-api-slug: dfr-rest-services-get-permits-get
  description: |-
    This procedure obtains data for the following sections of the Detailed Facility Report.
    > Facility Information (FRS) in the Facility Summary.
    > Regulatory Interests in the Facility Summary.
    > Also Reports in the Facility Summary.
    > Facility/System Characteristics in Facility/System Characteristics.
    > Facility Contact Information in Facility/System Characteristics.
    > Facility SIC Codes in Facility/System Characteristics section.
    > Facility NAICS Codes in Facility/System Characteristics section.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-permits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-permits-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Notices Service
  x-api-slug: dfr-rest-services-get-notices-get
  description: This procedure obtains data for the Notices/Informal Actions section
    of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-notices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-notices-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Permits by Statute Service
  x-api-slug: dfr-rest-services-get-nnnpermits-get
  description: This procedure obtains data for the Permits by Statute section of the
    DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-nnnpermits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-nnnpermits-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report NAICS Code Service
  x-api-slug: dfr-rest-services-get-naics-get
  description: This procedure obtains data for the Facility NAICS Codes section in
    Facility/System Characteristics of the Detailed Facility Report.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-naics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-naics-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Map Service
  x-api-slug: dfr-rest-services-get-map-get
  description: Returns an object with the facility's latitude and longitude coordinates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-map-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-map-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Inspections Summary Service
  x-api-slug: dfr-rest-services-get-inspections-get
  description: This procedure obtains data for Enforcement and Compliance Summary
    Section of the Detailed Facility report.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-inspections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-inspections-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report ICIS Formal Actions Service
  x-api-slug: dfr-rest-services-get-icis-formal-actions-get
  description: This procedure obtains data for the Integrated Compliance Information
    System, Formal Enforcement Actions section of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-icis-formal-actions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-icis-formal-actions-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Formal Actions Service
  x-api-slug: dfr-rest-services-get-formal-actions-get
  description: This procedure obtains data for the Formal Enforcement Actions section
    of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-formal-actions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-formal-actions-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Enforcement Summary Service
  x-api-slug: dfr-rest-services-get-enforcement-summary-get
  description: This procedure obtains data for the Enforcement and Compliance Summary
    in the Facility Summary section of the Detailed Facility Report.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-enforcement-summary-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-enforcement-summary-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Service
  x-api-slug: dfr-rest-services-get-dfr-get
  description: This procedure is the overall service for the Detailed Facility Report.
    It returns all of the data displayed in the DFR web report by invoking individual
    procedures that each return a targeted portion of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-dfr-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-dfr-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Demographics Report Service
  x-api-slug: dfr-rest-services-get-demographics-get
  description: Returns a complex object with Demographics from the 2010 Census and
    2010 American Community Survey based on a 3 mile radius around the facility spatial
    coordinates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-demographics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-demographics-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report CWA SEV Compliance Service
  x-api-slug: dfr-rest-services-get-cwa-se-compliance-get
  description: This procedure obtains data for the CWA Single Event Violations section
    of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-se-compliance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-se-compliance-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report CWA RNC Compliance Service
  x-api-slug: dfr-rest-services-get-cwa-rnc-compliance-get
  description: |-
    This procedure obtains data for the CWA SNC/RNC History section located in the Three Year ompliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows.
    > S = SNC/Category I - an enforcement action has been issued, and the facility is not meeting its compliance schedule
    > E = SNC/Category I - effluent violations of monthly average limits (Technical Review Criteria and chronic)
    > X = SNC/Category I - effluent violations of non-monthly average limits (Technical Review Criteria and chronic)
    > T = SNC/Category I - compliance schedule reporting violation
    > D = SNC/Category I - reporting violation - nonreceipt of DMR
    > N = RNC/Category II - reportable non-compliance
    > P = Resolved Pending - an enforcement action has been issued, and facility compliance with the action is pending final completion
    > R = Resolved - the facility has returned to compliance with its permit conditions, either with or without issuance of an enforcement action
    > C = Not considered in RNC/SNC based on manual review of data by state or EPA region. This manual override status is also indicated by a superscripted "m".
    > Blank = Not considered in RNC/SNC
    > N/A = EPA's data system is not able to determine the facility-level compliance status based upon the information available. This information may be available from a state database.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-rnc-compliance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-rnc-compliance-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report CWA PSV Compliance Service
  x-api-slug: dfr-rest-services-get-cwa-ps-compliance-get
  description: This procedure obtains data for the CWA Permit Schedule Violations
    section of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-ps-compliance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-ps-compliance-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report CWA Effluent Compliance Service
  x-api-slug: dfr-rest-services-get-cwa-eff-compliance-get
  description: This procedure obtains data for the CWA Effluent Compliance section
    on the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-eff-compliance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-eff-compliance-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report CWA Effluent ALR Service
  x-api-slug: dfr-rest-services-get-cwa-eff-alr-get
  description: This procedure obtains data for the CWA Pollutant Discharge section
    located in the Three Year Compliance Status by Quarter portion of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-eff-alr-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-eff-alr-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report CWA CSV Compliance Service
  x-api-slug: dfr-rest-services-get-cwa-cs-compliance-get
  description: This procedure obtains data for the CWA Compliance Schedule Violations
    section of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-cs-compliance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-cs-compliance-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report 3 Year CWA Facility-Level Status Service
  x-api-slug: dfr-rest-services-get-cwa-3yr-compliance-get
  description: |-
    This procedure obtains data for the CWA Facility-Level Status section located in the Three Year Compliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows:
    > "In Viol" = Facility is in violation
    > "No Viol" = No violation found
    > "Unk" = Unknown status
    > "SNC/Cat 1" = SNC/Category I violation found
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-3yr-compliance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-cwa-3yr-compliance-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Compliance Summary Service
  x-api-slug: dfr-rest-services-get-compliance-summary-get
  description: This procedure obtains data for Compliance Summary Data in the Enforcement
    and Compliance Section of the Detailed Facility report.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-compliance-summary-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-compliance-summary-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report 5 Year Compliance Monitoring History Service
  x-api-slug: dfr-rest-services-get-compliance-history-get
  description: This procedure obtains data for the Compliance Monitoring History (5
    years) in the Enforcement and Compliance Section of the Detailed Facility report.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-compliance-history-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-compliance-history-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Air Quality Report Service
  x-api-slug: dfr-rest-services-get-air-quality-get
  description: This procedure obtains data for Air Quality in the Environmental Conditions
    Section of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-air-quality-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-air-quality-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) - Detailed Facility Report Air Compliance Report Service
  x-api-slug: dfr-rest-services-get-air-compliance-get
  description: This procedure obtains data for Air Compliance in the Environmental
    Conditions Section of the DFR.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-air-compliance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/dfr-rest-services-get-air-compliance-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Effluent Charting
    and Reporting - ECHO CWA Parameter Lookup Service
  x-api-slug: rest-lookups-cwa-parameters-get
  description: Look up Clean Water Act parameter codes and descriptions in the Integrated
    Compliance Information System - National Pollutant Discharge Elimination System
    (ICIS-NPDES) by code or term.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-cwa-parameters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-cwa-parameters-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Effluent Charting
    and Reporting - Summary Effluent Chart Service
  x-api-slug: eff-rest-services-get-summary-chart-get
  description: Summary of compliance status each outfall and parameter for one NPDES
    permit. Provides the current compliance status and overall compliance status for
    the date range of interest. This service supports the Summary Matrix on the Effluent
    Charts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/eff-rest-services-get-summary-chart-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/eff-rest-services-get-summary-chart-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Effluent Charting
    and Reporting - Detailed Effluent Chart Service
  x-api-slug: eff-rest-services-get-effluent-chart-get
  description: Discharge Monitoring Report (DMR) data supporting each effluent chart
    for one NPDES permit. Includes Discharge Monitoring Reports and NPDES Violations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/eff-rest-services-get-effluent-chart-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/eff-rest-services-get-effluent-chart-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Effluent Charting
    and Reporting - Effluent Charts Download Service
  x-api-slug: eff-rest-services-download-effluent-chart-get
  description: Downloads tabular Discharge Monitoring Report (DMR) and compliance
    data for one NPDES permit as a CSV.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/eff-rest-services-download-effluent-chart-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/eff-rest-services-download-effluent-chart-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case
    Search - ECHO ICIS Law Sections Lookup Service
  x-api-slug: rest-lookups-icis-law-sections-get
  description: Returns the ICIS Law Section Descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-icis-law-sections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rest-lookups-icis-law-sections-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case
    Search - Enforcement Case Metadata Service
  x-api-slug: case-rest-services-metadata-get
  description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
    parameter for get_cases endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-metadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-metadata-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case
    Search - Enforcement Case Paginated Results Service
  x-api-slug: case-rest-services-get-qid-get
  description: GET_QID is passed with a query ID corresponding to a previously run
    get_cases query. It then returns a CASES object containing all matching cases.
    The main purpose of GET_QID is for large querysets that contain multiple pages
    (responsesets) of output. GET_QID allows for pagination and for the selection
    and sorting of columns.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-get-qid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-get-qid-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case
    Search - Enforcement Case Map Service
  x-api-slug: case-rest-services-get-map-get
  description: The purpose of the GET_MAP service is to display facility coordinates
    and facility clusters related to a get_cases query. Currently, the maximum number
    of coordinates returned is 500. GET_MAP performs automatic clustering at the state,
    county, and zip code levels to maximize the number of coordinates returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-get-map-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-get-map-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case
    Search - Enforcement Case Download Data Service
  x-api-slug: case-rest-services-get-download-get
  description: Based on the QID obtained from a get_cases query, return a comma sepated
    vaule (CSV) file of the cases found.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-get-download-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-get-download-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case
    Search - Enforcement Criminal Case Summary Report Search
  x-api-slug: case-rest-services-get-crcase-report-get
  description: The get_crcase_report service end point returns a complex object of
    criminal case detials based on the provided criminal case id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-get-crcase-report-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-get-crcase-report-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case
    Search - Enforcement Case Search
  x-api-slug: case-rest-services-get-cases-get
  description: The get_cases service end point searches for civil enforcement and
    criminal cases based on the provided selection criteria.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-get-cases-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-get-cases-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case
    Search - Enforcement Case Summary Report Search
  x-api-slug: case-rest-services-get-case-report-get
  description: The get_case_report service endpoint returns a complex object of civil
    enforcement case details based on the provided case id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-get-case-report-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/case-rest-services-get-case-report-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Resource Conservation
    and Recovery Act  - Resource Conservation and Recovery Act (RCRA) Metadata Service
  x-api-slug: rcra-rest-services-metadata-get
  description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
    parameter for get_qid, get_facility_info and other service endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-metadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-metadata-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Resource Conservation
    and Recovery Act  - Resource Conservation and Recovery Act (RCRA) Paginated Results
    Service
  x-api-slug: rcra-rest-services-get-qid-get
  description: GET_QID is passed with a query ID corresponding to a previously run
    get_facilities query. It then returns a Facility object containing all matching
    facilities. The main purpose of GET_QID is for large querysets that contain multiple
    pages (responsesets) of output. GET_QID allows for pagination and for the selection
    and sorting of columns.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-qid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-qid-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Resource Conservation
    and Recovery Act  - Resource Conservation and Recovery Act (RCRA) Map Service
  x-api-slug: rcra-rest-services-get-map-get
  description: The purpose of the GET_MAP service is to display facility coordinates
    and facility clusters related to a get_facilities facility query. Currently, the
    maximum number of coordinates returned is 500. GET_MAP performs automatic clustering
    at the state, county, and zip code levels to maximize the number of coordinates
    returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-map-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-map-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Resource Conservation
    and Recovery Act  - Resource Conservation and Recovery Act (RCRA) Info Clusters
    Service
  x-api-slug: rcra-rest-services-get-info-clusters-get
  description: Based on the QID obtained from a clustered get_facility_info query,
    download cluster facility information as either a CSV or GEOJSON file.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-info-clusters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-info-clusters-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Resource Conservation
    and Recovery Act  - Resource Conservation and Recovery Act (RCRA) GeoJSON Service
  x-api-slug: rcra-rest-services-get-geojson-get
  description: Based on the QID obtained from a get_facilities or get_facility_info
    query, return GeoJSON of the facilities found.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-geojson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-geojson-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Resource Conservation
    and Recovery Act  - Resource Conservation and Recovery Act (RCRA) Facility Enhanced
    Search Service
  x-api-slug: rcra-rest-services-get-facility-info-get
  description: Returns either an array of Facilities or an array of Clusters that
    meet the specified search criteria.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-facility-info-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-facility-info-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Resource Conservation
    and Recovery Act  - Resource Conservation and Recovery Act (RCRA) Facility Search
    Service
  x-api-slug: rcra-rest-services-get-facilities-get
  description: Validates query search parameters and returns query identifier.  Use
    the responseset parameter to set the page size
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-facilities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-facilities-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Resource Conservation
    and Recovery Act  - Resource Conservation and Recovery Act (RCRA) Download Data
    Service
  x-api-slug: rcra-rest-services-get-download-get
  description: Based on the QID obtained from a get_facilities or get_facility_info
    query, return a comma sepated vaule (CSV) file of the facilities found.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-download-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/rcra-rest-services-get-download-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Safe Drinking
    Water Act - Safe Drinking Water Act (SDWA) Metadata Service
  x-api-slug: sdw-rest-services-metadata-get
  description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
    parameter for get_systems endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/sdw-rest-services-metadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/sdw-rest-services-metadata-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Safe Drinking
    Water Act - Safe Drinking Water Act (SDWA) Systems Search Service
  x-api-slug: sdw-rest-services-get-systems-get
  description: Returns an array of public water systems that meet the specified search
    criteria.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/sdw-rest-services-get-systems-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/sdw-rest-services-get-systems-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Safe Drinking
    Water Act - Safe Drinking Water Act (SDWA) Paginated Results Service
  x-api-slug: sdw-rest-services-get-qid-get
  description: GET_QID is passed with a query ID corresponding to a previously run
    get_systems query. It then returns a Systems object containing all matching water
    systems. The main purpose of GET_QID is for large querysets that contain multiple
    pages (responsesets) of output. GET_QID allows for pagination and for the selection
    and sorting of columns.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/sdw-rest-services-get-qid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/sdw-rest-services-get-qid-get-openapi.md
- name: U.S. EPA Enforcement and Compliance History Online (ECHO) - Safe Drinking
    Water Act - Safe Drinking Water Act (SDWA) Download Data Service
  x-api-slug: sdw-rest-services-get-download-get
  description: Based on the QID obtained from a get_systems query, return a comma
    sepated vaule (CSV) file of the water systems found.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/773-epa-envirofacts.jpg
  humanURL: http://www.epa.gov
  baseURL: https://ofmpub.epa.gov//echo
  tags: Environmental database, Environment, Science, Dead, Environment, Federal Government,
    Stack Network, Enterprise, API Provider, Profiles, General Data, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/sdw-rest-services-get-download-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/epa-envirofacts/sdw-rest-services-get-download-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://envestnet.api.gallery.streamdata.io
- type: x-api-stack
  url: http://epa.envirofacts.stack.network
- type: x-base
  url: http://iaspub.epa.gov/enviro/efservice/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/us-epa
- type: x-crunchbase
  url: https://crunchbase.com/organization/u-s-environmental-protection-agency
- type: x-developer
  url: http://www.epa.gov/enviro/facts/services.html
- type: x-email
  url: breen.barry@epa.gov
- type: x-email
  url: stanich.ted@epa.gov
- type: x-email
  url: brennan.thomas@epa.gov
- type: x-email
  url: R3_RA@epa.gov
- type: x-email
  url: dunn.alexandra@epa.gov
- type: x-email
  url: EPA-region01-RA@epa.gov
- type: x-email
  url: hladick.christopher@epa.gov
- type: x-email
  url: r7actionline@epa.gov
- type: x-email
  url: vette.alan@epa.gov
- type: x-email
  url: baxter.lisa@epa.gov
- type: x-twitter
  url: https://twitter.com/EPA
- type: x-website
  url: http://www.epa.gov
- type: x-website
  url: http://epa.gov
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---