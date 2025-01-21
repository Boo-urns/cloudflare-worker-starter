# Cloudflare Worker Starter

## Overview

This project is a starter template for building applications using Cloudflare Workers. It leverages modern tools and practices to streamline development and deployment.

## Key Features

- **Conventional Commits**: We use conventional commits to maintain a clean and structured commit history. This helps in automating the versioning and changelog generation processes.

- **GitHub Actions**: Automated workflows are set up using GitHub Actions to deploy the Cloudflare Worker seamlessly. Every push to the main branch triggers a deployment, ensuring that the latest changes are always live.

- **Cloudflare Workers**: The core of this project is built on Cloudflare Workers, allowing you to run serverless applications at the edge, close to your users.

## Getting Started

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Boo-urns/cloudflare-worker-starter.git
   cd cloudflare-worker-starter
   ```

2. **Install Dependencies**:
   We use PNPM for package management. Install it globally if you haven't already:

   ```bash
   npm install -g pnpm
   pnpm install
   ```

3. **Development**:
   Start the development server:

   ```bash
   pnpm dev
   ```

   Open your browser at `http://localhost:8787` to see your worker in action.

4. **Deployment**:
   Deploy your worker by creating a PR.
   - Setup a couple variables in Github
     - `CLOUDFLARE_API_TOKEN` and `CLOUDFLARE_ACCOUNT_ID` You should be able to create the API token for default workers setting in Cloudflare.
     - `GH_TOKEN` push access to repo.

## Additional Resources

- **Cloudflare Workers Documentation**: Learn more about building with Cloudflare Workers [here](https://developers.cloudflare.com/workers/).
- **Conventional Commits**: Understand the conventional commits specification [here](https://www.conventionalcommits.org/).

## Contributing

We welcome contributions! Please follow the conventional commit guidelines and ensure all tests pass before submitting a pull request.
