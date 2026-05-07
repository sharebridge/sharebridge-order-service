# sharebridge-order-service

> Order management microservice

## Overview

This repository contains the **Order Management Service** - the core business logic for creating, tracking, and fulfilling charitable food orders.

**Key Responsibilities:**
- 📦 Order creation and validation
- 🔄 Order state management (pending, confirmed, in-progress, delivered, cancelled)
- 🗺️ Location safety verification (integration with AI Safety Service)
- 📸 Photo verification workflow
- 🚚 Delivery tracking and status updates
- 💰 Price calculation and vendor selection
- ⏱️ Order timeout and retry logic
- 📊 Order history and analytics
- 🔁 Pledge pool and crowdfunding order coordination

**Technology Stack:** Node.js with NestJS or Python with FastAPI

For overall project context, see the [main ShareBridge repository](https://github.com/sharebridge/sharebridge).

## AI-Powered Development

This project uses AI-assisted development. Code and documentation are generated through prompts stored in the /prompting folder.

## Prompting Folder

The prompting/ folder contains:
- All prompts used to generate code for this component
- Feature requests and requirements in natural language
- AI model instructions and specifications
- Prompt templates for future development

**Transparency:** Anyone can see how features were specified and generated.  
**Reproducibility:** Use similar prompts to regenerate or modify components.  
**Collaboration:** Non-coders can contribute by writing or refining prompts.

## Repository Status

🚧 **Status:** Initial Setup  
📅 **Date:** January 9, 2026

## Getting Started

> Coming soon - Development setup instructions

## Contributing

See the [main repository's CALL_FOR_CONTRIBUTORS.md](https://github.com/sharebridge/sharebridge/blob/main/development/CALL_FOR_CONTRIBUTORS.md) for:
- How to contribute (technical and non-technical)
- Joining GitHub Discussions
- Submitting prompts and feature ideas

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Part of the [ShareBridge](https://github.com/sharebridge/sharebridge) ecosystem
