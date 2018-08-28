---
name: Atlassian
x-slug: atlassian
description: Millions of users globally rely on Atlassian products every day for improving
  software development, project management, collaboration, and code quality.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
x-kinRank: "8"
x-alexaRank: "1656"
tags: Themes
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/apis.md
specificationVersion: "0.14"
apis:
- name: The Confluence Cloud REST API - Get themes
  x-api-slug: settingstheme-get
  description: |-
    Returns all themes, not including the default theme.

    **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingstheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingstheme-get-openapi.md
- name: The Confluence Cloud REST API - Get global theme
  x-api-slug: settingsthemeselected-get
  description: |-
    Returns the globally assigned theme.

    **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemeselected-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemeselected-get-openapi.md
- name: The Confluence Cloud REST API - Get theme
  x-api-slug: settingsthemethemekey-get
  description: |-
    Returns a theme. This includes information about the theme name,
    description, and icon.

    **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemethemekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemethemekey-get-openapi.md
- name: The Confluence Cloud REST API - Get space theme
  x-api-slug: spacespacekeytheme-get
  description: "Returns the theme selected for a space, if one is set. If no space
    \ntheme is set, this means that the space is inheriting the global look \nand
    feel settings.\n\n**[Permissions required](https://confluence.atlassian.com/x/_AozKw)**:
    \u2018View\u2019 permission for the space."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-get-openapi.md
- name: The Confluence Cloud REST API - Set space theme
  x-api-slug: spacespacekeytheme-put
  description: "Sets the theme for a space. Note, if you want to reset the space theme
    to \nthe default Confluence theme, use the 'Reset space theme' method instead
    \nof this method.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**:\n'Admin' permission for the space."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-put-openapi.md
- name: The Confluence Cloud REST API - Reset space theme
  x-api-slug: spacespacekeytheme-delete
  description: "Resets the space theme. This means that the space will inherit the
    \nglobal look and feel settings\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**:\n'Admin' permission for the space."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-delete-openapi.md
- name: The Confluence Cloud REST API - Get global theme
  x-api-slug: settingsthemeselected-get
  description: |-
    Returns the globally assigned theme.

    **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemeselected-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemeselected-get-openapi.md
- name: The Confluence Cloud REST API - Get theme
  x-api-slug: settingsthemethemekey-get
  description: |-
    Returns a theme. This includes information about the theme name,
    description, and icon.

    **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemethemekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemethemekey-get-openapi.md
- name: The Confluence Cloud REST API - Get space theme
  x-api-slug: spacespacekeytheme-get
  description: "Returns the theme selected for a space, if one is set. If no space
    \ntheme is set, this means that the space is inheriting the global look \nand
    feel settings.\n\n**[Permissions required](https://confluence.atlassian.com/x/_AozKw)**:
    \u2018View\u2019 permission for the space."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-get-openapi.md
- name: The Confluence Cloud REST API - Set space theme
  x-api-slug: spacespacekeytheme-put
  description: "Sets the theme for a space. Note, if you want to reset the space theme
    to \nthe default Confluence theme, use the 'Reset space theme' method instead
    \nof this method.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**:\n'Admin' permission for the space."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-put-openapi.md
- name: The Confluence Cloud REST API - Reset space theme
  x-api-slug: spacespacekeytheme-delete
  description: "Resets the space theme. This means that the space will inherit the
    \nglobal look and feel settings\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**:\n'Admin' permission for the space."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-delete-openapi.md
- name: The Confluence Cloud REST API - Reset space theme
  x-api-slug: spacespacekeytheme-delete
  description: "Resets the space theme. This means that the space will inherit the
    \nglobal look and feel settings\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**:\n'Admin' permission for the space."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-delete-openapi.md
- name: The Confluence Cloud REST API - Reset space theme
  x-api-slug: spacespacekeytheme-delete
  description: "Resets the space theme. This means that the space will inherit the
    \nglobal look and feel settings\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**:\n'Admin' permission for the space."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-delete-openapi.md
- name: The Confluence Cloud REST API - Set space theme
  x-api-slug: spacespacekeytheme-put
  description: "Sets the theme for a space. Note, if you want to reset the space theme
    to \nthe default Confluence theme, use the 'Reset space theme' method instead
    \nof this method.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**:\n'Admin' permission for the space."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-put-openapi.md
- name: The Confluence Cloud REST API - Set space theme
  x-api-slug: spacespacekeytheme-put
  description: "Sets the theme for a space. Note, if you want to reset the space theme
    to \nthe default Confluence theme, use the 'Reset space theme' method instead
    \nof this method.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**:\n'Admin' permission for the space."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-put-openapi.md
- name: The Confluence Cloud REST API - Get space theme
  x-api-slug: spacespacekeytheme-get
  description: "Returns the theme selected for a space, if one is set. If no space
    \ntheme is set, this means that the space is inheriting the global look \nand
    feel settings.\n\n**[Permissions required](https://confluence.atlassian.com/x/_AozKw)**:
    \u2018View\u2019 permission for the space."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-get-openapi.md
- name: The Confluence Cloud REST API - Get space theme
  x-api-slug: spacespacekeytheme-get
  description: "Returns the theme selected for a space, if one is set. If no space
    \ntheme is set, this means that the space is inheriting the global look \nand
    feel settings.\n\n**[Permissions required](https://confluence.atlassian.com/x/_AozKw)**:
    \u2018View\u2019 permission for the space."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/spacespacekeytheme-get-openapi.md
- name: The Confluence Cloud REST API - Get theme
  x-api-slug: settingsthemethemekey-get
  description: |-
    Returns a theme. This includes information about the theme name,
    description, and icon.

    **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemethemekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemethemekey-get-openapi.md
- name: The Confluence Cloud REST API - Get theme
  x-api-slug: settingsthemethemekey-get
  description: |-
    Returns a theme. This includes information about the theme name,
    description, and icon.

    **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemethemekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemethemekey-get-openapi.md
- name: The Confluence Cloud REST API - Get global theme
  x-api-slug: settingsthemeselected-get
  description: |-
    Returns the globally assigned theme.

    **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemeselected-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemeselected-get-openapi.md
- name: The Confluence Cloud REST API - Get global theme
  x-api-slug: settingsthemeselected-get
  description: |-
    Returns the globally assigned theme.

    **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**: None
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemeselected-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/themes/master/_listings/atlassian/settingsthemeselected-get-openapi.md
x-common:
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/platform/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/confluence/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/software/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/service-desk/swagger.v3.json
- type: x-website
  url: http://atlassian.com/
- type: x-website
  url: http://www.atlassian.com
- type: x-api-gallery
  url: http://att.dev.program.api.gallery.streamdata.io
- type: x-api-stack
  url: http://atlassian.stack.network
- type: x-blog
  url: http://blogs.atlassian.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/atlassian
- type: x-crunchbase
  url: http://www.crunchbase.com/company/atlassian
- type: x-email
  url: copyright@atlassian.com
- type: x-email
  url: trademarks@atlassian.com
- type: x-email
  url: sales@atlassian.com
- type: x-email
  url: ar_enterprise@atlassian.com
- type: x-email
  url: privacy@atlassian.com
- type: x-email
  url: eudatarep@atlassian.com
- type: x-email
  url: experts@atlassian.com
- type: x-email
  url: remittance@atlassian.com
- type: x-email
  url: ap@atlassian.com
- type: x-email
  url: procurement@atlassian.com
- type: x-github
  url: https://github.com/atlassian
- type: x-privacy-policy
  url: https://www.atlassian.com/legal/privacy-policy?_ga=2.188884514.868776184.1519225620-845241124.1519225620
- type: x-twitter
  url: https://twitter.com/atlassian
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---