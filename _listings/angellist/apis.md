---
name: AngelList
x-slug: angellist
description: AngelList is where the world meets startups. Find a great startup job,
  invest in a startup, or raise money
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
x-kinRank: "9"
x-alexaRank: "2447"
tags: AngelList
created: "2018-05-24"
modified: "2018-05-24"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/apis.md
specificationVersion: "0.14"
apis:
- name: AngelList Get Accreditation
  x-api-slug: angellist
  description: Pulls the accreditation for a startup and users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///accreditation
  tags: Startups,Businesses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/accreditation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/accreditation-get-openapi.md
- name: AngelList Get Comments
  x-api-slug: angellist
  description: Pulls the comments for given object.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///comments
  tags: Startups,Businesses,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/comments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/comments-get-openapi.md
- name: AngelList Add Comment
  x-api-slug: angellist
  description: Adds a comment for given object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///comments
  tags: Startups,Businesses,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/comments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/comments-post-openapi.md
- name: AngelList Delete Comment
  x-api-slug: angellist
  description: Deletes a comment for given object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///comments/{comment_id}
  tags: Startups,Businesses,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/commentscomment-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/commentscomment-id-delete-openapi.md
- name: AngelList Delete Follow
  x-api-slug: angellist
  description: Delete the follow for given user or startup.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///follows
  tags: Startups,Businesses,Follow
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/follows-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/follows-delete-openapi.md
- name: AngelList Add Follow
  x-api-slug: angellist
  description: Add a follow for user or startup on AngelList.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///follows
  tags: Startups,Businesses,Follow
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/follows-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/follows-post-openapi.md
- name: AngelList Get Batch of Follows
  x-api-slug: angellist
  description: Returns a batched lists of follows
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///follows/batch
  tags: Startups,Businesses,Follow
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/followsbatch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/followsbatch-get-openapi.md
- name: AngelList Get Follows Relationship
  x-api-slug: angellist
  description: Gets the relationships for followers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///follows/relationship
  tags: Startups,Businesses,Relationships
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/followsrelationship-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/followsrelationship-get-openapi.md
- name: AngelList Get Jobs
  x-api-slug: angellist
  description: Get jobs.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///jobs
  tags: Startups,Businesses,Jobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/jobs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/jobs-get-openapi.md
- name: AngelList Get Job
  x-api-slug: angellist
  description: Get job.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///jobs/{job_id}
  tags: Startups,Businesses,Jobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/jobsjob-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/jobsjob-id-get-openapi.md
- name: AngelList Add Like
  x-api-slug: angellist
  description: Add like.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///like
  tags: Startups,Businesses,Likes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/like-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/like-post-openapi.md
- name: AngelList Get Likes
  x-api-slug: angellist
  description: Get likes
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///likes
  tags: Startups,Businesses,Likes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/likes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/likes-get-openapi.md
- name: AngelList Add Like
  x-api-slug: angellist
  description: Add Like
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///likes
  tags: Startups,Businesses,Likes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/likes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/likes-post-openapi.md
- name: AngelList Delete Like
  x-api-slug: angellist
  description: Delete Like
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///likes/{like_id}
  tags: Startups,Businesses,Likes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/likeslike-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/likeslike-id-delete-openapi.md
- name: AngelList Get Me
  x-api-slug: angellist
  description: Get Me
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///me
  tags: Startups,Businesses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/me-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/me-get-openapi.md
- name: AngelList Get Press
  x-api-slug: angellist
  description: Get Press
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///press
  tags: Startups,Businesses,Press
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/press-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/press-get-openapi.md
- name: AngelList Get Press
  x-api-slug: angellist
  description: Get Press
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///press/{press_id}
  tags: Startups,Businesses,Press
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/presspress-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/presspress-id-get-openapi.md
- name: AngelList Get Reviews
  x-api-slug: angellist
  description: Get Reviews
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///reviews
  tags: Startups,Businesses,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/reviews-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/reviews-get-openapi.md
- name: AngelList Get Review
  x-api-slug: angellist
  description: Get Review
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///reviews/{review_id}
  tags: Startups,Businesses,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/reviewsreview-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/reviewsreview-id-get-openapi.md
- name: AngelList Search AngelList
  x-api-slug: angellist
  description: Search AngelList.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///search
  tags: Startups,Businesses,Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/search-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/search-get-openapi.md
- name: AngelList Search Slugs
  x-api-slug: angellist
  description: Search by slug
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///search/slugs
  tags: Startups,Businesses,Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/searchslugs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/searchslugs-get-openapi.md
- name: AngelList Search Startups
  x-api-slug: angellist
  description: Search Startups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///startups
  tags: Startups,Businesses,Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startups-get-openapi.md
- name: AngelList Get Startup
  x-api-slug: angellist
  description: Get Startup
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///startups/{startup_id}
  tags: Startups,Businesses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-id-get-openapi.md
- name: AngelList Get Startup Comments
  x-api-slug: angellist
  description: Get Startup Comments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///startups/{startup_id}/comments
  tags: Startups,Businesses,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idcomments-get-openapi.md
- name: AngelList Get Startup Followers
  x-api-slug: angellist
  description: Get Startup Followers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///startups/{startup_id}/followers
  tags: Startups,Businesses,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idfollowers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idfollowers-get-openapi.md
