# HTTP Response and Error codes

The Basicmails API uses the following HTTP codes:

Error Code | Meaning
---------- | -------
202 | Accepted
400 | Bad Request -- Your request is invalid.
401 | Unauthorized -- Your API key is invalid or expired.
403 | Forbidden
404 | Not Found
406 | Not Acceptable -- You requested a format that isn't json.
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
