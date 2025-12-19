# CI/CD Pipeline Demo Project

## Overview

This project demonstrates a complete CI/CD (Continuous Integration and Continuous Deployment) pipeline implementation with a React frontend. It includes automated testing, building, and deployment workflows, along with interactive components that showcase successful CI/CD operation.

## Features
- **Automated CI/CD Pipeline**

    - GitHub Actions workflows for testing and deployment

    - Auto-merge functionality for valid pull requests

    - Deployment status badges

- **Interactive Demo Components**

    - CI/CD success visualization with animated popups

    - Comment section with real-time updates

    - Visual feedback for pipeline status

- **Modern Tech Stack**

    - React 19 with TypeScript

    - Tailwind CSS for styling

    - Framer Motion for animations

    - GitHub Actions for automation

## Getting Started
### Prerequisites
- Node.js (v16 or higher)

- npm (v8 or higher) or yarn

- GitHub account

### Installation
**Clone the repository:**
```
git clone https://github.com/your-username/ci-cd-demo.git
cd ci-cd-demo
```

**Install dependencies:**

```
npm install
# or
yarn install
```
Start the development server:

```
npm run dev
```
## CI/CD Workflows
This project includes two main GitHub Actions workflows:

1. Auto Merge (/.github/workflows/automerge.yml)

    -   Automatically merges PRs that contain index.html

    -   Requires no manual approvals

    -   Uses squash merge strategy

2. Build & Deploy (/.github/workflows/deploy.yml)

    -    Runs on push to main branch



## Builds production bundle
```
npm run build
```

## Deploys to GitHub Pages

Project Structure
```
ci-cd-ga/
├── .github/
│   └── workflows/          
│       ├── ci-cd-vercel.yaml
├── assets/
├── index.html
├── ci-cd.svg
└── README.md
```
## How It Works
**Development:** Developers work on feature branches

**Pull Request:** When a PR is opened:

- CI checks run automatically

- Valid PRs (with index.html) are auto-merged

**Deployment:** Merged code triggers deployment

**Verification:** The Testing component visually confirms successful CI/CD

## Contributing
Contributions are welcome! Please follow these steps:

- Fork the repository

- Create a feature branch (`git checkout -b feature/your-feature`)

- Commit your changes (`git commit -m 'Add some feature'`)

- Push to the branch (`git push origin feature/your-feature`)

- Open a Pull Request

## License
This project is licensed under the [MIT License](./LICENSE.md) - see the LICENSE file for details.
