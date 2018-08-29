---
name: AngelList
x-slug: angellist
description: AngelList is where the world meets startups. Find a great startup job,
  invest in a startup, or raise money
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
x-kinRank: "9"
x-alexaRank: "2447"
tags: AngelList
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/apis.md
specificationVersion: "0.14"
apis:
- name: AngelList - Get Accreditation
  x-api-slug: accreditation-get
  description: Pulls the accreditation for a startup and users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/accreditation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/accreditation-get-openapi.md
- name: AngelList - Get Comments
  x-api-slug: comments-get
  description: Pulls the comments for given object.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/comments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/comments-get-openapi.md
- name: AngelList - Add Comment
  x-api-slug: comments-post
  description: Adds a comment for given object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/comments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/comments-post-openapi.md
- name: AngelList - Delete Comment
  x-api-slug: commentscomment-id-delete
  description: Deletes a comment for given object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/commentscomment-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/commentscomment-id-delete-openapi.md
- name: AngelList - Delete Follow
  x-api-slug: follows-delete
  description: Delete the follow for given user or startup.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/follows-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/follows-delete-openapi.md
- name: AngelList - Add Follow
  x-api-slug: follows-post
  description: Add a follow for user or startup on AngelList.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/follows-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/follows-post-openapi.md
- name: AngelList - Get Batch of Follows
  x-api-slug: followsbatch-get
  description: Returns a batched lists of follows
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/followsbatch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/followsbatch-get-openapi.md
- name: AngelList - Get Follows Relationship
  x-api-slug: followsrelationship-get
  description: Gets the relationships for followers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/followsrelationship-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/followsrelationship-get-openapi.md
- name: AngelList - Get Jobs
  x-api-slug: jobs-get
  description: Get jobs.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/jobs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/jobs-get-openapi.md
- name: AngelList - Get Job
  x-api-slug: jobsjob-id-get
  description: Get job.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/jobsjob-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/jobsjob-id-get-openapi.md
- name: AngelList - Add Like
  x-api-slug: like-post
  description: Add like.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/like-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/like-post-openapi.md
- name: AngelList - Get Likes
  x-api-slug: likes-get
  description: Get likes
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/likes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/likes-get-openapi.md
- name: AngelList - Add Like
  x-api-slug: likes-post
  description: Add Like
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/likes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/likes-post-openapi.md
- name: AngelList - Delete Like
  x-api-slug: likeslike-id-delete
  description: Delete Like
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/likeslike-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/likeslike-id-delete-openapi.md
- name: AngelList - Get Me
  x-api-slug: me-get
  description: Get Me
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/me-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/me-get-openapi.md
- name: AngelList - Get Press
  x-api-slug: press-get
  description: Get Press
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/press-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/press-get-openapi.md
- name: AngelList - Get Press
  x-api-slug: presspress-id-get
  description: Get Press
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/presspress-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/presspress-id-get-openapi.md
- name: AngelList - Get Reviews
  x-api-slug: reviews-get
  description: Get Reviews
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/reviews-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/reviews-get-openapi.md
- name: AngelList - Get Review
  x-api-slug: reviewsreview-id-get
  description: Get Review
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/reviewsreview-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/reviewsreview-id-get-openapi.md
- name: AngelList - Search AngelList
  x-api-slug: search-get
  description: Search AngelList.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/search-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/search-get-openapi.md
- name: AngelList - Search Slugs
  x-api-slug: searchslugs-get
  description: Search by slug
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/searchslugs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/searchslugs-get-openapi.md
- name: AngelList - Search Startups
  x-api-slug: startups-get
  description: Search Startups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startups-get-openapi.md
- name: AngelList - Get Startup
  x-api-slug: startupsstartup-id-get
  description: Get Startup
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-id-get-openapi.md
- name: AngelList - Get Startup Comments
  x-api-slug: startupsstartup-idcomments-get
  description: Get Startup Comments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idcomments-get-openapi.md
- name: AngelList - Get Startup Followers
  x-api-slug: startupsstartup-idfollowers-get
  description: Get Startup Followers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idfollowers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idfollowers-get-openapi.md
- name: AngelList - Get Startup Followers IDs
  x-api-slug: startupsstartup-idfollowersids-get
  description: Get Startup Followers IDs
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idfollowersids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idfollowersids-get-openapi.md
- name: AngelList - Get Startup Roles
  x-api-slug: startupsstartup-idroles-get
  description: Get Startup Roles
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startupsstartup-idroles-get-openapi.md
- name: AngelList - Get Startup Roles
  x-api-slug: startup-roles-get
  description: Get Startup Roles
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startup-roles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/startup-roles-get-openapi.md
- name: AngelList - Get Status Updates
  x-api-slug: status-updates-get
  description: Get Status Updates
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/status-updates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/status-updates-get-openapi.md
- name: AngelList - Add Status Update
  x-api-slug: status-updates-post
  description: Add Status Update
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/status-updates-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/status-updates-post-openapi.md
- name: AngelList - Delete Status Update
  x-api-slug: status-updatesstatus-update-id-delete
  description: Delete Status Update
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/status-updatesstatus-update-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/status-updatesstatus-update-id-delete-openapi.md
- name: AngelList - Get Tag
  x-api-slug: tagstag-id-get
  description: Get Tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-id-get-openapi.md
- name: AngelList - Get Tags Children
  x-api-slug: tagstag-idchildren-get
  description: Get Tags Children
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idchildren-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idchildren-get-openapi.md
- name: AngelList - Get Jobs by Tag
  x-api-slug: tagstag-idjobs-get
  description: Get Jobs by Tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idjobs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idjobs-get-openapi.md
- name: AngelList - Get Tag Parents
  x-api-slug: tagstag-idparents-get
  description: Get Tag Parents
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idparents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idparents-get-openapi.md
- name: AngelList - Get Startups by Tag
  x-api-slug: tagstag-idstartups-get
  description: Get Startups by Tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idstartups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idstartups-get-openapi.md
- name: AngelList - Get Users by Tag
  x-api-slug: tagstag-idusers-get
  description: Get Users by Tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/tagstag-idusers-get-openapi.md
- name: AngelList - User Search
  x-api-slug: userssearch-get
  description: User Search
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/userssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/userssearch-get-openapi.md
- name: AngelList - Get User
  x-api-slug: usersuser-id-get
  description: Get User
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-id-get-openapi.md
- name: AngelList - Get User Followers
  x-api-slug: usersuser-idfollowers-get
  description: Get User Followers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowers-get-openapi.md
- name: AngelList - Get User Follower IDs
  x-api-slug: usersuser-idfollowersids-get
  description: Get User Follower IDs
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowersids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowersids-get-openapi.md
- name: AngelList - Get Users Following
  x-api-slug: usersuser-idfollowing-get
  description: Get Users Following
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowing-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowing-get-openapi.md
- name: AngelList - Get User Following IDs
  x-api-slug: usersuser-idfollowingids-get
  description: Get User Following IDs
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/339-angellist.jpg
  humanURL: http://angel.co
  baseURL: https://api.angel.co//1/
  tags: Investing, Startup, Business, My API Stack, Angellist API Stack, Stack Network,
    Startups, Media, Marketplace, internet, API Provider, Directories, Profiles, SDIO
    Data, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowingids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/angellist/master/_listings/angellist/usersuser-idfollowingids-get-openapi.md
x-common:
- type: x-blog
  url: https://blog.angel.co
- type: x-api-gallery
  url: http://angellist.api.gallery.streamdata.io
- type: x-api-stack
  url: http://angellist.stack.network
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