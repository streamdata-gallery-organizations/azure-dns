{
  "info": {
    "name": "Azure DNS API Zones Delete",
    "_postman_id": "af146385-8d47-4fa5-b130-0dbf85ed5eee",
    "description": "Deletes a DNS zone. WARNING: All DNS records in the zone will also be deleted. This operation cannot be undone.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "zones",
      "item": [
        {
          "id": "ce1ad25c-f17c-4f31-9e2e-13a475e78834",
          "name": "Zones_Delete",
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
            "method": "DELETE",
            "header": [
              {
                "key": "If-Match",
                "value": "{}",
                "description": "The etag of the DNS zone",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a DNS zone"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "01e2dfb7-d0f9-4876-a4e1-f2dd17429541"
            }
          ]
        }
      ]
    }
  ]
}