
# Next.js Saas Boilerplate (Coventech)

A production-ready template for building enterprise applications with Next.js. This boilerplate provides a solid foundation with carefully selected technologies and ready-to-go infrastructure to help you develop high-quality applications efficiently.

## Motivation

This is **Co-Ventech-next-saas-boilerplate**, a customized Next.js boilerplate for Coventech's enterprise applications. It provides strategic simplicity for enterprise teams with a streamlined foundation and high-impact features to maximize developer productivity and accelerate time-to-market.



This repository has been adapted for use by Coventech. Replace or extend this README with project-specific documentation and internal links as needed.

## Documentation

Project-specific documentation should be added under your organization's docs or internal wiki. Remove or update links to external vendor docs as needed.

## Integrated features

### Boilerplate
With this template you will get all the boilerplate features included:

* [Next.js 15](https://nextjs.org/) - Performance-optimized configuration using App Directory
* [Tailwind CSS v4](https://tailwindcss.com/) - Utility-first CSS framework for efficient UI development
* [ESlint 9](https://eslint.org/) and [Prettier](https://prettier.io/) - Code consistency and error prevention
* [Corepack](https://github.com/nodejs/corepack) & [pnpm](https://pnpm.io/) as the package manager - For project management without compromises 
* [Strict TypeScript](https://www.typescriptlang.org/) - Enhanced type safety with carefully crafted config and [ts-reset](https://github.com/total-typescript/ts-reset) library
* [GitHub Actions](https://github.com/features/actions) - Pre-configured workflows including bundle size and performance tracking
* Perfect Lighthouse score - Optimized performance metrics
* [Bundle analyzer](https://www.npmjs.com/package/@next/bundle-analyzer) - Monitor and manage bundle size during development
* Testing suite - [Vitest](https://vitest.dev), [React Testing Library](https://testing-library.com/react), and [Playwright](https://playwright.dev/) for comprehensive testing
* [Storybook](https://storybook.js.org/) - Component development and documentation
* Advanced testing - Smoke and acceptance testing capabilities
* [Conventional commits](https://www.conventionalcommits.org/) - Standardized commit history management
* [Observability](https://opentelemetry.io/) - Open Telemetry integration
* [Absolute imports](https://nextjs.org/docs/advanced-features/module-path-aliases) - Simplified import structure
* [Health checks](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/) - Kubernetes-compatible monitoring
* [Radix UI](https://www.radix-ui.com/) - Headless components for customization
* [CVA](http://cva.style/) (Class Variance Authority) - Consistent design system creation
* [Renovate BOT](https://www.whitesourcesoftware.com/free-developer-tools/renovate) - Automated dependency and security updates
* [Patch-package](https://www.npmjs.com/package/patch-package) - External dependency fixes without compromises
* Component relationship tools - Graph for managing coupling and cohesion
* [Semantic Release](https://github.com/semantic-release/semantic-release) - Automated changelog generation
* [T3 Env](https://env.t3.gg/) - Streamlined environment variable management

### Infrastructure & deployments

#### Vercel

Easily deploy your Next.js app with [Vercel](https://vercel.com/) by clicking the button below:

[![Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/coventech/next-enterprise)

#### Custom cloud infrastructure

This boilerplate offers infrastructure as code (IaC) solutions built with Terraform, designed specifically for deploying Next.js applications at Coventech.

Learn more in your organization's docs about deployments and quickstarts. Update the link placeholder in this README when you have internal docs.

#### Available cloud providers and theirs features:

* **AWS (Amazon Web Services)**
  * Automated provisioning of AWS infrastructure
  * Scalable & secure setup using:
     * VPC - Isolated network infrastructure
     * Elastic Container Service (ECS) - Container orchestration
     * Elastic Container Registry (ECR) - Container image storage
     * Application Load Balancer - Traffic distribution
     * S3 + CloudFront - Static asset delivery and caching
     * AWS WAF - Web Application Firewall protection
     * Redis Cluster - Caching
  * CI/CD ready - Continuous integration and deployment pipeline

*... more coming soon*

### Team & maintenance

**Co-Ventech-next-saas-boilerplate** is maintained by [Coventech](https://github.com/coventech).

For questions, support, or contributions, please reach out to the Coventech development team.

[docs]: #
