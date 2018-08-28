swagger: "2.0"
x-collection-name: Google Drive
x-complete: 1
info:
  title: Google Drive
  description: manages-files-in-drive-including-uploading-downloading-searching-detecting-changes-and-updating-sharing-permissions-
  termsOfService: https://developers.google.com/terms/
  contact:
    name: Google
    url: https://google.com
  version: v3
host: www.googleapis.com
basePath: /drive/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /about:
    get:
      summary: Get About
      description: Gets information about the user, the user's Drive, and system capabilities.
      operationId: drive.about.get
      x-api-path-slug: about-get
      responses:
        200:
          description: OK
      tags:
      - About