- name: AngelList Get Startup Followers IDs
  x-api-slug: angellist
  description: Get Startup Followers IDs
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///startups/{startup_id}/followers/ids
  tags: Startups,Businesses,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idfollowersids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idfollowersids-get-openapi.md
- name: AngelList Get Startup Roles
  x-api-slug: angellist
  description: Get Startup Roles
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///startups/{startup_id}/roles
  tags: Startups,Businesses,Roles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idroles-get-openapi.md
- name: AngelList Get Startup Roles
  x-api-slug: angellist
  description: Get Startup Roles
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///startup_roles
  tags: Startups,Businesses,Roles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startup-roles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startup-roles-get-openapi.md
- name: AngelList Get Status Updates
  x-api-slug: angellist
  description: Get Status Updates
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///status_updates
  tags: Startups,Businesses,Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/status-updates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/status-updates-get-openapi.md
- name: AngelList Add Status Update
  x-api-slug: angellist
  description: Add Status Update
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///status_updates
  tags: Startups,Businesses,Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/status-updates-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/status-updates-post-openapi.md
- name: AngelList Delete Status Update
  x-api-slug: angellist
  description: Delete Status Update
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///status_updates/{status_update_id}
  tags: Startups,Businesses,Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/status-updatesstatus-update-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/status-updatesstatus-update-id-delete-openapi.md
- name: AngelList Get Tag
  x-api-slug: angellist
  description: Get Tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///tags/{tag_id}
  tags: Startups,Businesses,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-id-get-openapi.md
- name: AngelList Get Tags Children
  x-api-slug: angellist
  description: Get Tags Children
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///tags/{tag_id}/children
  tags: Startups,Businesses,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idchildren-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idchildren-get-openapi.md
- name: AngelList Get Jobs by Tag
  x-api-slug: angellist
  description: Get Jobs by Tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///tags/{tag_id}/jobs
  tags: Startups,Businesses,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idjobs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idjobs-get-openapi.md
- name: AngelList Get Tag Parents
  x-api-slug: angellist
  description: Get Tag Parents
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///tags/{tag_id}/parents
  tags: Startups,Businesses,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idparents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idparents-get-openapi.md
- name: AngelList Get Startups by Tag
  x-api-slug: angellist
  description: Get Startups by Tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///tags/{tag_id}/startups
  tags: Startups,Businesses,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idstartups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idstartups-get-openapi.md
- name: AngelList Get Users by Tag
  x-api-slug: angellist
  description: Get Users by Tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///tags/{tag_id}/users
  tags: Startups,Businesses,Tags,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idusers-get-openapi.md
- name: AngelList User Search
  x-api-slug: angellist
  description: User Search
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///users/search
  tags: Startups,Businesses,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/userssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/userssearch-get-openapi.md
- name: AngelList Get User
  x-api-slug: angellist
  description: Get User
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///users/{user_id}
  tags: Startups,Businesses,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-id-get-openapi.md
- name: AngelList Get User Followers
  x-api-slug: angellist
  description: Get User Followers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///users/{user_id}/followers
  tags: Startups,Businesses,Users,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowers-get-openapi.md
- name: AngelList Get User Follower IDs
  x-api-slug: angellist
  description: Get User Follower IDs
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///users/{user_id}/followers/ids
  tags: Startups,Businesses,Users,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowersids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowersids-get-openapi.md
- name: AngelList Get Users Following
  x-api-slug: angellist
  description: Get Users Following
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///users/{user_id}/following
  tags: Startups,Businesses,Users,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowing-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowing-get-openapi.md
- name: AngelList Get User Following IDs
  x-api-slug: angellist
  description: Get User Following IDs
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1///users/{user_id}/following/ids
  tags: Startups,Businesses,Users,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowingids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowingids-get-openapi.md
- name: AngelList
  x-api-slug: angellist
  description: AngelList is where the world meets startups. Find a great startup job,
    invest in a startup, or raise money
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: AngelList
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/openapi.md
x-common:
- type: x-blog
  url: https://blog.angel.co
- type: x-base-url
  url: http://api.angel.co/
- type: x-blog
  url: http://blog.angel.co
- type: x-blog-rss
  url: http://blog.angel.co/rss
- type: x-crunchbase
  url: http://www.crunchbase.com/company/angellist
- type: x-crunchbase
  url: https://crunchbase.com/organization/angellist
- type: x-developer
  url: https://angel.co/api
- type: x-email
  url: copyright@angel.co
- type: x-email
  url: syndicates@angel.co
- type: x-email
  url: team@angel.co
- type: x-email
  url: talent@angel.co
- type: x-email
  url: privacy@angel.co
- type: x-email
  url: abuse@angel.co
- type: x-github
  url: https://github.com/angellist
- type: x-postman-collection
  url: http://theapistack.com/data/angellist/angellist-postman-collection.json
- type: x-privacy
  url: https://angel.co/privacy
- type: x-sdks-io
  url: https://sdks.io/SDK/View/angellist-startup-api
- type: x-support
  url: https://angel.co/help
- type: x-terms-of-service
  url: https://angel.co/terms
- type: x-twitter
  url: https://twitter.com/angellist
- type: x-website
  url: http://angel.co
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---