---
name: BMC Software
x-slug: bmc-software
description: Transform your digital enterprise with BMC IT solutions. From mainframe
  to cloud to mobile, we???ll help you drive innovation and industrial efficiency.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
x-kinRank: "8"
x-alexaRank: "27308"
tags: Relays
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/apis.md
specificationVersion: "0.14"
apis:
- name: BMC Software Merged API - Set Relay Heartbeat
  x-api-slug: v1relaysheartbeat-post
  description: |-
    Updates the &#39;lastHeardFrom&#39; field of the relay configuration
    Returns the current system time in UNIX epoch of server.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: https:///
  tags: Monitoring, Applications, Devops, SaaS, Enterprise, Technology, ISP, API Provider,
    API Service Provider, Profiles, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysheartbeat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysheartbeat-post-openapi.md
- name: BMC Software Merged API - Get All Relay Configurations
  x-api-slug: v1relays-get
  description: Gets the configurations for all visible relays
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: https:///
  tags: Monitoring, Applications, Devops, SaaS, Enterprise, Technology, ISP, API Provider,
    API Service Provider, Profiles, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relays-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relays-get-openapi.md
- name: BMC Software Merged API - Get Relay Configuration
  x-api-slug: v1relaysrelayconfig-get
  description: |-
    Retrieves config for a relay host if changed
    If no timestamp specified, configuration data is always returned
    If config has not changed the string &#39;not-modified&#39; is returned
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: https:///
  tags: Monitoring, Applications, Devops, SaaS, Enterprise, Technology, ISP, API Provider,
    API Service Provider, Profiles, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelayconfig-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelayconfig-get-openapi.md
- name: BMC Software Merged API - Set Relay Configuration
  x-api-slug: v1relaysrelayconfig-put
  description: |-
    Stores configuration for a relay.
     The relay will gather the configuration on the next poll and reconfigure itself as needed.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: https:///
  tags: Monitoring, Applications, Devops, SaaS, Enterprise, Technology, ISP, API Provider,
    API Service Provider, Profiles, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelayconfig-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelayconfig-put-openapi.md
- name: BMC Software Merged API - Toggle relay
  x-api-slug: v1relaysrelaytoggle-post
  description: Set a relay to be disabled or enabled
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: https:///
  tags: Monitoring, Applications, Devops, SaaS, Enterprise, Technology, ISP, API Provider,
    API Service Provider, Profiles, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelaytoggle-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelaytoggle-post-openapi.md
- name: BMC Software Merged API - Toggle relay plugin
  x-api-slug: v1relaysrelaytoggleplugin-post
  description: Sets a relay plugin to be disabled or enabled
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: https:///
  tags: Monitoring, Applications, Devops, SaaS, Enterprise, Technology, ISP, API Provider,
    API Service Provider, Profiles, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelaytoggleplugin-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelaytoggleplugin-post-openapi.md
- name: BMC Software Merged API - Add relay output
  x-api-slug: v1relaysrelayoutput-post
  description: |-
    Adds output messages to the relay.
    Used by the relay to communicate output from execution and commands
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: https:///
  tags: Monitoring, Applications, Devops, SaaS, Enterprise, Technology, ISP, API Provider,
    API Service Provider, Profiles, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelayoutput-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelayoutput-post-openapi.md
- name: BMC Software Merged API - Get relay output
  x-api-slug: v1relaysrelayoutputsince-get
  description: Queries for relay output messages.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: https:///
  tags: Monitoring, Applications, Devops, SaaS, Enterprise, Technology, ISP, API Provider,
    API Service Provider, Profiles, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelayoutputsince-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelayoutputsince-get-openapi.md
- name: BMC Software Merged API - Clear relay output
  x-api-slug: v1relaysrelayoutput-delete
  description: Wipes the logged output from the relay up to present.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: https:///
  tags: Monitoring, Applications, Devops, SaaS, Enterprise, Technology, ISP, API Provider,
    API Service Provider, Profiles, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelayoutput-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/relays/master/_listings/bmc-software/v1relaysrelayoutput-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://blogger.api.gallery.streamdata.io
- type: x-api-stack
  url: http://bmc.software.stack.network
- type: x-blog
  url: http://www.bmc.com/blogs
- type: x-blog-rss
  url: http://feeds.feedburner.com/BmcBlogs
- type: x-crunchbase
  url: https://crunchbase.com/organization/bmc
- type: x-documentation
  url: https://docs.bmc.com/docs/dashboard.action
- type: x-email
  url: customer_support@bmc.com
- type: x-email
  url: NA_Accounts_Payable@bmc.com
- type: x-email
  url: Collections_NA@bmc.com
- type: x-email
  url: education@bmc.com
- type: x-email
  url: investor@bmc.com
- type: x-email
  url: global_security@bmc.com
- type: x-email
  url: Compliance_EthicsOffice@bmc.com
- type: x-email
  url: 26Ethics@bmc.com
- type: x-email
  url: Community_Relations@bmc.com
- type: x-github
  url: https://github.com/bmcsoftware
- type: x-twitter
  url: https://twitter.com/bmcsoftware
- type: x-website
  url: http://www.bmc.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---