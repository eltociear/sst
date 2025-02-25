---
title: Overview
description: "Docs for the constructs in the @serverless-stack/resources package"
slug: /constructs
---

:::note
This is the SST v1 Constructs doc. If you are using v0.x, see the [Constructs doc here](/constructs/v0).
:::

Constructs are the basic building blocks of SST apps. Each construct consists of multiple AWS resources to make up a functional unit. SST picks sensible defaults for the underlying resources, so you are not exposed to all the complexity up front.

Here's a rough list of the types of contructs that SST supports.

## API
- [`Api`](./Api.md)
- [`GraphQLApi`](./GraphQLApi.md)
- [`AppSyncApi`](./AppSyncApi.md)
- [`WebSocketApi`](./WebSocketApi.md)

## Frontend
- [`RemixSite`](./RemixSite.md)
- [`StaticSite`](./StaticSite.md)
- [`NextjsSite`](./NextjsSite.md)
- [`ViteStaticSite`](./ViteStaticSite.md)
- [`ReactStaticSite`](./ReactStaticSite.md)

## Database
- [`RDS`](./RDS.md)
- [`Table`](./Table.md)

## Storage
- [`Bucket`](./Bucket.md)

## Auth
- [`Auth`](./Auth.md)
- [`Cognito`](./Cognito.md)

## Async
- [`Cron`](./Cron.md)
- [`Topic`](./Topic.md)
- [`Queue`](./Queue.md)
- [`EventBus`](./EventBus.md)
- [`KinesisStream`](./KinesisStream.md)
