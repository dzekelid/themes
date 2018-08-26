---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/themes/164593742.json:
    put:
      summary: Update a theme's attributes
      description: Update a theme's attributes.
      operationId: putAdminThemes164593742.json
      x-api-path-slug: adminthemes164593742-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Themes
      - Attributes
    delete:
      summary: Delete a theme
      description: Delete a theme.
      operationId: deleteAdminThemes164593742.json
      x-api-path-slug: adminthemes164593742-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Theme
  /admin/themes.json:
    get:
      summary: Get all shop themes
      description: Get all shop themes.
      operationId: getAdminThemes.json
      x-api-path-slug: adminthemes-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Shop
      - Themes
    post:
      summary: Create a new theme
      description: Create a new theme.
      operationId: postAdminThemes.json
      x-api-path-slug: adminthemes-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Theme
  /admin/themes/110163843/assets.json:
    get:
      summary: Get a list of all theme assets
      description: Get a list of all theme assets.
      operationId: getAdminThemes110163843Assets.json
      x-api-path-slug: adminthemes110163843assets-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Theme
      - Assets
  /admin/themes/110163843.json:
    get:
      summary: Get a single theme
      description: Get a single theme.
      operationId: getAdminThemes110163843.json
      x-api-path-slug: adminthemes110163843-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Theme
---