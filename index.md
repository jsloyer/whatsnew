---

 

copyright:

  years: 2015, 2017

lastupdated: "2017-09-15" 

---


{:shortdesc: .shortdesc} 
{:new_window: target="_blank"}

# What's new in {{site.data.keyword.Bluemix_notm}}

Stay up-to-date with the new features and services that are available in {{site.data.keyword.Bluemix}}, so that you get the most out of your {{site.data.keyword.Bluemix_notm}} experience. The updates are organized into these categories: [{{site.data.keyword.Bluemix_notm}} platform](index.html#platform_category), [{{site.data.keyword.Bluemix_notm}} Local and {{site.data.keyword.Bluemix_notm}} Dedicated](index.html#dedicatedandlocal), [Compute](index.html#compute_category), and [Services](index.html#services_category).
{:shortdesc}

## {{site.data.keyword.Bluemix_notm}} platform
{: #platform_category}

### {{site.data.keyword.Bluemix_notm}} global catalog 
New as of: 27 July 2017

Expanding on the last console update to manage your public regions from a single location in the console, {{site.data.keyword.Bluemix_notm}} now has a global catalog making the process of selecting and deploying items you select from the catalog a more streamlined process. Regardless of the region you have selected in the console, you can now see all services that are available across all public regions from your catalog. Once you select a tile from the catalog, you can see which regions the service is available in, and select where you want to deploy it.

For more information about the latest updates to the catalog, see [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon").

### {{site.data.keyword.Bluemix_notm}} console updates
New as of: 23 May 2017

You can now manage your public regions from a single location through the updated {{site.data.keyword.Bluemix_notm}} console. The region selector offers you streamlined access to your resources, and other enhancements include higher availability and improved performance.

For more information about this update, check out [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon").

### Identity and access management
New as of: 01 May 2017

With the latest updates and improvements, {{site.data.keyword.Bluemix_notm}} account owners or administrators can now use a new unified access control UI to take advantage of the following capabilities:
 * Manage users' fine-grained access to Kubernetes services and other services as they adopt the new access control features
 * Assign service policies and Cloud Foundry roles to users within their organizations

Additionally, {{site.data.keyword.Bluemix_notm}} platform users can create, delete, and list API keys associated with their user IDs. And platform users can use those API keys to authenticate when using APIs or CLIs.

Lastly, we’ve enhanced our unified user management capability to ensure that in a linked IaaS-PaaS account, users are managed in a unified way with no need to add users separately in the SoftLayer Customer Portal or the {{site.data.keyword.Bluemix_notm}} console.

For more information about the recent update, check out the [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") blog post.

### Navigation design changes for {{site.data.keyword.Bluemix_notm}} docs
New as of: 13 April 2017

With this navigation update, we think you'll understand how content is organized throughout our docs better, and will be able to find relevant content more efficiently. With fewer nested layers of content, you won't have to dig around to find the documentation you need to be successful with {{site.data.keyword.Bluemix_notm}}.


## {{site.data.keyword.Bluemix_notm}} Local and {{site.data.keyword.Bluemix_notm}} Dedicated
{: #dedicatedandlocal}

### August updates for the administration console
{: #augustadminconsole}
New as of: 31 August 2017

With the latest updates and improvements from August, you can use the following new features:

#### Updates to {{site.data.keyword.cloudant_short_notm}} service usage metrics

  * The computation of usage metrics for {{site.data.keyword.cloudant_short_notm}} has been updated to reflect the total amount of GBs used and available across all nodes in a {{site.data.keyword.cloudant_short_notm}} cluster. Typically, a {{site.data.keyword.cloudant_short_notm}} cluster contains 3 nodes, and a document in the database is replicated across all the nodes in the cluster for high-availability and disaster recovery. With the August updates, the capacity metric in the {{site.data.keyword.cloudant_short_notm}} dial (available in the _Resource Usage > Services_ view) indicates the space across all the nodes in the cluster. For example, if a single {{site.data.keyword.cloudant_short_notm}} cluster contains 3 nodes, each with 1000 GB capacity, the capacity limit will be 3000 GB. If 1500 GBs of that capacity have been used, the {{site.data.keyword.cloudant_short_notm}} usage metric will be 50%.
 
#### Updates to the scheduling of maintenance updates
  
  * In {{site.data.keyword.Bluemix_notm}} Dedicated, customers can manage the dates and times when their dedicated environments are available for deployment of system updates. Customers can define availability windows representing dates and times when maintenance updates can and cannot be deployed to their Dedicated environment. In the August update, _Available Update Windows_ have been renamed _Update Windows_, and _Unavailable Update Windows_ have been renamed _Blackout Windows_. Beyond the terminology changes, customers now have more flexibility and margin for defining blackout (unavailable) dates. Once requested, blackout dates will require IBM approval, and the time it takes to gain approval will vary. When the requested blackout dates are approved, IBM will cancel any existing updates that are currently scheduled during the unavailable window. IBM will also create new records for these updates and schedule them outside the approved blackout dates.
  
See the [video demonstration](https://bit.ly/2eCQNvu){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") for more information.

### July updates for the administration console
{: #julyadminconsole}
New as of: 31 July 2017

With the latest updates and improvements from July, you can use the following new features:

#### Updates to resource usage history capabilities

  * In the previous update (June), the History view for memory and disk usage had introduced display of usage data over the last 48 hours, 30 days, and 5 mohths. In this latest July update, the resource usage history functionality has been expanded to allow customization of the time span for which to show resource usage data. Hourly, daily and monthly views remain, but users can now specify a start day/time and duration for which to display memory and disk usage metrics (for example, showing memory usage for 15 days starting on July 1st 2017).
  * A new CLI command has been introduced to display resource metrics history in the CLI. The parameters of the command, as well as usage examples can be found by typing the following: `_cf ba resource-metrics-history -help_`
 
See the [video demonstration](https://youtu.be/QBij0jB5qAk){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") for more information.

### June updates for the administration console
{: #mayadminconsole}
New as of: 26 June 2017

With the latest updates and improvements from June, you can use the following new features:

#### Updates to the Resource Usage Page

  * System resources
    * The History view for memory and disk has been updated to display data over 48 hours, 30 days, and 5 hours
    * A Learn More link is provided, showing how the administration console metrics api is used to generate the History views 
  * Applications
    * Provides usage information for all applications in the environment
    * Sort by application name, physical memory, reserved memory, physical disk, reserved disk, physical CPU, or Organization name 
    * Search is provided to filter results by application name and Organization name
    * A Learn More link is provided, showing how the administration console metrics api is used to generate the Applications view
 
See [Resource usage](/docs/hybrid/index.html#resourceusage) for more information.

#### Updates to API for Metrics

  * Environment statistics have been added, providing averages by day or month for memory and disk consumption
  
See [API for Metrics](/docs/hybrid/index.html#envappmetricsapi) for more information.


### May updates for the administration console
{: #mayadminconsole}
New as of: 30 May 2017

With the latest updates and improvements from May, you can use the following new features:

 * Improvements on the Status page including more granular diagnostics on incidents affecting the Bluemix platform and runtimes.
 * Improvements to the security Reports and Logs page:
   * Reports are now displayed in a table format, simplyfying the browsing and searching of reports, including the ability to sort by report category, file name, or creation date. 
   * Enhanced filtering including simultaneous filtering of multiple categories 
   * Full screen mode for displaying the contents of a report
   * Capability to delete reports for admin users with "report write" permission
   * Faster display of report lists, progressively loading on-demand through continuous scrolling, resulting in better overall performance.
 * Security reports can be requested on-demand within a time range spanning up to one week and starting a maximum of 3 months back from the time of the request. Note that some environment specific configuration is required before this capability is available to admin users. Admin users will require "report write" permission for this capability.

### April updates for the administration console
{: #apriladminconsole}
New as of: 2 May 2017

With the latest updates and improvements from April, you can use the following new features:

 * Newly designed status app for {{site.data.keyword.Bluemix_notm}} Dedicated and Local environments. You can quickly search by component name or date of posting. You can also switch between the component status posts view and the notifications specific to your environment. See the [New {{site.data.keyword.Bluemix_notm}} Status Page](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") blog post for more information.
 * Service usage data for select services from the Resource Usage tile. See [Service usage details](/docs/hybrid/index.html#servicesresourceusage) for more information about what services are supported and what you can expect from the new view.

## Compute
{: #compute_category}

### Latest updates for buildpacks

Visit the following pages for a cumulative list of the latest updates:

* [Latest Updates to the SDK for Nodejs buildpack](/docs/runtimes/nodejs/updates.html#latest_updates)
* [Latest Updates to the Liberty buildpack](/docs/runtimes/liberty/updates.html#latest_updates)
* [Latest Updates to the ASP.NET Core buildpack](/docs/runtimes/dotnet/updates.html#latest_updates)
* [Latest updates to the IBM XPages for {{site.data.keyword.Bluemix_notm}} buildpack](/docs/starters/xpages/index.html#updates)

### Latest updates for {{site.data.keyword.containerlong_notm}}
New as of: 5 September 2017

{{site.data.keyword.containerlong_notm}} launched its Kubernetes architecture in May, now running in [Dallas, Frankfurt, London, and Sydney](https://www.ibm.com/blogs/bluemix/2017/07/ibm-bluemix-container-service-live-sydney-london/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"). [The plan is to fully deprecate the single and scalable container group architecture on December 5, 2017](https://www.ibm.com/blogs/bluemix/2017/07/deprecation-single-scalable-group-container-service-bluemix-public/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon").  

Leverage the capabilities of the new service with Kubernetes instead of single and scalable container groups as soon as possible. [See the documentation for information about migrating from a native Docker environment to a native Kubernetes environment on Bluemix](/docs/containers/cs_classic.html#cs_classic_migrating).

If you have questions, you can post them in the Slack at https://ibm-container-service.slack.com/.

### New Liberty for Java buildpack v3.11
New as of: 17 July 2017

The Liberty buildpack v3.11 provides new monthly Liberty runtime version and contains other improvements. The monthly Liberty runtime version was updated to the  [2017.7.0.0](https://developer.ibm.com/wasdev/blog/2017/07/07/beta-websphere-liberty-tools-july-2017/) release. The IBM JDK has been updated to the 8.0.4.7 and 7.1.4.5 versions. The buildpack also provides updated versions of the App Management utility and Auto-Scaling agent. The default Cloudant Library is now the official [java-cloudant](https://github.com/cloudant/java-cloudant), the [Ektorp library](https://github.com/helun/Ektorp) is still available as an option, for details on this change see the [blog post](https://www.ibm.com/blogs/bluemix/2017/05/default-library-change-cloudant-auto-wiring-liberty-buildpack/). The default heap size ratio is now 50% when your application has less than 512mb of memory, if it has more than 512mb it will still be 75%. A new staging task log is now generated, which allows for easier debugging of staging errors.See the [latest updates](https://console.ng.bluemix.net/docs/runtimes/liberty/updates.html) documentation for additional information.

### New Liberty for Java buildpack v3.10
New as of: 12 June 2017

The Liberty buildpack v3.10 provides new quarterly and monthly Liberty runtime versions and contains other improvements. The default Liberty runtime version was updated to 17.0.0.2. The monthly Liberty runtime version was updated to the  [2017.5.0.0](https://developer.ibm.com/wasdev/blog/2017/05/12/beta-websphere-liberty-tools-may-2017/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") release. The buildpack also provides updated versions of the App Management utility and Extreme Scale Client. See the [latest updates](/docs/runtimes/liberty/updates.html) documentation for additional information.

### New SDK for Node.js buildpack v3.12
New as of: 16 May 2017

The SDK for Node.js buildpack v3.12 provides IBM SDK for Node.js versions 0.12.17, 0.12.18, 4.8.0, 4.8.2, 6.10.0 and 6.10.2. The default is now changed from the latest 4.x to the latest 6.x, so it is currently 6.10.2. Being a major version change, this could affect apps that are relying on the default. See [Node.js version long-term support and the SDK for Node.js buildpack](https://www.ibm.com/blogs/bluemix/2016/11/node-version-support-and-sdk-buildpack/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") for more information about how to avoid any problems.

In addition to the new runtimes, this release contains a buildpack bug fix an issue with the App Management Health Center handler and Node.js versions 6.9.5 and 6.10.0.

### New Liberty for Java buildpack v3.9
New as of: 27 April 2017

The Liberty buildpack v3.9 provides new monthly Liberty runtime version and contains other improvements. The default Liberty runtime version was updated to include the PI77770, PI77605, IFPI77438 and IFPI79275 iFixes. The monthly Liberty runtime version was updated to the  [2017.3.0.0](https://developer.ibm.com/wasdev/blog/2017/03/14/beta-websphere-liberty-tools-march-2017/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") release. Memory Calculation was moved from staging to the start process, allowing for easier heap memory changes with the restart of an application. The buildpack also provides updated versions of the Auto-Scaling service agent, and Extreme Scale Client. See the [latest updates](/docs/runtimes/liberty/updates.html) documentation for additional information.

## Services
{: #services_category}

### New {{site.data.keyword.iva_full}} experimental service
New as of: 15 September 2017

With the new {{site.data.keyword.iva_full}} experimental service, you can create a cognitive voice agent built on Watson services that customers can call and speak to over the phone. With Watson artificial intelligence at its backbone, your voice agent can communicate in a conversational manner, handling complex interactions and solving customer calls within the voice agent.

{{site.data.keyword.iva_short}} seamlessly connects to and orchestrates the Watson {{site.data.keyword.speechtotextshort}}, {{site.data.keyword.conversationshort}}, and {{site.data.keyword.texttospeechshort}} services to simulate natural-language conversation. Each voice agent automatically scales to handle multiple calls at the same time. In this experimental release, you can customize your voice agent by using the following key features:

* Import the sample {{site.data.keyword.conversationshort}} dialog to get started, then create your own dialog to fit your company's needs.
* Program voice agent behavior from within the {{site.data.keyword.conversationshort}} service by using our APIs. You control everything from barge-in behavior to hanging up the call for any node in your dialog.
* Easily create and manage multiple voice agents if you want to connect different phone numbers to cognitive agents that are specialized for different topics.
* Expand the service's capabilities by connecting a service orchestration engine (SOE) so you can use third-party APIs. For example, the SOE can listen for triggers from the {{site.data.keyword.conversationshort}} service, then use your provided APIs to look up information in existing systems or provide other analysis.

To get started, see the [Getting started with {{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html) documentation.


### {{site.data.keyword.streaminganalyticsshort}} service update: The console includes new ways to pinpoint problems in your applications
New as of: 14 August 2017
 
For Python and Java applications, the source file location is displayed based on your @spl_note annotations. 
 
For details, see [Latest improvements to the {{site.data.keyword.streaminganalyticsshort}}](https://developer.ibm.com/streamsdev/2017/08/14/latest-improvements-streaming-analytics-console/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon").

### IBM Cloud Monitoring is now also available in the United Kingdom region
New as of: 01 August 2017

Use the {{site.data.keyword.monitoringlong}} service to expand your collection, retention, and analysis capabilities in {{site.data.keyword.Bluemix_notm}} when working with metrics. 

* Alert into action! {{site.data.keyword.monitoringlong}} offers an API that you can use to set performance thresholds, and to be notified when those thresholds are breached. Define alert rules for a single service instance or app instance, and alert rules that report on a set of instances. When an alert is triggered, get a notification through an e-mail, a PagerDuty event, a webhook notification, or any combination of the three.

* Add custom metrics. {{site.data.keyword.monitoringlong}} premium plan offers APIs that you can use to add relevant application and business metrics to your Cloud Monitoring data. You can also use them to send metric data from outside the {{site.data.keyword.IBM_notm}} Cloud into the {{site.data.keyword.monitoringlong}} service.

* Build reusable dashboards and make them interactive. {{site.data.keyword.monitoringlong}}’s hosted Grafana provides support for building custom dashboards with a large palate of visualization options.  Make your dashboards dynamic with templating by using metric queries with variables.

* Access your service through the {{site.data.keyword.Bluemix_notm}} catalog. {{site.data.keyword.monitoringlong}} is available as a service tile in the DevOps section of the {{site.data.keyword.Bluemix_notm}} catalog.  For the {{site.data.keyword.containershort}} service with single and group containers, you can access the service from the {{site.data.keyword.Bluemix_notm}} UI.

* Choose the service plan that fits your needs. You may choose the Lite service plan or the Premium service plan to match your usage needs. The Lite plan offers metric collection at once per minute, retention for 15 days, and complementary alerting.  Alternatively, you can select the Premium plan to enable greater consumption, longer metrics retention, and to gain access to the service APIs, for example, to send or retrieve metrics from the {{site.data.keyword.monitoringlong}} service. {{site.data.keyword.monitoringlong}} offers metric collection at once per minute.  The Lite plan retains metrics at full resolution for 15 days. The Premium plan retains metrics at full resolution for 45 days.

The legacy {{site.data.keyword.monitoringshort}} service collected metrics at service defined frequencies starting at 30 seconds, and summarized to 1 hour frequencies over time. {{site.data.keyword.monitoringlong}} now offers full resolution collection at 1 minute.  The Lite plan retains metrics for 15 days.  The Premium plan retains metrics for 45 days.

For more information about the {{site.data.keyword.monitoringlong}} service, refer to [the Getting started with Monitoring documentation](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) or [the IBM Cloud Monitoring – Service Refresh with New Features![External link icon](../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).


### IBM Cloud Log Analysis is now available in the US South region
New as of: 31 July 2017

The {{site.data.keyword.loganalysisfull}} service provides log collection and log search services for the {{site.data.keyword.Bluemix_notm}} platform, automatically collecting application and {{site.data.keyword.Bluemix_notm}} services’ data from select {{site.data.keyword.Bluemix_notm}} services. Use the {{site.data.keyword.loganalysisshort}} service to:

* Retain logs as long as you require.  

    Logs are stored on IBM Cloud storage.  You can download logs when you need them.
	
* Manage your retained logs, and send log data from outside the {{site.data.keyword.IBM_notm}} Cloud by using the new API.

* Choose the amount of logs that you can search per day.  

    Different plans are available that you can use to search up to 500MB,  2GB, 5GB, and 10GB of logs per day.

* Build reusable dashboards and make them interactive. 

    {{site.data.keyword.loganalysisshort}}’s hosted Kibana provides support for building custom dashboards.

* Access your service through the Bluemix catalog.  

    For the  {{site.data.keyword.loganalysisshort}} service with single and group containers, and {{site.data.keyword.IBM_notm}} Cloud Foundry services, you can access the service from the {{site.data.keyword.Bluemix_notm}} UI.

For more information about the {{site.data.keyword.loganalysisshort}} service, refer to the [Getting started with {{site.data.keyword.loganalysisfull}}](/docs/services/CloudLogAnalysis/index.html#getting-started-with-ibm-cloud-log-analysis) and the [{{site.data.keyword.loganalysisshort}} overview](/docs/services/CloudLogAnalysis/log_analysis_ov.html#log_analysis_ov).

### IBM dashDB for Analytics has been renamed
New as of: 18 July 2017

The following table summarizes the new name:

| Previous name               | New name                   | Effective date |
|-----------------------------|----------------------------|----------------|
| IBM dashDB for Analytics    | IBM Db2 Warehouse on Cloud | July 18, 2017  |
{: caption="Table 1. Service name change" caption-side="top"}
 
For a cumulative list of updates for Db2 Warehouse on Cloud and Db2 on Cloud, see: [What's New in Db2 Warehouse on Cloud and Db2 on Cloud](http://www.ibm.com/support/docview.wss?uid=swg21961758){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"). 

### IBM Cloud Monitoring is now available in the US South region
New as of: 17 July 2017

Use the {{site.data.keyword.monitoringlong}} service to expand your collection, retention, and analysis capabilities in {{site.data.keyword.Bluemix_notm}} when working with metrics. 

* Alert into action! {{site.data.keyword.monitoringlong}} offers an API that you can use to set performance thresholds, and to be notified when those thresholds are breached. Define alert rules for a single service instance or app instance, and alert rules that report on a set of instances. When an alert is triggered, get a notification through an e-mail, a PagerDuty event, a webhook notification, or any combination of the three.

* Add custom metrics. {{site.data.keyword.monitoringlong}} premium plan offers APIs that you can use to add relevant application and business metrics to your Cloud Monitoring data. You can also use them to send metric data from outside the {{site.data.keyword.IBM_notm}} Cloud into the {{site.data.keyword.monitoringlong}} service.

* Build reusable dashboards and make them interactive. {{site.data.keyword.monitoringlong}}’s hosted Grafana provides support for building custom dashboards with a large palate of visualization options.  Make your dashboards dynamic with templating by using metric queries with variables.

* Access your service through the {{site.data.keyword.Bluemix_notm}} catalog. {{site.data.keyword.monitoringlong}} is available as a service tile in the DevOps section of the {{site.data.keyword.Bluemix_notm}} catalog.  For the {{site.data.keyword.containershort}} service with single and group containers, you can access the service from the {{site.data.keyword.Bluemix_notm}} UI.

* Choose the service plan that fits your needs. You may choose the Lite service plan or the Premium service plan to match your usage needs. The Lite plan offers metric collection at once per minute, retention for 15 days, and complementary alerting.  Alternatively, you can select the Premium plan to enable greater consumption, longer metrics retention, and to gain access to the service APIs, for example, to send or retrieve metrics from the {{site.data.keyword.monitoringlong}} service. {{site.data.keyword.monitoringlong}} offers metric collection at once per minute.  The Lite plan retains metrics at full resolution for 15 days. The Premium plan retains metrics at full resolution for 45 days.

The legacy {{site.data.keyword.monitoringshort}} service collected metrics at service defined frequencies starting at 30 seconds, and summarized to 1 hour frequencies over time. {{site.data.keyword.monitoringlong}} now offers full resolution collection at 1 minute.  The Lite plan retains metrics for 15 days.  The Premium plan retains metrics for 45 days.

For more information about the {{site.data.keyword.monitoringlong}} service, refer to [the Getting started with Monitoring documentation](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) or [the IBM Cloud Monitoring – Service Refresh with New Features![External link icon](../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).

### {{site.data.keyword.contdelivery_full}} upgrade
New as of: 11 July 2017

Benefits of the upgrade include bug fixes, performance improvements, and refinements to the user experience. Noteworthy enhancements, if not already present on your environment, include:
<ul>
<li>Fixes and improvements to internationalization and accessibility.</li>
<li>Toolchain access control, available from a toolchain's Manage tab.</li>
<li>New tool integrations in the Continuous Delivery tool catalog.</li>
<li>Improved grouping of multiple workspaces in the Orion Web IDE.</li>
<li>Support for multiple editor tabs in the Orion Web IDE.</li>
<li>Support for UI themes in the Orion Web IDE.</li>
</ul>

### {{site.data.keyword.uccr_full}} beta 
New as of: 23 June 2017

{{site.data.keyword.uccr_short}} is an enterprise-scale release management solution that supports both cloud-native and on-prem deployment tools.

The beta version of {{site.data.keyword.uccr_short}} provides the following key features:
* Use releases to manage multiple deployment plans and events, and collaborate on multi-team release efforts.
* Create events for any release-related activity and manage them with the calendar.
* Import your own events and releases.
* Customize calendar events to fit your organization.
* Use email and Slack type tasks for release notifications.

### dashDB for Transactions has been renamed to {{site.data.keyword.DB2OnCloud_short}}
New as of: 14 June 2017

IBM {{site.data.keyword.DB2OnCloud_short}} is the new name for dashDB for Transactions. As part of this renaming the former self-managed IBM {{site.data.keyword.DB2OnCloud_short}} service will also be renamed to IBM Db2 Hosted. At this time only display names are updated, so any APIs or command line interfaces remain unchanged.

### {{site.data.keyword.sparks}} updates: Stocator-S3 connector includes support for IBM Cloud Object Storage Cross Region service (Beta)
New as of: 05 June 2017

{{site.data.keyword.sparks}} users can now access and do analytics on data stored in the IBM Cloud Object Storage Cross Region service. This capability is offered as a Beta. IBM Cloud Object Storage offers high-capacity, cost-effective storage for analytics and other applications that is scalable, flexible and simple to use.

The Apache Spark accesses IBM Cloud Object Storage data through a storage connector based on Stocator technology, which is implicitly designed for object storage and thus faster than legacy object storage connectors. As a user, you do not need to change or recompile Apache Spark code.

[Access and Analyze data in IBM Cross Region Cloud Object Storage](https://www.ibm.com/blogs/bluemix/2017/06/access-analyze-data-ibm-cross-region-cloud-object-storage/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") blog post describes usage of IBM Cloud Object Storage data with {{site.data.keyword.sparks}} on {{site.data.keyword.Bluemix_notm}} and the IBM Data Science Experience (DSx).

Please reach out to us at [sparksrv@us.ibm.com](sparksrv@us.ibm.com), if you have any questions or comments. Your input is greatly appreciated!

### New scalable plan available for {{site.data.keyword.dashdbshort}} for Transactions
New as of: 31 May 2017

A new plan is available for {{site.data.keyword.dashdbshort}} for Transactions that can grow with your database needs. The new Flex plan allows you to start with a small system and grow the power and storage capacity of that system easily and quickly. {{site.data.keyword.dashdbshort}} for Transactions is 100% DB2-compatible and provides a 99.95% SLA on high availability plans.

### New Updates to  {{site.data.keyword.mobilepush}} service on {{site.data.keyword.Bluemix_notm}}
New as of: 24 May 2017

The following are the new updates available for {{site.data.keyword.mobilepush}} service on {{site.data.keyword.Bluemix_notm}}

**Lite Plan**: We are introducing a new Lite Plan in addition to the existing Basic Plan for {{site.data.keyword.mobilepush}} Service. As per the new plan the users can send upto hundred thousand digital messages for free per month. While upgrading from Lite plan to basic plan the user will be charged post one million digital messages starting from the count where the Lite plan usage was clipped.

**Monitoring**: You can now get insights on notifications sent and devices registered in the {{site.data.keyword.mobilepush}} Service Console. You can also use REST API's for message level tracking. From message delivery to message dispatching to message receipt, the details can be obtained by configuring webhooks.  See [Monitoring for {{site.data.keyword.mobilepush}}](/docs/services/mobilepush/t_push_monitoring.html#monitor-notifications).

**Web Notifications**: You can now send notifications to Safari Web browsers.

### Secure Gateway Updates
New as of: 24 May 2017

The latest Secure Gateway maintenance update includes minor bug fixes in the UI and API manager, updated documentation, and the client has been updated to version 1.7.1. The Secure Gateway client is now available on AIX 7.1+ and supports connecting outbound through a squid proxy.

### {{site.data.keyword.streaminganalyticsfull}} service updates: Develop Streams applications in your Python development environment
New as of: 13 April 2017

In the past, you had to install a local version of IBM Streams to develop Python applications. That’s no longer the case. Now you can develop applications with Python in your favorite development environment or in a Jupyter interactive notebook.

You can use the STREAMING_ANALYTICS_SERVICE context to submit a Python application to the {{site.data.keyword.streaminganalyticsshort}} service. The {{site.data.keyword.streaminganalyticsshort}} service requires Python 3.5.

You can create sample Python applications using Jupyter notebooks in IBM Data Science Experience (DSX), and submit these applications to the {{site.data.keyword.streaminganalyticsshort}} instance directly from DSX. Check out the sample stream-processing Python applications in notebooks on the [DSX community page](https://datascience.ibm.com/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon").

For more information about the {{site.data.keyword.streaminganalyticsshort}} service updates, see [{{site.data.keyword.streaminganalyticsshort}} updates: DSX integration and easier Python development](https://www.ibm.com/blogs/bluemix/2017/05/streaming-analytics-updates-dsx-integration-easier-python-development/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon").

### {{site.data.keyword.sparks}} updates: Apache Spark 2.1 is supported now
New as of: 21 April 2017

{{site.data.keyword.sparkl}} is introducing the support for Apache Spark 2.1 to create algorithms that harness insights from complex data. Apache Spark 2.1 will help significantly around structured streaming with added support for event time watermarks and Kafka 0.10. Apache Spark 2.1 also focused on increasing stability and usability in Spark SQL, SparkR and the MLlib modules. For more details on Spark 2.1, see [Spark Release 2.1.0](http://spark.apache.org/releases/spark-release-2-1-0.html).

We are happy to answer any questions related to {{site.data.keyword.sparkl}} or the newer version of Apache Spark 2.1 and are reachable at sparksrv@us.ibm.com. 

### {{site.data.keyword.macm_long}} is being deprecated
New as of: 18 April 2017

As of March 30th, 2017, {{site.data.keyword.macm_long}} service tile will be removed from the {{site.data.keyword.Bluemix_notm}} Catalog and you will no longer be able to provision new MACM instances. However, existing instances will continue to be supported. The End of Support Date is 30 March 2018. Please delete your {{site.data.keyword.macm_short}} (MACM) service instances before the End of Support Date. We encourage users to migrate to the IBM Watson Content Hub. Watson Content Hub is available on IBM Marketplace and provides users with a 30-day free trial. IBM Watson Content Hub provides similar functionality to MACM with added new capabilities such as asset management, cognitive tagging using IBM Watson services, and included content delivery network (CDN) to ensure an optimal experience for your customers. IBM offers service engagments to migrate content from MACM to Watson Content Hub.

### {{site.data.keyword.streaminganalyticsfull}} service updates: Develop Streams applications in your Python development environment
New as of: 13 April 2017

In the past, you had to install a local version of IBM Streams to develop Python applications. That’s no longer the case. Now you can develop applications with Python in your favorite  development environment or in a Jupyter interactive notebook.

You can use the STREAMING_ANALYTICS_SERVICE context to submit a Python application to the {{site.data.keyword.streaminganalyticsshort}} service. The {{site.data.keyword.streaminganalyticsshort}} service requires Python 3.5.

Check out the sample stream-processing Python applications in notebooks on the [community page of IBM Data Science Experience](http://datascience.ibm.com){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"). 

### {{site.data.keyword.sparkl}} updates: Notebook support now in Data Science Experience
New as of: 11 April 2017

Your new platform to work with notebooks and Spark is Data Science Experience. Sign up to [Data Science Experience](http://datascience.ibm.com/), and start creating notebooks and sharing your expertise with other data scientists.

If you worked with notebooks in {{site.data.keyword.sparks}}, you can migrate your notebooks to Data Science Experience. For more information, see the [Migrating notebooks documentation](/docs/services/AnalyticsforApacheSpark/index-gentopic2.html#migration_to_dsx).
