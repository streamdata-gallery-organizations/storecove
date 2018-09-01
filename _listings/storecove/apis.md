---
name: Storecove
x-slug: storecove
description: Storecove is Netherlands&rsquo; first online platform that provides people
  and companies with a way to view all their invoices in one online overview. Dolf
  Kars, founder and former owner of Videostrip (acquired by RTL Nederland), established
  Storecove in 2014 with cofounder Michael Riviera and Willem Stemfoort. Storecove
  mainly focuses on automatically collecting invoices, which saves time and money.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
x-kinRank: "7"
x-alexaRank: "0"
tags: Storecove
created: "2018-08-31"
modified: "2018-08-31"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/apis.md
specificationVersion: "0.14"
apis:
- name: Storecove - Submit a new invoice
  x-api-slug: invoice-submissions-post
  description: |-
    Submit an invoice for delivery.
    include::examples/invoice_submissions/create_invoice_submission/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/invoice-submissions-post-openapi.md
- name: Storecove - Preflight an invoice recipient
  x-api-slug: invoice-submissionspreflight-post
  description: |-
    Check whether Storecove can deliver an invoice for a list of ids.
    include::examples/invoice_submissions/preflight_invoice_recipient/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/invoice-submissionspreflight-post-openapi.md
- name: Storecove - Create a new LegalEntity
  x-api-slug: legal-entities-post
  description: Create a new LegalEntity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/legal-entities-post-openapi.md
- name: Storecove - Delete LegalEntity
  x-api-slug: legal-entitiesid-delete
  description: Delete a specific LegalEntity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/legal-entitiesid-delete-openapi.md
- name: Storecove - Get LegalEntity
  x-api-slug: legal-entitiesid-get
  description: Get a specific LegalEntity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/legal-entitiesid-get-openapi.md
- name: Storecove - Update LegalEntity
  x-api-slug: legal-entitiesid-patch
  description: Update a specific LegalEntity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/legal-entitiesid-patch-openapi.md
- name: Storecove - Create a new PeppolIdentifier
  x-api-slug: legal-entitieslegal-entity-idpeppol-identifiers-post
  description: Create a new PeppolIdentifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/legal-entitieslegal-entity-idpeppol-identifiers-post-openapi.md
- name: Storecove - Delete PeppolIdentifier
  x-api-slug: legal-entitieslegal-entity-idpeppol-identifiersiso6523actoridupisschemeidentifier-delete
  description: Delete a specific PeppolIdentifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/legal-entitieslegal-entity-idpeppol-identifiersiso6523actoridupisschemeidentifier-delete-openapi.md
- name: Storecove - Update PeppolIdentifier
  x-api-slug: legal-entitieslegal-entity-idpeppol-identifiersiso6523actoridupisschemeidentifier-patch
  description: Update a specific PeppolIdentifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/legal-entitieslegal-entity-idpeppol-identifiersiso6523actoridupisschemeidentifier-patch-openapi.md
- name: Storecove - Get ShopAccountRequests
  x-api-slug: shop-account-requests-get
  description: |-
    Retrieve all active ShopAccountRequests for one of your entities.
    include::examples/shop_account_requests/shop_account_requests_index/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/shop-account-requests-get-openapi.md
- name: Storecove - Create ShopAccountRequest
  x-api-slug: shop-account-requests-post
  description: |-
    Create a new ShopAccountRequest
    include::examples/shop_account_requests/create_shop_account_request/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/shop-account-requests-post-openapi.md
- name: Storecove - Delete ShopAccountRequest
  x-api-slug: shop-account-requestsid-delete
  description: |-
    Delete a specific ShopAccountRequest
    include::examples/shop_account_requests/delete_shop_account_request/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/shop-account-requestsid-delete-openapi.md
- name: Storecove - Get ShopAccountRequest
  x-api-slug: shop-account-requestsid-get
  description: |-
    Show a specific ShopAccountRequest
    include::examples/shop_account_requests/get_shop_account_request/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/shop-account-requestsid-get-openapi.md
- name: Storecove - Update ShopAccountRequest
  x-api-slug: shop-account-requestsid-patch
  description: |-
    Update a specific ShopAccountRequest
    include::examples/shop_account_requests/update_shop_account_request/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/shop-account-requestsid-patch-openapi.md
- name: Storecove - Get ShopAccounts for an entity
  x-api-slug: shop-accounts-get
  description: |-
    Retrieve all active ShopAccounts for one of your entities.
    include::examples/shop_accounts/shop_accounts_index/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/shop-accounts-get-openapi.md
- name: Storecove - Create ShopAccount
  x-api-slug: shop-accounts-post
  description: |-
    Create a new ShopAccount.
    include::examples/shop_accounts/create_shop_account/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/shop-accounts-post-openapi.md
- name: Storecove - Get ShopAccounts with authorization failures
  x-api-slug: shop-accountsauth-failures-get
  description: |-
    Get ShopAccounts with authorization failures.
    include::examples/shop_accounts/shop_accounts_auth_failures/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/shop-accountsauth-failures-get-openapi.md
- name: Storecove - Delete ShopAccount
  x-api-slug: shop-accountsid-delete
  description: |-
    Delete a specific ShopAccount.
    include::examples/shop_accounts/delete_shop_account/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/shop-accountsid-delete-openapi.md
- name: Storecove - Get ShopAccount
  x-api-slug: shop-accountsid-get
  description: |-
    Get a specific ShopAccount.
    include::examples/shop_accounts/get_shop_account/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/shop-accountsid-get-openapi.md
- name: Storecove - Update ShopAccount
  x-api-slug: shop-accountsid-patch
  description: |-
    Update a specific ShopAccount.
    include::examples/shop_accounts/update_shop_account/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/shop-accountsid-patch-openapi.md
- name: Storecove - Get Shops
  x-api-slug: shops-get
  description: |-
    Get all available shops.
    include::examples/shops/shops_index/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/storecove/master/_listings/storecove/shops-get-openapi.md
x-common:
- type: x-website
  url: http://www.storecove.com
- type: x-api-gallery
  url: http://stocktwits.api.gallery.streamdata.io
- type: x-api-stack
  url: http://storecove.stack.network
- type: x-blog
  url: https://www.storecove.com/blog/
- type: x-blog-rss
  url: https://www.storecove.com/blog/rss/
- type: x-documentation
  url: https://www.storecove.com/en/docs
- type: x-github
  url: https://github.com/storecove
- type: x-openapi
  url: https://www.storecove.com/api/v2/openapi.json
- type: x-twitter
  url: https://twitter.com/storecove
- type: x-website
  url: http://storecove.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---