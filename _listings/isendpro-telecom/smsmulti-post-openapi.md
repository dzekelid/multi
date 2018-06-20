---
swagger: "2.0"
x-collection-name: iSendPro Telecom
x-complete: 0
info:
  title: API i Send Pro Envoyer des SMS
  description: Envoi de SMS vers 1 ou plusieurs destinataires
  termsOfService: https://www.isendpro.com/cgv.php
  contact:
    name: iSendPro Support Team
    url: https://www.isendpro.com/
    email: support@isendpro.com
  version: 1.0.0
host: apirest.isendpro.com
basePath: /cgi-bin
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /smsmulti:
    post:
      summary: Envoyer des SMS
      description: Envoi de SMS vers 1 ou plusieurs destinataires
      operationId: sendSmsMulti
      x-api-path-slug: smsmulti-post
      parameters:
      - in: body
        name: smsrequest
        description: sms request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Smsmulti
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