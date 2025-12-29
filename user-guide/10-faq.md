# Frequently Asked Questions

Quick answers to common questions about using Orderly.

## Table of Contents

- [General Questions](#general-questions)
- [Account & Login](#account--login)
- [Playbooks & Workflows](#playbooks--workflows)
- [Tasks & Assignments](#tasks--assignments)
- [Team & Permissions](#team--permissions)
- [Technical Questions](#technical-questions)

---

## General Questions

<details>
<summary><strong>What is Orderly?</strong></summary>

Orderly is a **process enforcement platform** that uses hard blocking to ensure tasks are completed in the correct order. Unlike traditional task managers, Orderly physically prevents out-of-order execution.

**Key features:**
- Hard blocking workflow engine
- AI-powered workflow creation
- Multi-user collaboration
- Real-time progress tracking

</details>

<details>
<summary><strong>What is "hard blocking"?</strong></summary>

Hard blocking means tasks cannot be started until all their dependencies are complete. This ensures:

- Processes are followed exactly
- No steps are accidentally skipped
- Quality is maintained
- Compliance is enforced

**Example:** In an approval workflow, you physically cannot deploy code until the code review is marked complete.

</details>

<details>
<summary><strong>What's the difference between a Playbook and a Workflow?</strong></summary>

| Playbook | Workflow |
|----------|----------|
| A template (recipe) | An active execution (cooking) |
| Reusable | One-time instance |
| Defines the process | Tracks actual work |
| Created once | Started many times |

</details>

<details>
<summary><strong>Can I use Orderly on mobile?</strong></summary>

Yes! Orderly is fully responsive and works on:
- Desktop browsers
- Tablets
- Mobile phones

The interface adapts to your screen size with a mobile-friendly navigation bar.

</details>

---

## Account & Login

<details>
<summary><strong>I forgot my password</strong></summary>

1. Go to the login page
2. Click **"Forgot Password"**
3. Enter your email address
4. Check your email for reset instructions
5. Click the link and create a new password

</details>

<details>
<summary><strong>I'm not receiving emails from Orderly</strong></summary>

Try these steps:
1. Check your spam/junk folder
2. Add noreply@orderly.app to your contacts
3. Check if your email is correct in your profile
4. Contact your IT team about email filtering
5. Reach out to your organization admin

</details>

<details>
<summary><strong>Can I change my email address?</strong></summary>

Yes:
1. Go to **Profile**
2. Click **Edit Profile**
3. Update your email
4. Verify the new email
5. New email becomes active

</details>

<details>
<summary><strong>How do I enable dark mode?</strong></summary>

1. Click your profile icon
2. Look for the theme toggle (sun/moon icon)
3. Click to switch between light and dark mode

Or: Your system preference may be detected automatically.

</details>

---

## Playbooks & Workflows

<details>
<summary><strong>How do I create a playbook?</strong></summary>

**Using AI (recommended):**
1. Go to **Playbooks**
2. Click **Create Playbook**
3. Describe your process in plain English
4. Click **Generate**
5. Review and adjust
6. Activate when ready

**Manually:**
1. Click **Create Playbook**
2. Select **Start from Scratch**
3. Add steps using the Stage Editor
4. Set dependencies
5. Save and activate

</details>

<details>
<summary><strong>Why can't I start a workflow from my playbook?</strong></summary>

The playbook might be in **Draft** status. To start workflows:
1. Open the playbook
2. Click the **⋮** menu
3. Select **Activate**
4. Now you can start instances

</details>

<details>
<summary><strong>Can I edit an active workflow?</strong></summary>

**Limited editing is possible:**
- Reassign tasks ✅
- Add notes ✅
- Extend due dates ✅
- Change priority ✅

**Not possible:**
- Add new tasks ❌
- Remove tasks ❌
- Change dependencies ❌

To change structure, edit the playbook for future instances.

</details>

<details>
<summary><strong>How do I cancel a workflow?</strong></summary>

1. Open the workflow
2. Click the **⋮** menu
3. Select **Cancel Workflow**
4. Add a reason (optional)
5. Confirm cancellation

All in-progress tasks will stop, and the workflow marks as cancelled.

</details>

---

## Tasks & Assignments

<details>
<summary><strong>Why is my task locked?</strong></summary>

Tasks are locked when their dependencies haven't completed. Check:

1. Open the workflow detail page
2. Look at the task list or flow diagram
3. Find which task(s) must complete first
4. Wait for or help complete those tasks

</details>

<details>
<summary><strong>Can I work on multiple tasks at once?</strong></summary>

Yes, you can have multiple tasks **In Progress** across different workflows. Within the same workflow:
- In **fully sequential** mode: One task at a time
- In **stage sequential** mode: Multiple parallel tasks in the same stage

</details>

<details>
<summary><strong>How do I reassign a task?</strong></summary>

1. Open the task details
2. Click **Reassign**
3. Select the new assignee
4. Add a reason (optional)
5. Confirm

The new assignee will be notified.

</details>

<details>
<summary><strong>What happens when I skip a task?</strong></summary>

Skipping a task:
- Marks it as "Skipped" (not completed)
- Unlocks dependent tasks (same as completing)
- Records who skipped and when
- Allows the workflow to continue

Use sparingly - skipped tasks indicate process deviations.

</details>

<details>
<summary><strong>How do escalations work?</strong></summary>

Escalations notify managers when tasks are overdue:

| Level | Trigger | Action |
|-------|---------|--------|
| Warning | Approaching due date | Task shows yellow warning |
| Escalated | Past due date | Manager is notified |
| Critical | Significantly overdue | Higher escalation |

Managers can then take action (reassign, extend deadline, etc.)

</details>

---

## Team & Permissions

<details>
<summary><strong>What can each role do?</strong></summary>

| Action | Owner | Manager | Member |
|--------|-------|---------|--------|
| Create playbooks | ✅ | ✅ | ❌ |
| Start workflows | ✅ | ✅ | ❌ |
| Complete tasks | ✅ | ✅ | ✅ |
| Invite users | ✅ | ✅ | ❌ |
| Change roles | ✅ | ❌ | ❌ |
| Manage settings | ✅ | ❌ | ❌ |

</details>

<details>
<summary><strong>How do I invite a new team member?</strong></summary>

1. Go to **Settings** > **Team Management**
2. Click **Invite Team Member**
3. Enter their email
4. Select their role
5. Click **Send Invitation**

They'll receive an email to join your organization.

</details>

<details>
<summary><strong>Can I have multiple organizations?</strong></summary>

Currently, each account belongs to one organization. If you need to work with multiple organizations:
- Create separate accounts with different emails
- Ask to be invited to each organization

</details>

---

## Technical Questions

<details>
<summary><strong>What browsers are supported?</strong></summary>

Orderly works best on modern browsers:
- Chrome 90+ ✅
- Firefox 88+ ✅
- Safari 14+ ✅
- Edge 90+ ✅

Internet Explorer is not supported.

</details>

<details>
<summary><strong>Is my data secure?</strong></summary>

Yes, Orderly uses:
- HTTPS encryption for all traffic
- Encrypted database storage
- Secure authentication with JWT
- Regular security audits
- Multi-tenant data isolation

</details>

<details>
<summary><strong>Can I export my data?</strong></summary>

Yes, you can export:
- Workflow history (CSV)
- Analytics reports (PDF, CSV)
- Playbook definitions (JSON)

Go to **Settings** > **Data Export** to download your data.

</details>

<details>
<summary><strong>Does Orderly have an API?</strong></summary>

Yes, Orderly provides a REST API for:
- Workflow management
- Task operations
- User management
- Analytics

Contact your admin for API documentation and access credentials.

</details>

<details>
<summary><strong>What happens if I lose internet connection?</strong></summary>

Orderly requires an internet connection. If you lose connectivity:
- Your current view will remain visible
- New actions won't be saved
- Reconnecting will sync your data
- No data is lost

</details>

---

## Still Have Questions?

If you can't find your answer:

1. **Check related documentation**
   - [Getting Started](./01-getting-started.md)
   - [Dashboard](./02-dashboard.md)
   - [Playbooks](./03-playbooks.md)
   - [Workflows](./04-workflows.md)
   - [Tasks](./05-tasks.md)

2. **Contact your organization admin**
   - They can help with role-specific questions
   - They have access to organization settings

3. **Report issues**
   - For bugs, report at: https://github.com/ashishkdmathpal/process-app/issues
   - Include steps to reproduce the problem

---

*Documentation last updated: December 2024*
