<img alt="SrcLaunch Logo" src="https://raw.githubusercontent.com/srclaunch/.github/main/profile/logo-wide-light-bg.svg?#gh-light-mode-only" width="300" /><br /><br />

<img alt="SrcLaunch Logo" src="https://raw.githubusercontent.com/srclaunch/.github/main/profile/logo-wide-dark-bg.svg?#gh-dark-mode-only" width="300" /><br /><br />

![GitHub followers](https://img.shields.io/github/followers/srclaunch?style=social) ![Stars](https://img.shields.io/github/stars/srclaunch?style=social) 

SrcLaunch is a platform built with the goal of eliminating repetitive software engineering tasks so engineers can focus on releasing features.

## Features
<!-- ###### Feature Statuses
| Icon | Status | Description |
|:----:|:-------|:------------|
| 💡 | Idea | Idea for a feature that needs requirement gathering and validation.|
| 🚧 | In-Progress | Features with defined specs that are currently being worked on.|
| ✅ | Complete | Features whose requirements have been met, and have been released. -->



<!-- ###### Feature Statuses
| Icon | Status | Description |
|:----:|:-------|:------------|
| 💡 | Idea | Idea for a feature that needs requirement gathering and validation.|
| 🚧 | In-Progress | Features with defined specs that are currently being worked on.|
| ✅ | Complete | Features whose requirements have been met, and have been released. -->

### DX

Developer Experience features that help in configuring the development environment around best practices for the specific platform or build target. 

| Feature | Status | Description |
|:--------|:------:|:------------|
|**Linting**| 🚧 | Linter configurations for specific project types and targets.||
|Commitlint| 🚧 ||
|ESLint| ✅ ||
|Prettier| ✅ ||
|Stylelint| ✅ ||
|Versionlint| 🚧 |
|**Testing** | ||
|Ava | ✅ ||
|Jest | ✅ ||
|**Static Type Checking** | ✅ |  |
|TypeScript| ✅ ||
    
### Core Objects

Core Objects are business-case specific custom objects that make up the data layer of a SrcLaunch application or service.

| Feature | Status | Description |
|:--------|:------:|:------------|
| **Data Modeling** | ✅ | Global data model definitions|
| **Library Generation** | ✅ | Convenience libraries for performing CRUD operations on Core Objects.
|`core-api`| ✅ | CoreAPI server configured with CRUD endpoints for Core Objects.
|`http-client`| ✅ | Instance of HttpClient from `@srclaunch/http-client` with CRUD request endpoints configured for the CoreAPI.
|`redux-state`| ✅ | Redux State and actions for managing Core Objects.
|`sequelize-models`| ✅ | Sequelize model definitions.
|`types`| ✅ | TypeScript type definitions for Core Objects.

### Infrastructure

| Feature | Sub-features | Status | Description |
|:--------|:-------------|:------:|:------------|

### Logging

| Feature | Sub-features | Status | Description |
|:--------|:-------------|:------:|:------------|

### Exception Handling

| Feature | Sub-features | Status | Description |
|:--------|:-------------|:------:|:------------|

### Accessibility

| Feature | Sub-features | Status | Description |
|:--------|:-------------|:------:|:------------|

### Internationalization

| Feature | Sub-features | Status | Description |
|:--------|:-------------|:------:|:------------|

### UI Component Library

| Feature | Sub-features | Status | Description |
|:--------|:-------------|:------:|:------------|

### CLI Tool

| Command | Sub-command  | Status | Description |
|:--------|:-------------|:------:|:------------|
| `changeset` |              |        |             |
|         | `add`     |        |             |
|         | `list`          |        |             |
|         | `delete`       |        |             |
| `build` |              |        |             |
|         | `esbuild`      |        |             |
|         | `swc`          |        |             |
|         | `parcel`       |        |             |
|         | `vite`         |        |             |
|         | `types`   |        |             |
| `test`  |              |        |             |
|         | `ava`          |        |             |
|         | `coverage`         |        |             |
|         | `jest`         |        |             |
|`release`|              |        |             |

--- 

## Libraries

<!-- ##### Stability

| Icon | Name | Description |
|:----:|:-----------|:-----------|
| 🔴 | Broken | Cannot be used at the present time.
| 🟠 | Unstable | Can be used, but some features may be missing or don't function correctly. 
| 🟢 | Stable | Stable and follows semantic versioning guidelines. -->



### [@srclaunch/a11y](https://github.com/srclaunch/a11y) 

![Stars](https://img.shields.io/github/stars/srclaunch/a11y?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/a11y?style=social)

Accessibility utilities and helpers.

[![Issues](https://img.shields.io/github/issues/srclaunch/a11y?label=Issues)](https://github.com/srclaunch/a11y/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/a11y?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/a11y) [![Build](https://github.com/srclaunch/a11y/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/a11y/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/a11y?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/a11y)

---

### [ @srclaunch/actions](https://github.com/srclaunch/actions)

![Stars](https://img.shields.io/github/stars/srclaunch/actions?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/actions?style=social)

Actions (send an email, submit a form, create a record, etc) that can be invoked by SrcLaunch applications, services, tasks and pipelines. 

[![Issues](https://img.shields.io/github/issues/srclaunch/actions?label=Issues)](https://github.com/srclaunch/actions/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/actions?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/actions) [![Build](https://github.com/srclaunch/actions/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/actions/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/actions?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/actions)

---

### [@srclaunch/cli](https://github.com/srclaunch/cli)

![Stars](https://img.shields.io/github/stars/srclaunch/cli?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/cli?style=social)

CLI tool for managing SrcLaunch Workspaces and Projects.


[![Issues](https://img.shields.io/github/issues/srclaunch/cli?label=Issues)](https://github.com/srclaunch/cli/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/cli?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/cli) [![Build](https://github.com/srclaunch/cli/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/cli/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/cli?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/cli)

---

### [@srclaunch/core-api-server](https://github.com/srclaunch/core-api-server)

![Stars](https://img.shields.io/github/stars/srclaunch/core-api-server?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/core-api-server?style=social)

Utilities for managing a CoreAPI server instance.

[![Issues](https://img.shields.io/github/issues/srclaunch/core-api-server?label=Issues)](https://github.com/srclaunch/core-api-server/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/core-api-server?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/core-api-server) [![Build](https://github.com/srclaunch/core-api-server/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/ccore-api-serverore-api-server/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/cli?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/core-api-server)

---

 ### [@srclaunch/cx](https://github.com/srclaunch/cx)

![Stars](https://img.shields.io/github/stars/srclaunch/cx?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/cx?style=social)

Customer Experience and support components and libraries.

[![Issues](https://img.shields.io/github/issues/srclaunch/cx?label=Issues)](https://github.com/srclaunch/cx/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/cx?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/cx) [![Build](https://github.com/srclaunch/cx/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/cx/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/cx?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/cx)

---

### [@srclaunch/data-client](https://github.com/srclaunch/data-client)

![Stars](https://img.shields.io/github/stars/srclaunch/data-client?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/data-client?style=social)

Sequelize client wrapper for easily performing CRUD operations.

[![Issues](https://img.shields.io/github/issues/srclaunch/data-client?label=Issues)](https://github.com/srclaunch/data-client/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/data-client?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/data-client) [![Build](https://github.com/srclaunch/cldata-clienti/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/data-client/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/data-client?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/data-client)

---

### [@srclaunch/dx](https://github.com/srclaunch/dx)

![Stars](https://img.shields.io/github/stars/srclaunch/dx?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/dx?style=social)

Re-usable DX tooling configuration (linting, testing, build, etc) for various project types and environments.

[![Issues](https://img.shields.io/github/issues/srclaunch/dx?label=Issues)](https://github.com/srclaunch/dx/issues) [![Build](https://github.com/srclaunch/dx/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/dx/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/dx?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/dx)

---

### [@srclaunch/exceptions](https://github.com/srclaunch/exceptions)

![Stars](https://img.shields.io/github/stars/srclaunch/exceptions?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/exceptions?style=social)


Exception handling and remediation utilities and helpers.

[![Issues](https://img.shields.io/github/issues/srclaunch/exceptions?label=Issues)](https://github.com/srclaunch/exceptions/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/exceptions?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/exceptions) [![Build](https://github.com/srclaunch/exceptions/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/exceptions/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/exceptions?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/exceptions)

---

### [@srclaunch/http-client](https://github.com/srclaunch/http-client)

![Stars](https://img.shields.io/github/stars/srclaunch/http-client?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/http-client?style=social)

HTTP client wrapper around Axios.

[![Issues](https://img.shields.io/github/issues/srclaunch/http-client?label=Issues)](https://github.com/srclaunch/http-client/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/http-client?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/http-client) [![Build](https://github.com/srclaunch/http-client/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/http-client/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/http-client?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/http-client)

---

### [@srclaunch/http-server](https://github.com/srclaunch/http-server)

![Stars](https://img.shields.io/github/stars/srclaunch/http-server?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/http-server?style=social)

HTTP server wrapper around Express.

[![Issues](https://img.shields.io/github/issues/srclaunch/http-server?label=Issues)](https://github.com/srclaunch/http-server/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/http-server?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/http-server) [![Build](https://github.com/srclaunch/http-server/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/http-server/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/http-server?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/http-server)

---

### [@srclaunch/i18n](https://github.com/srclaunch/i18n)

![Stars](https://img.shields.io/github/stars/srclaunch/i18n?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/i18n?style=social)

Internationalization utilities and helpers.

[![Issues](https://img.shields.io/github/issues/srclaunch/i18n?label=Issues)](https://github.com/srclaunch/i18n/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/i18n?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/i18n) [![Build](https://github.com/srclaunch/i18n/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/i18n/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/i18n?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/i18n)

---

### [@srclaunch/icons](https://github.com/srclaunch/icons)

![Stars](https://img.shields.io/github/stars/srclaunch/icons?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/icons?style=social)

React SVG component library.

[![Issues](https://img.shields.io/github/issues/srclaunch/icons?label=Issues)](https://github.com/srclaunch/icons/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/icons?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/icons) [![Build](https://github.com/srclaunch/icons/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/icons/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/icons?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/icons)

---

### [@srclaunch/knowledge](https://github.com/srclaunch/knowledge)

![Stars](https://img.shields.io/github/stars/srclaunch/knowledge?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/knowledge?style=social)

Documentation generation utilties for React component libraries, API blueprints, data or object models, and others.

[![Issues](https://img.shields.io/github/issues/srclaunch/knowledge?label=Issues)](https://github.com/srclaunch/knowledge/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/knowledge?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/knowledge) [![Build](https://github.com/srclaunch/knowledge/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/knowledge/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/knowledge?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/knowledge)

---

### [@srclaunch/logger](https://github.com/srclaunch/logger)

![Stars](https://img.shields.io/github/stars/srclaunch/logger?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/logger?style=social)

Logging utilities for both console logging and logging to cloud services. Integrates fully with all other SrcLaunch libraries.

[![Issues](https://img.shields.io/github/issues/srclaunch/logger?label=Issues)](https://github.com/srclaunch/logger/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/logger?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/logger) [![Build](https://github.com/srclaunch/logger/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/logger/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/logger?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/logger)

---

### [@srclaunch/node-environment](https://github.com/srclaunch/node-environment)

![Stars](https://img.shields.io/github/stars/srclaunch/node-environment?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/node-environment?style=social)

Node.js platform specific environment utilities.

[![Issues](https://img.shields.io/github/issues/srclaunch/node-environment?label=Issues)](https://github.com/srclaunch/node-environment/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/node-environment?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/node-environment) [![Build](https://github.com/srclaunch/node-environment/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/node-environment/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/node-environment?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/node-environment)

---

### [@srclaunch/pipelines](https://github.com/srclaunch/pipelines)

![Stars](https://img.shields.io/github/stars/srclaunch/pipelines?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/pipelines?style=social)

Build, deployment, and other pipeline configurations and utilities.

[![Issues](https://img.shields.io/github/issues/srclaunch/pipelines?label=Issues)](https://github.com/srclaunch/pipelines/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/pipelines?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/pipelines) [![Build](https://github.com/srclaunch/pipelines/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/pipelines/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/pipelines?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/pipelines)

---


### [@srclaunch/queues](https://github.com/srclaunch/queues)

![Stars](https://img.shields.io/github/stars/srclaunch/queues?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/queues?style=social)

Create tasks and assign to job queues for asynchronous long-running task handling.

[![Issues](https://img.shields.io/github/issues/srclaunch/queues?label=Issues)](https://github.com/srclaunch/queues/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/queues?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/queues) [![Build](https://github.com/srclaunch/queues/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/queues/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/queues?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/queues)

---

### [@srclaunch/react-hooks](https://github.com/srclaunch/react-hooks)

![Stars](https://img.shields.io/github/stars/srclaunch/react-hooks?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/react-hooks?style=social)

React hooks used in AppLab applications

[![Issues](https://img.shields.io/github/issues/srclaunch/react-hooks?label=Issues)](https://github.com/srclaunch/react-hooks/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/react-hooks?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/react-hooks) [![Build](https://github.com/srclaunch/react-hooks/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/react-hooks/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/react-hooks?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/react-hooks)

---

### [@srclaunch/secrets](https://github.com/srclaunch/secrets)

![Stars](https://img.shields.io/github/stars/srclaunch/secrets?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/secrets?style=social)

Secret management and retrieval.

[![Issues](https://img.shields.io/github/issues/srclaunch/secrets?label=Issues)](https://github.com/srclaunch/secrets/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/secrets?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/secrets) [![Build](https://github.com/srclaunch/secrets/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/secrets/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/secrets?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/secrets)

---

### [@srclaunch/themes](https://github.com/srclaunch/themes)

![Stars](https://img.shields.io/github/stars/srclaunch/themes?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/themes?style=social)


UI themes library

[![Issues](https://img.shields.io/github/issues/srclaunch/themes?label=Issues)](https://github.com/srclaunch/themes/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/themes?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/themes) [![Build](https://github.com/srclaunch/themes/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/themes/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/themes?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/themes)

---

### [@srclaunch/transform](https://github.com/srclaunch/transform)

![Stars](https://img.shields.io/github/stars/srclaunch/transform?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/transform?style=social)

Utilities for transforming data from one type to another

[![Issues](https://img.shields.io/github/issues/srclaunch/transform?label=Issues)](https://github.com/srclaunch/transform/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/transform?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/transform) [![Build](https://github.com/srclaunch/transform/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/transform/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/transform?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/transform)

---

### [@srclaunch/types](https://github.com/srclaunch/types)

![Stars](https://img.shields.io/github/stars/srclaunch/types?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/types?style=social)

TypeScript definitions for SrcLaunch workspaces, projects, apps and services.

[![Issues](https://img.shields.io/github/issues/srclaunch/types?label=Issues)](https://github.com/srclaunch/types/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/types?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/types) [![Build](https://github.com/srclaunch/types/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/types/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/types?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/types)

---

### [@srclaunch/ui](https://github.com/srclaunch/ui)

![Stars](https://img.shields.io/github/stars/srclaunch/ui?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/ui?style=social)

Full featured, React component library.

[![Issues](https://img.shields.io/github/issues/srclaunch/ui?label=Issues)](https://github.com/srclaunch/ui/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/ui?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/ui) [![Build](https://github.com/srclaunch/ui/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/ui/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/ui?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/ui)

---

### [@srclaunch/validation](https://github.com/srclaunch/validation)

![Stars](https://img.shields.io/github/stars/srclaunch/validation?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/validation?style=social)

Form/value validation library.

[![Issues](https://img.shields.io/github/issues/srclaunch/validation?label=Issues)](https://github.com/srclaunch/validation/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/validation?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/validation) [![Build](https://github.com/srclaunch/validation/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/validation/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/validation?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/validation)

---

### [@srclaunch/web-application-state](https://github.com/srclaunch/web-application-state)

![Stars](https://img.shields.io/github/stars/srclaunch/web-application-state?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/web-application-state?style=social)

Redux state implementation and utilities.

[![Issues](https://img.shields.io/github/issues/srclaunch/web-application-state?label=Issues)](https://github.com/srclaunch/web-application-state/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/web-application-state?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/web-application-state) [![Build](https://github.com/srclaunch/web-application-state/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/web-application-state/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/web-application-state?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/web-application-state)

---

### [@srclaunch/web-environment](https://github.com/srclaunch/web-environment)

![Stars](https://img.shields.io/github/stars/srclaunch/web-environment?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/srclaunch/web-environment?style=social)

Web browser environment specific utilities and helpers.

[![Issues](https://img.shields.io/github/issues/srclaunch/web-environment?label=Issues)](https://github.com/srclaunch/web-environment/issues) [![Coveralls](https://img.shields.io/coveralls/github/srclaunch/web-environment?label=Test%20Coverage)](https://coveralls.io/github/srclaunch/web-environment) [![Build](https://github.com/srclaunch/web-environment/actions/workflows/publish.yml/badge.svg)](https://github.com/srclaunch/web-environment/actions/workflows/publish.yml) [![npms.io (final)](https://img.shields.io/npms-io/final-score/@srclaunch/web-environment?label=NPMS%20Score)](https://npms.io/search?q=@srclaunch/web-environment)

