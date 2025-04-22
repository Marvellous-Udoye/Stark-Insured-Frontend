🤝 Contributing to Stark Insured — Frontend
Welcome! 👋
We’re excited that you’re interested in contributing to the Stark Insured frontend — the gateway to our next-gen decentralized insurance platform built on StarkNet.

Your work will help users interact with tamper-proof, transparent, and automated insurance services, all powered by smart contracts and DAO governance.

📋 Table of Contents
Getting Started

Tech Stack

How to Contribute

Code Style & Guidelines

Pull Request Workflow

Commit Conventions

🚀 Getting Started
Fork the repository and clone your fork:

bash
Copy
Edit
git clone https://github.com/your-username/stark-insured-frontend.git
cd stark-insured-frontend
Install dependencies:

bash
Copy
Edit
npm install
Run the development server:

bash
Copy
Edit
npm run dev
Run tests:

bash
Copy
Edit
npm run test
⚙️ Tech Stack
Framework: Next.js / React

Styling: Tailwind CSS

State Management: Zustand / Context API

Wallets & Blockchain: StarkNet.js

Smart Contract Interaction: Cairo contracts via StarkNet Provider

API Layer: GraphQL / REST (depending on integration)

🧠 How to Contribute
🐛 Report Bugs – Open an issue with steps to reproduce.

✨ Request Features – Suggest ideas that align with decentralized insurance.

🛠 Submit Code – Fix a bug, add UI improvements, or implement a new component.

🧪 Write Tests – Help improve reliability with unit or integration tests.

🧼 Refactor – Help clean up or optimize existing components.

🖼️ Code Style & Guidelines
Use TypeScript for all components.

Follow component naming conventions (PascalCase).

Keep components modular and reusable.

Use Tailwind CSS utility classes for styling.

Use React Hooks and avoid class-based components.

For blockchain interactions, use starknet-react hooks or services from /lib/starknet.

🔁 Pull Request Workflow
Create a new branch:

bash
Copy
Edit
git checkout -b feat/your-feature-name
Push your changes:

bash
Copy
Edit
git push origin feat/your-feature-name
Open a PR to the main branch.

Follow the PR template and:

Link related issues

Provide screenshots or demos (if applicable)

Explain your change clearly

Wait for review and feedback from maintainers.

📝 Commit Conventions
Follow Conventional Commits to make commit messages clear and standardized.

Examples:

makefile
Copy
Edit
feat(ui): add claim submission form
fix: resolve wallet connection issue
chore: update dependency versions
refactor: simplify risk pool card logic
🙌 Final Notes
Contributions should align with our mission of trustless, community-governed insurance.

If you’re unsure about anything, feel free to open an issue or draft PR to discuss.

We encourage clean UI/UX, responsive design, and Web3 best practices.

Thanks for helping build the future of decentralized insurance! 💙

