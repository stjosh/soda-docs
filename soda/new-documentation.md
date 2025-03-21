---
layout: default
title: What's new in Soda docs?
description: Review a changelog of additions and revisions to Soda documentation.
parent: Learning resources
---

# What's new in Soda docs?

<br />

#### March 14, 2025
 * Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.9.3.

#### February 27, 2025
 * Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.39.

#### February 26, 2025
 * Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.9.2.

#### February 24, 2025
 * Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.9.1.

#### February 21, 2025
 * Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.9.0.

#### February 20, 2025
 * Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.5.0.

#### February 14, 2025
 * Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.8.19.

#### February 6, 2025
 * Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.38.

#### February 4, 2025
 * Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.8.16 - 1.8.18.

#### January 28, 2025
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.8.14.

#### January 9, 2025
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.8.13.

#### January 8, 2025
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.8.12.

#### January 7, 2025
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.8.10 - 1.8.11 and Soda Core 3.4.4.

#### January 6, 2025
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.8.6 - 1.8.9.

#### November 29, 2024
* Published a new How To guide for building a custom Soda data quality [dashboard]({% link api-docs/public-api-to-grafana.md %}) in Grafana. 

#### November 28, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.4.2.

#### November 27, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.8.4.

#### November 26, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.8.3.

#### November 19, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.34.

