# Browsers (browsers)
An index and topic collection covering programmable browsers, headless browser engines, and browser-automation APIs. The Browsers topic focuses on the browser execution surface — the runtime where pages are loaded, JavaScript is evaluated, and interactions are scripted — including local libraries like Puppeteer, Playwright, and Selenium, as well as managed browser-as-a-service platforms used for automation, data extraction, agentic web tasks, and cross-browser testing. This collection is distinct from web scraping and pure test-runner topics; it emphasizes the browser instance, session, and navigation surface that other automation, scraping, and AI-agent capabilities build on top of.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Headless Browser, Browser Automation, Web Automation, Browser-as-a-Service, WebDriver, Browser Testing

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Browser Session Schema](https://raw.githubusercontent.com/api-evangelist/browsers/refs/heads/main/json-schema/browsers-browser-session-schema.json)
- [JSONSchema - Navigation Action Schema](https://raw.githubusercontent.com/api-evangelist/browsers/refs/heads/main/json-schema/browsers-navigation-action-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/browsers/refs/heads/main/json-ld/browsers-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/browsers/refs/heads/main/vocabulary/browsers-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Headless Browser Execution | Programmable browser runtimes like Chromium, WebKit, and Gecko driven without a visible UI for automated navigation, rendering, and DOM interaction. |
| Browser Automation Libraries | Client libraries like Puppeteer, Playwright, and Selenium that expose a high-level API for controlling browser sessions, pages, frames, and inputs. |
| Browser-as-a-Service | Managed cloud platforms that provision pre-warmed browser instances over WebSocket, CDP, or HTTP so consumers do not have to host their own browser fleet. |
| Session and Profile Management | APIs for creating, persisting, and reusing browser sessions, cookies, localStorage, fingerprints, and authenticated profiles across runs. |
| Navigation and DOM Interaction | A consistent surface for navigating to URLs, waiting for selectors, clicking, typing, scrolling, evaluating JavaScript, and capturing rendered DOM state. |
| Network and Stealth Controls | Proxy routing, header and user-agent customization, request interception, and anti-bot evasion controls layered on top of the browser instance. |
| Capture and Artifact APIs | Endpoints for screenshots, full-page PDFs, HAR network logs, video recordings, and trace files generated from automated browser sessions. |
| Agent-Ready Browser Surfaces | AI-agent oriented interfaces, including Model Context Protocol servers and natural-language navigation, that expose a browser as a tool for LLMs. |

## Use Cases

| Name | Description |
|------|-------------|
| Automated Web Data Extraction | Drive a real browser to render JavaScript-heavy pages and extract structured data that static HTTP scraping cannot reach. |
| Cross-Browser End-to-End Testing | Run application tests against Chromium, Firefox, and WebKit on real or virtualized devices to validate behavior before release. |
| Synthetic Monitoring and Uptime Checks | Schedule scripted browser flows to continuously verify that critical user journeys remain functional in production. |
| Agentic Web Task Execution | Provide AI agents with a controlled browser session so they can complete multi-step tasks like form filling, booking, and research. |
| Visual and PDF Generation | Render web content to high-fidelity screenshots, social-share images, or PDF reports on demand via a managed browser API. |
| Authenticated Session Automation | Maintain logged-in browser profiles so automation can perform actions inside customer-account areas across runs. |
| Accessibility and Performance Audits | Execute Lighthouse, axe, and similar audits inside a real browser to track accessibility and performance regressions over time. |
| Legacy Application Robotics | Use browser automation as a UI-layer integration mechanism for systems that lack a usable API. |

## Integrations

| Name | Description |
|------|-------------|
| Playwright | Open-source browser automation library from Microsoft that drives Chromium, Firefox, and WebKit through a unified API. |
| Puppeteer | Node.js library from the Chrome team that controls headless Chromium via the Chrome DevTools Protocol. |
| Selenium | Long-standing browser automation suite built around WebDriver, used heavily for cross-browser end-to-end testing. |
| BrowserStack | Cloud browser and device platform providing real browsers and devices for automated and live cross-browser testing. |
| Bright Data Scraping Browser | Managed remote browser endpoint with built-in proxies and anti-bot infrastructure for large-scale automation. |
| Apify | Web automation platform whose Actors run Puppeteer and Playwright workloads at scale on managed infrastructure. |
| Browser Use | AI-agent oriented library that gives LLMs a controllable browser as a tool surface for autonomous web tasks. |
| Checkly | Synthetic monitoring platform that runs Playwright scripts on a schedule to validate production user journeys. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Browser Session Schema](json-schema/browsers-browser-session-schema.json)
- [Navigation Action Schema](json-schema/browsers-navigation-action-schema.json)

### JSON Structure

- [Browser Session Structure](json-structure/browsers-browser-session-structure.json)
- [Navigation Action Structure](json-structure/browsers-navigation-action-structure.json)

### JSON-LD

- [Browsers Context](json-ld/browsers-context.jsonld)

## Vocabulary

- [Browsers Vocabulary](vocabulary/browsers-vocabulary.yaml) — Unified taxonomy of browser-runtime resources, navigation actions, automation workflows, and personas across headless libraries and browser-as-a-service platforms

## Network

This index references the following programmable browser and browser-automation repositories:

- [AgentQL](https://github.com/api-evangelist/agentql)
- [Apify](https://github.com/api-evangelist/apify)
- [API Snap](https://github.com/api-evangelist/api-snap)
- [Appium](https://github.com/api-evangelist/appium)
- [Apple Safari](https://github.com/api-evangelist/apple-safari)
- [Bright Data](https://github.com/api-evangelist/bright-data)
- [Browser Use](https://github.com/api-evangelist/browser-use)
- [BrowserStack](https://github.com/api-evangelist/browserstack)
- [Checkly](https://github.com/api-evangelist/checkly)
- [Crawlee](https://github.com/api-evangelist/crawlee)
- [Cucumber](https://github.com/api-evangelist/cucumber)
- [Google Chrome](https://github.com/api-evangelist/google-chrome)
- [Microsoft Edge](https://github.com/api-evangelist/microsoft-edge)
- [Microsoft Playwright](https://github.com/api-evangelist/microsoft-playwright)
- [Playwright](https://github.com/api-evangelist/playwright)
- [Puppeteer](https://github.com/api-evangelist/puppeteer)
- [Scrapfly](https://github.com/api-evangelist/scrapfly)
- [ScrapingAnt](https://github.com/api-evangelist/scrapingant)
- [ScrapingBee](https://github.com/api-evangelist/scrapingbee)
- [Selenium](https://github.com/api-evangelist/selenium)
- [Servo](https://github.com/api-evangelist/servo)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
