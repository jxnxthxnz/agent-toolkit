# Changelog

All notable changes to this project will be documented in this file.
## [1.4.0] - 2025-07-25
### Added
- Added support for Amazon Bedrock via `paypal_agent_toolkit.bedrock`.
- Added a usage example in python/examples/bedrock demonstrating how to build and run a Bedrock-powered agent.

## [1.3.0] - 2025-04-23
### Added
- Added support for PayPal Disputes, Shipment tracking and Transactions Search.
- Improved and streamlined error logging mechanisms.

## [1.2.1] - 2025-04-23
### Added
- Included User-Agent telemetry data for enhanced tracking.
- Improved and streamlined error logging mechanisms.

## [1.2.0] - 2025-04-23
### Added
- Added CrewAI support via `crewai.PayPalToolkit.get_tools()` for seamless use with CrewAI agents.
- Refactored toolkit/shared code for improved structure and maintainability.

## [1.1.0] - 2025-04-21
### Added
- Added support for PayPal Invoices.
- Added LangChain integration with `langchain.PayPalToolkit.get_tools()` for LangChain agents.

## [1.0.1] - 2025-04-18
### Fixed
- Handled `204 No Content` response formatting issue.
- Fixed parameters formatting issue.

## [1.0.0] - 2025-04-18
### Added
- First release of `paypal-agent-toolkit`
