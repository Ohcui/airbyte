# Chartmogul

## Sync overview

The PersistIq source supports Full Refresh syncs only.

This source syncs data for the [PersistIq API](https://dev.chartmogul.com/reference/).


### Output schema

This Source is capable of syncing the following streams:

* [Users](https://apidocs.persistiq.com/#users)
* [Leads](https://apidocs.persistiq.com/#leads)
* [Campaigns](https://apidocs.persistiq.com/#campaigns)

### Features

| Feature | Supported?\(Yes/No\)
| :--- | :--- |
| Full Refresh Sync | Yes |
| Incremental - Append Sync | No |
| Namespaces | No |

### Performance considerations

The Chartmogul connector should not run into Chartmogul API limitations under normal usage. Please [create an issue](https://github.com/airbytehq/airbyte/issues) if you see any rate limit issues that are not automatically retried successfully.

## Getting started

### Requirements

* PersistIq API Key

### Setup guide

Please read [How to find your API key](https://apidocs.persistiq.com/#introduction).