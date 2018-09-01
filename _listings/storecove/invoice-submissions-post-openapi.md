---
swagger: "2.0"
x-collection-name: Storecove
x-complete: 0
info:
  title: Storecove Submit a new invoice
  description: |-
    Submit an invoice for delivery.
    include::examples/invoice_submissions/create_invoice_submission/tabs.adoc[]
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