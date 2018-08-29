---
swagger: "2.0"
info:
  title: AngelList
  description: The AngelList API provides developers with a RESTful interface to the
    AngelList data set. For more information, read the OAuth FAQ.
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
  /startup_roles:
    get:
      summary: Get Startup Roles
      description: Get Startup Roles
      operationId: 1Startup_roles
      parameters:
      - in: query
        name: startup_id
      - in: query
        name: v
      responses:
        200:
          description: OK
      tags:
      - startups
      - businesses
      - roles
definitions:
  error:
    properties:
      error:
        description: This is a default description.
        type: get
      message:
        description: This is a default description.
        type: get
      type:
        description: This is a default description.
        type: get
      gadget:
        description: This is a default description.
        type: delete
  accreditation:
    properties:
      id:
        description: This is a default description.
        type: get
  comments:
    properties:
      id:
        description: This is a default description.
        type: delete
  followed:
    properties:
      angellist_url:
        description: This is a default description.
        type: get
      bio:
        description: This is a default description.
        type: get
      followed:
        description: This is a default description.
        type: get
      follower_count:
        description: This is a default description.
        type: get
      id:
        description: This is a default description.
        type: get
      image:
        description: This is a default description.
        type: get
      name:
        description: This is a default description.
        type: get
      type:
        description: This is a default description.
        type: get
  jobs:
    properties:
      job_id:
        description: This is a default description.
        type: get
  user:
    properties:
      angellist_url:
        description: This is a default description.
        type: delete
      bio:
        description: This is a default description.
        type: delete
      follower_count:
        description: This is a default description.
        type: delete
      id:
        description: This is a default description.
        type: delete
      image:
        description: This is a default description.
        type: delete
      name:
        description: This is a default description.
        type: delete
      user:
        description: This is a default description.
        type: delete
  me:
    properties:
      name:
        description: This is a default description.
        type: get
      id:
        description: This is a default description.
        type: get
      bio:
        description: This is a default description.
        type: get
      follower_count:
        description: This is a default description.
        type: get
      angellist_url:
        description: This is a default description.
        type: get
      image:
        description: This is a default description.
        type: get
      email:
        description: This is a default description.
        type: get
      blog_url:
        description: This is a default description.
        type: get
      online_bio_url:
        description: This is a default description.
        type: get
      twitter_url:
        description: This is a default description.
        type: get
  skills:
    properties:
      id:
        description: This is a default description.
        type: get
      tag_type:
        description: This is a default description.
        type: get
      name:
        description: This is a default description.
        type: get
      display_name:
        description: This is a default description.
        type: get
      angellist_url:
        description: This is a default description.
        type: get
      level:
        description: This is a default description.
        type: get
  press:
    properties:
      created_at:
        description: This is a default description.
        type: get
      flags:
        description: This is a default description.
        type: get
      id:
        description: This is a default description.
        type: get
      image_url:
        description: This is a default description.
        type: get
      owner_id:
        description: This is a default description.
        type: get
      owner_type:
        description: This is a default description.
        type: get
      posted_at:
        description: This is a default description.
        type: get
      press:
        description: This is a default description.
        type: get
      snippet:
        description: This is a default description.
        type: get
      title:
        description: This is a default description.
        type: get
  relationship_to_reviewer:
    properties:
      as:
        description: This is a default description.
        type: get
      created_at:
        description: This is a default description.
        type: get
      id:
        description: This is a default description.
        type: get
      note:
        description: This is a default description.
        type: get
      relationship:
        description: This is a default description.
        type: get
      relationship_to_reviewer:
        description: This is a default description.
        type: get
      reviewer:
        description: This is a default description.
        type: get
      permissions:
        description: This is a default description.
        type: get
  search:
    properties:
      id:
        description: This is a default description.
        type: get
      name:
        description: This is a default description.
        type: get
      pic:
        description: This is a default description.
        type: get
      type:
        description: This is a default description.
        type: get
      url:
        description: This is a default description.
        type: get
  abilities:
    properties:
      intro:
        description: This is a default description.
        type: get
  startups_comments:
    properties:
      Comments:
        description: This is a default description.
        type: get
  users:
    properties:
      angellist_url:
        description: This is a default description.
        type: get
      bio:
        description: This is a default description.
        type: get
      follower_count:
        description: This is a default description.
        type: get
      id:
        description: This is a default description.
        type: get
      image:
        description: This is a default description.
        type: get
      name:
        description: This is a default description.
        type: get
      users:
        description: This is a default description.
        type: get
  ids:
    properties:
      ids:
        description: This is a default description.
        type: get
  startup:
    properties:
      angellist_url:
        description: This is a default description.
        type: get
      community_profile:
        description: This is a default description.
        type: get
      company_url:
        description: This is a default description.
        type: get
      confirmed:
        description: This is a default description.
        type: get
      created_at:
        description: This is a default description.
        type: get
      ended_at:
        description: This is a default description.
        type: get
      follower_count:
        description: This is a default description.
        type: get
      hidden:
        description: This is a default description.
        type: get
      high_concept:
        description: This is a default description.
        type: get
      id:
        description: This is a default description.
        type: get
  status_updates:
    properties:
      created_at:
        description: This is a default description.
        type: delete
      id:
        description: This is a default description.
        type: delete
      message:
        description: This is a default description.
        type: delete
      status_updates:
        description: This is a default description.
        type: delete
  locations:
    properties:
      angellist_url:
        description: This is a default description.
        type: get
      display_name:
        description: This is a default description.
        type: get
      id:
        description: This is a default description.
        type: get
      locations:
        description: This is a default description.
        type: get
      name:
        description: This is a default description.
        type: get
      tag_type:
        description: This is a default description.
        type: get
  all:
    properties:
      all:
        description: This is a default description.
        type: get
      followers:
        description: This is a default description.
        type: get
      investor_followers:
        description: This is a default description.
        type: get
      startups:
        description: This is a default description.
        type: get
  children:
    properties:
      children:
        description: This is a default description.
        type: get
  startups:
    properties:
      startup_id:
        description: This is a default description.
        type: get
x-collection-name: AngelList
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