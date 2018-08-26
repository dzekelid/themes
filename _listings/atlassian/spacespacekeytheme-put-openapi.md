---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Confluence Cloud API Set space theme
  description: "Sets the theme for a space. Note, if you want to reset the space theme
    to \nthe default Confluence theme, use the 'Reset space theme' method instead
    \nof this method.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**:\n'Admin' permission for the space."
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
  /settings/theme/selected:
    get:
      summary: Get global theme
      description: |-
        Returns the globally assigned theme.

        **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
      operationId: com.atlassian.confluence.plugins.restapi.resources.ThemeResource.getGlobalTheme_get
      x-api-path-slug: settingsthemeselected-get
      responses:
        200:
          description: OK
      tags:
      - Global
      - Theme
  /settings/theme/{themeKey}:
    get:
      summary: Get theme
      description: |-
        Returns a theme. This includes information about the theme name,
        description, and icon.

        **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
      operationId: com.atlassian.confluence.plugins.restapi.resources.ThemeResource.getTheme_get
      x-api-path-slug: settingsthemethemekey-get
      parameters:
      - in: path
        name: themeKey
        description: The key of the theme to be returned
      responses:
        200:
          description: OK
      tags:
      - Theme
  /space/{spaceKey}/theme:
    get:
      summary: Get space theme
      description: "Returns the theme selected for a space, if one is set. If no space
        \ntheme is set, this means that the space is inheriting the global look \nand
        feel settings.\n\n**[Permissions required](https://confluence.atlassian.com/x/_AozKw)**:
        \u2018View\u2019 permission for the space."
      operationId: com.atlassian.confluence.plugins.restapi.resources.SpaceThemeResource.getSpaceTheme_get
      x-api-path-slug: spacespacekeytheme-get
      parameters:
      - in: path
        name: spaceKey
        description: The key of the space to be queried for its theme
      responses:
        200:
          description: OK
      tags:
      - Space
      - Theme
    put:
      summary: Set space theme
      description: "Sets the theme for a space. Note, if you want to reset the space
        theme to \nthe default Confluence theme, use the 'Reset space theme' method
        instead \nof this method.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**:\n'Admin' permission for the space."
      operationId: com.atlassian.confluence.plugins.restapi.resources.SpaceThemeResource.setSpaceTheme_put
      x-api-path-slug: spacespacekeytheme-put
      parameters:
      - in: path
        name: spaceKey
        description: The key of the space to set the theme for
      responses:
        200:
          description: OK
      tags:
      - Set
      - Space
      - Theme
    delete:
      summary: Reset space theme
      description: "Resets the space theme. This means that the space will inherit
        the \nglobal look and feel settings\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**:\n'Admin' permission for the space."
      operationId: com.atlassian.confluence.plugins.restapi.resources.SpaceThemeResource.resetSpaceTheme_delete
      x-api-path-slug: spacespacekeytheme-delete
      parameters:
      - in: path
        name: spaceKey
        description: The key of the space to reset the theme for
      responses:
        200:
          description: OK
      tags:
      - Reset
      - Space
      - Theme
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