---
swagger: "2.0"
x-collection-name: AppVeyor CI
x-complete: 1
info:
  title: App Veyor
  description: appveyor-is-a-hosted-continuous-integration-service-which-runs-on-microsoftwindows---the-appveyor-rest-api-provides-a-restful-way-to-interact-with-theappveyor-service---this-includes-managing-projects-builds-deploymentsand-the-teams-that-build-them-additional-help-and-discussion-of-the-appveyor-rest-api-is-available-athttphelp-appveyor-comdiscussionsthis-swagger-definition-is-an-unofficial-description-of-the-appveyorrest-api-maintained-at-httpsgithub-comkevinoidappveyorswaggerplease-report-any-issues-or-suggestions-for-this-swagger-definition-athttpsgithub-comkevinoidappveyorswaggerissuesnew-api-conventionsfields-which-are-missing-from-update-operations-put-requests-aretypically-reset-to-their-default-values---so-although-most-fields-are-nottechnically-required-they-should-usually-be-specified-in-practice-
  termsOfService: https://www.appveyor.com/terms-of-service/
  contact:
    name: AppVeyor Team
    url: https://www.appveyor.com/about/
    email: team@appveyor.com
  version: 0.20170106.0
host: ci.appveyor.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/{accountName}/{projectSlug}/settings/environment-variables:
    get:
      summary: Get Projects Accountname Projectslug Settings Environment Variables
      description: Get projects accountname projectslug settings environment variables.
      operationId: getProjectsAccountnameProjectslugSettingsEnvironmentVariables
      x-api-path-slug: projectsaccountnameprojectslugsettingsenvironmentvariables-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Environment
      - Variables
    parameters:
      summary: Parameters Projects Accountname Projectslug Settings Environment Variables
      description: Parameters projects accountname projectslug settings environment
        variables.
      operationId: parametersProjectsAccountnameProjectslugSettingsEnvironmentVariables
      x-api-path-slug: projectsaccountnameprojectslugsettingsenvironmentvariables-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Environment
      - Variables
    put:
      summary: Put Projects Accountname Projectslug Settings Environment Variables
      description: Put projects accountname projectslug settings environment variables.
      operationId: putProjectsAccountnameProjectslugSettingsEnvironmentVariables
      x-api-path-slug: projectsaccountnameprojectslugsettingsenvironmentvariables-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Environment
      - Variables
---