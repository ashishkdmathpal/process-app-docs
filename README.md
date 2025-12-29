# Orderly Documentation

> **Process Enforcement Platform** - Ensure workflows are completed in the right order, every time.

<div class="hero-section">
  <h2>Welcome to Orderly</h2>
  <p>Hard blocking workflow engine that physically prevents tasks from executing out of order.</p>
</div>

## What is Orderly?

Orderly is a **process enforcement SaaS platform** designed for teams that need guaranteed workflow compliance. Unlike traditional task managers with soft dependencies, Orderly uses **hard blocking** - tasks remain locked until all prerequisites are complete.

**Perfect for:**
- 🏥 Healthcare compliance workflows
- 🏭 Manufacturing quality control
- 📋 Employee onboarding processes
- 🚀 Software deployment pipelines
- ✅ Any process that must follow a strict order

---

## Quick Start

| I want to... | Go to... |
|--------------|----------|
| Create an account | [Getting Started](user-guide/01-getting-started.md) |
| Understand the dashboard | [Dashboard Guide](user-guide/02-dashboard.md) |
| Create a workflow template | [Creating Playbooks](user-guide/03-playbooks.md) |
| Run a workflow | [Running Workflows](user-guide/04-workflows.md) |
| Complete my tasks | [Task Management](user-guide/05-tasks.md) |
| Manage my team | [Team Management](user-guide/08-team-management.md) |
| View analytics | [Analytics & Reports](user-guide/07-analytics.md) |

---

## User Guides by Role

<!-- tabs:start -->

### **Founders/Owners**

Start here if you're setting up Orderly for your organization.

<span class="role-badge role-founder">Owner</span>

1. [Getting Started](user-guide/01-getting-started.md) - Account setup and first login
2. [Dashboard Overview](user-guide/02-dashboard.md) - Navigate your workspace
3. [Creating Playbooks](user-guide/03-playbooks.md) - Build workflow templates
4. [Team Management](user-guide/08-team-management.md) - Invite and manage users
5. [Tags & Organization](user-guide/09-tags-organization.md) - Organize with departments and teams
6. [Analytics & Reports](user-guide/07-analytics.md) - Track organization performance

### **Managers**

Start here if you lead a team using Orderly.

<span class="role-badge role-manager">Manager</span>

1. [Getting Started](user-guide/01-getting-started.md) - Logging in
2. [Dashboard Overview](user-guide/02-dashboard.md) - Your workspace
3. [Creating Playbooks](user-guide/03-playbooks.md) - Build workflow templates
4. [Running Workflows](user-guide/04-workflows.md) - Start and manage workflows
5. [Task Management](user-guide/05-tasks.md) - Assign and track tasks
6. [Team Progress](user-guide/06-team-progress.md) - Monitor your team

### **Team Members**

Start here if you're completing tasks in Orderly.

<span class="role-badge role-member">Member</span>

1. [Getting Started](user-guide/01-getting-started.md) - Logging in
2. [Dashboard Overview](user-guide/02-dashboard.md) - Your workspace
3. [My Tasks](user-guide/05-tasks.md) - View and complete your assignments

<!-- tabs:end -->

---

## Key Concepts

### Hard Blocking

Unlike traditional task managers with "soft" dependencies (notifications/warnings), Orderly uses **hard blocking**:

```
🔒 Locked → ⭕ Available → 🔄 In Progress → ✅ Completed
```

Tasks are physically locked until all prerequisite tasks are completed. This ensures processes are followed correctly every time.

### Playbooks vs Workflows

| Concept | Description | Analogy |
|---------|-------------|---------|
| **Playbook** | A reusable template defining the process | Recipe |
| **Workflow Instance** | An active execution of a playbook | Cooking with the recipe |

### Blocking Modes

| Mode | Behavior |
|------|----------|
| **Fully Sequential** | Tasks unlock one at a time, in order |
| **Stage Sequential** | All tasks in a stage run in parallel; stages are sequential |
| **No Blocking** | All tasks available from start |

---

## Complete Guide Index

| # | Guide | Description |
|---|-------|-------------|
| 1 | [Getting Started](user-guide/01-getting-started.md) | Account setup, login, user roles |
| 2 | [Dashboard](user-guide/02-dashboard.md) | Navigation and workspace overview |
| 3 | [Playbooks](user-guide/03-playbooks.md) | Creating and managing workflow templates |
| 4 | [Workflows](user-guide/04-workflows.md) | Running and managing workflow instances |
| 5 | [Tasks](user-guide/05-tasks.md) | Task management and completion |
| 6 | [Team Progress](user-guide/06-team-progress.md) | Monitoring team performance |
| 7 | [Analytics](user-guide/07-analytics.md) | Reports and insights |
| 8 | [Team Management](user-guide/08-team-management.md) | User invitations and permissions |
| 9 | [Tags & Organization](user-guide/09-tags-organization.md) | Departments, teams, and labels |
| 10 | [FAQ](user-guide/10-faq.md) | Frequently asked questions |

---

## Need Help?

- **[FAQ](user-guide/10-faq.md)** - Common questions and answers
- **[GitHub Issues](https://github.com/ashishkdmathpal/process-app/issues)** - Report bugs or request features

---

*Documentation last updated: December 2024*
