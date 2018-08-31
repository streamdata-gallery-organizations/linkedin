---
swagger: "2.0"
x-collection-name: LinkedIn
x-complete: 0
info:
  title: LinkedIn Get Companies (,name,ticker,description)
  description: Get companies  (,name,ticker,description)
  version: 1.0.0
host: api.linkedin.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /companies/{id}/updates/key={update-key}/update-comments-as-company/:
    post:
      summary: Add Companies Updates Key Update Key Update Comments As Company
      description: Post companies  updates key update key update comments as company
      operationId: postCompaniesUpdatesKeyUpdateKeyUpdateCommentsAsCompany
      x-api-path-slug: companiesidupdateskeyupdatekeyupdatecommentsascompany-post
      responses:
        200:
          description: OK
      tags:
      - Companies
      - ""
      - Updates
      - Key
      - Update
      - Key
      - Update
      - Comments
      - As
      - Company
  /people/~:
    get:
      summary: Get People
      description: Get people ~
      operationId: getPeople~
      x-api-path-slug: people-get
      parameters:
      - in: query
        name: format
        description: The message format
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - People
  /people/shares:
    post:
      summary: Add People ~ Shares
      description: Post people ~ shares
      operationId: postPeople~Shares
      x-api-path-slug: peopleshares-post
      parameters:
      - in: header
        name: Content-Type
        description: The content type
      - in: query
        name: format
        description: The message format
        type: string
        format: string
      - in: header
        name: x-li-format
        description: The content type
      responses:
        200:
          description: OK
      tags:
      - People
      - Shares
  /companies/{id}/is-company-share-enabled:
    get:
      summary: Get Companies Is Company Share Enabled
      description: Get companies  is company share enabled
      operationId: getCompaniesIsCompanyShareEnabled
      x-api-path-slug: companiesidiscompanyshareenabled-get
      responses:
        200:
          description: OK
      tags:
      - Companies
      - ""
      - Is
      - Company
      - Share
      - Enabled
  /companies/{id}/relation-to-viewer/is-company-share-enabled:
    get:
      summary: Get Companies Relation To Viewer Is Company Share Enabled
      description: Get companies  relation to viewer is company share enabled
      operationId: getCompaniesRelationToViewerIsCompanyShareEnabled
      x-api-path-slug: companiesidrelationtovieweriscompanyshareenabled-get
      responses:
        200:
          description: OK
      tags:
      - Companies
      - ""
      - Relation
      - To
      - Viewer
      - Is
      - Company
      - Share
      - Enabled
  /companies/:
    get:
      summary: Get Companies
      description: Get companies
      operationId: getCompanies
      x-api-path-slug: companies-get
      responses:
        200:
          description: OK
      tags:
      - Companies
  /companies/{id}:
    get:
      summary: Get Companies
      description: Get companies
      operationId: getCompanies
      x-api-path-slug: companiesid-get
      parameters:
      - in: query
        name: format
        description: The message format
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Companies
  /companies/{id}:(id,name,ticker,description):
    get:
      summary: Get Companies (,name,ticker,description)
      description: Get companies  (,name,ticker,description)
      operationId: getCompanies(,name,ticker,description)
      x-api-path-slug: companiesididnametickerdescription-get
      responses:
        200:
          description: OK
      tags:
      - Companies
      - ""
      - (
      - name
      - ticker
      - description)
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