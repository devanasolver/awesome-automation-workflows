<h1 align="center">Awesome Automation and Workflows</h1>

<p align="center"><img src="assets/banner.png" alt="Awesome Automation and Workflows" width="100%"></p>

<p align="center">
<a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
<img src="https://img.shields.io/badge/PRs-welcome-brightgreen" alt="PRs welcome">
<img src="https://img.shields.io/badge/license-CC0--1.0-blue" alt="License CC0 1.0">
<a href="https://github.com/devanasolver/awesome-automation-workflows/commits/main"><img src="https://img.shields.io/github/last-commit/devanasolver/awesome-automation-workflows" alt="Last commit"></a>
</p>

<p align="center">
<a href="https://github.com/devanasolver"><img src="https://img.shields.io/badge/Follow-@devanasolver-181717?style=for-the-badge&logo=github" alt="Follow on GitHub"></a>
<a href="https://github.com/devanasolver/awesome-automation-workflows/stargazers"><img src="https://img.shields.io/github/stars/devanasolver/awesome-automation-workflows?style=for-the-badge&logo=github&label=Star%20this%20list" alt="Star this list"></a>
<a href="https://buymeacoffee.com/isaac49"><img src="https://img.shields.io/badge/Buy%20me%20a%20coffee-isaac49-ffdd00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy me a coffee"></a>
</p>

> Open-source workflow engines, no-code builders, RPA, scheduling and browser automation for repeatable work. Every entry shows its license.

