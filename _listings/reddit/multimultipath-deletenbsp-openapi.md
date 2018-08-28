---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 0
info:
  title: Reddit Delete Multi Multipath
  description: Delete a multi.
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /multi/copy:
    post&nbsp;:
      summary: Add Multi Copy
      description: Copy a multi.
      operationId: post&nbsp;MultiCopy
      x-api-path-slug: multicopy-postnbsp
      parameters:
      - in: query
        name: display_name
        description: a string no longer than 50 characters
        type: string
      - in: query
        name: from
        description: multireddit url path
        type: string
      - in: query
        name: to
        description: destination multireddit url path
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Copy
  /multi/mine:
    get&nbsp;:
      summary: Get Multi Mine
      description: Fetch a list of multis belonging to the current user.
      operationId: get&nbsp;MultiMine
      x-api-path-slug: multimine-getnbsp
      parameters:
      - in: query
        name: expand_srs
        description: boolean value
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Mine
  /multi/rename:
    post&nbsp;:
      summary: Add Multi Rename
      description: Rename a multi.
      operationId: post&nbsp;MultiRename
      x-api-path-slug: multirename-postnbsp
      parameters:
      - in: query
        name: display_name
        description: a string no longer than 50 characters
        type: string
      - in: query
        name: from
        description: multireddit url path
        type: string
      - in: query
        name: to
        description: destination multireddit url path
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Rename
  /multi/user/username:
    get&nbsp;:
      summary: Get Multi User Username
      description: Fetch a list of public multis belonging to username
      operationId: get&nbsp;MultiUserUsername
      x-api-path-slug: multiuserusername-getnbsp
      parameters:
      - in: query
        name: expand_srs
        description: boolean value
        type: string
      - in: query
        name: username
        description: A valid, existing reddit username
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - User
      - Username
  /multi/multipath:
    delete&nbsp;:
      summary: Delete Multi Multipath
      description: Delete a multi.
      operationId: delete&nbsp;MultiMultipath
      x-api-path-slug: multimultipath-deletenbsp
      parameters:
      - in: query
        name: expand_srs
        description: boolean value
        type: string
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
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