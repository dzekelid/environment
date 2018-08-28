---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case
    Search Enforcement Case Download Data Service
  description: Based on the QID obtained from a get_cases query, return a comma sepated
    vaule (CSV) file of the cases found.
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 1.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /echo_rest_services.metadata:
    get:
      summary: Combined ECHO Metadata Service
      description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
        parameter for get_qid, get_facility_info and other service endpoints.
      operationId: returns-the-json-object-name-and-columnid-for-usage-with-the-qcolumns-parameter-for-get-qid-get-faci
      x-api-path-slug: echo-rest-services-metadata-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Combined
      - ECHO
      - Metadata
      - Service
  /echo_rest_services.get_qid:
    get:
      summary: Combined ECHO Paginated Results Service
      description: GET_QID is passed with a query ID corresponding to a previously
        run get_facilities query. It then returns a Facility object containing all
        matching facilities. The main purpose of GET_QID is for large querysets that
        contain multiple pages (responsesets) of output. GET_QID allows for pagination
        and for the selection and sorting of columns.
      operationId: get-qid-is-passed-with-a-query-id-corresponding-to-a-previously-run-get-facilities-query--it-then-re
      x-api-path-slug: echo-rest-services-get-qid-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: qcolumns
        description: Used to cutomize service output
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Combined
      - ECHO
      - Paginated
      - Results
      - Service
  /echo_rest_services.get_map:
    get:
      summary: Combined ECHO Map Service
      description: The purpose of the GET_MAP service is to display facility coordinates
        and facility clusters related to a get_facilities facility query. Currently,
        the maximum number of coordinates returned is 500. GET_MAP performs automatic
        clustering at the state, county, and zip code levels to maximize the number
        of coordinates returned.
      operationId: the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-
      x-api-path-slug: echo-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Combined
      - ECHO
      - Map
      - Service
  /echo_rest_services.get_info_clusters:
    get:
      summary: Combined ECHO Info Clusters Service
      description: Based on the QID obtained from a clustered get_facility_info query,
        download cluster facility information as either a CSV or GEOJSON file.
      operationId: based-on-the-qid-obtained-from-a-clustered-get-facility-info-query-download-cluster-facility-informa
      x-api-path-slug: echo-rest-services-get-info-clusters-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Combined
      - ECHO
      - Info
      - Clusters
      - Service
  /echo_rest_services.get_geojson:
    get:
      summary: Combined ECHO GeoJSON Service
      description: Based on the QID obtained from a get_facilities or get_facility_info
        query, return GeoJSON of the facilities found.
      operationId: based-on-the-qid-obtained-from-a-get-facilities-or-get-facility-info-query-return-geojson-of-the-fac
      x-api-path-slug: echo-rest-services-get-geojson-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: qcolumns
        description: Used to cutomize service output
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Combined
      - ECHO
      - GeoJSON
      - Service
  /echo_rest_services.get_facility_info:
    get:
      summary: Combined ECHO Facility Enhanced Search Service
      description: Returns either an array of Facilities or an array of Clusters that
        meet the specified search criteria.
      operationId: returns-either-an-array-of-facilities-or-an-array-of-clusters-that-meet-the-specified-search-criteri
      x-api-path-slug: echo-rest-services-get-facility-info-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: qcolumns
        description: Used to cutomize service output
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Combined
      - ECHO
      - Facility
      - Enhanced
      - Search
      - Service
  /echo_rest_services.get_facilities:
    get:
      summary: Combined ECHO Facility Search Service
      description: Validates query search parameters and returns query identifier.  Use
        the responseset parameter to set the page size
      operationId: validates-query-search-parameters-and-returns-query-identifier---use-the-responseset-parameter-to-se
      x-api-path-slug: echo-rest-services-get-facilities-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: qcolumns
        description: Used to cutomize service output
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Combined
      - ECHO
      - Facility
      - Search
      - Service
  /echo_rest_services.get_download:
    get:
      summary: Combined ECHO Download Data Service
      description: Based on the QID obtained from a get_facilities or get_facility_info
        query, return a comma sepated vaule (CSV) file of the facilities found.
      operationId: based-on-the-qid-obtained-from-a-get-facilities-or-get-facility-info-query-return-a-comma-sepated-va
      x-api-path-slug: echo-rest-services-get-download-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: qcolumns
        description: Used to cutomize service output
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Combined
      - ECHO
      - Download
      - Data
      - Service
  /air_rest_services.metadata:
    get:
      summary: Clean Air Act Metadata Service
      description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
        parameter for get_qid, get_facility_info and other service endpoints.
      operationId: returns-the-json-object-name-and-columnid-for-usage-with-the-qcolumns-parameter-for-get-qid-get-faci
      x-api-path-slug: air-rest-services-metadata-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Air
      - Act
      - Metadata
      - Service
  /air_rest_services.get_qid:
    get:
      summary: Clean Air Act Search by Query ID
      description: GET_QID is passed with a query ID corresponding to a previously
        run get_facilities query. It then returns a Facility object containing all
        matching facilities. The main purpose of GET_QID is for large querysets that
        contain multiple pages (responsesets) of output. GET_QID allows for pagination
        and for the selection and sorting of columns.
      operationId: get-qid-is-passed-with-a-query-id-corresponding-to-a-previously-run-get-facilities-query--it-then-re
      x-api-path-slug: air-rest-services-get-qid-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Air
      - Act
      - Search
      - By
      - Query
      - ID
  /air_rest_services.get_map:
    get:
      summary: Clean Air Act Map Service
      description: The purpose of the GET_MAP service is to display facility coordinates
        and facility clusters related to a get_facilities facility query. Currently,
        the maximum number of coordinates returned is 500. GET_MAP performs automatic
        clustering at the state, county, and zip code levels to maximize the number
        of coordinates returned.
      operationId: the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-
      x-api-path-slug: air-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Air
      - Act
      - Map
      - Service
  /air_rest_services.get_info_clusters:
    get:
      summary: Clean Air Act Info Clusters Service
      description: Based on the QID obtained from a clustered get_facility_info query,
        download cluster facility information as either a CSV or GEOJSON file.
      operationId: based-on-the-qid-obtained-from-a-clustered-get-facility-info-query-download-cluster-facility-informa
      x-api-path-slug: air-rest-services-get-info-clusters-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Air
      - Act
      - Info
      - Clusters
      - Service
  /air_rest_services.get_geojson:
    get:
      summary: Clean Air Act GeoJSON Service
      description: Based on the QID obtained from a get_facilities or get_facility_info
        query, return GeoJSON of the facilities found.
      operationId: based-on-the-qid-obtained-from-a-get-facilities-or-get-facility-info-query-return-geojson-of-the-fac
      x-api-path-slug: air-rest-services-get-geojson-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Air
      - Act
      - GeoJSON
      - Service
  /air_rest_services.get_facility_info:
    get:
      summary: Clean Air Act Facility Enhanced Search
      description: Returns either an array of Facilities or an array of Clusters that
        meet the specified search criteria.
      operationId: returns-either-an-array-of-facilities-or-an-array-of-clusters-that-meet-the-specified-search-criteri
      x-api-path-slug: air-rest-services-get-facility-info-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Air
      - Act
      - Facility
      - Enhanced
      - Search
  /air_rest_services.get_facilities:
    get:
      summary: Clean Air Act Facility Search
      description: Validates query search parameters and returns query identifier.  Use
        the responseset parameter to set the page size
      operationId: validates-query-search-parameters-and-returns-query-identifier---use-the-responseset-parameter-to-se
      x-api-path-slug: air-rest-services-get-facilities-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Air
      - Act
      - Facility
      - Search
  /air_rest_services.get_download:
    get:
      summary: Clean Air Act Download Data Service
      description: Based on the QID obtained from a get_facilities or get_facility_info
        query, return a comma sepated vaule (CSV) file of the facilities found.
      operationId: based-on-the-qid-obtained-from-a-get-facilities-or-get-facility-info-query-return-a-comma-sepated-va
      x-api-path-slug: air-rest-services-get-download-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Air
      - Act
      - Download
      - Data
      - Service
  /rest_lookups.wbd_name_lu:
    get:
      summary: ECHO WBD Name Lookup Service
      description: USGS Watershed Boundary Dataset (WBD) Code lookup based on a supplied
        WBD Name and Watershed Level
      operationId: usgs-watershed-boundary-dataset-wbd-code-lookup-based-on-a-supplied-wbd-name-and-watershed-level
      x-api-path-slug: rest-lookups-wbd-name-lu-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - ECHO
      - WBD
      - Name
      - Lookup
      - Service
  /rest_lookups.wbd_code_lu:
    get:
      summary: ECHO WBD Code Lookup Service
      description: USGS Watershed Boundary Dataset (WBD) Name lookup based on a supplied
        WBD Code and Watershed Level
      operationId: usgs-watershed-boundary-dataset-wbd-name-lookup-based-on-a-supplied-wbd-code-and-watershed-level
      x-api-path-slug: rest-lookups-wbd-code-lu-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - ECHO
      - WBD
      - Code
      - Lookup
      - Service
  /rest_lookups.npdes_parameters:
    get:
      summary: ECHO NPDES Parameters Lookup Service
      description: ICIS Limit Parameter Code and Name lookup based on the supply of
        a partial parameter name. (NPDES = National Pollutant Discharge Elimination
        System)
      operationId: icis-limit-parameter-code-and-name-lookup-based-on-the-supply-of-a-partial-parameter-name--npdes--na
      x-api-path-slug: rest-lookups-npdes-parameters-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - ECHO
      - NPDES
      - Parameters
      - Lookup
      - Service
  /rest_lookups.naics_codes:
    get:
      summary: ECHO NAICS Codes Lookup Service
      description: ""
      operationId: ""
      x-api-path-slug: rest-lookups-naics-codes-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - ECHO
      - NAICS
      - Codes
      - Lookup
      - Service
  /rest_lookups.icis_law_sections:
    get:
      summary: ECHO ICIS Law Sections Lookup Service
      description: Returns the ICIS Law Section Descriptions.
      operationId: returns-the-icis-law-section-descriptions-
      x-api-path-slug: rest-lookups-icis-law-sections-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - ECHO
      - ICIS
      - Law
      - Sections
      - Lookup
      - Service
  /rest_lookups.icis_inspection_types:
    get:
      summary: ECHO ICIS NPDES Inspection Types Lookup Service
      description: Returns the ICIS NPDES Compliance Monitoring Type Code and Description.
      operationId: returns-the-icis-npdes-compliance-monitoring-type-code-and-description-
      x-api-path-slug: rest-lookups-icis-inspection-types-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - ECHO
      - ICIS
      - NPDES
      - Inspection
      - Types
      - Lookup
      - Service
  /rest_lookups.federal_agencies:
    get:
      summary: ECHO Federal Agency Lookup Service
      description: Look up Federal Agency Code
      operationId: look-up-federal-agency-code
      x-api-path-slug: rest-lookups-federal-agencies-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - ECHO
      - Federal
      - Agency
      - Lookup
      - Service
  /rest_lookups.cwa_pollutants:
    get:
      summary: ECHO CWA Pollutants Lookup Service
      description: ""
      operationId: ""
      x-api-path-slug: rest-lookups-cwa-pollutants-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - ECHO
      - CWA
      - Pollutants
      - Lookup
      - Service
  /rest_lookups.cwa_parameters:
    get:
      summary: ECHO CWA Parameter Lookup Service
      description: Look up Clean Water Act parameter codes and descriptions in the
        Integrated Compliance Information System - National Pollutant Discharge Elimination
        System (ICIS-NPDES) by code or term.
      operationId: look-up-clean-water-act-parameter-codes-and-descriptions-in-the-integrated-compliance-information-sy
      x-api-path-slug: rest-lookups-cwa-parameters-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - ECHO
      - CWA
      - Parameter
      - Lookup
      - Service
  /rest_lookups.bp_tribes:
    get:
      summary: ECHO BP Tribes Lookup Service
      description: Returns the EPA Standard Indian Tribes and Native Alaskan Villages
        tribal_id and tribe_name.
      operationId: returns-the-epa-standard-indian-tribes-and-native-alaskan-villages-tribal-id-and-tribe-name-
      x-api-path-slug: rest-lookups-bp-tribes-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - ECHO
      - BP
      - Tribes
      - Lookup
      - Service
  /cwa_rest_services.metadata:
    get:
      summary: Clean Water Act (CWA) Metadata Service
      description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
        parameter for get_qid, get_facility_info and other service endpoints.
      operationId: returns-the-json-object-name-and-columnid-for-usage-with-the-qcolumns-parameter-for-get-qid-get-faci
      x-api-path-slug: cwa-rest-services-metadata-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Water
      - Act
      - (CWA)
      - Metadata
      - Service
  /cwa_rest_services.get_qid:
    get:
      summary: Clean Water Act (CWA) Paginated Results Service
      description: GET_QID is passed with a query ID corresponding to a previously
        run get_facilities query. It then returns a Facility object containing all
        matching facilities. The main purpose of GET_QID is for large querysets that
        contain multiple pages (responsesets) of output. GET_QID allows for pagination
        and for the selection and sorting of columns.
      operationId: get-qid-is-passed-with-a-query-id-corresponding-to-a-previously-run-get-facilities-query--it-then-re
      x-api-path-slug: cwa-rest-services-get-qid-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: qcolumns
        description: Used to cutomize service output
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Water
      - Act
      - (CWA)
      - Paginated
      - Results
      - Service
  /cwa_rest_services.get_map:
    get:
      summary: Clean Water Act (CWA) Map Service
      description: The purpose of the GET_MAP service is to display facility coordinates
        and facility clusters related to a get_facilities facility query. Currently,
        the maximum number of coordinates returned is 500. GET_MAP performs automatic
        clustering at the state, county, and zip code levels to maximize the number
        of coordinates returned.
      operationId: the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-
      x-api-path-slug: cwa-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Water
      - Act
      - (CWA)
      - Map
      - Service
  /cwa_rest_services.get_info_clusters:
    get:
      summary: Clean Water Act (CWA) Info Clusters Service
      description: Based on the QID obtained from a clustered get_facility_info query,
        download cluster facility information as either a CSV or GEOJSON file.
      operationId: based-on-the-qid-obtained-from-a-clustered-get-facility-info-query-download-cluster-facility-informa
      x-api-path-slug: cwa-rest-services-get-info-clusters-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Water
      - Act
      - (CWA)
      - Info
      - Clusters
      - Service
  /cwa_rest_services.get_geojson:
    get:
      summary: Clean Water Act (CWA) Download Data Service
      description: Based on the QID obtained from a get_facilities or get_facility_info
        query, return a comma sepated vaule (CSV) file of the facilities found.
      operationId: based-on-the-qid-obtained-from-a-get-facilities-or-get-facility-info-query-return-a-comma-sepated-va
      x-api-path-slug: cwa-rest-services-get-geojson-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: qcolumns
        description: Used to cutomize service output
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Water
      - Act
      - (CWA)
      - Download
      - Data
      - Service
  /cwa_rest_services.get_facility_info:
    get:
      summary: Clean Water Act (CWA) Facility Enhanced Search Service
      description: Returns either an array of Facilities or an array of Clusters that
        meet the specified search criteria.
      operationId: returns-either-an-array-of-facilities-or-an-array-of-clusters-that-meet-the-specified-search-criteri
      x-api-path-slug: cwa-rest-services-get-facility-info-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: qcolumns
        description: Used to cutomize service output
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Water
      - Act
      - (CWA)
      - Facility
      - Enhanced
      - Search
      - Service
  /cwa_rest_services.get_facilities:
    get:
      summary: Clean Water Act (CWA) Facility Search Service
      description: Validates query search parameters and returns query identifier.  Use
        the responseset parameter to set the page size
      operationId: validates-query-search-parameters-and-returns-query-identifier---use-the-responseset-parameter-to-se
      x-api-path-slug: cwa-rest-services-get-facilities-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: qcolumns
        description: Used to cutomize service output
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Water
      - Act
      - (CWA)
      - Facility
      - Search
      - Service
  /cwa_rest_services.get_download:
    get:
      summary: Clean Water Act (CWA) GeoJSON Service
      description: Based on the QID obtained from a get_facilities or get_facility_info
        query, return GeoJSON of the facilities found.
      operationId: based-on-the-qid-obtained-from-a-get-facilities-or-get-facility-info-query-return-geojson-of-the-fac
      x-api-path-slug: cwa-rest-services-get-download-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: qcolumns
        description: Used to cutomize service output
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Water
      - Act
      - (CWA)
      - GeoJSON
      - Service
  /dfr_rest_services.get_water_quality:
    get:
      summary: Detailed Facility Report Water Quality Service
      description: This procedure obtains data for the Water Quality section of the
        DFR.
      operationId: this-procedure-obtains-data-for-the-water-quality-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-water-quality-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Water
      - Quality
      - Service
  /dfr_rest_services.get_tribes:
    get:
      summary: Detailed Facility Report Tribes Service
      description: This procedure obtains data for the Tribes and Reservations section
        of the DFR.
      operationId: this-procedure-obtains-data-for-the-tribes-and-reservations-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-tribes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Tribes
      - Service
  /dfr_rest_services.get_tri_releases:
    get:
      summary: Detailed Facility Report TRI Releases Service
      description: This procedrue obtains data for the TRI Releases section of the
        DFR.
      operationId: this-procedrue-obtains-data-for-the-tri-releases-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-tri-releases-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - TRI
      - Releases
      - Service
  /dfr_rest_services.get_tri_history:
    get:
      summary: Detailed Facility Report TRI History Service
      description: This procedure obtains data for the TRI History section of the
        DFR.
      operationId: this-procedure-obtains-data-for-the-tri-history-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-tri-history-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - TRI
      - History
      - Service
  /dfr_rest_services.get_spatial_metadata:
    get:
      summary: Detailed Facility Report Spatial Metadata Service
      description: Returns an object with the facility coordinate spatial metadata.
      operationId: returns-an-object-with-the-facility-coordinate-spatial-metadata-
      x-api-path-slug: dfr-rest-services-get-spatial-metadata-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Spatial
      - Metadata
      - Service
  /dfr_rest_services.get_sic_codes:
    get:
      summary: Detailed Facility Report SIC Code Service
      description: This procedure obtains data for the Facility SIC Codes section
        in Facility/System Characteristics of the Detailed Facility Report.
      operationId: this-procedure-obtains-data-for-the-facility-sic-codes-section-in-facilitysystem-characteristics-of-
      x-api-path-slug: dfr-rest-services-get-sic-codes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - SIC
      - Code
      - Service
  /dfr_rest_services.get_sdwis_compliance:
    get:
      summary: Detailed Facility Report SDWIS Compliance Service
      description: This procedure obtains data for the SDWA Compliance section of
        the DFR.
      operationId: this-procedure-obtains-data-for-the-sdwa-compliance-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-sdwis-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - SDWIS
      - Compliance
      - Service
  /dfr_rest_services.get_sdwa_violations:
    get:
      summary: Detailed Facility Report SDWA Violations Service
      description: This procedure obtains data for the SDWA Violations section of
        the DFR.
      operationId: this-procedure-obtains-data-for-the-sdwa-violations-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-sdwa-violations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - SDWA
      - Violations
      - Service
  /dfr_rest_services.get_sdwa_site_visits:
    get:
      summary: Detailed Facility Report SDWA Sanitary Site Visits Service
      description: This procedure obtains data for the SDWA, Sanitary Site Visits
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-sdwa-sanitary-site-visits-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-sdwa-site-visits-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - SDWA
      - Sanitary
      - Site
      - Visits
      - Service
  /dfr_rest_services.get_sdwa_sanitary_surveys:
    get:
      summary: Detailed Facility Report SDWA Sanitary Surveys Service
      description: This procedure obtains data for the SDWA, Sanitary Surveys section
        of the DFR.
      operationId: this-procedure-obtains-data-for-the-sdwa-sanitary-surveys-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-sdwa-sanitary-surveys-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - SDWA
      - Sanitary
      - Surveys
      - Service
  /dfr_rest_services.get_sdwa_lead_and_copper:
    get:
      summary: Detailed Facility Report SDWA Lead and Copper Service
      description: This procedure obtains data for the SDWA, Lead and Copper Rule
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-sdwa-lead-and-copper-rule-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-sdwa-lead-and-copper-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - SDWA
      - Lead
      - Copper
      - Service
  /dfr_rest_services.get_rcra_compliance:
    get:
      summary: Detailed Facility Report RCRA Compliance Service
      description: This procedure obtains data for the RCRA Compliance section of
        the DFR.
      operationId: this-procedure-obtains-data-for-the-rcra-compliance-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-rcra-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - RCRA
      - Compliance
      - Service
  /dfr_rest_services.get_permits:
    get:
      summary: Detailed Facility Report Permits Service
      description: |-
        This procedure obtains data for the following sections of the Detailed Facility Report.
        > Facility Information (FRS) in the Facility Summary.
        > Regulatory Interests in the Facility Summary.
        > Also Reports in the Facility Summary.
        > Facility/System Characteristics in Facility/System Characteristics.
        > Facility Contact Information in Facility/System Characteristics.
        > Facility SIC Codes in Facility/System Characteristics section.
        > Facility NAICS Codes in Facility/System Characteristics section.
      operationId: this-procedure-obtains-data-for-the-following-sections-of-the-detailed-facility-report--facility-inf
      x-api-path-slug: dfr-rest-services-get-permits-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Permits
      - Service
  /dfr_rest_services.get_notices:
    get:
      summary: Detailed Facility Report Notices Service
      description: This procedure obtains data for the Notices/Informal Actions section
        of the DFR.
      operationId: this-procedure-obtains-data-for-the-noticesinformal-actions-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-notices-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Notices
      - Service
  /dfr_rest_services.get_nnnPermits:
    get:
      summary: Detailed Facility Report Permits by Statute Service
      description: This procedure obtains data for the Permits by Statute section
        of the DFR.
      operationId: this-procedure-obtains-data-for-the-permits-by-statute-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-nnnpermits-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Permits
      - By
      - Statute
      - Service
  /dfr_rest_services.get_naics:
    get:
      summary: Detailed Facility Report NAICS Code Service
      description: This procedure obtains data for the Facility NAICS Codes section
        in Facility/System Characteristics of the Detailed Facility Report.
      operationId: this-procedure-obtains-data-for-the-facility-naics-codes-section-in-facilitysystem-characteristics-o
      x-api-path-slug: dfr-rest-services-get-naics-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - NAICS
      - Code
      - Service
  /dfr_rest_services.get_map:
    get:
      summary: Detailed Facility Report Map Service
      description: Returns an object with the facility's latitude and longitude coordinates.
      operationId: returns-an-object-with-the-facilitys-latitude-and-longitude-coordinates-
      x-api-path-slug: dfr-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Map
      - Service
  /dfr_rest_services.get_inspections:
    get:
      summary: Detailed Facility Report Inspections Summary Service
      description: This procedure obtains data for Enforcement and Compliance Summary
        Section of the Detailed Facility report.
      operationId: this-procedure-obtains-data-for-enforcement-and-compliance-summary-section-of-the-detailed-facility-
      x-api-path-slug: dfr-rest-services-get-inspections-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Inspections
      - Summary
      - Service
  /dfr_rest_services.get_icis_formal_actions:
    get:
      summary: Detailed Facility Report ICIS Formal Actions Service
      description: This procedure obtains data for the Integrated Compliance Information
        System, Formal Enforcement Actions section of the DFR.
      operationId: this-procedure-obtains-data-for-the-integrated-compliance-information-system-formal-enforcement-acti
      x-api-path-slug: dfr-rest-services-get-icis-formal-actions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - ICIS
      - Formal
      - Actions
      - Service
  /dfr_rest_services.get_formal_actions:
    get:
      summary: Detailed Facility Report Formal Actions Service
      description: This procedure obtains data for the Formal Enforcement Actions
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-formal-enforcement-actions-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-formal-actions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Formal
      - Actions
      - Service
  /dfr_rest_services.get_enforcement_summary:
    get:
      summary: Detailed Facility Report Enforcement Summary Service
      description: This procedure obtains data for the Enforcement and Compliance
        Summary in the Facility Summary section of the Detailed Facility Report.
      operationId: this-procedure-obtains-data-for-the-enforcement-and-compliance-summary-in-the-facility-summary-secti
      x-api-path-slug: dfr-rest-services-get-enforcement-summary-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Enforcement
      - Summary
      - Service
  /dfr_rest_services.get_dfr:
    get:
      summary: Detailed Facility Report Service
      description: This procedure is the overall service for the Detailed Facility
        Report. It returns all of the data displayed in the DFR web report by invoking
        individual procedures that each return a targeted portion of the DFR.
      operationId: this-procedure-is-the-overall-service-for-the-detailed-facility-report--it-returns-all-of-the-data-d
      x-api-path-slug: dfr-rest-services-get-dfr-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Service
  /dfr_rest_services.get_demographics:
    get:
      summary: Detailed Facility Report Demographics Report Service
      description: Returns a complex object with Demographics from the 2010 Census
        and 2010 American Community Survey based on a 3 mile radius around the facility
        spatial coordinates.
      operationId: returns-a-complex-object-with-demographics-from-the-2010-census-and-2010-american-community-survey-b
      x-api-path-slug: dfr-rest-services-get-demographics-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Demographics
      - Report
      - Service
  /dfr_rest_services.get_cwa_se_compliance:
    get:
      summary: Detailed Facility Report CWA SEV Compliance Service
      description: This procedure obtains data for the CWA Single Event Violations
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-cwa-single-event-violations-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-cwa-se-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - CWA
      - SEV
      - Compliance
      - Service
  /dfr_rest_services.get_cwa_rnc_compliance:
    get:
      summary: Detailed Facility Report CWA RNC Compliance Service
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
      operationId: this-procedure-obtains-data-for-the-cwa-sncrnc-history-section-located-in-the-three-year-ompliance-s
      x-api-path-slug: dfr-rest-services-get-cwa-rnc-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - CWA
      - RNC
      - Compliance
      - Service
  /dfr_rest_services.get_cwa_ps_compliance:
    get:
      summary: Detailed Facility Report CWA PSV Compliance Service
      description: This procedure obtains data for the CWA Permit Schedule Violations
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-cwa-permit-schedule-violations-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-cwa-ps-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - CWA
      - PSV
      - Compliance
      - Service
  /dfr_rest_services.get_cwa_eff_compliance:
    get:
      summary: Detailed Facility Report CWA Effluent Compliance Service
      description: This procedure obtains data for the CWA Effluent Compliance section
        on the DFR.
      operationId: this-procedure-obtains-data-for-the-cwa-effluent-compliance-section-on-the-dfr---
      x-api-path-slug: dfr-rest-services-get-cwa-eff-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - CWA
      - Effluent
      - Compliance
      - Service
  /dfr_rest_services.get_cwa_eff_alr:
    get:
      summary: Detailed Facility Report CWA Effluent ALR Service
      description: This procedure obtains data for the CWA Pollutant Discharge section
        located in the Three Year Compliance Status by Quarter portion of the DFR.
      operationId: this-procedure-obtains-data-for-the-cwa-pollutant-discharge-section-located-in-the-three-year-compli
      x-api-path-slug: dfr-rest-services-get-cwa-eff-alr-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - CWA
      - Effluent
      - ALR
      - Service
  /dfr_rest_services.get_cwa_cs_compliance:
    get:
      summary: Detailed Facility Report CWA CSV Compliance Service
      description: This procedure obtains data for the CWA Compliance Schedule Violations
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-cwa-compliance-schedule-violations-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-cwa-cs-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - CWA
      - CSV
      - Compliance
      - Service
  /dfr_rest_services.get_cwa_3yr_compliance:
    get:
      summary: Detailed Facility Report 3 Year CWA Facility-Level Status Service
      description: |-
        This procedure obtains data for the CWA Facility-Level Status section located in the Three Year Compliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows:
        > "In Viol" = Facility is in violation
        > "No Viol" = No violation found
        > "Unk" = Unknown status
        > "SNC/Cat 1" = SNC/Category I violation found
      operationId: this-procedure-obtains-data-for-the-cwa-facilitylevel-status-section-located-in-the-three-year-compl
      x-api-path-slug: dfr-rest-services-get-cwa-3yr-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - "3"
      - Year
      - CWA
      - Facility-Level
      - Status
      - Service
  /dfr_rest_services.get_compliance_summary:
    get:
      summary: Detailed Facility Report Compliance Summary Service
      description: This procedure obtains data for Compliance Summary Data in the
        Enforcement and Compliance Section of the Detailed Facility report.
      operationId: this-procedure-obtains-data-for-compliance-summary-data-in-the-enforcement-and-compliance-section-of
      x-api-path-slug: dfr-rest-services-get-compliance-summary-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Compliance
      - Summary
      - Service
  /dfr_rest_services.get_compliance_history:
    get:
      summary: Detailed Facility Report 5 Year Compliance Monitoring History Service
      description: This procedure obtains data for the Compliance Monitoring History
        (5 years) in the Enforcement and Compliance Section of the Detailed Facility
        report.
      operationId: this-procedure-obtains-data-for-the-compliance-monitoring-history-5-years-in-the-enforcement-and-com
      x-api-path-slug: dfr-rest-services-get-compliance-history-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - "5"
      - Year
      - Compliance
      - Monitoring
      - History
      - Service
  /dfr_rest_services.get_air_quality:
    get:
      summary: Detailed Facility Report Air Quality Report Service
      description: This procedure obtains data for Air Quality in the Environmental
        Conditions Section of the DFR.
      operationId: this-procedure-obtains-data-for-air-quality-in-the-environmental-conditions-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-air-quality-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Air
      - Quality
      - Report
      - Service
  /dfr_rest_services.get_air_compliance:
    get:
      summary: Detailed Facility Report Air Compliance Report Service
      description: This procedure obtains data for Air Compliance in the Environmental
        Conditions Section of the DFR.
      operationId: this-procedure-obtains-data-for-air-compliance-in-the-environmental-conditions-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-air-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Air
      - Compliance
      - Report
      - Service
  /eff_rest_services.get_summary_chart:
    get:
      summary: Summary Effluent Chart Service
      description: Summary of compliance status each outfall and parameter for one
        NPDES permit. Provides the current compliance status and overall compliance
        status for the date range of interest. This service supports the Summary Matrix
        on the Effluent Charts.
      operationId: summary-of-compliance-status-each-outfall-and-parameter-for-one-npdes-permit--provides-the-current-c
      x-api-path-slug: eff-rest-services-get-summary-chart-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Summary
      - Effluent
      - Chart
      - Service
  /eff_rest_services.get_effluent_chart:
    get:
      summary: Detailed Effluent Chart Service
      description: Discharge Monitoring Report (DMR) data supporting each effluent
        chart for one NPDES permit. Includes Discharge Monitoring Reports and NPDES
        Violations.
      operationId: discharge-monitoring-report-dmr-data-supporting-each-effluent-chart-for-one-npdes-permit--includes-d
      x-api-path-slug: eff-rest-services-get-effluent-chart-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Effluent
      - Chart
      - Service
  /eff_rest_services.download_effluent_chart:
    get:
      summary: Effluent Charts Download Service
      description: Downloads tabular Discharge Monitoring Report (DMR) and compliance
        data for one NPDES permit as a CSV.
      operationId: downloads-tabular-discharge-monitoring-report-dmr-and-compliance-data-for-one-npdes-permit-as-a-csv-
      x-api-path-slug: eff-rest-services-download-effluent-chart-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Effluent
      - Charts
      - Download
      - Service
  /case_rest_services.metadata:
    get:
      summary: Enforcement Case Metadata Service
      description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
        parameter for get_cases endpoint.
      operationId: returns-the-json-object-name-and-columnid-for-usage-with-the-qcolumns-parameter-for-get-cases-endpoi
      x-api-path-slug: case-rest-services-metadata-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Enforcement
      - Case
      - Metadata
      - Service
  /case_rest_services.get_qid:
    get:
      summary: Enforcement Case Paginated Results Service
      description: GET_QID is passed with a query ID corresponding to a previously
        run get_cases query. It then returns a CASES object containing all matching
        cases. The main purpose of GET_QID is for large querysets that contain multiple
        pages (responsesets) of output. GET_QID allows for pagination and for the
        selection and sorting of columns.
      operationId: get-qid-is-passed-with-a-query-id-corresponding-to-a-previously-run-get-cases-query--it-then-returns
      x-api-path-slug: case-rest-services-get-qid-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Enforcement
      - Case
      - Paginated
      - Results
      - Service
  /case_rest_services.get_map:
    get:
      summary: Enforcement Case Map Service
      description: The purpose of the GET_MAP service is to display facility coordinates
        and facility clusters related to a get_cases query. Currently, the maximum
        number of coordinates returned is 500. GET_MAP performs automatic clustering
        at the state, county, and zip code levels to maximize the number of coordinates
        returned.
      operationId: the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-
      x-api-path-slug: case-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Enforcement
      - Case
      - Map
      - Service
  /case_rest_services.get_download:
    get:
      summary: Enforcement Case Download Data Service
      description: Based on the QID obtained from a get_cases query, return a comma
        sepated vaule (CSV) file of the cases found.
      operationId: based-on-the-qid-obtained-from-a-get-cases-query-return-a-comma-sepated-vaule-csv-file-of-the-cases-
      x-api-path-slug: case-rest-services-get-download-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Enforcement
      - Case
      - Download
      - Data
      - Service
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---