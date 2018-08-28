---
swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 0
info:
  title: AWS Elastic Beanstalk API Describe Environment Managed Action History
  version: 1.0.0
  description: Lists an environment's completed and failed managed actions.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AbortEnvironmentUpdate:
    get:
      summary: Abort Environment Update
      description: |-
        Cancels in-progress environment configuration update or application version
              deployment.
      operationId: abortEnvironmentUpdate
      x-api-path-slug: actionabortenvironmentupdate-get
      parameters:
      - in: query
        name: EnvironmentId
        description: This specifies the ID of the environment with the in-progress
          update that you want to      cancel
        type: string
      - in: query
        name: EnvironmentName
        description: This specifies the name of the environment with the in-progress
          update that you want to      cancel
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=ApplyEnvironmentManagedAction:
    get:
      summary: Apply Environment Managed Action
      description: Applies a scheduled managed action immediately.
      operationId: applyEnvironmentManagedAction
      x-api-path-slug: actionapplyenvironmentmanagedaction-get
      parameters:
      - in: query
        name: ActionId
        description: The action ID of the scheduled managed action to execute
        type: string
      - in: query
        name: EnvironmentId
        description: The environment ID of the target environment
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the target environment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=ComposeEnvironments:
    get:
      summary: Compose Environments
      description: |-
        Create or update a group of environments that each run a separate component of a single
              application.
      operationId: composeEnvironments
      x-api-path-slug: actioncomposeenvironments-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application to which the specified source bundles
          belong
        type: string
      - in: query
        name: GroupName
        description: The name of the group to which the target environments belong
        type: string
      - in: query
        name: VersionLabels.member.N
        description: A list of version labels, specifying one or more application
          source bundles that belong      to the target application
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=CreateEnvironment:
    get:
      summary: Create Environment
      description: |-
        Launches an environment for the specified application using the specified
              configuration.
      operationId: createEnvironment
      x-api-path-slug: actioncreateenvironment-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application that contains the version to be deployed
        type: string
      - in: query
        name: CNAMEPrefix
        description: If specified, the environment attempts to use this value as the
          prefix for the CNAME
        type: string
      - in: query
        name: Description
        description: Describes this environment
        type: string
      - in: query
        name: EnvironmentName
        description: A unique name for the deployment environment
        type: string
      - in: query
        name: GroupName
        description: The name of the group to which the target environment belongs
        type: string
      - in: query
        name: OptionSettings.member.N
        description: If specified, AWS Elastic Beanstalk sets the specified configuration
          options to the      requested value in the configuration set for the new
          environment
        type: string
      - in: query
        name: OptionsToRemove.member.N
        description: A list of custom user-defined configuration options to remove
          from the configuration      set for this new environment
        type: string
      - in: query
        name: SolutionStackName
        description: This is an alternative to specifying a template name
        type: string
      - in: query
        name: Tags.member.N
        description: This specifies the tags applied to resources in the environment
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template to use in deployment
        type: string
      - in: query
        name: Tier
        description: This specifies the tier to use for creating this environment
        type: string
      - in: query
        name: VersionLabel
        description: The name of the application version to deploy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=DeleteEnvironmentConfiguration:
    get:
      summary: Delete Environment Configuration
      description: Deletes the draft configuration associated with the running environment.
      operationId: deleteEnvironmentConfiguration
      x-api-path-slug: actiondeleteenvironmentconfiguration-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application the environment is associated with
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to delete the draft configuration
          from
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=DescribeEnvironmentHealth:
    get:
      summary: Describe Environment Health
      description: Returns information about the overall health of the specified environment.
      operationId: describeEnvironmentHealth
      x-api-path-slug: actiondescribeenvironmenthealth-get
      parameters:
      - in: query
        name: AttributeNames.member.N
        description: Specify the response elements to return
        type: string
      - in: query
        name: EnvironmentId
        description: Specify the environment by ID
        type: string
      - in: query
        name: EnvironmentName
        description: Specify the environment by name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=DescribeEnvironmentManagedActionHistory:
    get:
      summary: Describe Environment Managed Action History
      description: Lists an environment's completed and failed managed actions.
      operationId: describeEnvironmentManagedActionHistory
      x-api-path-slug: actiondescribeenvironmentmanagedactionhistory-get
      parameters:
      - in: query
        name: EnvironmentId
        description: The environment ID of the target environment
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the target environment
        type: string
      - in: query
        name: MaxItems
        description: The maximum number of items to return for a single request
        type: string
      - in: query
        name: NextToken
        description: The pagination token returned by a previous request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
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