---
layout: bidder
title: Viant
description: Prebid Viant Bidder Adapter
biddercode: viant
media_types: banner, video, native
tcfeu_supported: false
coppa_supported: true
usp_supported: true
gpp_supported: false
schain_supported: false
userId: uid2, unifiedId
pbjs: true
prebid_member: false
dchain_supported: false
safeframes_ok: false
deals_supported: true
floors_supported: true
fpd_supported: false
ortb_blocking_supported: false
gvl_id: none
pbs: false
multiformat_supported: will-bid-on-one
sidebarType: 1
---

### Registration

If you have any questions regarding set up, please reach out to <dist-runtime@viantinc.com>.

#### Bid Params

{: .table .table-bordered .table-striped }
| Name                | Scope    | Description                                                                                                                                                                   | Example                                               | Type             |
|---------------------|----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|------------------|
| `publisherId`       | required | PublisherId to identify the Site from which Bid Requests will be seen.                                                                                                        | `12345`                                               | `integer`         |
