---
icon: home
label: Home
---

![](/static/sa-crowdstrike-hero.webp)

# Welcome to the Docs!

The SA-CrowdstrikeDevices add-on allows Splunk Enterprise Security admins to use [CrowdStrike<small>:icon-link-external:</small>][crowdstrike]{ target="blank" } device data with the Asset Database. This documentation will cover the components used in the add-on and advanced configurations. 

!!!danger Important
This Supporting add-on is only intended to work with [Splunk Enterprise Security<small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/263){ target="blank" } deployments.
!!!

> __*Disclaimer*__
> 
> *This Splunk Supporting Add-on is __not__ affiliated with [__Crowdstrike, Inc.__<small>:icon-link-external:</small>][crowdstrike]{ target="blank" } and is not sponsored or sanctioned by the Crowdstrike team. As such, the included documentation does not contain information on how to get started with Crowdstrike. Rather, this documentation serves as a guide to use Crowdstrike device data with Splunk Enterprise Security. Please visit [https://www.crowdstrike.com<small>:icon-link-external:</small>][crowdstrike]{ target="blank" } for more information about Crowdstrike.*

## Assumptions

This documentation assumes the following:

1. You have a working Splunk Enterprise Security environment. __This add-on is not intended to work without Splunk ES.__
2. You already have Crowdstrike device data ingested using the [Crowdstrike Devices technical add-on<small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/5570){ target="blank" }.
3. Familiarity with setting up a new Asset source in Enterprise Security.

## About

Info | Description
------|----------
SA-CrowdstrikeDevices | 1.1.1 - [Splunkbase<small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/6573){ target="blank" } \| [GitHub<small>:icon-link-external:</small>](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/releases/tag/v1.1.1){ target="blank" }
Splunk Enterprise Security Version <small>(Required)</small> | [7.x \| 6.x<small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/263){ target="blank" }
Crowdstrike Devices Add-on <small>(Required)</small> | [3.x<small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/5570){ target="blank" }
Add-on has a web UI | No, this add-on does not contain views.

[crowdstrike]: https://www.crowdstrike.com
