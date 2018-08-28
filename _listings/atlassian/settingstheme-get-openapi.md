---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Confluence Cloud API Get themes
  description: |-
    Returns all themes, not including the default theme.

    **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /settings/theme:
    get:
      summary: Get themes
      description: |-
        Returns all themes, not including the default theme.

        **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
      operationId: com.atlassian.confluence.plugins.restapi.resources.ThemeResource.getThemes_get
      x-api-path-slug: settingstheme-get
      parameters:
      - in: query
        name: limit
        description: The maximum number of themes to return per page
      - in: query
        name: start
        description: The starting index of the returned themes
      responses:
        200:
          description: OK
      tags:
      - Themes
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