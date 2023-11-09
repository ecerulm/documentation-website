---
layout: default
title: Plugin settings
parent: Configuring OpenSearch
nav_order: 100
---

# Plugin settings

The following settings are related to OpenSearch plugins.

## Alerting plugin settings

For information about alerting settings, see [Alerting settings]({{site.url}}{{site.baseurl}}/observing-your-data/alerting/settings/#alerting-settings).

## Anomaly Detection plugin settings

For information about anomaly detection settings, see [Settings]({{site.url}}{{site.baseurl}}/observing-your-data/ad/settings/).

## Asynchronous Search plugin settings

For information about asynchronous search settings, see [Settings]({{site.url}}{{site.baseurl}}/search-plugins/async/settings/).

## Cross-Cluster Replication plugin settings

For information about cross-cluster replication settings, see [Replication settings]({{site.url}}{{site.baseurl}}/tuning-your-cluster/replication-plugin/settings/).

## Custom Codecs plugin settings

For information about settings related to custom codecs, see [Index codecs]({{site.url}}{{site.baseurl}}/im-plugin/index-codecs/).

## Geospatial plugin settings

For information about the Geospatial plugin's IP2Geo processor settings, see [Cluster settings]({{site.url}}{{site.baseurl}}/ingest-pipelines/processors/ip2geo/#cluster-settings).

## Index Management plugin settings

For information about index state management (ISM) settings, see [ISM settings]({{site.url}}{{site.baseurl}}/im-plugin/ism/settings/).

### Index rollup settings

For information about index rollup settings, see [Settings]({{site.url}}{{site.baseurl}}/im-plugin/index-rollups/settings/).

## Job Scheduler plugin settings

For information about the Job Scheduler plugin settings, see [Job Scheduler cluster settings]({{site.url}}{{site.baseurl}}/monitoring-your-cluster/job-scheduler/index/#job-scheduler-cluster-settings).

## k-NN plugin settings

For information about k-NN settings, see [k-NN settings]({{site.url}}{{site.baseurl}}/search-plugins/knn/settings/).

## ML Commons plugin settings

For information about machine learning settings, see [ML Commons cluster settings]({{site.url}}{{site.baseurl}}/ml-commons-plugin/cluster-settings/).

## Neural Search plugin settings

The Security Analytics plugin supports the following settings:

- `plugins.neural_search.hybrid_search_disabled` (Boolean): Disables hybrid search. Default is `false`.

## Security plugin settings

For information about the Security plugin settings, see [Security settings]({{site.url}}{{site.baseurl}}/install-and-configure/configuration/security-settings/).

## Security Analytics plugin settings

The Security Analytics plugin supports the following settings:

- `plugins.security_analytics.enable_workflow_usage` (Boolean): Supports Alerting plugin workflow integration with Security Analytics. Determines whether composite monitor workflows are generated for the Alerting plugin after creating a new threat detector in Security Analytics. By default, the setting is `true`. 

    When set to `true`, composite monitor workflows based on an associated threat detector's configuration are enabled. When set to `false`, composite monitor workflows based on an associated threat detector's configuration are disabled. 
    
    For more information about Alerting plugin workflow integration with Security Analytics, see [Integrated Alerting plugin workflows]({{site.url}}{{site.baseurl}}/security-analytics/sec-analytics-config/detectors-config/#integrated-alerting-plugin-workflows). 

## SQL plugin settings

For information about settings related to SQL and PPL, see [SQL settings]({{site.url}}{{site.baseurl}}/search-plugins/sql/settings/).