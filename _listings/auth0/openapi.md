---
swagger: "2.0"
x-collection-name: Auth0
x-complete: 1
info:
  title: Auth0 Users API
  version: v1
host: login.auth0.com
basePath: /users
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v2/users/{id}/multifactor/{provider}:
    delete:
      summary: Deletes a multifactor provider for a user.
      description: Deletes a multifactor provider for a user..
      operationId: delete_multifactor_by_provider
      x-api-path-slug: apiv2usersidmultifactorprovider-delete
      parameters:
      - in: path
        name: id
        description: The user_id of the user to delete
      - in: path
        name: provider
        description: The multifactor provider
      responses:
        200:
          description: OK
      tags:
      - Users
      - Id
      - Multifactor
      - Provider
---