**Rules of this list:** every repo exists, is public, is not archived, states a license and has had a commit in the last year. One plain sentence each. Star counts and claims are the authors' own, we did not test every tool. Checked 2026-10-18. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [No-code and low-code automation](#no-code-and-low-code-automation)
- [Workflow and orchestration engines](#workflow-and-orchestration-engines)
- [Job queues and schedulers](#job-queues-and-schedulers)
- [Browser and web automation](#browser-and-web-automation)
- [Desktop and RPA](#desktop-and-rpa)
- [Integrations and connectors](#integrations-and-connectors)
- [AI-driven automation](#ai-driven-automation)
- [Home and device automation](#home-and-device-automation)
- [How to choose](#how-to-choose)
- [Contributing](#contributing)

## No-code and low-code automation

Visual builders like Zapier you host yourself.

- [activepieces/activepieces](https://github.com/activepieces/activepieces) ![stars](https://img.shields.io/github/stars/activepieces/activepieces?style=flat&label=%E2%98%85) - Open-source no-code automation, an alternative to Zapier. _(check repo)_
- [automatisch/automatisch](https://github.com/automatisch/automatisch) ![stars](https://img.shields.io/github/stars/automatisch/automatisch?style=flat&label=%E2%98%85) - Open-source Zapier alternative for business automation. _(check repo)_
- [huginn/huginn](https://github.com/huginn/huginn) ![stars](https://img.shields.io/github/stars/huginn/huginn?style=flat&label=%E2%98%85) - Build agents that watch the web and act on your behalf. _(MIT)_
- [n8n-io/n8n](https://github.com/n8n-io/n8n) ![stars](https://img.shields.io/github/stars/n8n-io/n8n?style=flat&label=%E2%98%85) - Visual workflow automation with hundreds of integrations. Fair-code license with limits. _(check repo)_
- [node-red/node-red](https://github.com/node-red/node-red) ![stars](https://img.shields.io/github/stars/node-red/node-red?style=flat&label=%E2%98%85) - Low-code, flow-based programming for hardware and APIs. _(Apache-2.0)_
- [windmill-labs/windmill](https://github.com/windmill-labs/windmill) ![stars](https://img.shields.io/github/stars/windmill-labs/windmill?style=flat&label=%E2%98%85) - Turn scripts into workflows, apps and internal tools. _(check repo)_

## Workflow and orchestration engines

Code-first engines for reliable jobs.

- [apache/airflow](https://github.com/apache/airflow) ![stars](https://img.shields.io/github/stars/apache/airflow?style=flat&label=%E2%98%85) - Platform to author, schedule and monitor workflows. _(Apache-2.0)_
- [argoproj/argo-workflows](https://github.com/argoproj/argo-workflows) ![stars](https://img.shields.io/github/stars/argoproj/argo-workflows?style=flat&label=%E2%98%85) - Container-native workflow engine for Kubernetes. _(Apache-2.0)_
- [conductor-oss/conductor](https://github.com/conductor-oss/conductor) ![stars](https://img.shields.io/github/stars/conductor-oss/conductor?style=flat&label=%E2%98%85) - Orchestration engine for microservices and workflows. _(Apache-2.0)_
- [dagster-io/dagster](https://github.com/dagster-io/dagster) ![stars](https://img.shields.io/github/stars/dagster-io/dagster?style=flat&label=%E2%98%85) - Orchestrator for data assets and pipelines. _(Apache-2.0)_
- [hatchet-dev/hatchet](https://github.com/hatchet-dev/hatchet) ![stars](https://img.shields.io/github/stars/hatchet-dev/hatchet?style=flat&label=%E2%98%85) - Background task and workflow platform. _(MIT)_
- [inngest/inngest](https://github.com/inngest/inngest) ![stars](https://img.shields.io/github/stars/inngest/inngest?style=flat&label=%E2%98%85) - Event-driven durable functions and workflows. _(check repo)_
- [kestra-io/kestra](https://github.com/kestra-io/kestra) ![stars](https://img.shields.io/github/stars/kestra-io/kestra?style=flat&label=%E2%98%85) - Event-driven orchestration platform with a declarative YAML approach. _(Apache-2.0)_
- [PrefectHQ/prefect](https://github.com/PrefectHQ/prefect) ![stars](https://img.shields.io/github/stars/PrefectHQ/prefect?style=flat&label=%E2%98%85) - Workflow orchestration for Python data and automation jobs. _(Apache-2.0)_
- [spotify/luigi](https://github.com/spotify/luigi) ![stars](https://img.shields.io/github/stars/spotify/luigi?style=flat&label=%E2%98%85) - Python module for building complex batch pipelines. _(Apache-2.0)_
- [temporalio/temporal](https://github.com/temporalio/temporal) ![stars](https://img.shields.io/github/stars/temporalio/temporal?style=flat&label=%E2%98%85) - Durable execution platform for reliable workflows. _(MIT)_

## Job queues and schedulers

Run work on a clock or from a queue.

- [agronholm/apscheduler](https://github.com/agronholm/apscheduler) ![stars](https://img.shields.io/github/stars/agronholm/apscheduler?style=flat&label=%E2%98%85) - Advanced Python scheduler for in-process jobs. _(MIT)_
- [celery/celery](https://github.com/celery/celery) ![stars](https://img.shields.io/github/stars/celery/celery?style=flat&label=%E2%98%85) - Distributed task queue for Python. _(check repo)_
- [citusdata/pg_cron](https://github.com/citusdata/pg_cron) ![stars](https://img.shields.io/github/stars/citusdata/pg_cron?style=flat&label=%E2%98%85) - Run periodic jobs inside Postgres. _(PostgreSQL)_
- [go-co-op/gocron](https://github.com/go-co-op/gocron) ![stars](https://img.shields.io/github/stars/go-co-op/gocron?style=flat&label=%E2%98%85) - Job scheduling library for Go. _(MIT)_
- [hibiken/asynq](https://github.com/hibiken/asynq) ![stars](https://img.shields.io/github/stars/hibiken/asynq?style=flat&label=%E2%98%85) - Simple, reliable distributed task queue in Go. _(MIT)_
- [sidekiq/sidekiq](https://github.com/sidekiq/sidekiq) ![stars](https://img.shields.io/github/stars/sidekiq/sidekiq?style=flat&label=%E2%98%85) - Background jobs for Ruby. _(check repo)_
- [taskforcesh/bullmq](https://github.com/taskforcesh/bullmq) ![stars](https://img.shields.io/github/stars/taskforcesh/bullmq?style=flat&label=%E2%98%85) - Message queue and job processing for Node.js and Python. _(MIT)_

## Browser and web automation

Drive a browser for testing or tasks.

- [browser-use/browser-use](https://github.com/browser-use/browser-use) ![stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat&label=%E2%98%85) - Make websites accessible for AI agents. _(MIT)_
- [browserless/browserless](https://github.com/browserless/browserless) ![stars](https://img.shields.io/github/stars/browserless/browserless?style=flat&label=%E2%98%85) - Headless browser service for automation and scraping. _(check repo)_
- [cypress-io/cypress](https://github.com/cypress-io/cypress) ![stars](https://img.shields.io/github/stars/cypress-io/cypress?style=flat&label=%E2%98%85) - Fast browser testing and automation tool. _(MIT)_
- [microsoft/playwright](https://github.com/microsoft/playwright) ![stars](https://img.shields.io/github/stars/microsoft/playwright?style=flat&label=%E2%98%85) - Reliable end-to-end testing and automation across browsers. _(Apache-2.0)_
- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) ![stars](https://img.shields.io/github/stars/microsoft/playwright-mcp?style=flat&label=%E2%98%85) - MCP server that lets assistants drive a browser with Playwright. _(Apache-2.0)_
- [puppeteer/puppeteer](https://github.com/puppeteer/puppeteer) ![stars](https://img.shields.io/github/stars/puppeteer/puppeteer?style=flat&label=%E2%98%85) - JavaScript API to control Chrome and Firefox. _(Apache-2.0)_
- [SeleniumHQ/selenium](https://github.com/SeleniumHQ/selenium) ![stars](https://img.shields.io/github/stars/SeleniumHQ/selenium?style=flat&label=%E2%98%85) - Browser automation framework and ecosystem. _(Apache-2.0)_

## Desktop and RPA

Automate desktop apps and files.

- [AutoHotkey/AutoHotkey](https://github.com/AutoHotkey/AutoHotkey) ![stars](https://img.shields.io/github/stars/AutoHotkey/AutoHotkey?style=flat&label=%E2%98%85) - Scripting language for desktop automation on Windows. _(GPL-2.0)_
- [autokey/autokey](https://github.com/autokey/autokey) ![stars](https://img.shields.io/github/stars/autokey/autokey?style=flat&label=%E2%98%85) - Desktop automation utility for Linux. _(GPL-3.0)_
- [robocorp/rpaframework](https://github.com/robocorp/rpaframework) ![stars](https://img.shields.io/github/stars/robocorp/rpaframework?style=flat&label=%E2%98%85) - Open-source libraries and tools for robotic process automation. _(Apache-2.0)_
- [robotframework/robotframework](https://github.com/robotframework/robotframework) ![stars](https://img.shields.io/github/stars/robotframework/robotframework?style=flat&label=%E2%98%85) - Generic automation framework for acceptance testing and RPA. _(Apache-2.0)_

## Integrations and connectors

Move data between services.

- [airbytehq/airbyte](https://github.com/airbytehq/airbyte) ![stars](https://img.shields.io/github/stars/airbytehq/airbyte?style=flat&label=%E2%98%85) - Data integration platform with many connectors. _(check repo)_
- [apache/camel](https://github.com/apache/camel) ![stars](https://img.shields.io/github/stars/apache/camel?style=flat&label=%E2%98%85) - Integration framework with many connectors. _(Apache-2.0)_
- [apache/nifi](https://github.com/apache/nifi) ![stars](https://img.shields.io/github/stars/apache/nifi?style=flat&label=%E2%98%85) - Automate data flow between systems. _(Apache-2.0)_
- [dlt-hub/dlt](https://github.com/dlt-hub/dlt) ![stars](https://img.shields.io/github/stars/dlt-hub/dlt?style=flat&label=%E2%98%85) - Python library for loading data from many sources. _(Apache-2.0)_
- [mage-ai/mage-ai](https://github.com/mage-ai/mage-ai) ![stars](https://img.shields.io/github/stars/mage-ai/mage-ai?style=flat&label=%E2%98%85) - Tool for building and running data pipelines. _(Apache-2.0)_
- [meltano/meltano](https://github.com/meltano/meltano) ![stars](https://img.shields.io/github/stars/meltano/meltano?style=flat&label=%E2%98%85) - Declarative, code-first data integration engine. _(MIT)_

## AI-driven automation

Workflows that call LLMs and agents.

- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) ![stars](https://img.shields.io/github/stars/crewAIInc/crewAI?style=flat&label=%E2%98%85) - Framework for orchestrating role-playing AI agents. _(MIT)_
- [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) ![stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=flat&label=%E2%98%85) - Library for building stateful, multi-step agents as graphs. _(MIT)_
- [langgenius/dify](https://github.com/langgenius/dify) ![stars](https://img.shields.io/github/stars/langgenius/dify?style=flat&label=%E2%98%85) - Platform for building LLM apps with workflows and RAG. _(check repo)_

## Home and device automation

Automate smart devices and local services.

- [eclipse-mosquitto/mosquitto](https://github.com/eclipse-mosquitto/mosquitto) ![stars](https://img.shields.io/github/stars/eclipse-mosquitto/mosquitto?style=flat&label=%E2%98%85) - Open-source MQTT message broker. _(check repo)_
- [home-assistant/core](https://github.com/home-assistant/core) ![stars](https://img.shields.io/github/stars/home-assistant/core?style=flat&label=%E2%98%85) - Open-source home automation that puts local control first. _(Apache-2.0)_
- [ioBroker/ioBroker](https://github.com/ioBroker/ioBroker) ![stars](https://img.shields.io/github/stars/ioBroker/ioBroker?style=flat&label=%E2%98%85) - Integration platform for the Internet of Things. _(MIT)_
- [openhab/openhab-core](https://github.com/openhab/openhab-core) ![stars](https://img.shields.io/github/stars/openhab/openhab-core?style=flat&label=%E2%98%85) - Vendor-neutral home automation platform. _(EPL-2.0)_

## How to choose

- **Start with one boring task** you do every week.
- **Handle failures.** Add retries, alerts and logs before you depend on a flow.
- **Keep secrets out of workflows.** Use the tool's credential store.
- **Check the license.** Some popular engines are fair-code with limits for resale.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). One entry per pull request, plain words, real sources only.

## About

Maintained by [@devanasolver](https://github.com/devanasolver). Listings follow the rules in CONTRIBUTING.

## Sponsor me

If this list is useful, [buy me a coffee](https://buymeacoffee.com/isaac49).
