# Platform 2

A modern web platform built with Node.js and TypeScript.

## Getting Started

This project uses npm workspaces and Yarn for dependency management.

### Prerequisites

- Node.js (version 18 or higher)
- Yarn package manager

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd platform-2
   ```

2. Install dependencies:
   ```bash
   yarn install
   ```

### Development

The project uses Docker Compose for local development:

```bash
docker compose up
```

### Testing

- Unit tests: `.spec.ts` files
- Integration tests: `.integration.ts` files  
- End-to-end tests: `.e2e.ts` files

## Project Structure

- `evolutions/` - Project evolution documentation
- `fixtures/` - Test fixtures and sample data
- `.vscode/` - VS Code workspace configuration

## Deployment

This project uses Fly for deployments. Configuration is managed via `fly.toml`.

## License

[Add your license information here]
