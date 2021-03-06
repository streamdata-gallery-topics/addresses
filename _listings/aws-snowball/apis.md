---
name: AWS Snowball
x-slug: aws-snowball
description: Snowball is a petabyte-scale data transport solution that uses secure
  appliances totransfer large amounts of datainto and out of theAWS cloud. Using Snowball
  addresses common challenges with large-scale data transfers including high network
  costs, long transfer times, and security concerns. Transferring data with Snowball
  is simple, fast, secure, and can be as little as one-fifth the cost of high-speed
  Internet.With Snowball, you don&rsquo;t need to write any code or purchase any hardware
  to transfer your data. Simply create a job in the AWS Management Console and a Snowball
  appliance will be automatically shipped to you*. Once it arrives, attach the appliance
  to your local network, download and run the Snowball client to establish a connection,
  and then use the client to select the file directories that you want to transfer
  to the appliance. The client will then encrypt and transfer the files to the appliance
  at high speed. Once the transfer is complete and the appliance is ready to be returned,
  the E Ink shipping label will automatically update and you can track the job status
  viaAmazon Simple Notification Service (SNS), text messages, or directly in the Console.Snowball
  uses multiple layers of security designed to protect your data including tamper-resistant
  enclosures, 256-bit encryption, and an industry-standard Trusted Platform Module
  (TPM) designed to ensure both security and full chain-of-custody of your data. Once
  the data transfer job has been processed and verified, AWS performs a software erasure
  of the Snowball appliance.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Addresses
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Snowball API - Create Address
  x-api-slug: actioncreateaddress-get
  description: Creates an address for a Snowball to be shipped to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actioncreateaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actioncreateaddress-get-openapi.md
- name: AWS Snowball API - Describe Address
  x-api-slug: actiondescribeaddress-get
  description: |-
    Takes an AddressId and returns specific details about that address in the
          form of an Address object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actiondescribeaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actiondescribeaddress-get-openapi.md
- name: AWS Snowball API - Describe Addresses
  x-api-slug: actiondescribeaddresses-get
  description: Returns a specified number of ADDRESS objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actiondescribeaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actiondescribeaddresses-get-openapi.md
- name: AWS Snowball API - Create Address
  x-api-slug: actioncreateaddress-get
  description: Creates an address for a Snowball to be shipped to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actioncreateaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actioncreateaddress-get-openapi.md
- name: AWS Snowball API - Describe Address
  x-api-slug: actiondescribeaddress-get
  description: |-
    Takes an AddressId and returns specific details about that address in the
          form of an Address object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actiondescribeaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actiondescribeaddress-get-openapi.md
- name: AWS Snowball API - Describe Addresses
  x-api-slug: actiondescribeaddresses-get
  description: Returns a specified number of ADDRESS objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actiondescribeaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actiondescribeaddresses-get-openapi.md
- name: AWS Snowball API - Describe Address
  x-api-slug: actiondescribeaddress-get
  description: |-
    Takes an AddressId and returns specific details about that address in the
          form of an Address object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actiondescribeaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/addresses/master/_listings/aws-snowball/actiondescribeaddress-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.simple.queue.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.snowball.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/snowball/latest/api-reference/api-reference.html
- type: x-faq
  url: https://aws.amazon.com/snowball/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/snowball/getting-started/
- type: x-tools
  url: https://aws.amazon.com/snowball/tools/
- type: x-website
  url: https://aws.amazon.com/snowball/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---