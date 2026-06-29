# Programmatic API Onboarding — Apigee

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for Apigee: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`apigee-api-auth.mjs`](apigee-api-auth.mjs)
- Run `node apigee-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/07/02/apigee-and-programmatic-api-onboarding/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
