---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Real Time Futures Search Futures
  description: Returns futures match the name
  version: 1.0.0
host: globalrealtimefutures.xignite.com
basePath: xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ListBaseFutures:
    get:
      summary: List Base Futures
      description: Returns a list of base future symbols
      operationId: ListBaseFutures
      x-api-path-slug: listbasefutures-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - List
      - Base
      - Futures
  /SearchFutures:
    get:
      summary: Search Futures
      description: Returns futures match the name
      operationId: SearchFutures
      x-api-path-slug: searchfutures-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Search
      - Futures
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