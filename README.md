# Documentation Modernization POC

## Overview

This repository contains a Docusaurus-based Proof of Concept (POC) to evaluate a modern documentation platform with support for versioning, search, theming, AI integration, and Docs-as-Code workflows.

## Tech Stack

* Docusaurus
* React
* MDX
* Node.js
* npm
* GitHub Actions / GitLab CI/CD
* Elasticsearch (Evaluation)
* Ollama (AI/RAG Evaluation)

## Features

* Modern documentation experience
* Light/Dark theme support
* Documentation versioning
* Full-text search
* MDX-based content authoring
* Git-based review and publishing workflow
* AI-assisted documentation exploration (POC)

## Project Structure

```text
docs/               # Documentation content
src/                # Custom React components and pages
static/             # Static assets
versioned_docs/     # Versioned documentation
blog/               # Release notes and announcements
```

## Local Development

### Prerequisites

* Node.js 20+
* npm 10+

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run start
```

The site will be available at:

```text
http://localhost:3000
```

### Build for Production

```bash
npm run build
```

### Serve Production Build

```bash
npm run serve
```

## Goals

* Evaluate Docusaurus as an alternative documentation platform
* Assess migration feasibility from MadCap Flare
* Validate versioning, search, and customization capabilities
* Explore AI-powered documentation assistance
* Demonstrate a scalable Docs-as-Code workflow

## License

This repository is intended for evaluation and proof-of-concept purposes.
