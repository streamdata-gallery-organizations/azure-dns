---
swagger: "2.0"
x-collection-name: Azure DNS
x-complete: 0
info:
  title: Azure DNS API Record Sets Update
  description: Updates a record set within a DNS zone.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/dnsZones/{zoneName}/{recordType}/{relativeRecordSetName}
  : patch:
      summary: Record Sets Update
      description: Updates a record set within a DNS zone.
      operationId: RecordSets_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordtyperelativerecordsetname-patch
      parameters:
      - in: header
        name: If-Match
        description: The etag of the record set
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the Update operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: recordType
        description: The type of DNS record in this record set
      - in: path
        name: relativeRecordSetName
        description: The name of the record set, relative to the name of the zone
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: zoneName
        description: The name of the DNS zone (without a terminating dot)
      responses:
        200:
          description: OK
      tags:
      - Record Sets
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