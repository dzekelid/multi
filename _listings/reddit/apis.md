---
name: Reddit
x-slug: reddit
description: Reddit is a community of millions of users engaging in the creation of
  content and the sharing of conversation across tens of thousands of topics.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
x-kinRank: "9"
x-alexaRank: "6"
tags: Multi
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/apis.md
specificationVersion: "0.14"
apis:
- name: Reddit Add Multi Copy
  x-api-slug: reddit
  description: Copy a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/copy
  tags: Multi, Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multicopy-postnbsp-openapi.md
- name: Reddit Get Multi Mine
  x-api-slug: reddit
  description: Fetch a list of multis belonging to the current user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/mine
  tags: Multi, Mine
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimine-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimine-getnbsp-openapi.md
- name: Reddit Add Multi Rename
  x-api-slug: reddit
  description: Rename a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/rename
  tags: Multi, Rename
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multirename-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multirename-postnbsp-openapi.md
- name: Reddit Get Multi User Username
  x-api-slug: reddit
  description: Fetch a list of public multis belonging to username
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/user/username
  tags: Multi, User, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multiuserusername-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multiuserusername-getnbsp-openapi.md
- name: Reddit Delete Multi Multipath
  x-api-slug: reddit
  description: Delete a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/multipath
  tags: Multi, Multipath
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipath-deletenbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipath-deletenbsp-openapi.md
- name: Reddit Get Multi Multipath
  x-api-slug: reddit
  description: Fetch a multi&#39;s data and subreddit list by name.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/multipath
  tags: Multi, Multipath
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipath-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipath-getnbsp-openapi.md
- name: Reddit Add Multi Multipath
  x-api-slug: reddit
  description: Create a multi. Responds with 409 Conflict if it already exists.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/multipath
  tags: Multi, Multipath
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipath-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipath-postnbsp-openapi.md
- name: Reddit Put Multi Multipath
  x-api-slug: reddit
  description: Create or update a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/multipath
  tags: Multi, Multipath
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipath-putnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipath-putnbsp-openapi.md
- name: Reddit Get Multi Multipath Description
  x-api-slug: reddit
  description: Get a multi&#39;s description.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/multipath/description
  tags: Multi, Multipath, Description
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipathdescription-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipathdescription-getnbsp-openapi.md
- name: Reddit Put Multi Multipath Description
  x-api-slug: reddit
  description: Change a multi&#39;s markdown description.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/multipath/description
  tags: Multi, Multipath, Description
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipathdescription-putnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipathdescription-putnbsp-openapi.md
- name: Reddit Delete Multi Multipath Srname
  x-api-slug: reddit
  description: Remove a subreddit from a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/multipath/r/srname
  tags: Multi, Multipath, Srname
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipathrsrname-deletenbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipathrsrname-deletenbsp-openapi.md
- name: Reddit Get Multi Multipath Srname
  x-api-slug: reddit
  description: Get data about a subreddit in a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/multipath/r/srname
  tags: Multi, Multipath, Srname
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipathrsrname-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipathrsrname-getnbsp-openapi.md
- name: Reddit Put Multi Multipath Srname
  x-api-slug: reddit
  description: Add a subreddit to a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/multipath/r/srname
  tags: Multi, Multipath, Srname
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipathrsrname-putnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/multimultipathrsrname-putnbsp-openapi.md
- name: Reddit
  x-api-slug: reddit
  description: Reddit is a community of millions of users engaging in the creation
    of content and the sharing of conversation across tens of thousands of topics.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Multi
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/multi/master/_listings/reddit/openapi.md
x-common:
- type: x-authentication
  url: https://github.com/reddit/reddit/wiki/OAuth2
- type: x-base
  url: https://www.reddit.com/
- type: x-best-practices
  url: https://github.com/reddit/reddit/wiki/API
- type: x-blog
  url: http://www.redditblog.com/
- type: x-blog-rss
  url: https://www.reddit.com/r/datasets/.rss
- type: x-blog-rss
  url: http://www.redditblog.com/feeds/posts/default?alt=rss
- type: x-code-libraries
  url: https://github.com/reddit/reddit/wiki/API-Wrappers
- type: x-console
  url: https://apigee.com/console/reddit
- type: x-crunchbase
  url: https://crunchbase.com/organization/reddit
- type: x-developer
  url: http://www.reddit.com/dev/api
- type: x-email
  url: legal@reddit.com
- type: x-github
  url: https://github.com/reddit
- type: x-privacy
  url: https://www.reddit.com/help/privacypolicy
- type: x-security
  url: https://www.reddit.com/help/privacypolicy#section_security
- type: x-support
  url: https://www.reddit.com/contact/
- type: x-terms-of-service
  url: http://www.reddit.com/help/useragreement
- type: x-transparency-report
  url: https://www.reddit.com/wiki/transparency
- type: x-twitter
  url: https://twitter.com/reddit
- type: x-website
  url: http://www.reddit.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---