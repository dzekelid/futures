---
name: Xignite
x-slug: xignite
description: Financial market data on-demand. Xignite financial Web services help
  build smarter websites and applications in minutes with zero up-front investment.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
x-kinRank: "9"
x-alexaRank: "383974"
tags: Futures
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/apis.md
specificationVersion: "0.14"
apis:
- name: Xignite Futures List Futures
  x-api-slug: xignite-futures
  description: List all commodity futures and the exchange on which they are traded.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xFutures.json/XigniteFutures//ListFutures
  tags: Market Data,List, Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/listfutures-get-openapi.md
- name: Xignite Futures List Futures By Category
  x-api-slug: xignite-futures
  description: List futures information by byfuture category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xFutures.json/XigniteFutures//ListFuturesByCategory
  tags: Market Data,List, Futures, By, Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/listfuturesbycategory-get-openapi.md
- name: Xignite Futures List Futures By Exchange
  x-api-slug: xignite-futures
  description: List futures information by exchange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xFutures.json/XigniteFutures//ListFuturesByExchange
  tags: Market Data,List, Futures, By, Exchange
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/listfuturesbyexchange-get-openapi.md
- name: Xignite Futures Get All Delayed Futures
  x-api-slug: xignite-futures
  description: Returns delayed quotes for all contracts for a commodity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xFutures.json/XigniteFutures//GetAllDelayedFutures
  tags: Market Data,Delayed, Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/getalldelayedfutures-get-openapi.md
- name: Xignite Futures Get Top Delayed Futures
  x-api-slug: xignite-futures
  description: Returns delayed quotes for a given number of contract (front-future
    first) for a commodity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xFutures.json/XigniteFutures//GetTopDelayedFutures
  tags: Market Data,Top, Delayed, Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/gettopdelayedfutures-get-openapi.md
- name: Xignite Futures Get Delayed Futures
  x-api-slug: xignite-futures
  description: Returns delayed quotes for multiple future contracts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xFutures.json/XigniteFutures//GetDelayedFutures
  tags: Market Data,Delayed, Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/getdelayedfutures-get-openapi.md
- name: Xignite Futures Get All Delayed Futures By Session
  x-api-slug: xignite-futures
  description: Returns delayed quotes for all contracts for a commodity by exchange
    session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xFutures.json/XigniteFutures//GetAllDelayedFuturesBySession
  tags: Market Data,Delayed, Futures, By, Session
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/getalldelayedfuturesbysession-get-openapi.md
- name: Xignite Futures Get Delayed Futures By Session
  x-api-slug: xignite-futures
  description: Returns delayed quotes for multiple future contracts by exchange session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xFutures.json/XigniteFutures//GetDelayedFuturesBySession
  tags: Market Data,Delayed, Futures, By, Session
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/getdelayedfuturesbysession-get-openapi.md
- name: Xignite Futures Get Historical Futures
  x-api-slug: xignite-futures
  description: Returns historical quotes for multiple future contracts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xFutures.json/XigniteFutures//GetHistoricalFutures
  tags: Market Data,Historical, Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/gethistoricalfutures-get-openapi.md
- name: Xignite Futures Get All Historical Futures With Status
  x-api-slug: xignite-futures
  description: Returns historical quotes for all contracts for a commodity as of a
    specific date including status information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xFutures.json/XigniteFutures//GetAllHistoricalFuturesWithStatus
  tags: Market Data,Historical, Futures, With, Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/getallhistoricalfutureswithstatus-get-openapi.md
- name: Xignite Futures Get All Historical Futures
  x-api-slug: xignite-futures
  description: Returns historical quotes for all contracts for a commodity as of a
    specific date.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xFutures.json/XigniteFutures//GetAllHistoricalFutures
  tags: Market Data,Historical, Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/getallhistoricalfutures-get-openapi.md
- name: Xignite Futures
  x-api-slug: xignite-futures
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xFutures.json/XigniteFutures
  tags: Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/openapi.md
- name: Xignite Global Futures List Base Futures
  x-api-slug: xignite-global-futures
  description: Returns a list of base future symbols
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures//ListBaseFutures
  tags: List, Base, Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/listbasefutures-get-openapi.md
- name: Xignite Global Futures Search Futures
  x-api-slug: xignite-global-futures
  description: Returns futures match the name
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures//SearchFutures
  tags: Search, Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/searchfutures-get-openapi.md
- name: Xignite Global Futures
  x-api-slug: xignite-global-futures
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures
  tags: Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/openapi.md
- name: Xignite Global Real Time Futures List Base Futures
  x-api-slug: xignite-global-real-time-futures
  description: Returns a list of base future symbols
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalrealtimefutures.xignite.com/xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures//ListBaseFutures
  tags: Market Data,List, Base, Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/listbasefutures-get-openapi.md
- name: Xignite Global Real Time Futures Search Futures
  x-api-slug: xignite-global-real-time-futures
  description: Returns futures match the name
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalrealtimefutures.xignite.com/xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures//SearchFutures
  tags: Market Data,Search, Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/searchfutures-get-openapi.md
- name: Xignite Global Real Time Futures
  x-api-slug: xignite-global-real-time-futures
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalrealtimefutures.xignite.com/xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures
  tags: Futures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/futures/master/_listings/xignite/openapi.md
x-common:
- type: x--net-sdk
  url: http://xignite.github.io/DotNetSDK/
- type: x-base
  url: http://globalmaster.xignite.com
- type: x-case-studies
  url: https://resources.xignite.com/case-studies
- type: x-case-studies
  url: http://www.xignite.com/market-data/resources/case-studies/
- type: x-blog
  url: https://resources.xignite.com/xignite-blog
- type: x-contact-form
  url: http://www.xignite.com/market-data/contact-us
- type: x-crunchbase
  url: http://www.crunchbase.com/company/xignite
- type: x-crunchbase
  url: https://crunchbase.com/organization/xignite
- type: x-developer
  url: http://www.xignite.com/developers
- type: x-email
  url: support@xignite.com
- type: x-email
  url: accounting@xignite.com
- type: x-email
  url: sales@xignite.com
- type: x-email
  url: marketing@xignite.com
- type: x-email
  url: info@xignite.com
- type: x-email
  url: jobs@xignite.com
- type: x-email
  url: klangstaff@xignite.com
- type: x-faq
  url: http://www.xignite.com/Support/FAQs.aspx
- type: x-getting-started
  url: http://www.xignite.com/Support/GettingStarted.aspx
- type: x-github
  url: https://github.com/Xignite
- type: x-java-sdk
  url: http://xignite.github.io/JavaSDK/
- type: x-privacy
  url: http://www.xignite.com/Documents/PrivacyPolicy.aspx
- type: x-support
  url: http://www.xignite.com/Support/SupportPlans.aspx
- type: x-blog
  url: http://www.xignite.com/market-data/blog/tech/
- type: x-blog-rss
  url: http://www.xignite.com/market-data/feed/
- type: x-terms-of-service
  url: http://www.xignite.com/Policies/SiteUseTerms.aspx
- type: x-twitter
  url: https://twitter.com/xignite
- type: x-videos
  url: http://www.xignite.com/market-data/resources/videos/
- type: x-webinar
  url: http://www.xignite.com/market-data/resources/webinars/
- type: x-webinars
  url: https://resources.xignite.com/webinars
- type: x-website
  url: http://www.xignite.com
- type: x-website
  url: http://xignite.com
- type: x-website
  url: http://xignite.com/
- type: x-white-papers
  url: http://www.xignite.com/market-data/resources/white-papers/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---