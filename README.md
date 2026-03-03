# GaiterGuard Documentation

This repository contains the documentation for GaiterGuard, an intercepting API gateway that enforces human-in-the-loop authorization for autonomous AI agents.

## About GaiterGuard

GaiterGuard ensures agents never hold production credentials and high-impact actions require explicit human approval through an out-of-band dashboard. The trust boundary is enforced by the gateway — not by the agent.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview the documentation locally:

```bash
npm i -g mint
```

Run the following command at the root of your documentation:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Changes are deployed to production automatically after pushing to the main branch via the Mintlify GitHub app.

## Documentation structure

- **Get Started** - Introduction, quickstart, and installation guides
- **Core Concepts** - Architecture, security model, risk assessment, and approval flow
- **Guides** - Deployment, configuration, and agent integration
- **API Reference** - Complete API documentation for all endpoints

## Need help?

- [GaiterGuard GitHub Repository](https://github.com/Shashank-H/gaiter-gaurd)
- [Mintlify Documentation](https://mintlify.com/docs)