#### November 15, 2024
* Added instructions for optimizing Soda Agent performance using [Change sample data and failed rows memory limit]({% link soda-agent/extras.md %}#change-sample-data-and-failed-rows-memory-limits)
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.33.

#### November 14, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.8.2.

#### November 13, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.8.1.

#### November 1, 2024
* Updated [anomaly detection check]({% link soda-cl/anomaly-detection.md %}) documentation to include support for freshness and user-defined metrics.

#### October 29, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.8.0 and Soda Agent 1.1.32.

#### October 28, 2024
* Add to Soda Agent extras with [instructions]({% link soda-agent/extras.md %}#use-soda-cloud-api-keys-from-an-existing-secret) on how to use an existing Kubernetes secret for Soda Cloud API keys.

#### October 25, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.7.1.

#### October 23, 2024
* Added instructions for installing `pydanticv1` extra library package; see [Troubleshoot]({% link soda-library/install.md %}#troubleshoot) section of installation instructions.

#### October 22, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.4.1.

#### October 21, 2024
* Published a new How To guide for building a custom Soda data quality [reporting dashboard]({% link api-docs/reporting-api-to-overview-dashboards.md %}) in Sigma. 
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.4.0.

#### October 17, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.6.5 and 1.7.0, and Soda Cloud Bulk-edit of dataset responsibilities and attributes.

#### October 16, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.31.

#### October 10, 2024
* Added an optional `auto_exclude_anomalies` parameter for [anomaly detection]({% link soda-cl/anomaly-detection.md %}#add-optional-training-dataset-configurations) that you can use to ignore or include existing anomalies in a training dataset.

#### October 9, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.30.
* Updated Test data quality in a Databricks pipeline to include, among minor edits, [Input data checks and model output checks]({% link soda/quick-start-databricks-pipeline.md %}#input-data-checks-and-model-output-checks).

#### October 8, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.6.4.

#### October 7, 2024
* Updated the [Soda Library Python API reference]({% link soda-library/python_api.md %}) documentation with attributes for samples limit, and an optional config for using variables.

#### October 3, 2024
* Added documentation for using [variables]({% link soda-cl/failed-row-samples.md %}#configure-a-python-custom-sampler) in the `SampleRef` `message` parameter for Python custom sampler to collect and display failed row samples.

#### October 2, 2024
* Added documentation of new parameters for the `soda-pandas-dask` package to address changed behavior when upgrading to version 1.6.4 or greater. See [Add optional parameter for `COUNT`]({% link soda/connect-dask.md %}#add-optional-parameter-for-count) and [Add optional parameter for text data conversion]({% link soda/connect-dask.md %}#add-optional-parameter-for-text-data-conversion).
* Added example for `SampleRef` with Python Custom Sampler to direct users to a [bespoke location]({% link soda-cl/failed-row-samples.md %}#configure-a-python-custom-sampler) to find failed row samples for checks with failed test results.
* Added details for [assigning global roles]({% link soda-cloud/roles-global.md %}#manage-global-roles) to users or user groups.

#### September 30, 2024
* Added [Soda Library Python API reference]({% link soda-library/python_api.md %}) documentation.

#### September 26, 2024
* Updated documentation to include customizable permissions for [global]({% link soda-cloud/roles-global.md %}) and [dataset roles]({% link soda-cloud/roles-dataset.md %}) in Soda Cloud, plus the ability to create new roles.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.6.3 and Soda Agent 1.1.29.

#### September 25, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.28.
* Published [Soda product release states]({% link release-notes/states.md %}) to describe the status of newly-released features or functionality.

#### September 24, 2024
* Add [Configuration and setting hierarchy]({% link soda-cl/failed-row-samples.md %}#configuration-and-setting-hierarchy) section to offer an overview of behavior for failed row sample collection.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.6.2.
* Removed note about an upper limit of 10,000 for collecting failed row samples.
* Added Soda Cloud connection configuration details to [Connect to Dask and Pandas]({% link soda/connect-dask.md %}), and corrcted install package names in Troubleshooting section.
* Added [troubleshooting]({% link soda/integrate-msteams.md %}#troubleshoot) solution to MS Teams integration.

#### September 23, 2024
* Compiled and updated [failed row samples]({% link soda-cl/failed-row-samples.md %}) documentation, including:
  * the option to use `scan context` in a CustomSampler to read/write data to/from a scan
  * the option to `collect failed rows` samples from specific columns in a dataset in Soda Cloud
  * the option to disable failed row sample collection from all datasets, except those with explicit configuration to collect samples
* Updated [Failed row checks]({% link soda-cl/failed-rows-checks.md %}) and [User-defined checks]({% link soda-cl/user-defined.md %}) to include optional configuration to specify a single column against which to run the check.
* Revised [check attributes]({% link soda-cl/check-attributes.md %}#apply-an-attribute-to-one-or-more-checks) configuration when applying attributes to more than one check.

#### September 23, 2024
* Moved [data contract lanugage reference]({% link soda/data-contracts-checks.md %}) content to soda-core GitHub repository to avoid confusion with SodaCL reference. 

#### September 19, 2024
* Added attribute mapping to [Okta SSO integration]({% link soda-cloud/sso.md %}#add-soda-cloud-to-okta) documentation.
* Correct reconciliation check documentation to remove the option to add a list of comma-separated datasets to compare.

#### September 18, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.27.

#### September 17, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.6.1.

#### September 13, 2024
* Added egress IP addresses for Soda Cloud. See: [Receiving events from Soda Cloud]({% link soda/data-privacy.md %}#receiving-events-from-soda-cloud).

#### September 12, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.3.15 - 3.3.22.

#### September 8, 2024
* Published new use case guide for using Soda to test data quality in a [Dasger pipeline]({% link soda/quick-start-dagster.md %}).

#### September 4, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.6.0 and Soda Agent 1.1.26.

#### August 29, 2024
* Published new use case guide for using Soda to test data quality in an [Azure Data Factory pipeline]({% link soda/quick-start-adf.md %}).

#### August 28, 2024
* Updated documentation to [clarify]({% link soda/setup-guide.md %}#soda-hosted-vs-self-hosted-agent) when to deploy a self-hosted vs. Soda-hosted agent. 

#### August 20, 2024
* Published new use case guide for using Soda to test data quality in a [Databricks pipeline]({% link soda/quick-start-databricks-pipeline.md %}).

#### August 19, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.25.

#### August 14, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.25 and Soda Core 3.3.14.

#### August 13, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.24 and Soda Agent 1.1.24.

#### August 8, 2024
* Added content to clarify that Soda Library officially supports Python 3.8, 3.9, and 3.10.

#### August 2, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.23 and Soda Agent 1.1.23.

#### August 1, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.22 and Soda Agent 1.1.22.

#### July 31, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.21.
* Added [troubleshooting tip]({% link soda-cl/troubleshoot.md %}#databricks-issue-with-column-names-that-being-with-a-number) for running Soda scans on Databricks where column names beging with numbers.
* Added [Known issues and limitations]({% link soda-cloud/anomaly-dashboard.md %}#known-issues-and-limitations) section to anomaly dashboard content.

#### July 29, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.3.13.

#### July 25, 2024
* Documented instructions for how to add one-way [user group synchronization]({% link soda-cloud/sso.md %}#sync-user-groups-from-an-idp) from an SSO IdP to Soda Cloud.
* Updated [data type support]({% link soda/connect-mssql.md %}#supported-data-types) for MS SQL Server to include NCHAR, NVARCHAR, and BINARY. 

#### July 24, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.20 and Soda Agent 1.1.21.

#### July 23, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.19.

#### July 22, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.18.
* Updated [compatibility]({% link soda-cloud/anomaly-dashboard.md %}#compatibility) for anomaly dashboard preview activation.
* Added clarification for [Soda compatibility]({% link soda/connect-db2.md %}#compatibility) with IBM DB2 data sources, LUW vs. z/OS.

#### July 19, 2024
* Updated MS Teams integration documentation to reference creating Workflows in MS Teams instead of Office 365 Connectors. Microsoft is retiring the connectors effective August 15, 2024. If you have previously set up a Soda integration with an Office 365 connector, follow the instructions for <a href="https://support.microsoft.com/en-us/office/creating-a-workflow-from-a-channel-in-teams-242eb8f2-f328-45be-b81f-9817b51a5f0e" target="_blank">Creating a workflow from a channel in Teams</a>, then update the integration URL in your existing Soda <> MS Teams integration in Soda Cloud.

#### July 18, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agnet 1.1.20 and Soda Core 3.3.12.
* Added `host` and `port` as optional connection configuration parameters for [Snowflake]({% link soda/connect-snowflake.md %}).
* Added an optional `multi_subnet_failover` parameter to the connection configuration for [MS SQL]({% link soda/connect-mssql.md %}).
* Added an optional `sslmode` parameter to the connection configurations for [PostgreSQL]({% link soda/connect-postgres.md %}) and [Denodo]({% link soda/connect-denodo.md %}).

#### July 17, 2024
* The preview program for anomaly dashboards for observability has reached its quota. Removed "Request preview access" links from documentation.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.17 and Soda Core 3.3.11.
* Corrected [Missing metrics]({% link soda-cl/missing-metrics.md %}#list-of-missing-metrics) and [Validity metrics]({% link soda-cl/validity-metrics.md %}#list-of-validity-metrics) to indicate that column config keys that use regex are supported only for text data types.

#### July 16, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.16 and Soda Agent 1.1.19.

#### July 15, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.15.

#### July 10, 2024
* Revised SodaGPT documentation to replace it with details about [Ask AI]({% link soda-cloud/ask-ai.md %}), Soda's in-product generative AI assistant.

#### July 8, 2024
* Documented the new functionality that enables Admin users in Soda Cloud to [create user groups]({% link soda-cloud/roles-global.md %}). 
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.3.10.

#### July 5, 2024
* Added clarification to the inclusion and exclusion [rules]({% link soda-cl/profile.md %}#inclusion-and-exclusion-rules) for profiling behavior.
* Repeated the configuration instructions for `samples columns` when implicitly collecting failed row samples in multiple places, notably in [Collect failed row samples]({% link soda-cl/optional-config.md %}#collect-failed-rows-samples).
* Added details about `RollingUpdate` when [upgrading]({% link soda/upgrade.md %}#upgrade-a-self-hosted-soda-agent) a self-hosted Soda Agent.

#### July 2, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.17 & 1.1.18 and Soda Library 1.5.14.

#### June 28, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.15 & 1.1.16, Soda Library 1.5.13, and Soda Core 3.3.7, 3.3.8 & 3.3.9. 
* Published documentation to accompany data contracts version 4 release.

#### June 27, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.14 and Soda Library 1.5.12.

#### June 24, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.13 and Soda Library 1.5.11.

#### June 21, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.12 and Soda Library 1.5.10.
* Documented how to [double-onboard a data source]({% link soda-cloud/double-onboard-datasource.md %}).

#### June 10, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.3.6 and Soda Library 1.5.9.

#### June 18, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.10 & 1.1.11 and Soda Library 1.5.7 & 1.5.8.

#### June 17, 2024
* Added a new docs page to begin recording data source [connection issues]({% link soda/connect-troubleshoot.md %}) and workarounds.
* Added link to troubleshooting advice for [reference checks]({% link soda-cl/reference.md %}#example-with-dataset-filter) that use dataset filters.
* Added troubleshooting advice for [Snowflake connections]({% link soda/connect-snowflake.md %}#troubleshoot) that use proxies.
* Clarified the use of [scan definition names]({% link soda-library/programmatic.md %}#set-up-basic-programmatic-invocation-in-python) in multiple programmatic scans in different pipelines.
* Added requirement for [SSO setup]({% link soda-cloud/sso.md %}#sso-access-to-soda-cloud) for customers to indicate whether they use Identity Provider Initiated (IdP-initiated) or and Service Provider Initiated (SP-initiated) single sign-on integrations. (Also included in procedural instructions.)
* Updated experimental support for [data contracts]({% link soda/data-contracts.md %}).

#### June 10, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.9 and Soda Library 1.5.6.

#### June 7, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.8.

#### June 6, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.7.

#### June 5, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.5.
* Added details about IRSA authentication for Athena and Redshift data sources.
* Added new [example script]({% link api-docs/api2csv-example.md %}) to fetch dataset and check info from a Soda Cloud account and transfer data into CSV files.

#### May 30, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for the Soda AI features generally available or available for preview access upon request.

#### May 29, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.4 and Soda Agents 1.1.5 and 1.1.6.
* Added documentation and example of including a failed rows query in a [user-defined check]({% link soda-cl/user-defined.md %}#example-with-failed-rows).

#### May 28, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.3.

#### May 25, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.4.

#### May 24, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.2, Soda Core 3.3.5, and Soda Agent 1.1.3.

#### May 23, 2024
* Documented the new feature for data quality observability, the automated, ML-driven [Anomaly Dashboard]({% link soda-cloud/anomaly-dashboard.md %}). 
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.1 and Soda Agent 1.1.2.
* Added note about using a different key for `database` for connecting to a [DuckDB]({% link soda/connect-duckdb.md %}) data source.

#### May 20, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.5.0.

#### May 17, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.4.10.

#### May 14, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.1 and Soda Library 1.4.9.

#### May 8, 2024
* Added to programmatic scan to include option to [run the scan locally]({% link soda-library/programmatic.md %}#set-up-basic-programmatic-invocation-in-python) and not send results to Soda Cloud.

#### May 7, 2024
* Added to example script for a programmatic scan to include a [check template]({% link soda-cl/check-template.md %}) file path. 
* Added [prerequisite]({% link soda-cl/soda-cl-overview.md %}#prerequisites) to no-code check creation that datasets must be discovered during data source onboarding.
* Touched up some details for advanced configuration of the [anomaly detection simulator]({% link soda-cl/anomaly-detection.md %}#adjust-advanced-simulator-parameters).
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.3.3 and 3.3.4, and Soda Library 1.4.8.

#### May 6, 2024
* Removed the Agreement deprecation notice as the decision to deprecate the feature has been reversed. 

#### April 30, 2024
* Published documentation for V3 of [data contracts]({% link soda/data-contracts.md %}), Soda's experimental way to set data quality standards for data products. 

#### April 29, 2024
* Added optional connection parameters to [Denodo]({% link soda/connect-denodo.md %}) data source configuration.

#### April 26, 2024
* Included information about [allocating resources]({% link soda-agent/deploy.md %}#system-requirements) for improved performance of a self-hosted Soda Agent.

#### April 25, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.1.0.
* Added documentation to initiate an [integration]({% link soda/integrate-purview.md %}) between Soda Cloud and Microscoft Purview.

#### April 24, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.3.2.

#### April 22, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.0.8-10.

#### April 12, 2024
* Added infomation about using [Soda and Airflow]({% link soda-library/orchestrate-scans.md %}#about-soda-and-airflow).

#### April 10, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.4.7, and Soda Agent 1.0.6 and 1.0.7
* Documented new parameters for [Dremio data source]({% link soda/connect-dremio.md %}) connections.

#### April 4, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.4.5 & 1.4.6, and Soda Agent 1.0.4 and 1.0.5.
* Updated the [example script]({% link soda/route-failed-rows.md %}#example-script) in Reroute failed row samples guide.

#### March 27, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.3.1, Soda Library 1.4.4, and Soda Agent 1.0.3.

#### March 21, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.4.3.
* Added more content and example for rerouting failed row samples.
* Added [requirement]({% link soda-cl/anomaly-detection.md %}#track-anomalies-and-relative-changes-by-group) for using anomaly detection checks in group by configurations: requires Soda Library 1.1.27 or greater, or Soda Agent 0.8.57 or greater. 

#### March 20, 2024
* Updated [Oracle connection]({% link soda/connect-oracle.md %}) configuration to use a more generic `connectstring` value.
* Prepred a separate reference section for [data contract checks]({% link soda/data-contracts-checks.md %}).

#### March 18, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.2.4 and 3.3.0.
* Added details for [passlisting domain names]({% link soda-agent/deploy.md %}#troubleshoot-deployment) for Soda Agent to communicate with Soda Cloud. 

#### March 15, 2024
* Published documentation for V2 of [data contracts]({% link soda/data-contracts.md %}), Soda's experimental way to set data quality standards for data products. 

#### March 12, 2024
* Add instructions for how to programmatically use Soda Library with an example script to [reroute failed row samples]({% link soda/route-failed-rows.md %}) to the CLI output instead of Soda Cloud.

#### March 6, 2024
* Update Soda [integration with dbtCloud]({% link soda/integrate-dbt.md %}#ingest-results-from-dbt-cloud-into-soda-cloud) to include instruction for dbt's new `access_URL`. 
* Updated the [Integrate Soda with Microsoft Teams]({% link soda/integrate-msteams.md %}) documentation to accommodate new MS isntructions for creating an incoming webhook.

#### March 5, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 1.0.1.
* Added MS SQL Server and Redshift to the [list of data sources]({% link soda-agent/managed-agent.md %}#compatibility) you can connect to using a Soda-hosted Agent. 
* Added details to Integrate with Alation documentation to [access an Alation account]({% link soda/integrate-alation.md %}#enable-api-access-to-alation-with-sso) guarded by SSO.
* Added example for [loading a JSON file]({% link soda/connect-dask.md %}#load-json-file-into-dataframe) into a Dataframe using Dask and Pandas.
* Added example for [comparing partitioned datasets]({% link soda-cl/compare.md %}#compare-partitioned-data-in-the-same-data-source-but-different-schemas) in different schemas in the same data source. 
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.4.2, Soda Core 3.2.3, Soda Agent 1.0.2, and Soda Agent 0.9.2.

#### March 1, 2024
* Published guidance for [managing sensitive data]({% link soda/sensitive-data.md %}) in Soda.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.4.1.
* Added a compatibility legend to SodaCL reference documentation to clarify which checks are available via various means; see [example]({% link soda-cl/cross-row-checks.md %}).

#### February 29, 2024
* Following improvements and changes to the self-hosted Soda Agent 1.0.0, removed the documented details for including idle replicas and polling intervals in a cluster that aimed to improve scan times. Also, added release notes to inform existing Soda Agent users about changes to parameter configuration with 1.0.0 and advice for optimal performance using managed node groups instead of Fargate profiles in Amazon EKS, GCP Autopilot, or AKS Virtual Clusters. See [Soda Agent release notes]({% link release-notes/soda-agent.md %}#upgrade-to-100) for upgrade details.
* Added details for [system requirements]({% link soda-agent/deploy.md %}#system-requirements) for deploying a Soda Agent in a Kubernetes cluster.
* Included schema checks as available to add as a no-code check to a dataset in a data source that uses a Soda Agent to execute scans.
* Added instructions for how to run a Soda Cloud-defined scan remotely using the Soda Library CLI. See the **Remotely run a scan** tab in [Scan for data quality]({% link soda-library/run-a-scan.md %}l#scan-for-data-quality).
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.3.4, 1.4.0 and Soda Core 1.3.3.
* Added Databricks SQL to the [list of data sources]({% link soda-agent/managed-agent.md %}#compatibility) you can connect to using a Soda-hosted Agent. 

#### February 28, 2024
* Added notation for opting out of [usage statistics]({% link soda-library/usage-stats.md %}) with a Soda Agent.
* Added notation that [Group By checks]({% link soda-cl/group-by.md %}#define-a-group-by-configuration) support a maximum of 1000 groups.
* Changed instances of **scheduled scan** and **scan schedule** to **scan definition** to match the Soda Cloud user interface.
* Clarified the support for [casting columns]({% link soda-cl/freshness.md %}#details-and-limitations) when using a freshness check.
* Clarified the Basic SAML Configuration values to provide during SSO integration with [Azure AD]({% link soda-cloud/sso.md %}#add-soda-cloud-to-azure-ad).

#### February 26, 2024
* Added [release notes]({% link release-notes/soda-agent.md %}) documentation for Soda Agent 0.9.1, which maps to Soda Library 1.3.2.

#### February 22, 2024
* Updated [Soda Cloud API]({% link api-docs/public-cloud-api-v1.md %}) documentation to clarify details.

#### February 21, 2024
* Added API documentation for the [Soda Cloud API]({% link api-docs/public-cloud-api-v1.md %}) that enables you to trigger Soda Cloud scans programmatically.
* Added a new section to [Scan for data quality](#scan-for-data-quality) for triggering a scan via API.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 0.9.0, which maps to Soda Library 1.3.2.

#### February 14, 2024
* Updated connection configuration parameters for [Athena]({% link soda/connect-athena.md %}) and [Oracle]({% link soda/connect-oracle.md %}).
* Made corrections to the connection details for [Athena]({% link soda/connect-athena.md %}) and [Redshift]({% link soda/connect-redshift.md %}); access keys are required parameters for each, regardless of whether you also use a `role_arn` parameter.

#### February 13, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.3.3.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.3.2 and Soda Core 3.2.1.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 0.8.57, which maps to Soda Library 1.3.2.

#### February 9, 2024
* Published documentation for the new ability to add [multiple group by configurations]({% link soda-cl/group-by.md %}#add-multiple-group-configurations), and instructions for how to [preserve historical measurements]({% link soda-cl/group-by.md %}#change-configurations-and-preserve-check-history) when making changes to a `group by` configuration.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.3.1.

#### February 8, 2024
* Documented how to use the [anomaly detection simulator]({% link soda-cl/anomaly-detection.md %}#test-optional-configuration-using-a-simulator).
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.3.0 and Soda Core 3.2.0.

#### February 2, 2024
* Added links to a [video]({% link soda/quick-start-databricks.md %}) that demonstrates how to add Soda to a Databricks pipeline. 
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 0.8.56, which maps to Soda Library 1.2.4.

#### February 1, 2024
* Published new documentation for the [Soda-hosted agent]({% link soda-agent/managed-agent.md %}), a secure, out-of-the-box agent you can use to connect to data sources from within the Soda Cloud user interface.
* Added documentation for the new [anomaly detection]({% link soda-cl/anomaly-detection.md %}) check, which replaces the [anomaly score]({% link soda-cl/anomaly-score.md %}) check.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 0.8.55, which maps to Soda Library 1.2.3.

#### January 29, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 0.8.54, which maps to Soda Library 1.2.3.

#### January 26, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.2.2 & 1.2.3 and Soda Core 3.1.4 & 3.1.5.
* Added instructions for [customizing a dashboard]({% link soda-cloud/collaborate.md %}#customize-your-dashboard).

#### January 22, 2024
* Updated the documentation for rerouting failed row samples to include new, optional configuration parameters that offer users direct access to the failed row sample data.

#### January 19, 2024
* Updated [compatible data sources]({% link soda-agent/deploy.md %}#deploy-a-soda-agent-in-a-kubernetes-cluster) for Soda Agent to include Databricks SQL.

#### January 15, 2024
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.2.1.

#### January 12, 2024
* Documented configuration changes and performance improvements for [record reconciliation checks]({% link soda-cl/recon.md %}#record-reconciliation-checks). 
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.2.0.

#### January 5, 2024
* Published a new use case guide for [integrating an External Secrets Manager]({% link soda/quick-start-secrets.md %}) with a Soda Agent.
* Adjusted [Roles and Rights in Soda Cloud]({% link soda-cloud/roles-global.md %}) to accommodate licensing models that are not based on Author or Viewer volumnes.

#### January 3, 2024
* Updated [Integrate Jira with Soda]({% link soda/integrate-jira.md %}) to include copy-able code snippets for the field values in Jira.
* Documented the [optional syntax]({% link soda-cl/anomaly-score.md %}#produce-warnings-instead-of-fails) for anomaly score checks to produce warnings instead of fails.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.29 and Soda Core 3.1.3.

#### January 2, 2024
* Added alertnate syntax for failed row check using a failed row condition.

#### December 21, 2021
* Documented the support for tracking [anomalies and changes over time]({% link soda-cl/group-by.md %}#track-anomalies-and-relative-changes-by-group) in checks grouped by category.
* Updated the [Self-serve Soda]({% link soda/quick-start-end-user.md %}#begin-a-discussion-and-propose-checks) use case guide to include instructions for using no-code checks and Discussions to empower non-coders to join the team effort of establishing good-quality data. 

#### December 15, 2023
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.27 and Soda Agent 0.8.53.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.28 and Soda Core 3.1.2.

#### December 13, 2023
* Updated [freshness check]({% link soda-cl/freshness.md %}#optional-check-configurations) to include support for in-check filters.
* Added documentation to clarify that Soda supports Azure Data Factory (ADF) with Airflow using [Synapse]({% link soda/connect-synapse.md %}) connection configuration.
* Documented the support for adding quotes to all datasets that Soda acts upon automatically such as with [profiling or discovering]({% link soda-cl/profile.md %}#add-quotes-to-all-datasets) datasets. 
* Added an example of an [in-check filter]({% link soda-cl/filters.md %}#configure-in-check-filters) that uses a string value.
* Added a troubleshooting item for the error [NoneType object is not iteratable]({% link soda-cl/troubleshoot.md %}#nonetype-object-is-not-iteratable).
* Added instructions for dynamically including a [dataset name]({% link soda-cl/for-each.md %}#add-a-dynamic-name-to-for-each-checks) in a for each configuration.
* Prepared new, independent documentation for integrating Soda with [Jira]({% link soda/integrate-jira.md %}) and [ServiceNow]({% link soda/integrate-servicenow.md %}).

#### December 7, 2023
* Introducting [no-code check creation]({% link soda-cl/soda-cl-overview.md %}#define-sodacl-checks) in Soda Cloud. Create checks via the Soda Cloud user interface that creates SodaCL checks without writing any SodaCL.

#### December 4, 2023
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.26, Soda Core 3.1.1, and Soda Agent 0.8.51 - 0.8.52.

#### November 29, 2023
* Corrected the example included in [User-defined checks]({% link soda-cl/user-defined.md %}#define-user-defined-checks).

#### November 28, 2023
* Added to [Best practice for using reconciliation checks]({% link soda-cl/recon.md %}#best-practice-for-using-reconciliation-checks) with advice on batch processing.
* Added instruction for using reference checks with DataFrames; see [Use Soda Library with Spark DataFrames on Databricks]({% link soda/connect-spark.md %}#use-soda-library-with-spark-dataframes-on-databricks).
* Added content to the Self-serve Soda use case guide with a list of [compatible data sources]({% link soda/quick-start-end-user.md %}#connect-a-data-source) and a link to data source configuration reference content.

#### November 24, 2023
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.24 - 1.1.25.
* Added Known issue to [Group By]({% link soda-cl/group-by.md %}) configuration; does not support anomaly score checks.
* Adjusted workaround advice for troubleshooting error using quotes with an [in-check filter]({% link soda-cl/troubleshoot.md %}#errors-when-using-in-check-filters).
* Added [Advanced configuration]({% link soda-cl/recon.md %}#advanced-configuration) for setting key column identifiers.

#### November 22, 2023
* Added an [example]({% link soda-cl/schema.md %}#example-detect-pii) of a schema check that detects columns which could contain PII.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Agent 0.8.49 - 0.8.50.

#### November 21, 2023
* Added documentation for [managing scans]({% link soda-cloud/scan-mgmt.md %}) and setting up failed scan notifications. 
* Added `work_group` as an optional connection configuration property for [Athena]({% link soda/connect-athena.md %}).
* Added troubleshooting tip for using quotes on column names within an in-check filter. See [Troubleshoot SodaCL]({% link soda-cl/troubleshoot.md %}#errors-when-using-in-check-filters).
* In the context of Soda Cloud, changed instances of `scan defintion` to `scan schedule` to reflect the updated naming in the Soda Cloud UI.

#### November 16, 2023
* Introducing the launch of [data contracts]({% link soda/data-contracts.md %}), Soda's experimental way to set data quality standards for data products. 
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Core 3.1.0.

#### November 15, 2023
* Corrected the rule that numeric characters in a list of `valid values`, `invalid values`, or `missing values`, must be wrapped in single quotes. This is not the case. See [Specify valid or invalid values]({% link soda-cl/validity-metrics.md %}#specify-valid-or-invalid-values) for corrected content.

#### November 14, 2023
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.22 and Soda Core 3.0.54.

#### November 8, 2023
* Removed Reporting API v0 documentation as the version is now deprecated.

#### November 7, 2023
* Added two configuration keys for use with [validity metrics]({% link soda-cl/validity-metrics.md %}#list-of-validity-metrics): `invalid format`, `invalid regex`.
* Soda Cloud Reporting API v0 is now deprecated. Please use [Reporting API v1]({% link api-docs/reporting-api-v1.md %}).
* Updated data source configuration reference content to fill in blanks and offer more examples.

#### November 2, 2023
* Added `pollingInterval` to Soda Agent [deployment]({% link soda-agent/deploy.md %}) instructions.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.20 - 1.1.21 and Soda Core 3.0.52 - 3.0.53.
* Added sample input values and clarifying notes to data source connection config reference for Athena.

#### October 30, 2023
* Updated anomaly score documentation to include support for dataset filters.
* Added documentation to accompany new support for [Presto]({% link soda/connect-presto.md %}) data source.

#### October 26, 2023
* Added documentation to accompany new support for [MotherDuck]({% link soda/connect-motherduck.md %}) data source.

#### October 25, 2023
* Added to the list of supported check types in SodaGPT.
* Added another example snippet to [Group By checks]({% link soda-cl/group-by.md %}).

#### October 24, 2023
* Added instructions to [Connect Soda to Spark]({% link soda/connect-spark.md %}#connect-to-spark-dataframes) to recommend changing the name of the `data_source_name` in step 5.

#### October 23, 2023
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.19.
* Clarify instructions about adding a check identity to a check; see [Add a check identity]({% link soda-cl/optional-config.md %}#add-a-check-identity).
* Corrected the syntax for data source connection values when using the GitHub Action for Soda in a Workflow; needed spaces before and after variables in single curly braces. See [Add the GitHub Action for Soda to a Workflow]({% link soda/quick-start-dev.md %}#add-the-github-action-for-soda-to-a-workflow).
* Added Slack icon in header to link to Soda Community.

#### October 17, 2023
* Deprecated sampling from [distribution check]({% link soda-cl/distribution.md %}) DRO generation.
* Documented the support for adding alert coniditions to a [failed row check]({% link soda-cl/failed-rows-checks.md %}#optional-check-configurations).
* Added instructions for applying check attributes to [multiple checks]({% link soda-cl/check-attributes.md %}(#apply-an-attribute-to-one-or-more-checks)) in a single `checks for dataset_name` block. 

#### October 13, 2023
* Added new content to clarify what an [active check]({% link soda/active-check.md %}) is. Soda's licensing model can inlcude volume-based measures of active checks.
* Added link to new video for [Atlan integration]({% link soda/integrate-atlan.md %}).

#### October 12, 2023
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.17 - 1.1.18.
* Removed support for quotes in dataset name identifiers in checks; see [Use quotes in a check]({% link soda-cl/optional-config.md %}#use-quotes-in-a-check).
* Adjusted instructions for [Connect Soda using Dask and Pandas]({% link soda/connect-dask.md %}).

#### October 11, 2023
* Refactored the content on docs.soda.io to focus more on use cases, tasks, and reader goals. The goal of the project was to pivot from a products-based set of documentation to task-based/use case-based content. <br />You may notice a change to the navigation on docs.soda.io that is organized by actions (Install, Deploy, Run Scans, Set alerts, etc.) instead of by product (Soda Library, Soda Cloud, Soda Agent, etc.)
  * Access a new [Get started roadmap]({% link soda/get-started-roadmap.md %}) with recommendations to help you quickly become productive and confident using Soda for data quality testing. 
  * Get inspired by new [Use case guides]({% link soda/use-case-guides.md %}) to offer guidance in setting up Soda to meet a specific need.
  * Get your Soda account [organized]({% link soda-cloud/collaborate.md %}) and set up to maximize your team's data quality testing efficiency.
* Updated [Integrate Soda with dbt]({% link soda/integrate-dbt.md %}) to install sub-packages with double-quotes. 
* Update best practices for [reconciliation checks]({% link soda-cl/recon.md %}) to recommend creating a separate agreement for a reconciliation project.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.15 - 1.1.16 and Soda Core 3.0.51.

#### October 6, 2023
* Updated `session_parameters` config to `session_params` in [Snowflake]({% link soda/connect-snowflake.md %}) connection config reference.
* Added instructions for how to [reset anomaly history]({% link soda-cl/anomaly-score.md %}#reset-anomaly-history) for an anolamy score check.
* Added detail to [programmatic scan]({% link soda-library/programmatic.md %}#basic-programmatic-scan) to include a filename in a scan when checks are included inline.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.14.

#### October 5, 2023
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Cloud dashboard.
* Added `schema_name` parameter to [DuckDB configuration]({% link soda/connect-duckdb.md %}).

#### September 27, 2023
* Added clarifying information about user input and how it is used by SodaGPT.
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.13 and Soda Core 3.0.50.

#### September 26, 2023
* Added documentation for reconciliation schema checks which now support [data type mapping]({% link soda-cl/recon.md %}#schema-reconciliation-checks).
* Documented a new scan option, `--local` that you can add to a `soda scan` command to prevent Soda Library from pushing any check results to Soda Cloud. See: [Add scan options]({% link soda-library/run-a-scan.md %}#add-scan-options) and Scan output in Soda Cloud.
* Revised and tigtened [Soda Core]({% link soda-core/overview-main.md %}) information.
* Documented the global configuration to disable sending any samples of data to Soda Cloud; see [Disable samples in Soda Cloud]({% link soda-cl/sample-datasets.md %}#disable-samples-in-soda-cloud).

#### September 21, 2023
* Updated support for dbt for [ingesting tests]({% link soda/integrate-dbt.md %}#prerequisites) into Soda Cloud. You must now install a `soda-dbt` subpackage that uses dbt 1.5 or 1.6.
* Added [release notes]({% link release-notes/soda-library.md %}) documentation for Soda Library 1.1.12. 

#### September 20, 2023
* Updated [schema reconciliation checks]({% link soda-cl/recon.md %}#types-of-reconciliation-checks) to clarify that the check validates columns names *and* data types.

#### September 19, 2023
* Added [release notes]({% link release-notes/all.md %}) documentation for Soda Library 1.1.11 and Soda Core 3.0.49.

#### September 18, 2023
* Added to [Reference check documentation]({% link soda-cl/reference.md %}#define-reference-checks) for the new configuration `must not exist`.
* Updated support for dbt-core 1.3, 1.5, and 1.6 for [ingesting tests]({% link soda/integrate-dbt.md %}#prerequisites) into Soda Cloud. 
* Added documentation for [schema reconciliation checks]({% link soda-cl/recon.md %}#types-of-reconciliation-checks).

#### September 14, 2023
* Removed known issue for inability to use check identity with failed row checks. This is now supported in Soda Library.

#### September 13, 2023
* Added [release notes]({% link release-notes/soda-library.md %}) documentation for Soda Library 1.1.10.

#### September 12, 2023
* Added [release notes]({% link release-notes/soda-library.md %}) documentation for Soda Library 1.1.9.

#### September 11, 2023
* Added [release notes]({% link release-notes/soda-library.md %}) documentation for Soda Library 1.1.6 - 1.1.8.
* Added a new section for [Best practice for using reconciliation checks]({% link soda-cl/recon.md %}#best-practice-for-using-reconciliation-checks)

#### September 1, 2023
* Added [release notes]({% link release-notes/soda-library.md %}) documentation for Soda Library 1.1.0 - 1.1.5.
* Added item to [Troubleshoot]({% link soda/connect-snowflake.md %}#troubleshoot) section for Snowflake.

#### August 31, 2023
* Added documentation for SodaCL [reconciliation checks]({% link soda-cl/recon.md %}), tailored for data migration use cases.
* Added [release notes]({% link release-notes/soda-library.md %}) documentation for Soda Library 1.1.0 - 1.1.5.

#### August 30, 2023
* Added instructions for integrating with an [external secrets manager]({% link soda-agent/extras.md %}#integrate-with-a-secrets-manager) with a Soda Agent to manage frequently-changed data source login credentials.
* Added screenchots to [Integrate Soda with Atlan]({% link soda/integrate-atlan.md %}) documentation.
* Added to [Troubleshoot]({% link soda-library/run-a-scan.md %}#troubleshoot) content for running a scan that produces an SSL certificate error.

#### August 24, 2023
* Added documentation for the new, native integration of [Soda in Atlan]({% link soda/integrate-atlan.md %}).
* Updated [orchestration]({% link soda-library/orchestrate-scans.md %}) documentation to include a link to an Astronomer tutorial for Data Quality Checks with Airflow, Snowflake, and Soda.
* Added to item to Troublshoot SodaCL for dealing with unexpected [missing checks]({% link soda-cl/troubleshoot.md %}#errors-with-missing-checks) behaviour.

#### August 23, 2023
* Update agreement documentation to reflect the change in behaviour where scans do not run until stakeholders have approved of the agreement.

#### August 21, 2023
* Removed "What the Action does" section from [Integrate Soda with a GitHub Workflow]({% link soda/integrate-github.md %}).

#### August 11, 2023
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.48.
* Added [release notes]({% link release-notes/soda-library.md %}) documentation for Soda Library 1.0.6 - 1.0.8.
* Added Known issue: [Failed rows checks]({% link soda-cl/failed-rows-checks.md %}#optional-check-configurations) do not support the check identity parameter. <!--SAS-2005-->
* Added a note to Create an agreement to clarify that you can only create agreements using data sources that have been added to Soda Cloud via a Soda Agent.
* Added [collection]({% link soda/glossary.md %}#collection) as a new term in the Glossary.

#### August 10, 2023
* Published new documentation for the [GitHub Action for Soda]({% link soda/integrate-github.md %}).
* Updated [Test data during development]({% link soda/quick-start-dev.md %}) to replace the GitHub Action recipe with the new <a href="https://github.com/marketplace/actions/soda-library-action" target="_blank">GitHub Action for Soda</a>.

#### August 8, 2023
* Revised documentation to reflect the new **Checks** dashboard, that displays checks and their latest scan results. This replaces the **Check Results** dashboard, that displayed all individual check results.

#### August 7, 2023
* Moved [Check suggestions]({% link soda-library/check-suggestions.md %}) documentation from SodaCL section to Soda Library.

#### July 26, 2023
* Added [release notes]({% link release-notes/soda-library.md %}) documentation for Soda Library 1.0.5.
* Added detail to [schema check]({% link soda-cl/schema.md %}) documentation for new `schema_name` parameter.

#### July 24, 2023
* Added support for failed row checks when using [check templates]({% link soda-cl/check-template.md %}).

#### July 21, 2023
* Added documentation to complement [Google CloudSQL]({% link soda/connect-cloudsql.md %}) support.
* Added [release notes]({% link release-notes/soda-library.md %}) documentation for Soda Library 1.0.3 and Soda Library 1.0.4.
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.42 - 3.0.47.
* Added new `http_headers` configuration parameter for [Trino data source]({% link soda/connect-trino.md %}).

#### July 6, 2023
* Added documentation for the `samples columns` check configuration for metrics and checks that implicitly collect failed row samples: [missing]({% link soda-cl/missing-metrics.md %}#failed-row-samples), [validity]({% link soda-cl/validity-metrics.md %}#failed-row-samples), [duplicates]({% link soda-cl/numeric-metrics.md %}#failed-row-samples), [reference]({% link soda-cl/reference.md %}#failed-row-samples).

#### July 4, 2023
* Updated commands for [installing]({% link soda-library/install.md %}#install) Soda Library using a Docker image.

#### June 27, 2023
* Documentation to accompany the preview launch of SodaGPT.

#### June 23, 2023
* Changed requirement for [check template]({% link soda-cl/check-template.md %}) to include the dataset identifier in the first line of the check so that Soda Cloud can properly render the check results.
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.40 and Soda Core 3.0.41.
* Added [release notes]({% link release-notes/soda-library.md %}) documentation for Soda Library 1.0.1 and Soda Library 1.0.2.
* Reverted Soda Agent to describe configuring Soda Core settings instead of Library. Will update to Soda Library details when updates are complete.

#### June 15, 2023
* Introducing Soda Library, a commercial extension of the Soda Core open-source software. It leverages all the power of Soda Core and SodaCL, and offers new features and functionality for Soda customers.
* New documentation for the new [Group by]({% link soda-cl/group-by.md %}) configuration and [Group evolution check]({% link soda-cl/group-evolution.md %}), both available with Soda Library.
* New documentation for [Check suggestions]({% link soda-library/check-suggestions.md %}) using the Soda Library CLI.
* New documentation for [Check template configuration]({% link soda-cl/check-template.md %}) supported by Soda Library.
* Revised syntax guidance regarding multiple thresholds for an alert. See [Optional check configurations]({% link soda-cl/optional-config.md %}#add-alert-configurations).
* All <a href="https://github.com/sodadata/soda-core/tree/main/docs" target="_blank">documentation for Soda Core</a>, the open-source Python library and CLI tool, has moved to the <a href="https://github.com/sodadata/soda-core" target="_blank">Soda Core repository</a> on GitHub.

#### June 12, 2023
* Remove "Preview" tag from the [Reporting API v1]({% link api-docs/reporting-api-v1.md %}) documentation.

#### June 9, 2023
* Added Known Issue for using BigQuery and specifying numeric [missing values]({% link soda-cl/missing-metrics.md %}#specify-missing-values-or-missing-regex) or [valid values]({% link soda-cl/validity-metrics.md %}#specify-valid-or-invalid-values) with single quotes. TL;DR: Don't use single quotes.
* Added clarification to the value for `path` when connecting a [DuckDB data source]({% link soda/connect-duckdb.md %}).
* Removed incorrect syntax guidance regarding multiple thresholds for an alert. Each `warn` or `fail` condition can contain only one threshold. See [Optional check configurations]({% link soda-cl/optional-config.md %}#add-alert-configurations).
* Updated instructions for configuring a `soda_cloud` connection in a `configuration.yml` file. New instructions involve copying the whole configuration instead of just API Key values.

#### June 8, 2023
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.38 and Soda Core 3.0.39.

#### May 31, 2023
* Added instructions and event payload details for using a [webhook]({% link soda/integrate-webhooks.md %}#webhooks-for-soda-cloud-agreement-notifications) to notify a third-party of new, deleted, or changed Soda agreements.

#### May 30, 2023
* Added a new parameter, `datasource_container_id` to the `.datasource-mapping.yml` file neede to map a [Soda Cloud-Alation]({% link soda/integrate-alation.md %}#set-up-the-integration) catalog integration.

#### May 25, 2023
* Added a step for [configuring]({% link soda/connect-spark.md %}#connect-to-spark-for-databricks-sql) `soda-core-spark[databricks]` to be sure to install `databricks-sql-connector` as well.

#### May 23, 2023
* Added a video overview showcasing the integration of [Soda and Alation]({% link soda/integrate-alation.md %}).
* Added a note for a [Known Issue]({% link soda-cl/profile.md %}#limitations-and-known-issues) regarding the use of variables in profiling configurations.

#### May 20, 2023
* Added documentation for using [private key authentication for Snowflake]({% link soda-agent/extras.md %}#use-a-values-file-to-store-private-key-authentication-values-for-snowflake) when deploying a Soda Agent. 

#### May 15, 2023
* Replaced getting started guides with entirely new content with a focus on data engineering. 
  * [Take a sip of Soda]({% link soda/quick-start-sip.md %})
  * [Test data in a pipeline]({% link soda/quick-start-prod.md %})
  * [Test data during development]({% link soda/quick-start-dev.md %})
  * [Enable end users to test data]({% link soda/quick-start-end-user.md %})
* Replaced the [product overview]({% link soda/product-overview.md %}) with newly-written material.

#### May 11, 2023
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.33 and Soda Core 3.0.34.
* Added instructions for [user-defined metrics]({% link soda-cl/user-defined.md %}#define-user-defined-checks) to access and use queries in separate SQL files.
* Adjusted content for the revised CLI and Soda Cloud scan output for [schema checks]({% link soda-cl/schema.md %}#expect-one-check-result). Schema check results now display the output for all alerts triggered during a scan.

#### May 9, 2023
* Added the install package to each connector's page.
* Added a connectivity troubleshooting tip to [Connect to Snowflake]({% link soda/connect-snowflake.md %}#troubleshoot).

#### May 2, 2023
* Published content regarding the set up of [multiple Soda Cloud organizations]({% link soda-cloud/roles-global.md %}) for use with different environments in your network infrastructure.
* Added a note about selecting a region when you sign up for a new Soda Cloud account.

#### April 28, 2023
* Corrected the explanation of the [`duplicate_count` check]({% link soda/quick-start-sodacl.md %}#duplicate-check) regarding checks that included multiple arguments (columns).

#### April 18, 2023
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.31 and Soda Core 3.0.32.

#### April 11, 2023
* Added a copy-to-clipboard button to most code snippets in documentation.
* Added attribute mapping details to add Soda Cloud to [Google Workspace as a SAML app]({% link soda-cloud/sso.md %}#add-soda-cloud-to-google-workspace).

#### March 29, 2023
* Revised instructions to add Soda Cloud to [Google Workspace as a SAML app]({% link soda-cloud/sso.md %}#add-soda-cloud-to-google-workspace).

#### March 28, 2023
* Added to Soda Agent documentation to include a setting for which Soda Cloud endpoint to use, according to region. See [Deploy an Soda Agent in a Kubernetes cluster]({% link soda-agent/deploy.md %}#deploy-using-cli-only).

#### March 24, 2023
* Added content to [Troubleshoot SodaCL]({% link soda-cl/troubleshoot.md %}#filter-not-passed-with-reference-check) to address challenges when using a reference check with a dataset filter.
* Added instructions to add Soda Cloud to [Google Workspace as a SAML app]({% link soda-cloud/sso.md %}#add-soda-cloud-to-google-workspace).
* Added parameter to Snowflake connection details for using private key encryption for [private key authentication]({% link soda/connect-snowflake.md %}#private-key-authentication).

#### March 21, 2023
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.29 and Soda Core 3.0.30.
* Added instructions for limiting samples for an entire data source.

#### March 9, 2023
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.28.

#### March 8, 2023
* Added to [Troubleshoot SodaCL]({% link soda-cl/troubleshoot.md %}#checks-not-evaluated) with information about checks that return `[NOT EVALUATED]` results.
* Added new content with advice to [Compare data using SodaCL]({% link soda-cl/compare.md %}).
* Documented how to prevent Soda from collecting failed rows samples and sending them to Soda Cloud using a [samples limit]({% link soda-cl/optional-config.md %}#disable-failed-row-samples-for-individual-checks).
* Corrected a prerequisite in Add a data source to indicate that you can deploy a Soda Agent in any Kubernetes cluster, not just Amazon EKS.

#### March 7, 2023
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.26 & 3.0.27.

#### February 28, 2023
* Published instructions for setting up private connectivity to a Soda Cloud account using AWS PrivateLink.

#### February 23, 2023
* Documented known issue with freshness check. See [Troubleshoot errors with freshness checks]({% link soda-cl/freshness.md %}#troubleshoot-errors-with-freshness-checks).
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.24 & 3.0.25.

#### February 22, 2023
* Removed preview status from agent deployment documentation for Azure Kubernetes Service (AKS) and Google Kubernetes Engine (GKE).
* Added instructions for programmatically running a Soda scan of the contents of a [local file]({% link soda/connect-file.md %}) using Dask.

#### February 21, 2023
* Revised documentation to clarify that you cannot wrap dataset names in quotes with [profiling or dataset discovery]({% link soda-cl/profile.md %}#limitations-and-known-issues), with [sample collection]({% link soda-cl/sample-datasets.md %}#optional-check-configurations), or in [for each]({% link soda-cl/for-each.md %}#limitations-and-specifics) configurations.
* Added advice about [avoiding reuse of check names]({% link soda-cl/optional-config.md %}#customize-check-names) in multiple agreements.

#### February 16, 2023
* Added documentation for the `invalid values` configuration key. Refer to [Validity metrics]({% link soda-cl/validity-metrics.md %}#list-of-configuration-keys) documentation.
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.23.
* Corrected custom check templates to use `fail condition` syntax, not `fail expression`. 
* Added instructions to [Configure a time partition using the NOW variable]({% link soda-cl/filters.md %}#configure-a-time-partition-using-the-now-variable).
* Added a note for limitations on using variables in checks in agreements in Soda Cloud. 

#### February 10, 2023
* Added a new section to Distribution check documentation for [defining a sample size]({% link soda-cl/distribution.md %}#define-the-sample-size).

#### February 9, 2023
* Add new documentation for [generating API keys]({% link soda-cloud/api-keys.md %}) for use with Soda Cloud.

#### January 25, 2023
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.22.
* Added a detail for adding an optional scheme property to `soda_cloud` configuration when connecting Soda Core to Soda Cloud. 
* Added documentation to accompany new support for [Dask and Pandas (Experimental)]({% link soda/connect-dask.md %}).

#### January 24, 2023
* Added documentation to accompany new support for [Vertica (Experimental)]({% link soda/connect-vertica.md %}).
* Added [troubleshooting tip]({% link soda-cl/troubleshoot.md %}#metrics-were-not-computed-for-check) for errors in which Soda does not compute metrics for a dataset that includes a schema in its identifier.

#### January 20, 2023
* Updated [agent upgrade]({% link soda/upgrade.md %}) docs with more detail.

#### January 19, 2023
* Added clarity to the documentation for [adding a check identity]({% link soda-cl/optional-config.md %}#add-a-check-identity) and using a scan definition name.
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.20.
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.21.
* Updated screenshots of Soda Cloud for [deploying an agent]({% link soda-agent/deploy.md %}#create-a-soda-cloud-account-and-api-keys).
* Added [explicit detail]({% link soda-cl/filters.md %}#configuration-details-and-limitations) about when to wrap date variables in single quotes.
* Added a custom check templates for validating event sequence with date columns.
* Updated the Soda product feature list.

#### January 13, 2023

* Updated Soda Agent for GKE documentation so that the instructions for using a file reference for a BigQuery data source connection use a Kubernetes secret instead of an Kubernetes ConfigMap.  

#### January 11, 2023
* Added documentation for the ability to create and use [check attributes]({% link soda-cl/check-attributes.md %}).
* Adjusted documentation for [adding dataset attributes]({% link soda-cloud/organize-datasets.md %}) to correspond with the new check attributes feature.
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.18.
* Removed the known issue for using `duplicate_count` and `duplicate_percent` metrics with an in-check filter.

#### January 10, 2023
* Added note about the new ability to add co-owners to an agreement.

#### December 28, 2022
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.17.

#### December 20, 2022
* Added preview documentation for [deploying a Soda Agent in a GKE cluster]({% link soda-agent/deploy.md %}). 

#### December 15, 2022
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.16.
* Corrected data types on which `max` and `min` metrics can be used. See [Numeric metrics]({% link soda-cl/numeric-metrics.md %}#list-of-numeric-metrics).

#### December 12, 2022
* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.15.

#### December 8, 2022
* Added preview documentation for the [Soda Cloud Reporting API v1]({% link api-docs/reporting-api-v1.md %}).
* Corrected documentation to properly reflect that you can add only one column against which to execute a metric in a check.
* Reverted the statement about using variables to pass any value *anywhere* in syntax or configuration at scan time. Refer to [variables documentation]({% link soda-cl/filters.md %}#configure-variables-in-sodacl) for details on how to use them.

#### December 2, 2022

* Added preview documentation for [deploying a Soda Agent in an AKS cluster]({% link soda-agent/deploy.md %}). Reorganized and expanded Soda Agent documentation in general.
* Added documentation to cast a column so as to use TEXT type data in a [freshness check]({% link soda-cl/freshness.md %}#details-and-limitations).
* Documented troubleshooting tips for Soda Cloud 400 response.

#### December 1, 2022

* Added [release notes]({% link release-notes/soda-core.md %}) documentation for Soda Core 3.0.14.
* Documented connection configuration for [Denodo (Experimental)]({% link soda/connect-denodo.md %}).
* Documented improvments to the feature for[rerouting failed rows samples to an HTTP endpoint.
* Documented [how to pass scan time variables]({% link soda-cl/filters.md %}#configure-variables-for-connection-configuration) for data source connection configuration values.
* Add an example to demonstrate how to define a [variable in an in-check filter]({% link soda-cl/filters.md %}#example-use-a-variable-in-an-in-check-filter).
* Documented how to [add an identity]({% link soda-cl/optional-config.md %}#add-a-check-identity) to a check to preserve check result history in Soda Cloud when a check is modified.

#### November 30, 2022

* Adjusted the documentation for dataset discovery because, as of Soda Core v3.0.14, the action no longer derives a `row_count` metric; see [Dataset discovery]({% link soda-cl/profile.md %}#discover-datasets).
* Added documentation for the preview of the [alert notification rules]({% link soda-cloud/notif-rules.md %}) feature. 

#### November 28, 2022

* Added [troubleshooting instructions]({% link soda-library/install.md %}#error-library-not-loaded) for Soda Core Scientific on an M1 MacOS machine.

#### November 23, 2022

* Updated [version compatibility]({% link soda-agent/deploy.md %}#compatibility) for Kubernetes clusters when deploying a Soda Agent. 
* Updated [version compatibility]({% link soda/connect-oracle.md %}#compatibility) for OracleDB data sources.
* Updated [version compatibility]({% link soda/connect-dremio.md %}#compatibility) for Dremio data sources.

#### November 18, 2022

* Added a [list of valid formats]({% link soda-cl/validity-metrics.md %}#formats-supported-with-soda-for-ms-sql-server) for validity metrics that Soda for MS SQL Server supports.
* Added documentation for rerouting failed rows samples to an HTTP endpoint; supported as of Soda Core 3.0.13.
* Removed content for overwriting Soda Cloud checks results using `-t` option.
* Archived all Soda SQL and Soda Spark content to the <a href="https://github.com/sodadata/soda-sql/tree/main/docs" target="_blank">sodadata/soda-sql</a> repository in GitHub. 

#### November 16, 2022

* Added content to more explictly describe the metrics that dataset discovery and column profiling derive, and the potential [compute costs]({% link soda-cl/profile.md %}#compute-consumption-and-cost-considerations) associated with these configurations.

#### November 15, 2022

* Added release notes documentation for Soda Core 3.0.13.
* Adjusted [freshness check]({% link soda-cl/freshness.md %}) documentation to reflect new support for columns that contain data type DATE.
* Added documentation to accompany new support for [OracleDB]({% link soda/connect-oracle.md %}).

#### November 14, 2022

* Corrected the location in which to [opt out]({% link soda-library/usage-stats.md %}#opt-out-of-usage-statistics) of sending Soda Core usage statistics.

#### November 10, 2022

* Added [private key authentication]({% link soda/connect-snowflake.md %}#private-key-authentication) detail to Snowflake connection documentation.
* Updated the [list of numeric metrics]({% link soda-cl/numeric-metrics.md %}#list-of-numeric-metrics) for updated data source support. 
* Added a simple list of all SodaCL metrics to [Metrics and checks]({% link soda-cl/metrics-and-checks.md %}#list-of-sodacl-metrics-and-checks) documentation.

#### November 8, 2022

* Added an example webhook integration for Soda Cloud and ServiceNow.

#### November 7, 2022

* Added examples for using [in-check variables]({% link soda-cl/filters.md %}#configure-variables-in-SodaCL) to provide dynamic values at scan time.

#### November 3, 2022

* Added [release notes]({% link release-notes/all.md %}) to correspond with the release of Soda Core 3.0.12.
* Added documentation for a new numeric metric: `duplicate_percent`. See [Numeric metrics]({% link soda-cl/numeric-metrics.md %}#list-of-numeric-metrics).
* Removed known issue regarding Soda Core for SparkDF not supporting anomaly score or distribution checks; now the checks are supported.
* Added documentation for a new feature to disable failed rows samples for specific columns.
* Added documentation for distribution checks which now support dataset and in-check filters. See [Distribution check optional check configurations]({% link soda-cl/distribution.md %}#optional-check-configurations).

#### November 2, 2022

* Removed `missing format` as a valid configuration key for [missing metrics]({% link soda-cl/missing-metrics.md %}).
* Added an independent [Connect to Databricks]({% link soda/connect-databricks.md %}) page that points to documentation to use Soda Core packages for Apache Spark to connect.

#### November 1, 2022

* Added [Limitations and known issues]({% link soda-cl/profile.md %}#limitations-and-known-issues) section to Display Profile information in Soda Cloud.

#### October 26, 2022

* Removed the Preview status from self-serve features which are now generally available in Soda Cloud, such as agreements and [profiling]({% link soda-cl/profile.md %}).
* Migrated custom metric templates from Soda SQL to SodaCL.

#### October 19, 2022

* Added [release notes]({% link release-notes/all.md %}) to correspond with the release of Soda Core 3.0.11.
* Documented connection configuration for [Azure Synapse (Experimental)]({% link soda/connect-synapse.md %}).
* Added documentation for an enhancement for [change-over-time checks]({% link soda-cl/numeric-metrics.md %}#change-over-time-thresholds) to gauge changes relative to the same day last week or month.
* Added documentation for the new `test-connection` command in Soda Core. See [Connect Soda to Amazon Athena]({% link soda/connect-athena.md %}#test-the-data-source-connection) for an example.

#### October 13, 2022

* Added notes about specifying the type of [quotes]({% link soda-cl/optional-config.md %}#use-quotes-in-a-check) you use in SodaCL checks must match that which the data source uses. 
* Added short snippet as an example to obtain scan exit codes in a [programmatic scan]({% link soda-library/programmatic.md %}#scan-exit-codes). 
* Added detail about using [multiple checks files]({% link soda-library/run-a-scan.md %}#anatomy-of-a-scan-command) in one scan command.
* Added detail about [re-using user-defined metrics]({% link soda-cl/user-defined.md %}#define-user-defined-checks) in multiple checks in the same checks YAML file.

#### October 11, 2022

* Added documentation for [grouping failed checks results]({% link soda-cl/failed-rows-checks.md %}#group-results-by-category) by one or more categories. 

#### October 5, 2022

* Added release notes to correspond with the release of Soda Core 3.0.10.
* Revised the value for the default number of [failed row samples]({% link soda-cl/optional-config.md %}#collect-failed-row-samples) that Soda automatically collects and displays in Soda Cloud from 1000 to 100.
* Added documentation to accompany new support for [Dremio]({% link soda/connect-dremio.md %}).
* Added documentation to accompany new support for [ClickHouse (Experimental)]({% link soda/connect-clickhouse.md %}).

#### September 29, 2022

* Added a link to a community contribution for Prefect 2.0 collection for Soda Core.
* Updated Reference checks documentation for [displaying failed]({% link soda-cl/reference.md %}#failed-row-samples) rows in Soda Cloud.

#### September 28, 2022

* Added release notes to correspond with the release of Soda Core 3.0.9.
* Added documentation for a new `samples limit` configuration key that you can add to checks that use [missing]({% link soda-cl/missing-metrics.md %}#failed-row-samples), [validity]({% link soda-cl/validity-metrics.md %}#failed-row-samples), or [duplicate_count]({% link soda-cl/numeric-metrics.md %}#failed-row-samples) metrics which automatically send 1000 failed row samples to Soda Cloud.
* Added instructions to [save failed row samples to a file]({% link soda-library/programmatic.md %}#save-failed-row-samples-to-a-file).
* Added [Windows-specific instructions]({% link soda-library/install.md %}) for installing Soda Core using a virtual environment.
* Removed known issue for in-check variables which are supported as of Soda Core 3.0.9: "Except for customizing [dynamic names for checks]({% link soda-cl/optional-config.md %}#customize-check-names), you *cannot* use in-check variables. For example, Soda does not support the following check:

```yaml
checks for dim_customers:
  - row_count > ${VAR_2}
```

#### September 23, 2022

* Added documentation to set up [integration with Microsoft Teams]({% link soda/integrate-webhooks.md %}) so that Soda Cloud can send alert notifications or incident events to MS Teams.
* Added detail for programmatically inspecting scan results; see [programmatic scans]({% link soda-library/programmatic.md %}). Available with Soda Core 3.0.9.
* Added details for using various [authentication methods]({% link soda/connect-bigquery.md %}#authentication-methods) to connect to BigQuery.

#### Septemeber 22, 2022

* Added release notes to correspond with the release of Soda Core 3.0.8.
* Removed Known issue: Connections to MS SQL Server do not support checks that use regex, such as with [missing metrics]({% link soda-cl/missing-metrics.md %}#list-of-missing-metrics) or [validity metrics]({% link soda-cl/validity-metrics.md %}#list-of-validity-metrics).

#### September 14, 2022

* Added instructions for configuring a custom sampler for failed rows.

#### September 13, 2022

* Added documentation to correspond with the release of Soda Core 3.0.7, including an update to [freshness check results]({% link soda-cl/freshness.md %}#freshness-check-results).
* Removed the known issue for using variables in the SQL or CTE of a [user-defined check]({% link soda-cl/user-defined.md %}). See <a href="https://github.com/sodadata/soda-core/issues/1577" target="_blank">GitHub Issue 1577</a>.
* Added instructions for configuring the same scan to run in multiple environments.
* Added information about [passing parameters]({% link soda/connect-snowflake.md %}) to a Snowflake data source in connection configurations, specifically which parameter to use to authenticate a connection via SSO with a SAML 2.0-compliant identity provider (IdP).

#### Septemeber 12, 2022

* Documented [Soda Cloud resources]({% link soda-cloud/soda-cloud-architecture.md %}#soda-cloud-resources) to add visual context to the parts that exist in Soda Cloud, and how they relate to each other, particularly when you delete a resource.
* Added documentation to correspond with Soda Cloud's new support for [webhooks]({% link soda/integrate-webhooks.md %}) to integrate with third-party service providers to send alert notifications or create and track incidents externally.
* Corrected documentation to indicate that [reference checks]({% link soda-cl/reference.md %}) do *not* support dataset filters.

#### September 9, 2022

* Decoupled data source connection configuration details from Soda Core. Created a separate page for each data source's connection config details. See [Connect a data source]({% link soda/connect-athena.md %}).

#### September 8, 2022

* Added inclusion and exclusion rules for [dataset discovery]({% link soda-cl/profile.md %}#define-dataset-discovery), [column profiling]({% link soda-cl/profile.md %}#define-column-profiling), and [dataset sampling]({% link soda-cl/sample-datasets.md %}#inclusion-and-exclusion-rules).

#### September 7, 2022

* Added content to correspond with Soda Core's new support for [Spark for Databricks SQL]({% link soda/connect-spark.md %}#connect-to-spark-for-databricks-sql).
* Adjusted documentation to reflect that Soda Core now supports the ingestion of [dbt tests]({% link soda/integrate-dbt.md %}).

#### August 30, 2022

* Recorded known issue: Soda Core for SparkDF does not support anomaly score or distribution checks.

#### August 29, 2022

* Added instructions for how to [disable dataset discovery]({% link soda-cl/profile.md %}#disable-dataset-discovery) and [disable column profiling]({% link soda-cl/profile.md %}#disable-column-profiling).
* Added details for obtaining info when [upgrading]({% link soda/upgrade.md %}#troubleshoot) a Soda Agent.
* Organized and tightened Soda Core documentation.

#### August 26, 2022

* Added documentation for how to use Soda Core for SparkDF with a Notebook to connect to [Databricks]({% link soda/connect-spark.md %}#use-soda-core-with-spark-dataframes-on-databricks).
* Adjusted the configuration for connecting to [MS SQL Server]({% link soda/connect-mssql.md %}) based on community feedback.

#### August 24, 2022

* Adjusted [configuration instructions]({% link soda/connect-spark.md %}) for `soda-core-spark-df` to separately install dependencies for Hive and ODBC as needed.
* Added content to correspond with Soda Core's new support for [Trino]({% link soda/connect-trino.md %}).
* Removed the known issue: The `missing format` configuration does not function as expected.

#### August 22, 2022

* Added an [example DAG]({% link soda-library/orchestrate-scans.md %}#example-dag) for using Soda with Airflow PythonOperator.
* Added [Tips and best practices for SodaCL]({% link soda/quick-start-sodacl.md %}#tips-and-best-practices-for-sodacl) documentation.
* Expanded [For each]({% link soda-cl/for-each.md %}) documentation with optional configurations and examples.
* Published a new Quick start for Soda Cloud (Preview) that outlines how to use preview features in Soda Cloud to connect to a data source, then write a new agreement for stakeholder approval.

#### August 11, 2022

* Added documentation for the new `-t` option for use with scan commands to overwrite scan output in Soda Cloud.

#### August 10, 2022

* Added content to correspond with Soda Core's new support for [MySQL]({% link soda/connect-mysql.md %}).
* Validated and clarified documentation for using [filters and variables]({% link soda-cl/filters.md %}).

#### August 9, 2022

* Added documentation to describe the migration path from Soda SQL to Soda Core.

#### August 2, 2022

* Adjusted the instructions for [Slack integration]({% link soda/integrate-slack.md %}) to correspond with a slightly changed UI experience.
* Added limitation to the [for each]({% link soda-cl/for-each.md %}) as the configuration is not compatible with dataset filters (also known as partitions).


#### August 1. 2022

* Added a "was this helpful" counter to most documentation pages.
* Added details for [connecting `soda-core-spark-df` to Soda Cloud]({% link soda/connect-spark.md %}#connect-soda-for-sparkdf-to-soda-cloud). 

#### July 27, 2022

* Added content to correspond with Soda Core's new support for [MS SQL Server]({% link soda/connect-mssql.md %}) and [IBM DB2]({% link soda/connect-db2.md %}).

#### July 20, 2022

* Published documentation associated with the preview release of Soda Cloud's self-serve features and functionality. This is a limited access preview release, so please ask us for access at <a href="mailto:support@soda.io">support@soda.io</a>.

#### June 29, 2022

* Added documentation to correspond with the new `samples limit` configuration for [Failed rows checks]({% link soda-cl/failed-rows-checks.md %}#define-failed-rows-checks)
* Added documentation for setting the [default role for dataset owners]({% link soda-cloud/roles-global.md %}) in Soda Cloud.

#### June 28, 2022

* Revised documentation to reflect the general availability of Soda Core and SodaCL.
* Archived the deprecated documentation for Soda SQL and Soda Spark.

#### June 23, 2022

* Added backlog of [Soda Core release notes]({% link release-notes/soda-core.md %}).
* Refined the [Quick start for SodaCL]({% link soda/quick-start-sodacl.md %}) with details on how to run a scan.
* Corrected the explanation of the [`duplicate_count` check]({% link soda/quick-start-sodacl.md %}#duplicate-check) regarding checks that included multiple arguments (columns).
* Removed a Known Issue from [freshness check]({% link soda-cl/freshness.md %}) that recorded problem when defining a custom name to the check.

#### June 22, 2022

* Added documentation to correspond with the new `percent` argument you can use in checks with [change-over-time thresholds]({% link soda-cl/numeric-metrics.md %}#change-over-time-thresholds).

#### June 21, 2022

* Added details to Soda Core documentation for using system variables.  to store sensitive credentials.
* Updated the Quick start for Soda Core and Soda Cloudwith slightly changed instructions.

#### June 20, 2022

* Changed all references to `table` in SodaCL to `dataset`, notably used with [for each]({% link soda-cl/freshness.md %}) and [distribution]({% link soda-cl/distribution.md %}) check syntax.
* Added deprecation warning banners to all Soda SQL and Soda Spark content.
* Revised and reorganized content to reframe focus on Soda Core in lieu of Soda SQL.
* New [How Soda Core works]({% link soda-library/how-library-works.md %}) documentation.
* Added more Soda Core documentation to main docs set. 
* Updated [Soda product overview]({% link soda/product-overview.md %}) to reflect new focus on Soda Core and imminent deprecation of Soda SQL and Soda Spark.
* Updated Soda Cloud documentation to reflect new focus on Soda Core.
* Update links on [docs home page]({% link index.html %}) to point to most recent content and shift Soda SQL and Soda Core to a Legacy section.

#### June 14, 2022

* Added documentation corresponding to Soda Core support for [Apache Spark DataFrames]({% link soda/connect-spark.md %}). For use with [programmatic Soda scans]({% link soda-library/programmatic.md %}), only.
* Updated the syntax for [freshness checks]({% link soda-cl/freshness.md %}) to remove `using` from the syntax and identify column name instead by wrapping in parentheses.
    * old: `freshness using created_at < 3h`
    * new: `freshness(created_at) < 3h`
* Added clarification to the context-specific measning of a [BigQuery dataset]({% link soda/connect-bigquery.md %}) versus a dataset in the context of Soda.
* Added instructions for setting a [default notification channel]({% link soda/integrate-slack.md %}#set-a-default-slack-channel-for-notifications) in Slack for Soda Cloud alerts.
* Added an explanation about anomaly score check results and the minimum number of measurements required to gauge an anomaly.
* Moved installation instructions for Soda Core Scientific to a sub-section of Install Soda Core.
* Added expanded example for setting up [Soda Core Spark DataFrames]({% link soda/connect-spark.md %}).

#### June 9, 2022

* Added some new Soda Core content to documentation.
* Moved Soda SQL and Soda Spark in documentation leftnav.
* Updated Home page with links to new Soda Core documentation.
* Fixed formatting in Quick start for Soda Core and Soda Cloud.

#### June 8, 2022

* Updated the [Quick start for SodaCL]({% link soda/quick-start-sodacl.md %}) with an example of a check for duplicates.
* Added documentation for installing Soda Spark on Windows.
* Updated the [Distribution check]({% link soda-cl/distribution.md %}) documentation to record a change in syntax for the check and the addition of two more methods available to use with distribution checks.

#### June 7, 2022

* Added new documentation for Install Soda Core Scientifc.
* Add a new [Quick start for SodaCL]({% link soda/quick-start-sodacl.md %}).

#### June 6, 2022

* Added clarifying details to [Cross checks]({% link soda-cl/cross-row-checks.md %}) and updated images on [Metrics and checks]({% link soda-cl/metrics-and-checks.md %}).
* Added [Use Docker to run Soda Core]({% link soda-library/install.md %}) to Soda Core installation documentation.

#### June 2, 2022

* Revised the SodaCL [User-defined checks]({% link soda-cl/user-defined.md %}) documentation.
* Revised [For each]({% link soda-cl/for-each.md %}) and [Filters]({% link soda-cl/filters.md %}) documentation.
* Updated [Glossary]({% link soda/glossary.md %}) with SodaCL terminology.

#### June 1, 2022

* Updated SodaCL [Freshness checks]({% link soda-cl/freshness.md %}) and [Cross checks]({% link soda-cl/cross-row-checks.md %}) (fka. Row count checks).
* Added new documentation for SodaCL [Failed rows checks]({% link soda-cl/failed-rows-checks.md %}) 

#### May 31, 2022

* Updated SodaCL [Schema checks]({% link soda-cl/schema.md %}) and [Reference checks]({% link soda-cl/reference.md %}) documentation.
* Corrected Soda Cloud connection syntax in the Quick start for Soda Core and Soda Cloud.
* Removed separate Duplicate checks documentation, redirecting to [Numeric metrics]({% link soda-cl/numeric-metrics.md %}).

#### May 26, 2022

* Updated various Soda Core documents to include support for Amazon Athena. See [Connect to Amazon Athena]({% link soda/connect-athena.md %}).
* Update [Optional check configurations]({% link soda-cl/optional-config.md %}) to include instructions for use an in-check filter to check a portion of your data.
* Added new documentation for [Missing metrics]({% link soda-cl/missing-metrics.md %}) and [Validity metrics]({% link soda-cl/validity-metrics.md %}).

#### May 25, 2022

* Revised and renamed **Data observability** to **Data concepts**.

#### May 24, 2022

* Updated the documentation for the [distribution check]({% link soda-cl/distribution.md %}) in SodaCL, including instructions to install Soda Core Scientific.

#### May 19, 2022

* Added new SodaCL documentation to elaborate on some configuration and offer broad language rules. See [Metrics and checks]({% link soda-cl/metrics-and-checks.md %}), [Optional check configurations]({% link soda-cl/optional-config.md %}), [Numeric metrics]({% link soda-cl/numeric-metrics.md %}), [Filters]({% link soda-cl/filters.md %}), Anomaly score check and [For each]({% link soda-cl/for-each.md %}).

#### May 18, 2022

* Updated the details pertaining to connecting Soda Core to Soda Cloud. The syntax for the key-value pairs for API keys changed from `api_key` and `api_secret` to `api_key_id` and `api_key_secret`.

#### May 9, 2022

* Updated the [Soda Core installation documentation]({% link soda-library/install.md %}) to indicate that Python 3.8 or greater is required.

#### April 26, 2022

* Updated a set of Soda product comparison matrices to illustrate the features and functionality available with different Soda tools.

#### April 25, 2022

* Updated the [Soda product overview]({% link soda/product-overview.md %}) with a more thorough explanation of the product suite and how the parts work together to establish and maintain data reliability.

#### April 22, 2022

* Replaced the quick start tutorials for Soda SQL and Soda Cloud with two new tutorials: 
  * Quick start for Soda SQL and Soda Cloud
  * Quick start for Soda Core and Soda Cloud

#### April 6, 2022

* Added details to the [Freshness check]({% link soda-cl/freshness.md %}) to clarify limitations when specifying duration.
* Added documentation for how to use system variables to store property values#provide-credentials-as-system-variables) instead of storing values in the `env_vars.yml` file.
* Updated Soda Core documentation to remove aspirational content from Adding scans to a pipeline.

#### April 1, 2022

* Added documentation for the `dataset_name` identifier in a scan YAML file. Use the identifier to send more precise dataset information to Soda Cloud. 

#### March 22, 2022

* New documentation for the beta release of Soda Core, a free, open-source, command-line tool that enables you to use the Soda Checks Language to turn user-defined input into aggregated SQL queries.
* New documentation for the beta release of [SodaCL]({% link soda-cl/soda-cl-overview.md %}), a domain-specific language you can use to define Soda Checks in a checks YAML file.


#### February 15, 2022

* Added content to explain how Soda Cloud notifies users of a scan failure. 

#### February 10, 2022

* Added documentation to offer advice on [organizing your datasets]({% link soda-cloud/organize-datasets.md %}) in Soda Cloud using attributes and tags.

#### January 18, 2022

* Add details to [Integrate Soda with dbt]({% link soda/integrate-dbt.md %}#ingest-results-from-dbt-cloud-into-soda-cloud) documentation for running `soda-ingest` using job ID or run ID.

#### January 17, 2022

* Added text to [Roles and rights]({% link soda-cloud/roles-global.md %}) documentation about the option to use the Reporting API to access Audit Trail data.

#### January 12, 2022

* Added documentation regarding [Licenses]({% link soda-cloud/roles-global.md %}) in Soda Cloud.

#### January 11, 2022

* Added requirement for installing Soda Spark on a Databricks cluster. See Soda Spark Requirements.

#### December 22, 2021

* Added data types information for Trino and MySQL.
* Adjusted the docs footer to offer users ways to suggest or make improve our docs.

#### December 16, 2021

* Added documentation for how to [integrate Soda with dbt]({% link soda/integrate-dbt.md %}). Access the test results from a dbt run directly within your Soda Cloud account.

#### December 14, 2021

* Added documentation to accompany the new [Soda Cloud Incidents]({% link soda-cloud/incidents.md %}) feature. Collaborate with your team in Soda Cloud and in Slack to investigate and resolve data quality issues.

#### December 13, 2021

* Added instructions for how to [integrate Soda with Metaphor]({% link soda/integrate-metaphor.md %}). Review data quality information from within the Metaphor UI.

#### December 6, 2021

* Added documenation for the new [audit trail]({% link soda-cloud/roles-global.md %}) feature for Soda Cloud.
* Added further detail about which rows Soda SQL sends to Soda Cloud as samples.

#### December 2, 2021

* Updated Quick start tutorial for Soda Cloud.
* Added information about using regex in a YAML file.

#### November 30, 2021

* Added documentation about the anonymous Soda SQL usage statistics that Soda collects. Learn more about the information Soda collects and how to opt out of sending statistics.

#### November 26, 2021

* Added instructions for how to [integrate Soda Cloud with Alation data catalog]({% link soda/integrate-alation.md %}). Review Soda Cloud data quality information from within the Alation UI.

#### November 24, 2021

* Added new API docs for the [Soda Cloud Reporting API]({% link api-docs/reporting-api-v1.md %}).
* Added instructions to [Build a reporting dashboard]({% link api-docs/reporting-api-to-overview-dashboards.md %}) using the Soda Cloud Reporting API.

#### November 23, 2021

* Revised the Quick start tutorial for Soda SQL to use the same demo repo as the interactive demo.

#### November 15, 2021

* Added a new, embedded interactive demo for Soda SQL.
* New documentation to accompany the soft-launch of Soda Spark, an extension of Soda SQL functionality.

#### November 9, 2021

* New documentation to accompany the new, preview release of historic metrics. This type of metric enables you to use Soda SQL to access the historic measurements in the Cloud Metric Store and write tests that use those historic measurements.

#### October 29, 2021

* Added SSO identity providers to the list of third-party IdPs to which you can add Soda Cloud as a service provider.

#### October 25, 2021

* Removed the feature to Add datasets directly in Soda Cloud. Instead, users add datasets using Soda SQL.
* Added support for Snowflake session parameter configuration in the warehouse YAML file.

#### October 18, 2021

* New documentation to accompany the new Schema Evolution Monitor in Soda Cloud. Use this monitor type to get notifications when columns are changed, added, or deleted in your dataset.

#### October 17, 2021

* New documentation to accompany the new feature to disable or reroute sample data to Soda Cloud.

#### September 30, 2021

* New documentation to accompany the release of [Roles and rights in Soda Cloud]({% link soda-cloud/roles-global.md %}).

#### September 28, 2021

* New documentation to accompany the release of [SSO integration]({% link soda-cloud/sso.md %}) for Soda Cloud.


#### September 17, 2021

* Added Soda Cloud metric names to primary list of column metrics.

#### September 9, 2021

* Published documentation for _time partitioning_, _column metrics_, and _sample data_ in Soda Cloud.

#### September 1, 2021

* Added information for new command options included in Soda CLI version 2.1.0b15 for
    * limiting the datasets that Soda SQL analyzes,
    * preventing Soda SQL from sending scan results to Soda Cloud after a scan, and
    * instructing Soda SQL to skip confirmations before running a scan.
* Added information about how to use a new option, `account_info_path`, to direct Soda SQL to your BigQuery service account JSON key file for configuration details.

#### August 31, 2021

* Added documentation for the feature that allows you to include or exclude specific datasets in your `soda analyze` command.

#### August 30, 2021

* Updated content and changed the name of **Data monitoring** documentation to **Data quality**.

#### August 23, 2021

* New document for custom metric templates that you can copy and paste into scan YAML files.

#### August 9, 2021

* Added details for Apache Spark support. See Install Soda SQL.
* Updated _Adjust a dataset scan schedule_ to include details instructions for triggering a Soda scan externally.

#### August 2, 2021

* Added new document to ouline the [Support]({% link soda/support.md %}) that Soda provides its users and customers.
* Updated BigQuery data source configuration to include `auth_scopes`.


#### July 29, 2021

* Added instructions for configuring BigQuery permissions to run Soda scans.
* Added an example of a programmatic scan using a lambda function.
* Added instructions for overwriting scan output in Soda Cloud.
* New document for Example test to compare row counts.

#### July 26. 2021

* Added Soda SQL documentation for configuring `excluded_columns` during scans.
* Updated compatible data sources for Soda SQL to include **MySQL (experimental)**, and Soda Cloud to improve accuracy.
* Updated Create monitors and alerts to include custom metrics as part of creation flow; updated prerequisites.
* Updated Product overview [comparison]({% link soda/product-overview.md %}#compare-features-and-functionality) for new `excluded_columns` functionality and custom metrics in Soda Cloud.
* Minor adjustments to reflect new and changed elements in the <a href="https://github.com/sodadata/soda-sql/blob/main/CHANGELOG.md#210b12---2021-07-23-frodo-baggins" target="_blank">Soda SQL 2.1.0b12</a> release.


#### July 16, 2021

* Added early iteraction of content for Best practices for defining tests and running scans.
* Added a link to the docs footer to open a Github issue to report issues with docs.

#### July 13, 2021

* New Add datasets documentation for the newly launched feature that enables your to connect to data sources and add datasets directly in Soda Cloud.
* New Collaborate on data monitoring documentation that incorporates how to integrate with Slack, and how to include your team in your efforts to monitor your data.
* New _Adjust a dataset scan schedule_ content to help you refine how often Soda scans a particular dataset.
* Revised Quick start tutorial for Soda Cloud that incorporates the new feature to add datasets.
* Improved Soda product overview page with a [comparison chart]({% link soda/product-overview.md %}#compare-features-and-functionality) for features and functionality.

#### July 6, 2021

* Improved [Home](/index.html) page design.
* New [Soda product overview]({% link soda/product-overview.md %}) documentation.


If you want to know which flavor of Soda is best, you need to examine the criteria of what makes a good Soda. Is it sweet? Is it performant? Is it an appealing color? Does it produce valid SQL?

Though not conclusive, early test results would indicate that the best flavors of Soda, in descending order, are as follows:
1. Cream Soda
2. Root Beer
3. Coca Cola
4. Ginger Beer
5. Cherry Cola

---

*Last modified on {% last_modified_at %}*
