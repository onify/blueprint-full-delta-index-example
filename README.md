![Onify Blueprints](https://files.readme.io/8ba3f14-onify-blueprints-logo.png)

[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)

# Onify Blueprint: Full and Delta indexing example

Example how to initiate either full- or delta (changes) indexing based on oldest items modified date. In this case we check if items are older than 24 hours. The workflow (process) will be scheduled to run every hour according to cron job settings.

![alt text](flow.png "Flow (BPMN)")

## Requirements

* Onify Hub v2
* Onify Flow license
* Camunda Modeler 4.4 or later 

## Included

* 1 x Flow

## Setup

1. Open `full-delta-index-example.bpmn` in Camunda Modeler
2. Click `Deploy current diagram`
3. Follow the instructions

## Run 

You can test and run the flow directly.

1. Open `full-delta-index-example.bpmn` in Camunda Modeler
2. Click `Start current diagram`

> NOTE: When you start the flow, it will automatically schedule the workflow.

## Support

* Community/forum: https://support.onify.co/discuss
* Documentation: https://support.onify.co/docs
* Support and SLA: https://support.onify.co/docs/get-support

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
