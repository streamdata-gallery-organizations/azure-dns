---
name: Azure DNS
x-slug: azure-dns
description: Azure DNS lets you host your DNS domains alongside your Azure apps and
  manage DNS records by using your existing Azure subscription. Microsoft&rsquo;s
  global network of name servers has the reach, scale, and redundancy to ensure ultra-fast
  DNS responses and ultra-high availability for your domains. With Azure DNS, you
  can be sure your DNS will always be fast and available.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-dns-01-host.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure DNS
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/apis.md
specificationVersion: "0.14"
apis:
- name: DnsManagementClient - Record Sets Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordtyperelativerecordsetname-patch
  description: Updates a record set within a DNS zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-dns-01-host.png
  humanURL: https://azure.microsoft.com/en-us/services/dns/
  baseURL: ://management.azure.com//
  tags: DNS, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordtyperelativerecordsetname-patch-openapi.md
- name: DnsManagementClient - Record Sets Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordtyperelativerecordsetname-put
  description: Creates or updates a record set within a DNS zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-dns-01-host.png
  humanURL: https://azure.microsoft.com/en-us/services/dns/
  baseURL: ://management.azure.com//
  tags: DNS, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordtyperelativerecordsetname-put-openapi.md
- name: DnsManagementClient - Record Sets Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordtyperelativerecordsetname-delete
  description: Deletes a record set from a DNS zone. This operation cannot be undone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-dns-01-host.png
  humanURL: https://azure.microsoft.com/en-us/services/dns/
  baseURL: ://management.azure.com//
  tags: DNS, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordtyperelativerecordsetname-delete-openapi.md
- name: DnsManagementClient - Record Sets Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordtyperelativerecordsetname-get
  description: Gets a record set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-dns-01-host.png
  humanURL: https://azure.microsoft.com/en-us/services/dns/
  baseURL: ://management.azure.com//
  tags: DNS, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordtyperelativerecordsetname-get-openapi.md
- name: DnsManagementClient - Record Sets List By Type
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordtype-get
  description: Lists the record sets of a specified type in a DNS zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-dns-01-host.png
  humanURL: https://azure.microsoft.com/en-us/services/dns/
  baseURL: ://management.azure.com//
  tags: DNS, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordtype-get-openapi.md
- name: DnsManagementClient - Record Sets List By Dns Zone
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordsets-get
  description: Lists all record sets in a DNS zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-dns-01-host.png
  humanURL: https://azure.microsoft.com/en-us/services/dns/
  baseURL: ://management.azure.com//
  tags: DNS, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordsets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonenamerecordsets-get-openapi.md
- name: DnsManagementClient - Zones Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonename-put
  description: Creates or updates a DNS zone. Does not modify DNS records within the
    zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-dns-01-host.png
  humanURL: https://azure.microsoft.com/en-us/services/dns/
  baseURL: ://management.azure.com//
  tags: DNS, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonename-put-openapi.md
- name: DnsManagementClient - Zones Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonename-delete
  description: 'Deletes a DNS zone. WARNING: All DNS records in the zone will also
    be deleted. This operation cannot be undone.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-dns-01-host.png
  humanURL: https://azure.microsoft.com/en-us/services/dns/
  baseURL: ://management.azure.com//
  tags: DNS, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonename-delete-openapi.md
- name: DnsManagementClient - Zones Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonename-get
  description: Gets a DNS zone. Retrieves the zone properties, but not the record
    sets within the zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-dns-01-host.png
  humanURL: https://azure.microsoft.com/en-us/services/dns/
  baseURL: ://management.azure.com//
  tags: DNS, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszoneszonename-get-openapi.md
- name: DnsManagementClient - Zones List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszones-get
  description: Lists the DNS zones within a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-dns-01-host.png
  humanURL: https://azure.microsoft.com/en-us/services/dns/
  baseURL: ://management.azure.com//
  tags: DNS, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszones-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkdnszones-get-openapi.md
- name: DnsManagementClient - Zones List
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-networkdnszones-get
  description: Lists the DNS zones in all resource groups in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-dns-01-host.png
  humanURL: https://azure.microsoft.com/en-us/services/dns/
  baseURL: ://management.azure.com//
  tags: DNS, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidprovidersmicrosoft-networkdnszones-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-dns/master/_listings/azure-dns/subscriptionssubscriptionidprovidersmicrosoft-networkdnszones-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.devtest.labs.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.dns.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/dns/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/dns/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/dns/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/dns/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---