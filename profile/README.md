# SrcLaunch

SrcLaunch is a platform built with the goal of eliminating repetitive software engineering tasks so engineers can focus on releasing features. 

---

## Features

###### Feature Statuses
| Icon | Status | Description |
|:----:|:-------|:------------|
| 💡 | Idea | Idea for a feature that needs requirement gathering and validation.|
| 🚧 | In-Progress | Feature with defined specs that is currently being worked on.|
| ✅ | Complete | Feature whose requirements have been met, and has been integrated into the release.

#### DX

Developer Experience features that help in configuring the development environment around best practices for the specific platform or build target. 

| Feature | Sub-features | Status | Description |
|:--------|:-------------|:------:|:------------|
| **Linting** | | 🚧 | Linter configurations for specific project types and targets.|
||Commitlint| 🚧 |
||ESLint| ✅ ||
||Prettier| ✅ ||
||Stylelint| ✅ ||
| **Testing** | ||
|| Ava | ✅ ||
|| Jest | ✅ ||
| **Static Typing** || ✅ |  |
||TypeScript| ✅ ||
    
---

#### Core Objects

Core Objects are business-case specific custom objects that make up the data layer of a SrcLaunch application or service.

| Feature | Sub-features | Status | Description |
|:--------|:-------------|:------:|:------------|
| **Data Modeling** | | ✅ | ESLint, Stylelint, Prettier |
| **Library Generation** | | ✅ | Convenience libraries for performing CRUD operations on Core Objects.
||`core-api`| ✅ | CoreAPI server configured with CRUD endpoints for Core Objects.
||`http-client`| ✅ | Instance of HttpClient from `@srclaunch/http-client` with CRUD request endpoints configured for the CoreAPI.
||`redux-state`| ✅ | Redux State and actions for managing Core Objects.
||`sequelize-models`| ✅ | Sequelize model definitions.
||`types`| ✅ | TypeScript type definitions for Core Objects.

#### Infrastructure

| Feature | Sub-features | Status | Description |
|:--------|:-------------|:------:|:------------|

#### Logging

| Feature | Sub-features | Status | Description |
|:--------|:-------------|:------:|:------------|

#### Logging

| Feature | Sub-features | Status | Description |
|:--------|:-------------|:------:|:------------|

--- 

## Libraries

##### Stability

| Icon | Name | Description |
|:----:|:-----------|:-----------|
| 🔴 | Broken | Cannot be used at the present time.
| 🟠 | Unstable | Can be used, but some features may be missing or don't function correctly. 
| 🟢 | Stable | Stable and follows semantic versioning guidelines.


---

### [@srclaunch/a11y](https://github.com/srclaunch/a11y)

Accessibility utilities and helpers.

**Stability:** 🔴 Broken

---

### [@srclaunch/actions](https://github.com/srclaunch/actions)

Actions (send an email, submit a form, create a record, etc) that can be invoked by SrcLaunch applications, services, tasks and pipelines. 

**Stability:** 🟢 Stable

---

### [@srclaunch/analytics](https://github.com/srclaunch/analytics)

Track user interactions and behavior.

**Stability:** 🔴 Concept

---
### [@srclaunch/cli](https://github.com/srclaunch/cli)

CLI tool for managing SrcLaunch Workspaces and Projects.

**Stability:** 🟢 Stable
**Todo:**
  - [ ] Generate models RTK Query bindings
  
---

### [@srclaunch/core-api-server](https://github.com/srclaunch/core-api-server)

Utilities for managing a CoreAPI server instance.

**Stability:** 🟢 Stable

---

### [@srclaunch/cx](https://github.com/srclaunch/cx)

Customer Experience and support components and libraries.

**Stability:** 🔴 Broken

---

### [@srclaunch/data-client](https://github.com/srclaunch/data-client)

Sequelize client wrapper for easily performing CRUD operations.

**Stability:** 🟢 Stable

---

### [@srclaunch/dx](https://github.com/srclaunch/dx)

Re-usable development environment configurations (linting, testing, build, etc) for various project types and environments.

**Stability:** 🟢 Stable

---

### [@srclaunch/exceptions](https://github.com/srclaunch/exceptions)

Exception handling and remediation utilities and helpers.

**Stability:** 🟢 Stable

---

### [@srclaunch/http-client](https://github.com/srclaunch/http-client)

HTTP client wrapper around Axios.

**Stability:** 🟢 Stable
**Todo:**
  * Migrate to RTK Query 

---

### [@srclaunch/http-server](https://github.com/srclaunch/http-server)

HTTP server wrapper around Express.

**Stability:** 🟢 Stable

---

### [@srclaunch/i18n](https://github.com/srclaunch/i18n)

Internationalization utilities and helpers.

**Stability:** 🟢 Stable

---

### [@srclaunch/icons](https://github.com/srclaunch/icons)

React SVG component library.

**Stability:** 🟢 Stable

---

### [@srclaunch/knowledge](https://github.com/srclaunch/knowledge)

Documentation generation utilties for React component libraries, API blueprints, data or object models, and others.

**Stability:** 🔴 Broken

---

### [@srclaunch/logger](https://github.com/srclaunch/logger)

Logging utilities for both console logging and logging to cloud services. Integrates fully with all other SrcLaunch libraries.

**Stability:** 🟢 Stable

---

### [@srclaunch/node-environment](https://github.com/srclaunch/node-environment)

Node.js platform specific environment utilities.

**Stability:** 🟢 Stable

---

### [@srclaunch/pipelines](https://github.com/srclaunch/pipelines)

Build, deployment, and other pipeline configurations and utilities.

**Stability:** 🔴 Broken

---


### [@srclaunch/queues](https://github.com/srclaunch/queues)

Create tasks and assign to job queues for asynchronous long-running task handling.

**Stability:** 🟢 Stable

---

### [@srclaunch/react-hooks](https://github.com/srclaunch/react-hooks)

Useful React hooks library.

**Stability:** 🟢 Stable

---

### [@srclaunch/secrets](https://github.com/srclaunch/secrets)

Secret management and retrieval.

**Stability:** 🟠 Unstable

---

### [@srclaunch/themes](https://github.com/srclaunch/themes)

UI themes library

**Stability:** 🟢 Stable

---

### [@srclaunch/transform](https://github.com/srclaunch/transform)

Utilities for transforming data from one type to another

**Stability:** 🟢 Stable

---

### [@srclaunch/types](https://github.com/srclaunch/types)

TypeScript definitions for SrcLaunch workspaces, projects, apps and services.
**Stability:** 🟢 Stable

### [@srclaunch/ui](https://github.com/srclaunch/ui)

Full featured, React component library.

**Stability:** 🟢 Stable

---

### [@srclaunch/validation](https://github.com/srclaunch/validation)

Form/value validation library.

**Stability:** 🟢 Stable

---

### [@srclaunch/web-application-state](https://github.com/srclaunch/cli)

Redux state definitions and utilities.

**Stability:** 🟢 Stable

---

### [@srclaunch/web-environment](https://github.com/srclaunch/cli)

Web browser environment specific utilities and helpers.

**Stability:** 🟢 Stable

