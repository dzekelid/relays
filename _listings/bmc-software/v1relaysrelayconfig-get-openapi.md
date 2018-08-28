---
swagger: "2.0"
x-collection-name: BMC Software
x-complete: 0
info:
  title: BMC Software API Get Relay Configuration
  version: 1.0.0
  description: |-
    Retrieves config for a relay host if changed
    If no timestamp specified, configuration data is always returned
    If config has not changed the string &#39;not-modified&#39; is returned
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/relays/heartbeat:
    post:
      summary: Set Relay Heartbeat
      description: |-
        Updates the &#39;lastHeardFrom&#39; field of the relay configuration
        Returns the current system time in UNIX epoch of server.
      operationId: set-relay-heartbeat
      x-api-path-slug: v1relaysheartbeat-post
      responses:
        200:
          description: OK
      tags:
      - Relays
  /v1/relays:
    get:
      summary: Get All Relay Configurations
      description: Gets the configurations for all visible relays
      operationId: get-all-relay-configurations
      x-api-path-slug: v1relays-get
      responses:
        200:
          description: OK
      tags:
      - Relays
  /v1/relays/:relay/config:
    get:
      summary: Get Relay Configuration
      description: |-
        Retrieves config for a relay host if changed
        If no timestamp specified, configuration data is always returned
        If config has not changed the string &#39;not-modified&#39; is returned
      operationId: get-relay-configuration
      x-api-path-slug: v1relaysrelayconfig-get
      responses:
        200:
          description: OK
      tags:
      - Relays
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