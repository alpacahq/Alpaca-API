# Alpaca API Issue Tracker

This repository is the place to report bugs in the Alpaca API, its OpenAPI specs, and its documentation. It does not accept feature requests or support questions; see [Where to go instead](#where-to-go-instead).

> [!WARNING]
> This repository is public. **Never include API keys, secrets, OAuth tokens, or account numbers** in an issue or comment. Replace them with placeholders such as `<API_KEY>`.

## Documentation

- [Alpaca API docs (US)](https://docs.alpaca.markets/us/)
- [OpenAPI specs (US)](https://docs.alpaca.markets/us/openapi)
- [Docs for other regions](https://docs.alpaca.markets/us/page/regions)

## Reporting a bug

1. Check the [status page](https://status.alpaca.markets) to rule out an ongoing incident.
2. Search the [existing issues](https://github.com/alpacahq/alpaca-api/issues?q=is%3Aissue). If one matches, add a thumbs-up reaction or a comment with new details instead of opening a duplicate.
3. [Open a new issue](https://github.com/alpacahq/alpaca-api/issues/new/choose) and pick the form that fits best:
   - **API bug**: an endpoint or stream returns wrong data, errors, or behaves unexpectedly.
   - **OpenAPI spec bug**: a spec is wrong, incomplete, invalid, or breaks code generation.
   - **Docs bug**: a docs page is incorrect, outdated, unclear, or broken.

If you're not sure whether something is a spec bug or a docs bug, pick the closest one. Fill in as much of the form as you can, especially the full request URL and the `X-Request-ID` response header, so we can find your request.

## Where to go instead

| You have | Go to |
| --- | --- |
| A question about your account, funding, or orders | [Support request](https://alpaca.markets/support/request) |
| A possible outage | [Status page](https://status.alpaca.markets), which offers email, SMS, Slack, webhook, and RSS subscriptions |
| A feature request, general question, or dashboard bug | [Community Forum](https://forum.alpaca.markets) or [Community Slack](https://alpaca.markets/slack) |
| An SDK bug or SDK feature request | The SDK's repository: [Python](https://github.com/alpacahq/alpaca-py/issues), [JavaScript](https://github.com/alpacahq/alpaca-trade-api-js/issues), [Go](https://github.com/alpacahq/alpaca-trade-api-go/issues), [C#](https://github.com/alpacahq/alpaca-trade-api-csharp/issues), [Java](https://github.com/alpacahq/alpaca-java/issues) |
| A Broker API issue as a broker partner | Your Customer Success Manager, or an issue here |
