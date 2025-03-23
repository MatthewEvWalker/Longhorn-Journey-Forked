# Longhorn-Journey

### Build Badges

<!-- * [![Next.js][Next.js]][Next-url] -->
* [![Astro][Astro-badge]][Astro-url]
* [![TypeScript][TypeScript]][TypeScript-url]
* [![Tailwind CSS][Tailwind]][Tailwind-url]
* [![pnpm][pnpm]][pnpm-url]

## Table of Contents
- [Concise Description](#concise-description)
- [Overview](#overview)
  - [Problem Statement](#problem-statement)
  - [Solution](#solution)
- [Key Features and Benefits](#key-features-and-benefits)
- [Target Audience](#target-audience)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation Steps](#installation-steps)
  - [Configuration Requirements](#configuration-requirements)
- [Architecture](#architecture)
  - [High-Level Architecture Overview](#high-level-architecture-overview)
  - [Key Components](#key-components)
  - [Design Principles](#design-principles)
- [Development Workflow](#development-workflow)
  - [Branch Naming Conventions](#branch-naming-conventions)
  - [Conventional Commits](#conventional-commits)
  - [Pull Request Process](#pr-process)
  - [Testing Expectations](#testing-expectations)
  - [Contribution Guidelines](#contribution-guidelines)
  - [Code of Conduct](#code-of-conduct)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [Deployment](#deployment)
- [Open Source License](#open-source-license)
- [Links](#links)


### Concise Description
Longhorn Journey is a web-based experience designed to guide new students through the history, traditions, and culture of the University of Texas at Austin.Longhorn Journey offers an engaging way to explore key campus landmarks, learn about important traditions, navigate academics, and understand what it means to be a Longhorn.


## Overview

### Problem Statement:
New students often struggle to adjust to university life, and getting familiar with campus traditions, culture, and key places can be overwhelming.

### Solution:
Longhorn Journey provides an interactive and engaging online experience that helps new students learn about the University of Texas at Austin’s history, important landmarks, and campus culture, making their transition easier and more fun.


### Key Features and Benefits
- Stories and media on Longhorn traditions, events, and history
- Information on academic resources, student orgs, and support services
- Guided onboarding paths for first-year and transfer students
- Built with accessibility, responsiveness, and scalability in mind

### Target Audience
- Incoming first-year students
- Transfer students
- Prospective students and families
- Orientation leaders and First Year Interest Group/ student mentors


## Getting Started 

### Prerequisites
1. Installations:
- [Astro](https://astro.build)
- [pnpm](https://pnpm.io)
- TypeScript 
- Git 

### Installation steps
```
git clone https://github.com/your-username/longhorn-journey.git
cd longhorn-journey
pnpm install
pnpm dev
```

### Configuration requirements
- TBD

## Architecture & High-level architecture overview
- Astro for frontend rendering (mostly static with dynamic islands if needed)
- Tailwind CSS for styling
- Markdown or CMS-driven content
- Vercel for deployment and hosting
### Key components
- TBD
### Design principles
- TBD

## Development Workflow
### Branch naming conventions + Conventional Commits
We follow the Conventional Commits specification for commit messages. This ensures a consistent commit history and enables automated versioning and changelog generation.

### Branch Naming Conventions 
```
<type>/<short-description>
```
Examples: 
- feature/{feature-name}
- fix/{bug-description}
- docs/{documentation-change}
### Commit Message
Follow this structure for commit messages
```
<type>(<scope>): <subject>
```
Where:
```type``` has one of the following:
- feat: New features
- fix: Bug fixes
- docs: Documentation changes
- style: Code formatting only
- refactor: Code changes without behavior change
- test: Adding or updating tests
- chore: Build process or tooling updates

### PR process
- Fork or branch from main
- Create a PR with a clear description
- Ensure checks pass (build, lint, test)
- Request review before merging

### Testing expectations
- Unit tests for UI components
- Integration tests for feature flows

### Contribution guidelines & Code of conduct reference
We welcome all to contribute! Please carefully read our [Contributing Guide](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) before getting started. All contributors must adhere to our Code of Conduct

## Available Scripts
-  ``pnpm dev``         # Start dev server
- ``pnpm build ``      # Build project for production
- ``pnpm preview ``    # Preview production build locally
- ``pnpm lint ``       # Lint codebase
- ``pnpm format ``     # Format code using Prettier

### Development commands
- TBD
### Building commands
- TBD
### Testing commands
- TBD
### Linting & formatting commands
- TBD

## Project Structure
- TBD
### Directory organization
### Key files and their purposes

## Deployment
### Environment information
- Hosted on [Vercel](https://vercel.com/)
### Deployment process
- Push changes to GitHub
- Vercel builds automatically from ``main`` branch
- Preview Deployments available on every PR
### Configuration details
- More details on [Astro Docs](https://docs.astro.build/en/guides/deploy/vercel/)

## Open Source License
### Usually MIT but choose as needed as some dependencies may require a different license

links:

[Astro-badge]: https://img.shields.io/badge/Astro-1e1e20?style=for-the-badge&logo=astro&logoColor=white  
[Astro-url]: https://astro.build

[Next.js]: https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/

[TypeScript]: https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white
[TypeScript-url]: https://www.typescriptlang.org/

[Tailwind]: https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white
[Tailwind-url]: https://tailwindcss.com/

[pnpm]: https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white
[pnpm-url]: https://pnpm.io/

[Bun]: https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white
[Bun-url]: https://bun.sh/