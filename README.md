# 🚀 Awesome Agentic Skills: Revolutionizing AI-Powered Software Development

Welcome to **Awesome Agentic Skills**, your comprehensive toolkit for empowering coding agents and supercharging your software development workflow. Built on a foundation of composable "skills" and intelligent instructions, this system transforms the way AI agents approach coding tasks, driving unprecedented productivity and code quality.

Are you looking to:
*   Accelerate your development cycles with intelligent automation?
*   Ensure high-quality, systematically tested code from your AI assistants?
*   Empower your agents to understand, plan, and execute complex engineering tasks autonomously?

Then **Awesome Agentic Skills** is for you!

## ✨ Key Features & How It Works

Our system guides your AI coding agents through a robust software development lifecycle, ensuring meticulous attention to detail and adherence to best practices.

1.  **💡 Intelligent Design & Specification (Brainstorming Skill)**:
    *   Your agent doesn't just jump into coding. It engages in an interactive design refinement process, asking clarifying questions and exploring alternatives.
    *   Designs are presented in manageable chunks for your review and validation, ensuring alignment with your vision.
    *   *Outcome*: Clear, validated specifications before a single line of code is written.

2.  **🏗️ Automated, Detailed Planning (Writing Plans Skill)**:
    *   Once a design is approved, the agent crafts a precise implementation plan.
    *   Tasks are broken down into bite-sized units (2-5 minutes each), complete with exact file paths, code snippets, and verification steps.
    *   *Outcome*: A foolproof roadmap for development, minimizing ambiguities and errors.

3.  **🤖 Autonomous Subagent-Driven Development (Executing Plans / SDD Skills)**:
    *   With your approval, the system launches a powerful subagent-driven development process.
    *   Specialized subagents tackle individual engineering tasks, with continuous inspection and review of their work.
    *   *Outcome*: High levels of autonomy, allowing agents to work for hours without deviating from the plan, significantly boosting developer productivity.

4.  **✅ Rigorous Test-Driven Development (TDD Skill)**:
    *   Enforces a strict RED-GREEN-REFACTOR cycle.
    *   Agents write failing tests first, observe the failure, write minimal code to pass the test, and then refactor.
    *   *Outcome*: Robust, well-tested code from the ground up, reducing bugs and technical debt.

5.  **🧐 Continuous Code Quality & Review (Requesting Code Review Skill)**:
    *   Between tasks, agents perform self-reviews against the established plan and quality metrics.
    *   Identifies and reports potential issues by severity, with critical issues blocking further progress until resolved.
    *   *Outcome*: Proactive quality assurance and adherence to coding standards.

6.  **🌿 Isolated Development Environments (Using Git Worktrees Skill)**:
    *   Ensures a clean, isolated workspace for each development branch.
    *   Automatically handles project setup and verifies a clean test baseline.
    *   *Outcome*: Conflict-free development and reliable testing environments.

7.  ** 마무리 Streamlined Branch Finalization (Finishing a Development Branch Skill)**:
    *   Upon task completion, verifies all tests pass.
    *   Presents clear options for merging, creating pull requests, keeping, or discarding the worktree.
    *   *Outcome*: Efficient project management and seamless integration of changes.

## 🌟 Why Choose Awesome Agentic Skills?

*   **Boost Developer Productivity**: Let AI agents handle the grunt work, from planning to testing.
*   **Ensure Code Quality**: Built-in TDD and rigorous review processes.
*   **Systematic Approach**: Say goodbye to ad-hoc coding; embrace a structured, repeatable workflow.
*   **Empower AI Agents**: Unlock the full potential of your coding assistants with a comprehensive skill set.
*   **Seamless Integration**: Designed to activate automatically, enhancing your existing agent setup.

## 🛠️ Installation Guide

**Note:** Installation methods vary by platform.

### For Claude Code Users (Recommended via Plugin Marketplace)

1.  **Register the Marketplace**:
    ```bash
    /plugin marketplace add obra/Awesome Agentic Skills-marketplace
    ```
2.  **Install the Plugin**:
    ```bash
    /plugin install Awesome Agentic Skills@Awesome Agentic Skills-marketplace
    ```

### Verify Installation (All Platforms)

