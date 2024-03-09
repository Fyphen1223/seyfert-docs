---
editUrl: false
next: false
prev: false
title: "RawFile"
---

Represents a file to be added to the request

## Properties

| Property | Type | Description |
| :------ | :------ | :------ |
| `contentType?` | `string` | Content-Type of the file |
| `data` |  \| `string` \| `number` \| `boolean` \| `Uint8Array` \| `Buffer` | The actual data for the file |
| `key?` | `string` | An explicit key to use for key of the formdata field for this file.
| `name` | `string` | The name of the file |