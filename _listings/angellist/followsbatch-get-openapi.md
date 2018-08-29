---
swagger: "2.0"
x-collection-name: AngelList
x-complete: 0
info:
  title: AngelList Get Batch of Follows
  description: Returns a batched lists of follows
  termsOfService: https://angel.co/terms
  contact:
    name: AngelList
    url: https://angel.co/api
    email: api@angel.co
  version: v1
host: api.angel.co
basePath: /1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accreditation:
    get:
      summary: Get Accreditation
      description: Pulls the accreditation for a startup and users.
      operationId: accreditation
      x-api-path-slug: accreditation-get
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
  /comments:
    get:
      summary: Get Comments
      description: Pulls the comments for given object.
      operationId: comments
      x-api-path-slug: comments-get
      parameters:
      - in: query
        name: commentable_id
      - in: query
        name: commentable_type
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Comments
    post:
      summary: Add Comment
      description: Adds a comment for given object
      operationId: comment
      x-api-path-slug: comments-post
      parameters:
      - in: query
        name: comment
      - in: query
        name: commentable_id
      - in: query
        name: commentable_type
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Comments
  /comments/{comment_id}:
    delete:
      summary: Delete Comment
      description: Deletes a comment for given object
      operationId: comment
      x-api-path-slug: commentscomment-id-delete
      parameters:
      - in: path
        name: comment_id
        description: The comment id
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Comments
  /follows:
    delete:
      summary: Delete Follow
      description: Delete the follow for given user or startup.
      operationId: follows
      x-api-path-slug: follows-delete
      parameters:
      - in: query
        name: id
      - in: query
        name: type
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Follow
    post:
      summary: Add Follow
      description: Add a follow for user or startup on AngelList.
      operationId: follows
      x-api-path-slug: follows-post
      parameters:
      - in: query
        name: id
      - in: query
        name: type
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Follow
  /follows/batch:
    get:
      summary: Get Batch of Follows
      description: Returns a batched lists of follows
      operationId: followsBatch
      x-api-path-slug: followsbatch-get
      parameters:
      - in: query
        name: ids
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Follow
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