Check for the new commands:
```bash
/help
```
You should see commands similar to:
```
# /Awesome Agentic Skills:brainstorm - Interactive design refinement
# /Awesome Agentic Skills:write-plan - Create implementation plan
# /Awesome Agentic Skills:execute-plan - Execute plan in batches
```

### For Codex Users

Instruct Codex to fetch and follow the installation script:
```
Fetch and follow instructions from https://raw.githubusercontent.com/obra/Awesome Agentic Skills/refs/heads/main/.codex/INSTALL.md
```
For detailed documentation, refer to: [docs/README.codex.md](docs/README.codex.md)

### For OpenCode Users

Instruct OpenCode to fetch and follow the installation script:
```
Fetch and follow instructions from https://raw.githubusercontent.com/obra/Awesome Agentic Skills/refs/heads/main/.opencode/INSTALL.md
```
For detailed documentation, refer to: [docs/README.opencode.md](docs/README.opencode.md)

## 📚 What's Inside: The Skills Library

Explore the powerful skills that drive **Awesome Agentic Skills**:

### **Testing & Quality Assurance**
*   **test-driven-development**: The essential RED-GREEN-REFACTOR cycle, including references for avoiding testing anti-patterns.
*   **verification-before-completion**: Ensures fixes are truly fixed, not just superficially addressed.

### **Debugging & Reliability**
*   **systematic-debugging**: A robust 4-phase process for root cause analysis, incorporating techniques like root-cause-tracing, defense-in-depth, and condition-based-waiting.

### **Collaboration & Workflow Management**
*   **brainstorming**: Socratic design refinement for optimal solutions.
*   **writing-plans**: Generates highly detailed and actionable implementation plans.
*   **executing-plans**: Facilitates batch execution with human checkpoints for critical oversight.
*   **dispatching-parallel-agents**: Enables concurrent subagent workflows for enhanced efficiency.
*   **requesting-code-review**: Prepares code for review with a comprehensive checklist.
*   **receiving-code-review**: Guides agents in effectively responding to feedback.
*   **using-git-worktrees**: Manages parallel development branches for isolated feature work.
*   **finishing-a-development-branch**: Streamlines the merge/PR decision workflow and cleanup.
*   **subagent-driven-development**: Offers fast iteration with a two-stage review process (spec compliance, then code quality).

### **Meta-Skills (Developing & Understanding the System)**
*   **writing-skills**: A guide to creating new skills following best practices, including testing methodology.
*   **using-Awesome Agentic Skills**: An introductory guide to understanding and leveraging the entire skills system.

## 💡 Our Philosophy

*   **Test-Driven Development (TDD)**: Always write tests first.
*   **Systematic over Ad-Hoc**: Prioritize process and proven methodologies over guesswork.
*   **Complexity Reduction**: Strive for simplicity as the ultimate design goal.
*   **Evidence over Claims**: Verify all work and changes before declaring success.

Learn more about the vision behind Awesome Agentic Skills: [Awesome Agentic Skills for Claude Code Blog Post](https://blog.fsck.com/2025/10/09/Awesome Agentic Skills/)

## 🤝 Contributing

We welcome contributions! Skills live directly within this repository.
1.  Fork the repository.
2.  Create a dedicated branch for your new skill.
3.  Follow the `writing-skills` guide (located at `skills/writing-skills/SKILL.md`) for best practices in skill creation and testing.
4.  Submit a Pull Request.

See `skills/writing-skills/SKILL.md` for the complete guide.

## ⬆️ Updating

Skills automatically update when you update the plugin:
```bash
/plugin update Awesome Agentic Skills
```

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## ❓ Support & Community

-   **💬 [Discord](https://discord.com/invite/jc4xtF58Ve):** Chat with us on Discord for real-time support and discussions.
-   **🐦 [Twitter](https://twitter.com/ishandutta2007):** Follow us on Twitter for the latest news and updates.
-   **🐦 [Github](https://github.com/ishandutta2007):** Follow me on Github for the latest commits and updates.

## 💖 Support & Sponsorship

If you find this project helpful or if it has saved you time and resources, please consider sponsoring the development. Your support helps maintain the project, develop new features, and keep the initiative open-source.

**[Sponsor @ishandutta2007 on GitHub](https://github.com/sponsors/ishandutta2007)**

Every contribution, no matter how small, makes a huge difference!
