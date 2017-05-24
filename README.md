# api-v2-docs
Parcelninja public store API version 2

# Parcelninja Store API Version 2

## Rules

1. Input dates use ISO 8601 format of _YYYYMMDD_
2. Dates in output data are in UTC - always
3. Country codes are ISO 3166-1 alpha-2 (eg, "ZA" for South Africa)
4. Shipments & Stock are referenced uniquely with a `ShortId` string (see *General Objects*)
5. All communication strictly over HTTPS

## Future Feature (V3) ![v3]

Some features may be annotated with ![v3] which indicates that it could be implemented in the next version of the API.

### Request Headers

All requests to the API should include these headers

|Name|Value(s)|
|---:|---|
|Content-Type|application/json|
|Accept|application/json|
|Authorization|*`Basic Base64(Username:Password)`*|

--------------------------------------------------------------------------------
## Inbounds

## Outbounds

## Inventory

## Value-Added-Services (VAS)

## Tracking

## Webhooks

## Delivery Quoting 

## Stock ![V3]

## Pickup ![V3]

## Fees 

## Billing

## Lookups

## Logs

## Courier

## General Objects

## References

* ISO 8601 "_Date formats_" [ISO8601]
* ISO 3166-1 "_Country codes_" [ISO3166-1]
    
--------------------------------------------------------------------------------
_End of document_

[v3]: https://thumb.ibb.co/fv6gYF/v3.jpg "Indicates concept could be implemented in v3"
[ISO8601]: https://en.wikipedia.org/wiki/ISO_8601
[ISO3166-1]: https://en.wikipedia.org/wiki/ISO_3166-1