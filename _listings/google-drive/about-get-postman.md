{
  "info": {
    "name": "Google Drive Get About",
    "_postman_id": "9481e775-3a1e-4aca-af6c-584aef6bb010",
    "description": "Gets information about the user, the user's Drive, and system capabilities.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "About",
      "item": [
        {
          "id": "f1d544af-4f62-4017-8fee-cd7783398fb5",
          "name": "drive.about.get",
          "request": {
            "url": "http://www.googleapis.com/drive/v3/about",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the user, the user's Drive, and system capabilities."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bacc607c-4226-4fdc-9e2e-33e1aa081040"
            }
          ]
        }
      ]
    }
  ]
}