---
swagger: "2.0"
info:
  title: AWS Directory Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListTagsForResource&k=1:
    get:
      summary: ' List Tags For Resource '
      description: Lists all tags on a directory
      operationId: listTagsForResource
      parameters:
      - in: query
        name: Limit
        description: Reserved for future use
        type: string
      - in: query
        name: NextToken
        description: Reserved for future use
        type: string
      - in: query
        name: ResourceId
        description: Identifier (ID) of the directory for which you want to retrieve
          tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - resource tags
definitions: []
x-collection-name: AWS Directory Service
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