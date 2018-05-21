---
swagger: "2.0"
x-collection-name: AngelList
x-complete: 0
info:
  title: AngelList Get Press
  description: Get Press
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
  /follows/relationship:
    get:
      summary: Get Follows Relationship
      description: Gets the relationships for followers
      operationId: followsRelationship
      x-api-path-slug: followsrelationship-get
      parameters:
      - in: query
        name: source_id
      - in: query
        name: target_id
      - in: query
        name: target_type
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Relationships
  /jobs:
    get:
      summary: Get Jobs
      description: Get jobs.
      operationId: jobs
      x-api-path-slug: jobs-get
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Jobs
  /jobs/{job_id}:
    get:
      summary: Get Job
      description: Get job.
      operationId: job
      x-api-path-slug: jobsjob-id-get
      parameters:
      - in: path
        name: job_id
        description: The id for the job
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Jobs
  /like:
    post:
      summary: Add Like
      description: Add like.
      operationId: like
      x-api-path-slug: like-post
      parameters:
      - in: query
        name: likable_id
      - in: query
        name: likable_type
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Likes
  /likes:
    get:
      summary: Get Likes
      description: Get likes
      operationId: likes
      x-api-path-slug: likes-get
      parameters:
      - in: query
        name: likable_id
      - in: query
        name: likable_type
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Likes
    post:
      summary: Add Like
      description: Add Like
      operationId: likes
      x-api-path-slug: likes-post
      parameters:
      - in: query
        name: likable_id
      - in: query
        name: likable_type
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Likes
  /likes/{like_id}:
    delete:
      summary: Delete Like
      description: Delete Like
      operationId: likes
      x-api-path-slug: likeslike-id-delete
      parameters:
      - in: query
        name: likable_type
      - in: path
        name: like_id
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Likes
  /me:
    get:
      summary: Get Me
      description: Get Me
      operationId: me
      x-api-path-slug: me-get
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
  /press:
    get:
      summary: Get Press
      description: Get Press
      operationId: press
      x-api-path-slug: press-get
      parameters:
      - in: query
        name: startup_id
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Press
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