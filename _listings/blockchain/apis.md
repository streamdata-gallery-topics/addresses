---
name: Blockchain
x-slug: blockchain
description: With the largest bitcoin wallet platform in the world, Blockchains software
  has powered over 100M transactions and empowered users in 130 countries across the
  globe to transact quickly and without costly intermediaries. We also offers tools
  for develo...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28138-blockchain-info.jpg
x-kinRank: "8"
x-alexaRank: "3499"
tags: Addresses
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/blockchain/apis.md
specificationVersion: "0.14"
apis:
- name: Blockchain Info Raw Address
  x-api-slug: blockchain-info
  description: Returns a single blockchain address.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28138-blockchain-info.jpg
  humanURL: https://blockchain.info
  baseURL: https://blockchain.info///rawaddr/{bitcoin_address}
  tags: Blockchain,Addresses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/blockchain/rawaddrbitcoin-address-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/blockchain/rawaddrbitcoin-address-get-openapi.md
- name: Blockchain Info Multi Adress
  x-api-slug: blockchain-info
  description: Returns multiple addresses
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28138-blockchain-info.jpg
  humanURL: https://blockchain.info
  baseURL: https://blockchain.info///multiaddr
  tags: Blockchain,Addresses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/blockchain/multiaddr-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/blockchain/multiaddr-get-openapi.md
- name: Blockchain Info
  x-api-slug: blockchain-info
  description: With the largest bitcoin wallet platform in the world, Blockchains
    software has powered over 100M transactions and empowered users in 130 countries
    across the globe to transact quickly and without costly intermediaries. We also
    offers tools for develo...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28138-blockchain-info.jpg
  humanURL: https://blockchain.info
  baseURL: https://blockchain.info/
  tags: Addresses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/blockchain/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/blockchain-info
- type: x-documentation
  url: https://blockchain.info/api
- type: x-github
  url: https://github.com/blockchain
- type: x-linkedin
  url: https://www.linkedin.com/company/blockchain
- type: x-twitter
  url: https://twitter.com/blockchain
- type: x-website
  url: https://blockchain.info
- type: x-websockets
  url: https://blockchain.info/api/api_websocket
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---