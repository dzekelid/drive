---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Create A Sharing Link For A Drive Item
  description: Create a sharing link for a DriveItem You can use createLink action
    to share a DriveItem via a sharing link.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/drive/items/{item-id}/createLink:
    post:
      summary: Create A Sharing Link For A Drive Item
      description: Create a sharing link for a DriveItem You can use createLink action
        to share a DriveItem via a sharing link.
      operationId: CreateASharingLinkForADriveItem
      x-api-path-slug: medriveitemsitemidcreatelink-post
      parameters:
      - in: path
        name: item-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - CreateSharing
      - LinkA
      - Drive
      - Item
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