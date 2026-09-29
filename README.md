# Ant Rodgers

Founder and developer building e-commerce and warehouse systems in **PHP/Laravel**, using an AI-native engineering workflow.

I've run a UK multichannel retailer ([The Protein Pick and Mix](https://proteinpickandmix.co.uk)) for 13 years and now a 3PL fulfilment business ([The BOXD Office](https://boxdoffice.co.uk)), so the software I build comes from real operational experience rather than a spec.

## Currently building: BXDOFF (private repo)

A multi-tenant warehouse and order management SaaS for UK 3PLs and multichannel D2C brands, where the 3PL and its clients share one system.

- **Integrations:** Shopify (public app), BigCommerce, TikTok Shop, WooCommerce
- **Warehouse:** goods-in, bin locations, stock ledger, barcode pick and pack, returns, purchase orders
- **Client portal:** live stock, orders, sales, profit and store connection health
- **Security and privacy:** strict tenant isolation, field-level encryption, GDPR export and erasure, 2FA and passkeys
- **Scale:** built solo in about 11 weeks, with ~2,700 automated tests, 167 merged PRs and 71 domain models

> **Development Status:** Currently in local dev.

## How I build

I direct development through Claude Code as a managed multi-agent workflow: a lead model/orchestrator for planning and high-risk design, a lighter model for implementation, and a read-only multi-model adversarial review agent that audits every change. Every phase ships with tests and nothing merges until the full suite, static analysis and formatting pass in CI.

## Stack

PHP 8.5 · Laravel 13 · Livewire 4 · Alpine.js · Tailwind CSS 4 · PostgreSQL · Pest · Playwright · PHPStan · GitHub Actions · Laravel Cloud

## Earlier

- Contributor to the Concrete5 open-source CMS core (merged pull requests)
- Head of Digital at an advertising agency, building websites, apps and campaigns for brands including Ferrero, Kellogg's and Unilever

## Contact

[LinkedIn](https://www.linkedin.com/in/ant-rodgers/) · ant@antrodgers.co.uk
