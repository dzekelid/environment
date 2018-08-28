---
name: AWS Elastic Beanstalk
x-slug: aws-elastic-beanstalk
description: AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling
  web applications and services developed with Java,.NET, PHP, Node.js, Python, Ruby,
  Go, andDockeron familiar servers such as Apache, Nginx, Passenger, andIIS.You can
  simply upload your code and Elastic Beanstalk automatically handles the deployment,
  from capacity provisioning, load balancing, auto-scaling to application health monitoring.
  At the same time, you retain full control over the AWS resources powering your application
  and can access the underlying resources at any time.There is no additional charge
  for Elastic Beanstalk - you pay only for the AWS resources needed to store and run
  your applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Environment
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Elastic Beanstalk API - Abort Environment Update
  x-api-slug: actionabortenvironmentupdate-get
  description: |-
    Cancels in-progress environment configuration update or application version
          deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actionabortenvironmentupdate-get-openapi.md
- name: AWS Elastic Beanstalk API - Apply Environment Managed Action
  x-api-slug: actionapplyenvironmentmanagedaction-get
  description: Applies a scheduled managed action immediately.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actionapplyenvironmentmanagedaction-get-openapi.md
- name: AWS Elastic Beanstalk API - Compose Environments
  x-api-slug: actioncomposeenvironments-get
  description: |-
    Create or update a group of environments that each run a separate component of a single
          application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actioncomposeenvironments-get-openapi.md
- name: AWS Elastic Beanstalk API - Create Environment
  x-api-slug: actioncreateenvironment-get
  description: |-
    Launches an environment for the specified application using the specified
          configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actioncreateenvironment-get-openapi.md
- name: AWS Elastic Beanstalk API - Delete Environment Configuration
  x-api-slug: actiondeleteenvironmentconfiguration-get
  description: Deletes the draft configuration associated with the running environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actiondeleteenvironmentconfiguration-get-openapi.md
- name: AWS Elastic Beanstalk API - Describe Environment Health
  x-api-slug: actiondescribeenvironmenthealth-get
  description: Returns information about the overall health of the specified environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actiondescribeenvironmenthealth-get-openapi.md
- name: AWS Elastic Beanstalk API - Describe Environment Managed Action History
  x-api-slug: actiondescribeenvironmentmanagedactionhistory-get
  description: Lists an environment's completed and failed managed actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actiondescribeenvironmentmanagedactionhistory-get-openapi.md
- name: AWS Elastic Beanstalk API - Describe Environment Managed Actions
  x-api-slug: actiondescribeenvironmentmanagedactions-get
  description: Lists an environment's upcoming and in-progress managed actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actiondescribeenvironmentmanagedactions-get-openapi.md
- name: AWS Elastic Beanstalk API - Describe Environment Resources
  x-api-slug: actiondescribeenvironmentresources-get
  description: Returns AWS resources for this environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actiondescribeenvironmentresources-get-openapi.md
- name: AWS Elastic Beanstalk API - Describe Environments
  x-api-slug: actiondescribeenvironments-get
  description: Returns descriptions for existing environments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actiondescribeenvironments-get-openapi.md
- name: AWS Elastic Beanstalk API - Rebuild Environment
  x-api-slug: actionrebuildenvironment-get
  description: |-
    Deletes and recreates all of the AWS resources (for example: the Auto Scaling group,
          load balancer, etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actionrebuildenvironment-get-openapi.md
- name: AWS Elastic Beanstalk API - Request Environment Info
  x-api-slug: actionrequestenvironmentinfo-get
  description: |-
    Initiates a request to compile the specified type of information of the deployed
          environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actionrequestenvironmentinfo-get-openapi.md
- name: AWS Elastic Beanstalk API - Retrieve Environment Info
  x-api-slug: actionretrieveenvironmentinfo-get
  description: Retrieves the compiled information from a.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actionretrieveenvironmentinfo-get-openapi.md
- name: AWS Elastic Beanstalk API - Swap Environment C N A M Es
  x-api-slug: actionswapenvironmentcnames-get
  description: Swaps the CNAMEs of two environments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actionswapenvironmentcnames-get-openapi.md
- name: AWS Elastic Beanstalk API - Terminate Environment
  x-api-slug: actionterminateenvironment-get
  description: Terminates the specified environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actionterminateenvironment-get-openapi.md
- name: AWS Elastic Beanstalk API - Update Environment
  x-api-slug: actionupdateenvironment-get
  description: |-
    Updates the environment description, deploys a new application version, updates the
          configuration settings to an entirely new configuration template, or updates select
          configuration option values in the running environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/aws-elastic-beanstalk/actionupdateenvironment-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.ec2.systems.manager.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.elastic.beanstalk.stack.network
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/AWS-Elastic-Beanstalk
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3.html
- type: x-documentation
  url: http://docs.aws.amazon.com/elasticbeanstalk/latest/api/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/elasticbeanstalk/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=86
- type: x-getting-started
  url: https://aws.amazon.com/elasticbeanstalk/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/elasticbeanstalk/pricing/
- type: x-website
  url: https://aws.amazon.com/elasticbeanstalk/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---