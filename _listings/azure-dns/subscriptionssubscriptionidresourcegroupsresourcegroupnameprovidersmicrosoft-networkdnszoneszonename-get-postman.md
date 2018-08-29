{
  "info": {
    "name": "Azure DNS API Zones Get",
    "_postman_id": "82720d97-096f-4dd8-a76c-cbaacb9882bb",
    "description": "Gets a DNS zone. Retrieves the zone properties, but not the record sets within the zone.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "zones",
      "item": [
        {
          "id": "7a79f913-768d-48e3-937c-28a72387503b",
          "name": "Zones_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/dnsZones/:zoneName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "zoneName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a DNS zone"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f54f8a65-54b6-4a6b-93dd-869f4cb9f0f2"
            }
          ]
        }
      ]
    }
  ]
}