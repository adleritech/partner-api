# Liftago Partner API

Current RAML specifications of the partner API.

HTML version available [here](https://s3-eu-west-1.amazonaws.com/partner-api/delivery-api-v1.0.html).

To upload:

```
raml2html delivery-api-v1.0.raml > delivery-api-v1.0.html
aws --region eu-west-1 s3 cp delivery-api-v1.0.html s3://partner-api/delivery-api-v1.0.html
```
