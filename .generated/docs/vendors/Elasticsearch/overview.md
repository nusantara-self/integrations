## Analyzers (1)

### Elasticsearch_Analysis `v1.0`
Search for IoCs in Elasticsearch

- **Author:** Nick Prokop
- **License:** MIT
- **Data Types:** `url`, `domain`, `ip`, `hash`, `filename`, `fqdn`, `mail`, `mail-subject`, `user-agent`, `hostname`, `username`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/Elasticsearch/Elasticsearch_Analysis.json)

---

## Responders (1)

### ElasticSecurity_AlertStatusSync `v1.0`
Sync TheHive case/alert status back to the corresponding Elastic Security detection alert(s), including a closing reason

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case`, `thehive:alert`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Elasticsearch/ElasticSecurity_AlertStatusSync.json)

---

## External Integrations (1)

External integrations that connect Elasticsearch with TheHive:

### TheHive Connector for Kibana
Native Kibana connector that allows Elasticsearch to create alerts and create cases in TheHive

- **Type:** connector
- **Documentation:** [https://www.elastic.co/docs/reference/kibana/connectors-kibana/thehive-action-type](https://www.elastic.co/docs/reference/kibana/connectors-kibana/thehive-action-type)
