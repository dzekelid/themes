---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix AppHub ARCS Delete theme
  description: Delete theme
  termsOfService: Terms of service
  contact:
    name: 'Digital Predix AppHub ARCS: Development'
  version: 1.0.0
host: predix-apphub-arcs-prod.run.aws-usw02-pr.ice.predix.io
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /themes:
    get:
      summary: Get theme information for a tenant
      description: Get theme information
      operationId: getThemeUsingGET
      x-api-path-slug: themes-get
      responses:
        200:
          description: OK
      tags:
      - Themes
    post:
      summary: Save theme config information
      description: Save theme config information
      operationId: saveThemeUsingPOST
      x-api-path-slug: themes-post
      parameters:
      - in: body
        name: theme
        description: theme
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Themes
    put:
      summary: Update theme
      description: Update theme
      operationId: updateThemeUsingPUT
      x-api-path-slug: themes-put
      parameters:
      - in: body
        name: theme
        description: theme
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Themes
  /themes/{uuid}:
    get:
      summary: Get the registered theme by uri
      description: Get the registered theme infromation for the given uri
      operationId: getThemeInfoByIdUsingGET
      x-api-path-slug: themesuuid-get
      parameters:
      - in: path
        name: uuid
        description: uuid
      responses:
        200:
          description: OK
      tags:
      - Themes
      - Uuid
    delete:
      summary: Delete theme
      description: Delete theme
      operationId: deleteThemeUsingDELETE
      x-api-path-slug: themesuuid-delete
      parameters:
      - in: path
        name: uuid
        description: uuid
      responses:
        200:
          description: OK
      tags:
      - Themes
      - Uuid
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