---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 0
info:
  title: Reddit Get Multi Multipath Srname
  description: Get data about a subreddit in a multi.
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
    get&nbsp;:
      summary: Get Multi Multipath
      description: Fetch a multi&#39;s data and subreddit list by name.
      operationId: get&nbsp;MultiMultipath
      x-api-path-slug: multimultipath-getnbsp
      parameters:
      - in: query
        name: expand_srs
        description: boolean value
        type: string
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
    post&nbsp;:
      summary: Add Multi Multipath
      description: Create a multi. Responds with 409 Conflict if it already exists.
      operationId: post&nbsp;MultiMultipath
      x-api-path-slug: multimultipath-postnbsp
      parameters:
      - in: query
        name: expand_srs
        description: boolean value
        type: string
      - in: query
        name: model
        description: 'json data:{  &quot;description_md&quot;: raw markdown text,  &quot;display_name&quot;:
          a string no longer than 50 characters,  &quot;icon_name&quot;: one of (`art
          and design`, `ask`, `books`, `business`, `cars`, `comics`, `cute animals`,
          `diy`, `entertainment`, `food and drink`, `funny`, `games`, `grooming`,
          `health`, `life advice`, `military`, `models pinup`, `music`, `news`, `philosophy`,
          `pictures and gifs`, `science`, `shopping`, `sports`, `style`, `tech`, `travel`,
          `unusual stories`, `video`, ``, `None`),  &quot;key_color&quot;: a 6-digit
          rgb hex color, e'
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
    put&nbsp;:
      summary: Put Multi Multipath
      description: Create or update a multi.
      operationId: put&nbsp;MultiMultipath
      x-api-path-slug: multimultipath-putnbsp
      parameters:
      - in: query
        name: expand_srs
        description: boolean value
        type: string
      - in: query
        name: model
        description: 'json data:{  &quot;description_md&quot;: raw markdown text,  &quot;display_name&quot;:
          a string no longer than 50 characters,  &quot;icon_name&quot;: one of (`art
          and design`, `ask`, `books`, `business`, `cars`, `comics`, `cute animals`,
          `diy`, `entertainment`, `food and drink`, `funny`, `games`, `grooming`,
          `health`, `life advice`, `military`, `models pinup`, `music`, `news`, `philosophy`,
          `pictures and gifs`, `science`, `shopping`, `sports`, `style`, `tech`, `travel`,
          `unusual stories`, `video`, ``, `None`),  &quot;key_color&quot;: a 6-digit
          rgb hex color, e'
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
  /multi/multipath/description:
    get&nbsp;:
      summary: Get Multi Multipath Description
      description: Get a multi&#39;s description.
      operationId: get&nbsp;MultiMultipathDescription
      x-api-path-slug: multimultipathdescription-getnbsp
      parameters:
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
      - Description
    put&nbsp;:
      summary: Put Multi Multipath Description
      description: Change a multi&#39;s markdown description.
      operationId: put&nbsp;MultiMultipathDescription
      x-api-path-slug: multimultipathdescription-putnbsp
      parameters:
      - in: query
        name: model
        description: 'json data:{  &quot;body_md&quot;: raw markdown text,}'
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
      - Description
  /multi/multipath/r/srname:
    delete&nbsp;:
      summary: Delete Multi Multipath Srname
      description: Remove a subreddit from a multi.
      operationId: delete&nbsp;MultiMultipathRSrname
      x-api-path-slug: multimultipathrsrname-deletenbsp
      parameters:
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      - in: query
        name: srname
        description: subreddit name
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
      - Srname
    get&nbsp;:
      summary: Get Multi Multipath Srname
      description: Get data about a subreddit in a multi.
      operationId: get&nbsp;MultiMultipathRSrname
      x-api-path-slug: multimultipathrsrname-getnbsp
      parameters:
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      - in: query
        name: srname
        description: subreddit name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
      - Srname
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