---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Track Changes For A Drive
  description: Track changes for a Drive This method allows your app to track changes
    to a drive and its children over time.
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
  /me/drive/root:/{item-path}:/createLink:
    post:
      summary: Create A Sharing Link For A Drive Item
      description: Create a sharing link for a DriveItem You can use createLink action
        to share a DriveItem via a sharing link.
      operationId: CreateASharingLinkForADriveItem
      x-api-path-slug: medriverootitempathcreatelink-post
      parameters:
      - in: path
        name: item-path
        type: string
      responses:
        200:
          description: OK
      tags:
      - CreateSharing
      - LinkA
      - Drive
      - Item
  /groups/{group-id}/drive/items/{item-id}/createLink:
    post:
      summary: Create A Sharing Link For A Drive Item
      description: Create a sharing link for a DriveItem You can use createLink action
        to share a DriveItem via a sharing link.
      operationId: CreateASharingLinkForADriveItem
      x-api-path-slug: groupsgroupiddriveitemsitemidcreatelink-post
      parameters:
      - in: path
        name: group-id
        type: string
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
  /drives/{drive-id}/items/{item-id}/createLink:
    post:
      summary: Create A Sharing Link For A Drive Item
      description: Create a sharing link for a DriveItem You can use createLink action
        to share a DriveItem via a sharing link.
      operationId: CreateASharingLinkForADriveItem
      x-api-path-slug: drivesdriveiditemsitemidcreatelink-post
      parameters:
      - in: path
        name: drive-id
        type: string
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
  /me/drive/root/delta:
    get:
      summary: Track Changes For A Drive
      description: Track changes for a Drive This method allows your app to track
        changes to a drive and its children over time.
      operationId: TrackChangesForADrive
      x-api-path-slug: medriverootdelta-get
      responses:
        200:
          description: OK
      tags:
      - Track
      - Changes
      - Drive
  /drives/{drive-id}/root/delta:
    get:
      summary: Track Changes For A Drive
      description: Track changes for a Drive This method allows your app to track
        changes to a drive and its children over time.
      operationId: TrackChangesForADrive
      x-api-path-slug: drivesdriveidrootdelta-get
      parameters:
      - in: path
        name: drive-id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Track
      - Changes
      - Drive
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