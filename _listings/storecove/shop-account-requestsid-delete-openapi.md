---
swagger: "2.0"
x-collection-name: Storecove
x-complete: 0
info:
  title: Storecove Delete ShopAccountRequest
  description: |-
    Delete a specific ShopAccountRequest
    include::examples/shop_account_requests/delete_shop_account_request/tabs.adoc[]
  version: 2.0.1
host: api.storecove.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /invoice_submissions:
    post:
      summary: Submit a new invoice
      description: |-
        Submit an invoice for delivery.
        include::examples/invoice_submissions/create_invoice_submission/tabs.adoc[]
      operationId: create_invoice_submission
      x-api-path-slug: invoice-submissions-post
      parameters:
      - in: body
        name: invoice_submission
        description: Invoice to submit
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Invoice
      - Submissions
  /invoice_submissions/preflight:
    post:
      summary: Preflight an invoice recipient
      description: |-
        Check whether Storecove can deliver an invoice for a list of ids.
        include::examples/invoice_submissions/preflight_invoice_recipient/tabs.adoc[]
      operationId: preflight_invoice_recipient
      x-api-path-slug: invoice-submissionspreflight-post
      parameters:
      - in: body
        name: invoice_recipient_preflight
        description: The invoice recipient to preflight
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Invoice
      - Submissions
      - Preflight
  /legal_entities:
    post:
      summary: Create a new LegalEntity
      description: Create a new LegalEntity.
      operationId: create_legal_entity
      x-api-path-slug: legal-entities-post
      parameters:
      - in: body
        name: legal_entity
        description: LegalEntity to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Legal
      - Entities
  /legal_entities/{id}:
    delete:
      summary: Delete LegalEntity
      description: Delete a specific LegalEntity.
      operationId: delete_legal_entity
      x-api-path-slug: legal-entitiesid-delete
      parameters:
      - in: path
        name: id
        description: legal_entity id
      responses:
        200:
          description: OK
      tags:
      - Legal
      - Entities
    get:
      summary: Get LegalEntity
      description: Get a specific LegalEntity.
      operationId: get_legal_entity
      x-api-path-slug: legal-entitiesid-get
      parameters:
      - in: path
        name: id
        description: legal_entity id
      responses:
        200:
          description: OK
      tags:
      - Legal
      - Entities
    patch:
      summary: Update LegalEntity
      description: Update a specific LegalEntity.
      operationId: update_legal_entity
      x-api-path-slug: legal-entitiesid-patch
      parameters:
      - in: path
        name: id
        description: legal_entity id
      - in: body
        name: legal_entity
        description: LegalEntity updates
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Legal
      - Entities
  /legal_entities/{legal_entity_id}/peppol_identifiers:
    post:
      summary: Create a new PeppolIdentifier
      description: Create a new PeppolIdentifier.
      operationId: create_peppol_identifier
      x-api-path-slug: legal-entitieslegal-entity-idpeppol-identifiers-post
      parameters:
      - in: path
        name: legal_entity_id
      - in: body
        name: peppol_identifier
        description: PeppolIdentifier to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Legal
      - Entities
      - Legal
      - Entity
      - Peppolentifiers
  /legal_entities/{legal_entity_id}/peppol_identifiers/iso6523-actorid-upis/{scheme}/{identifier}:
    delete:
      summary: Delete PeppolIdentifier
      description: Delete a specific PeppolIdentifier.
      operationId: delete_peppol_identifier
      x-api-path-slug: legal-entitieslegal-entity-idpeppol-identifiersiso6523actoridupisschemeidentifier-delete
      parameters:
      - in: path
        name: identifier
        description: PEPPOL identifier
      - in: path
        name: legal_entity_id
        description: The id of the LegalEntity this PeppolIdentifier belongs to
      - in: path
        name: scheme
        description: PEPPOL identifier scheme id, e
      responses:
        200:
          description: OK
      tags:
      - Legal
      - Entities
      - Legal
      - Entity
      - Peppolentifiers
      - Iso6523
      - Actorid
      - Upis
      - Schemeentifier
    patch:
      summary: Update PeppolIdentifier
      description: Update a specific PeppolIdentifier.
      operationId: update_peppol_identifier
      x-api-path-slug: legal-entitieslegal-entity-idpeppol-identifiersiso6523actoridupisschemeidentifier-patch
      parameters:
      - in: path
        name: identifier
        description: PEPPOL identifier
      - in: path
        name: legal_entity_id
        description: The id of the LegalEntity this PeppolIdentifier belongs to
      - in: body
        name: peppol_identifier
        description: PeppolIdentifier updates
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: scheme
        description: PEPPOL identifier scheme id, e
      responses:
        200:
          description: OK
      tags:
      - Legal
      - Entities
      - Legal
      - Entity
      - Peppolentifiers
      - Iso6523
      - Actorid
      - Upis
      - Schemeentifier
  /shop_account_requests:
    get:
      summary: Get ShopAccountRequests
      description: |-
        Retrieve all active ShopAccountRequests for one of your entities.
        include::examples/shop_account_requests/shop_account_requests_index/tabs.adoc[]
      operationId: shop_account_requests_index
      x-api-path-slug: shop-account-requests-get
      parameters:
      - in: query
        name: external_user_id
        description: Filter by the external_user_id
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Account
      - Requests
    post:
      summary: Create ShopAccountRequest
      description: |-
        Create a new ShopAccountRequest
        include::examples/shop_account_requests/create_shop_account_request/tabs.adoc[]
      operationId: create_shop_account_request
      x-api-path-slug: shop-account-requests-post
      parameters:
      - in: body
        name: shop_account_request
        description: ShopAccountRequest to add
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Account
      - Requests
  /shop_account_requests/{id}:
    delete:
      summary: Delete ShopAccountRequest
      description: |-
        Delete a specific ShopAccountRequest
        include::examples/shop_account_requests/delete_shop_account_request/tabs.adoc[]
      operationId: delete_shop_account_request
      x-api-path-slug: shop-account-requestsid-delete
      parameters:
      - in: path
        name: id
        description: shop_account_request id
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Account
      - Requests
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