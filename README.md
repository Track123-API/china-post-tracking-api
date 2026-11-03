# China Post Tracking API & Webhooks

Use Track123 to track China Post shipments through one unified shipment tracking API.

Track123 lets your application register China Post tracking numbers, retrieve tracking updates, and receive delivery events through webhooks.

- China Post carrier code: `china-post`

- [Track China Post packages on Track123](https://www.track123.com/carriers/china-post)

- [China Post API integration page](https://www.track123.com/carriers/china-post/api)

- [Track123 API documentation](https://docs.track123.com)

> This repository explains how to track China Post shipments with Track123. It is not official China Post API documentation.

## China Post tracking API integration

When your application already knows that a shipment is handled by China Post, set `courierCode` to `china-post` when registering the tracking number.

Use [Carrier Detection](https://docs.track123.com/reference/detection-courier) when your application does not have an approved carrier code.

Use your own tracking number in the registration request. Track123 does not provide public test tracking numbers in this repository.

## Integration guides

- [China Post tracking webhook](webhook.md)
- [China Post tracking statuses](tracking-status.md)
- [China Post API errors and rate limits](errors-and-rate-limits.md)

## China Post tracking API resources

- [Register package trackings](https://docs.track123.com/reference/register-package-trackings)
- [Get package trackings](https://docs.track123.com/reference/get-package-trackings)
- [Carrier detection](https://docs.track123.com/reference/detection-courier)

## Track China Post packages and view FAQs

For shipment lookup, carrier contact information, and customer-facing FAQs, visit [China Post tracking on Track123](https://www.track123.com/carriers/china-post).

## More Track123 resources

- [All supported carriers](https://www.track123.com/carriers)
- [Track123 developer documentation](https://docs.track123.com)

Carrier names and websites are used only to identify compatible carriers. Track123 is not affiliated with or endorsed by China Post unless explicitly stated.
