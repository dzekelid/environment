---
name: Google Tag Manager
x-slug: google-tag-manager
description: Deploy and update measurement tags on your websites and mobile apps without
  major code changes and app releases. Use Google Tag Manager to manage tags (such
  as tracking and marketing optimization JavaScript tags) on your site. Without editing
  your site code, you use GTM user interface to add and update AdWords, Google Analytics,
  Floodlight, and non-Google tags. This reduces errors and allows you to to deploy
  tags on your site quickly.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Environment
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/google-tag-manager/apis.md
specificationVersion: "0.14"
apis:
- name: Tag Manager - Get GTM Environments
  x-api-slug: accountsaccountidcontainerscontaineridenvironments-get
  description: Lists all GTM Environments of a GTM Container.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridenvironments-get-openapi.md
- name: Tag Manager - Create GTM Environment
  x-api-slug: accountsaccountidcontainerscontaineridenvironments-post
  description: Creates a GTM Environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridenvironments-post-openapi.md
- name: Tag Manager - Delete GTM Environment
  x-api-slug: accountsaccountidcontainerscontaineridenvironmentsenvironmentid-delete
  description: Deletes a GTM Environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridenvironmentsenvironmentid-delete-openapi.md
- name: Tag Manager - Get GTM Environment
  x-api-slug: accountsaccountidcontainerscontaineridenvironmentsenvironmentid-get
  description: Gets a GTM Environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridenvironmentsenvironmentid-get-openapi.md
- name: Tag Manager - Update GTM Environment
  x-api-slug: accountsaccountidcontainerscontaineridenvironmentsenvironmentid-patch
  description: Updates a GTM Environment. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridenvironmentsenvironmentid-patch-openapi.md
- name: Tag Manager - Update GTM Environment
  x-api-slug: accountsaccountidcontainerscontaineridenvironmentsenvironmentid-put
  description: Updates a GTM Environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridenvironmentsenvironmentid-put-openapi.md
- name: Tag Manager - Regenerate Authorization
  x-api-slug: accountsaccountidcontainerscontaineridreauthorize-environmentsenvironmentid-put
  description: Re-generates the authorization code for a GTM Environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/googl_tag_manager_gplus-250.png
  humanURL: https://developers.google.com/tag-manager/
  baseURL: ://www.googleapis.com//tagmanager/v1
  tags: Google APIs, Tags, Stack Network, API Service Provider, API Provider, Profiles,
    Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environment/master/_listings/google-tag-manager/accountsaccountidcontainerscontaineridreauthorize-environmentsenvironmentid-put-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.stackdriver.monitoring.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.tag.manager.stack.network
- type: x-authentication
  url: https://developers.google.com/tag-manager/api/v1/authorization
- type: x-change-log
  url: https://developers.google.com/tag-manager/api/v1/changelog
- type: x-code
  url: https://developers.google.com/tag-manager/api/v1/libraries
- type: x-documentation
  url: https://developers.google.com/tag-manager/api/v1/
- type: x-performance
  url: https://developers.google.com/tag-manager/api/v1/performance
- type: x-website
  url: https://developers.google.com/tag-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---