# Construction Monitor (construction-monitor)

Construction Monitor aggregates building-permit data from county and municipal sources nationwide and resells it as construction leads, contractor intelligence, and historical permit research. Programmatic access is offered through a REST + JSON API backed by Elasticsearch and a weekly data-dump option delivered over secure FTP. Both channels are account-managed; partners receive credentials and a documented endpoint contract directly from Construction Monitor.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/construction-monitor/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Construction
- Contractors
- Lead Generation
- Permits
- Real Estate

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-04-29

## APIs

### Construction Monitor Permits API
REST + JSON service backed by Elasticsearch that lets partners search building permits, retrieve full permit detail records, and pull delta updates on a polling schedule. Authentication is handled with a simple API-key scheme provisioned per customer. Used to drive lead-generation pipelines, populate CRM and BI tools, and power downstream construction analytics.

**Human URL:** [https://www.constructionmonitor.com/data](https://www.constructionmonitor.com/data)

#### Tags

- Elasticsearch, JSON, Permits, REST

### Construction Monitor Weekly Data Dump (SFTP)
Weekly bulk delivery of permit records over secure FTP for partners that prefer batch ingestion to live API polling. Suitable for warehousing millions of permits without operating a live integration.

#### Tags

- Bulk, Data Dump, Permits, SFTP

## Common Properties

- [Website](https://www.constructionmonitor.com)
- [Data Products](https://www.constructionmonitor.com/data)
- [Contact / API Access](https://www.constructionmonitor.com/contact)
- [Blog](https://www.constructionmonitor.com/blog)
- [Privacy Policy](https://www.constructionmonitor.com/privacy-policy)
- [Terms of Service](https://www.constructionmonitor.com/terms-of-use)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
