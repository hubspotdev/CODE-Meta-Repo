# CODE-Hub
This is the central hub for CODE

## Projects

| Project | Description |
|---|---|
| [associations-sync-server](https://github.com/hubspotdev/associations-sync-server) | Express.js server for creating, retrieving, deleting, and mapping associations between HubSpot CRM objects. |
| [crm-object-sync](https://github.com/hubspotdev/crm-object-sync) | Best practices for syncing CRM contact records between HubSpot and an external application. |
| [property-mapping-client](https://github.com/hubspotdev/property-mapping-client) | React client for mapping company and contact properties, used with property-mapping-server. |
| [property-mapping-server](https://github.com/hubspotdev/property-mapping-server) | Node.js server that manages property mappings between a native system and HubSpot. |
| [webhooks-journal-example](https://github.com/hubspotdev/webhooks-journal-example) | Keeps a local copy of CRM contacts in sync by polling the Webhooks Journal API, with bulk snapshot backfill and subscription filters. |

Each project is included as a git submodule. To clone everything at once:

```bash
git clone --recurse-submodules https://github.com/hubspotdev/CODE-Meta-Repo.git
```
