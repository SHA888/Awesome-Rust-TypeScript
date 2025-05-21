# Awesome Rust + TypeScript Templates

A curated collection of full-stack templates for building modern web applications with Rust (backend) and TypeScript (frontend). This hub provides a set of reusable, production-ready templates combining popular frontend frameworks and databases, designed for native setups with optional Docker support.

Whether you're building a small prototype or an enterprise-grade app, these templates offer modular, performant solutions inspired by stacks like MERN, MEAN, and MEVN.

## ✨ Why Use These Templates?

- 🚀 **Rust Backend**: High-performance, type-safe backend with Axum for REST APIs.
- 🎨 **TypeScript Frontend**: Type-safe, modern frontend development with leading frameworks.
- 🗄️ **Flexible Databases**: Support for PostgreSQL, SQLite, and MongoDB to suit various use cases.
- 💻 **Native-First**: Easy local setup with optional Docker for containerized workflows.
- 🔄 **CI/CD Ready**: GitHub Actions for automated testing and linting.

## 🗂 Templates

Below are the eight full-stack templates, each tailored to a specific frontend framework and database combination. Choose the one that best fits your project needs.

### 🎯 RPRT (Rust, PostgreSQL, React, TypeScript)

- **Frontend**: React with TypeScript (Vite, Tailwind CSS)
- **Database**: PostgreSQL (relational)
- **Use Case**: General-purpose web apps, similar to MERN but with a robust relational database.
- **Repository**: [RPRT-template](https://github.com/SHA888/RPRT)
- **Inspired by**: MERN stack

### 🎨 RVST (Rust, SQLite, Vue.js, TypeScript)

- **Frontend**: Vue.js with TypeScript (Vite, Tailwind CSS)
- **Database**: SQLite (serverless, lightweight)
- **Use Case**: Small to medium apps or prototypes needing a simple, file-based database.
- **Repository**: [RVST-template](https://github.com/SHA888/RVST)
- **Inspired by**: Lightweight modern stacks

### ⚡ RSMT (Rust, MongoDB, Svelte, TypeScript)

- **Frontend**: Svelte with TypeScript (SvelteKit, Tailwind CSS)
- **Database**: MongoDB (NoSQL)
- **Use Case**: Modern, dynamic apps with a focus on performance and NoSQL flexibility.
- **Repository**: [RSMT-template](https://github.com/SHA888/RSMT)
- **Inspired by**: MERN stack with Svelte

### 🏢 RPAT (Rust, PostgreSQL, Angular, TypeScript)

- **Frontend**: Angular with TypeScript (Angular CLI, Tailwind CSS)
- **Database**: PostgreSQL (relational)
- **Use Case**: Enterprise-grade apps requiring structured frontend and robust database.
- **Repository**: [RPAT-template](https://github.com/SHA888/RPAT)
- **Inspired by**: MEAN stack

### 🔍 RMNT (Rust, MongoDB, Next.js, TypeScript)

- **Frontend**: Next.js with TypeScript (React-based, Tailwind CSS)
- **Database**: MongoDB (NoSQL)
- **Use Case**: SEO-friendly or dynamic apps with server-side rendering, closest to MERN.
- **Repository**: [RMNT-template](https://github.com/SHA888/RMNT)
- **Inspired by**: MERN stack

### 📝 RSAT (Rust, SQLite, Astro, TypeScript)

- **Frontend**: Astro with TypeScript (supports React/Vue/Svelte components, Tailwind CSS)
- **Database**: SQLite (serverless, lightweight)
- **Use Case**: Content-driven or static sites with flexible frontend components.
- **Repository**: [RSAT-template](https://github.com/SHA888/RSAT)
- **Inspired by**: Modern content-driven stacks

### 🎭 RMVT (Rust, MongoDB, Vue.js, TypeScript)

- **Frontend**: Vue.js with TypeScript (Vite, Tailwind CSS)
- **Database**: MongoDB (NoSQL)
- **Use Case**: Dynamic apps with a reactive frontend and NoSQL database, like MEVN.
- **Repository**: [RMVT-template](https://github.com/SHA888/RMVT)
- **Inspired by**: MEVN stack

### 🏛️ RMAT (Rust, MongoDB, Angular, TypeScript)

- **Frontend**: Angular with TypeScript (Angular CLI, Tailwind CSS)
- **Database**: MongoDB (NoSQL)
- **Use Case**: Enterprise apps with a structured frontend and NoSQL flexibility, like MEAN.
- **Repository**: [RMAT-template](https://github.com/SHA888/RMAT)
- **Inspired by**: MEAN stack

## 📊 Choosing a Template

| Template | Frontend | Database | Best For | Inspired By |
|----------|----------|----------|----------|-------------|
| RPRT | React | PostgreSQL | General-purpose web apps | MERN |
| RVST | Vue.js | SQLite | Small apps or prototypes | Lightweight stacks |
| RSMT | Svelte | MongoDB | Modern, dynamic apps | MERN |
| RPAT | Angular | PostgreSQL | Enterprise-grade apps | MEAN |
| RMNT | Next.js | MongoDB | SEO-friendly, dynamic apps | MERN |
| RSAT | Astro | SQLite | Content-driven or static sites | Modern stacks |
| RMVT | Vue.js | MongoDB | Reactive, NoSQL-driven apps | MEVN |
| RMAT | Angular | MongoDB | Enterprise NoSQL apps | MEAN |

## 🚀 Getting Started

1. **Browse Templates**: Review the descriptions above to choose a template.
2. **Clone a Template**:
   - Visit the template's GitHub repository (linked above)
   - Click "Use this template" to create a new repository, or clone directly:
     ```bash
     git clone https://github.com/<your-username>/<template-name>.git
     ```
3. **Follow Setup Instructions**: Each template's README.md provides detailed steps for:
   - Native setup (Rust backend, TypeScript frontend, database)
   - Optional Docker setup
   - Testing and deployment

## 📋 Prerequisites

All templates require:

- **Rust**: Stable version (install via [rustup](https://rustup.rs/))
  ```bash
  curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
  ```
- **Node.js**: v20 or higher (install via [nvm](https://github.com/nvm-sh/nvm) or [official installer](https://nodejs.org/))
- **Database**: 
  - PostgreSQL (RPRT, RPAT)
  - SQLite (RVST, RSAT)
  - MongoDB (RSMT, RMNT, RMVT, RMAT)
- **Git**: For cloning repositories
- **Optional**: Docker and Docker Compose for containerized setups

## 🤝 Contributing

We welcome contributions to improve this hub or the templates! To contribute:

1. Fork this repository
2. Create a feature branch: `git checkout -b feature-name`
3. Update README.md or add new resources
4. Commit changes: `git commit -m "Add feature"`
5. Push to the branch: `git push origin feature-name`
6. Open a pull request

For template-specific contributions, visit their respective repositories. Report issues or suggest improvements via GitHub Issues in this repository.

## 📄 License

This repository and all templates are licensed under the MIT License. See the `LICENSE` file in each template repository for details.
