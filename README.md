# api

> **Version:** 5.7.0

This is the source code for the [BharatRadar](https://bharatradar.com) API.

It runs in Kubernetes and is written in Python / asyncio / aiohttp.

**This API is compatible with the ADSBExchange Rapid API. It is a drop-in replacement.**

## Documentation

Interactive documentation for the API lives at [api.bharatradar.com/docs](https://api.bharatradar.com/docs)

## Rate limits

Rate limits are dynamic based on the environment load. 

If you get 4xx errors, you are doing something wrong. 

In the future, you will require an API key which you can obtain by [feeding to BharatRadar](https://bharatradar.com/#become-feeder).

This will be a way to ensure that the API is being used responsibly and by people who are willing to contribute to the project.
