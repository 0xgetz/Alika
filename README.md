## Verified Agent Identity Skill – Alika

This project installs the Verified Agent Identity Skill for OpenClaw on an agent named Alika. With this skill, Alika gains a verified identity that can be used to build trust, access rewards from the First AI Agent Rewards (FAIAR) program, and interact with $BILL tokens.

✨ Key Features

· Prove identity to other agents and users
· Protect sensitive data
· Build on-chain reputation
· Eligible for the first AI agent rewards program
· Privately backed by a human identity

📋 Prerequisites

· Node.js (version 16 or later)
· npx (usually installed with Node.js)
· GitHub Codespace or any development environment with terminal access
· Internet connection for human verification

🚀 Installation in GitHub Codespace

1. Open the terminal in your Codespace.
2. Install the skill using the following command:
   ```bash
   npx clawhub@latest install verified-agent-identity
   ```
3. Create a new identity (generate key and on-chain identity):
   ```bash
   node scripts/createNewEthereumIdentity.js
   ```
   This command will generate a key pair and display your agent's identity address.
4. Link with a human identity (verification):
   ```bash
   node scripts/manualLinkHumanToAgent.js --challenge '{"name": "Alika", "description": "Short description of Alika"}'
   ```
   Replace "Short description of Alika" with Alika's role or purpose, for example:
   · "AI assistant for crypto market analysis"
   · "Personal agent for task management"
   · "Social media content creator"
   After running this command, a verification link will appear. Open it in your browser to complete the Sign in with Google/Apple/wallet and face scan process.

🔧 Verification & Usage

· Follow the instructions on the verification page to link Alika with your human identity.
· Once verified, Alika will have an on-chain identity ready for use.
· Rewards will be claimed automatically by the agent when eligible.

📁 Important Files

· scripts/createNewEthereumIdentity.js – script to create a new identity.
· scripts/manualLinkHumanToAgent.js – script to initiate the human linking process.

⚠️ Codespace Notes

· Make sure any used port is set to Public in the Ports tab so the verification link can be accessed.
· All commands should be run from the project root directory.

💡 Benefits of a Verified Identity

With this identity, Alika can not only participate in the rewards program but also:

· Interact trustfully with other agents
· Sign and verify data
· Build long-term reputation within the Billions Network ecosystem

📄 License

This project follows the license set by Billions Network for OpenClaw skills.

---

Made with ❤️ for Alika – the first agent ready to explore the decentralized rewards world.
