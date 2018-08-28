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
  /ListFutures:
    get:
      summary: List Futures
      description: List all commodity futures and the exchange on which they are traded.
      operationId: postListfutures
      x-api-path-slug: listfutures-get
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
      - Futures
  /ListFuturesByCategory:
    get:
      summary: List Futures By Category
      description: List futures information by byfuture category.
      operationId: postListfuturesbycategory
      x-api-path-slug: listfuturesbycategory-get
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
      - Futures
      - By
      - Category
  /ListFuturesByExchange:
    get:
      summary: List Futures By Exchange
      description: List futures information by exchange.
      operationId: postListfuturesbyexchange
      x-api-path-slug: listfuturesbyexchange-get
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
      - Futures
      - By
      - Exchange
  /GetAllDelayedFutures:
    get:
      summary: Get All Delayed Futures
      description: Returns delayed quotes for all contracts for a commodity.
      operationId: postGetalldelayedfutures
      x-api-path-slug: getalldelayedfutures-get
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
      - Delayed
      - Futures
  /GetTopDelayedFutures:
    get:
      summary: Get Top Delayed Futures
      description: Returns delayed quotes for a given number of contract (front-future
        first) for a commodity.
      operationId: postGettopdelayedfutures
      x-api-path-slug: gettopdelayedfutures-get
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
      - Top
      - Delayed
      - Futures
  /GetDelayedFutures:
    get:
      summary: Get Delayed Futures
      description: Returns delayed quotes for multiple future contracts.
      operationId: postGetdelayedfutures
      x-api-path-slug: getdelayedfutures-get
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
      - Delayed
      - Futures
  /GetAllDelayedFuturesBySession:
    get:
      summary: Get All Delayed Futures By Session
      description: Returns delayed quotes for all contracts for a commodity by exchange
        session.
      operationId: postGetalldelayedfuturesbysession
      x-api-path-slug: getalldelayedfuturesbysession-get
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
      - Delayed
      - Futures
      - By
      - Session
  /GetDelayedFuturesBySession:
    get:
      summary: Get Delayed Futures By Session
      description: Returns delayed quotes for multiple future contracts by exchange
        session.
      operationId: postGetdelayedfuturesbysession
      x-api-path-slug: getdelayedfuturesbysession-get
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
      - Delayed
      - Futures
      - By
      - Session
  /GetHistoricalFutures:
    get:
      summary: Get Historical Futures
      description: Returns historical quotes for multiple future contracts.
      operationId: postGethistoricalfutures
      x-api-path-slug: gethistoricalfutures-get
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
      - Historical
      - Futures
  /GetAllHistoricalFuturesWithStatus:
    get:
      summary: Get All Historical Futures With Status
      description: Returns historical quotes for all contracts for a commodity as
        of a specific date including status information.
      operationId: postGetallhistoricalfutureswithstatus
      x-api-path-slug: getallhistoricalfutureswithstatus-get
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
      - Historical
      - Futures
      - With
      - Status
  /GetAllHistoricalFutures:
    get:
      summary: Get All Historical Futures
      description: Returns historical quotes for all contracts for a commodity as
        of a specific date.
      operationId: postGetallhistoricalfutures
      x-api-path-slug: getallhistoricalfutures-get
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
      - Historical
      - Futures
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