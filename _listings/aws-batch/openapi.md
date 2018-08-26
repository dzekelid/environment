---
swagger: "2.0"
x-collection-name: AWS Batch
x-complete: 1
info:
  title: AWS Batch API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateComputeEnvironment:
    get:
      summary: Create Compute Environment
      description: Creates an AWS Batch compute environment.
      operationId: createComputeEnvironment
      x-api-path-slug: actioncreatecomputeenvironment-get
      parameters:
      - in: query
        name: computeEnvironmentName
        description: The name for your compute environment
        type: string
      - in: query
        name: computeResources
        description: Details of the compute resources managed by the compute environment
        type: string
      - in: query
        name: serviceRole
        description: The full Amazon Resource Name (ARN) of the IAM role that allows
          AWS Batch to make calls to other AWS         services on your behalf
        type: string
      - in: query
        name: state
        description: The state of the compute environment
        type: string
      - in: query
        name: type
        description: The type of the compute environment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compute Environment
  /?Action=DeleteComputeEnvironment:
    get:
      summary: Delete Compute Environment
      description: Deletes an AWS Batch compute environment.
      operationId: deleteComputeEnvironment
      x-api-path-slug: actiondeletecomputeenvironment-get
      parameters:
      - in: query
        name: computeEnvironment
        description: The name or Amazon Resource Name (ARN) of the compute environment
          to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compute Environment
  /?Action=DescribeComputeEnvironments:
    get:
      summary: Describe Compute Environments
      description: Describes one or more of your compute environments.
      operationId: describeComputeEnvironments
      x-api-path-slug: actiondescribecomputeenvironments-get
      parameters:
      - in: query
        name: computeEnvironments
        description: A list of up to 100 compute environment names or full Amazon
          Resource Name (ARN) entries
        type: string
      - in: query
        name: maxResults
        description: The maximum number of cluster results returned by            DescribeComputeEnvironments
          in paginated output
        type: string
      - in: query
        name: nextToken
        description: The nextToken value returned from a previous paginated            DescribeComputeEnvironments
          request where maxResults was used         and the results exceeded the value
          of that parameter
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compute Environment
  /?Action=UpdateComputeEnvironment:
    get:
      summary: Update Compute Environment
      description: Updates an AWS Batch compute environment.
      operationId: updateComputeEnvironment
      x-api-path-slug: actionupdatecomputeenvironment-get
      parameters:
      - in: query
        name: computeEnvironment
        description: The name or full Amazon Resource Name (ARN) of the compute environment
          to update
        type: string
      - in: query
        name: computeResources
        description: Details of the compute resources managed by the compute environment
        type: string
      - in: query
        name: serviceRole
        description: The name or full Amazon Resource Name (ARN) of the IAM role that
          allows AWS Batch to make calls to         ECS, Auto Scaling, and EC2 on
          your behalf
        type: string
      - in: query
        name: state
        description: The state of the compute environment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compute Environment
---