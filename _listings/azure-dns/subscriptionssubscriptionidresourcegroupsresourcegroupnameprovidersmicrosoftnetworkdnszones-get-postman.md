{
  "info": {
    "name": "Azure DNS API Zones List By Resource Group",
    "_postman_id": "321296b0-f3fb-4389-ac56-6f444bb89d91",
    "description": "Lists the DNS zones within a resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "zones resource group",
      "item": [
        {
          "id": "1baa6ed1-1a44-4492-83a7-fd623fb4fb30",
          "name": "Zones_ListByResourceGroup",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/dnsZones"
              ],
              "query": [
                {
                  "key": "$top",
                  "value": "%7B%7D",
                  "disabled": false
                },
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
            "description": "Lists the DNS zones within a resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d915170a-06e9-461d-b2b7-ab944d7484d4"
            }
          ]
        }
      ]
    }
  ]
}