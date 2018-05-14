---
name: NPR
description: NPR delivers breaking national and world news. Also top stories from
  business, politics, health, science, technology, music, arts and culture. Subscribe
  to podcasts and RSS feeds.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
x-kinRank: "9"
x-alexaRank: "641"
tags:
- Stack Network
- Stack
- Radio
- Publishing
- News
- Mobile
- Media
- Getting Started
- Federal Government
- Broadcasting
created: "2018-03-24"
modified: "2018-03-24"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/sponsors/master/_listings/npr/apis.yaml
specificationVersion: "0.14"
apis:
- name: NPR
  description: NPR delivers breaking national and world news
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: ""
  baseURL: https://api.npr.org//
  tags: Sponsors
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sponsors/master/_listings/npr/sponsorship-v2-ads-post.md
- name: NPR Request DAAST sponsorship units
  description: |-
    **Not** for use by NPR One clients (for whom sponsorship is already integrated into the Listening Service), this endpoint is designed to be used by our other client applications to request sponsorship on behalf of a user. Sponsorship units are returned in the form of DAAST XML. It is worth noting that this endpoint attempts to always return XML, even in the case of exceptions.

    The default behavior of this endpoint is asynchronous; on an initial request, a call to our external sponsorship provider is placed on a queue, which is typically processed within 3 minutes. Once the sponsorship call is received and processed, the returned sponsorship units are placed in a cache on our server for the current user. Subsequent calls to this endpoint will return DAAST sponsorship units from this cache until tracking information is submitted, which removes the ad from the cache and will automatically request additional ads asynchronously if there are fewer than a certain number remaining in the cache.

    For development purposes, it's worth noting that there is currently no way to clear a user's cache without submitting some form of tracking.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://www.npr.org
  baseURL: https://api.npr.org//
  tags: Sponsors
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sponsors/master/_listings/npr/sponsorship-v2-ads-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sponsors/master/_listings/npr/sponsorship-v2-ads-get-postman.md
x-common:
- type: x-base
  url: http://api.npr.org/
- type: x-codecademy
  url: http://www.codecademy.com/tracks/npr
- type: x-crunchbase
  url: https://crunchbase.com/organization/npr
- type: x-crunchbase
  url: http://www.crunchbase.com/company/npr
- type: x-developer
  url: http://dev.npr.org/
- type: x-documentation
  url: http://dev.npr.org/#accessing-the-api
- type: x-email
  url: permissions@npr.org
- type: x-email
  url: ogcstaff@npr.org
- type: x-email
  url: employment@npr.org
- type: x-email
  url: careers@npr.org
- type: x-email
  url: kroc@npr.org
- type: x-email
  url: mediarelations@npr.org
- type: x-email
  url: sponsorship@npr.org
- type: x-email
  url: ashamblin@npr.org
- type: x-email
  url: giving@npr.org
- type: x-email
  url: giftplanning@npr.org
- type: x-getting-started
  url: http://dev.npr.org/#quick-start
- type: x-github
  url: https://github.com/npr
- type: x-selfservice-registration
  url: http://www.npr.org/templates/reg/
- type: x-terms-of-service
  url: http://www.npr.org/about-npr/179876898/terms-of-use
- type: x-twitter
  url: https://twitter.com/NPR
- type: x-twitter
  url: https://twitter.com/NPRTechTeam
- type: x-website
  url: http://www.npr.org
- type: x-base
  url: http://api.npr.org/
- type: x-codecademy
  url: http://www.codecademy.com/tracks/npr
- type: x-crunchbase
  url: https://crunchbase.com/organization/npr
- type: x-crunchbase
  url: http://www.crunchbase.com/company/npr
- type: x-developer
  url: http://dev.npr.org/
- type: x-documentation
  url: http://dev.npr.org/#accessing-the-api
- type: x-email
  url: permissions@npr.org
- type: x-email
  url: ogcstaff@npr.org
- type: x-email
  url: employment@npr.org
- type: x-email
  url: careers@npr.org
- type: x-email
  url: kroc@npr.org
- type: x-email
  url: mediarelations@npr.org
- type: x-email
  url: sponsorship@npr.org
- type: x-email
  url: ashamblin@npr.org
- type: x-email
  url: giving@npr.org
- type: x-email
  url: giftplanning@npr.org
- type: x-getting-started
  url: http://dev.npr.org/#quick-start
- type: x-github
  url: https://github.com/npr
- type: x-selfservice-registration
  url: http://www.npr.org/templates/reg/
- type: x-terms-of-service
  url: http://www.npr.org/about-npr/179876898/terms-of-use
- type: x-twitter
  url: https://twitter.com/NPR
- type: x-twitter
  url: https://twitter.com/NPRTechTeam
- type: x-website
  url: http://www.npr.org
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---