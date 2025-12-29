# Team Management

Manage your organization's users, roles, and permissions in Orderly.

## Table of Contents

- [Overview](#overview)
- [User Roles](#user-roles)
- [Inviting Team Members](#inviting-team-members)
- [Managing Users](#managing-users)
- [Role Permissions](#role-permissions)
- [Best Practices](#best-practices)

---

## Overview

Team Management allows organization owners and admins to:
- Invite new team members
- Assign and change roles
- Manage permissions
- Remove users when needed

---

## User Roles

Orderly has three main roles:

| Role | Description | Typical Users |
|------|-------------|---------------|
| **Owner** | Full administrative access | Founders, executives |
| **Admin/Manager** | Team and workflow management | Team leads, managers |
| **Member** | Task completion and viewing | Individual contributors |

### Role Hierarchy

```
Owner (Full Access)
  └── Admin/Manager (Team Access)
        └── Member (Personal Access)
```

---

## Inviting Team Members

### Step 1: Navigate to Settings

1. Click your profile icon
2. Select **Settings**
3. Go to **Team Management**

### Step 2: Send Invitation

1. Click **Invite Team Member**
2. Enter their email address
3. Select their role
4. Add to specific tags/departments (optional)
5. Click **Send Invitation**

### Step 3: User Accepts

The invited user will:
1. Receive an email invitation
2. Click the invitation link
3. Create their password
4. Access the organization

### Bulk Invitations

For multiple users:
1. Click **Bulk Invite**
2. Upload a CSV with emails and roles
3. Or paste email list
4. Confirm and send

**CSV Format:**
```
email,role,department
alice@company.com,member,engineering
bob@company.com,manager,marketing
```

---

## Managing Users

### Viewing Users

The user list shows:

| Column | Description |
|--------|-------------|
| **Name** | User's display name |
| **Email** | Login email address |
| **Role** | Owner, Manager, or Member |
| **Status** | Active, Pending, Disabled |
| **Last Active** | Most recent login |
| **Tags** | Departments/teams |

### Editing User Details

1. Click on a user's row
2. Click **Edit**
3. Modify:
   - Display name
   - Role
   - Tags/departments
   - Notification preferences
4. Save changes

### Changing Roles

To promote or demote a user:
1. Find the user in the list
2. Click the role dropdown
3. Select new role
4. Confirm change

> **Note:** Only Owners can change other users' roles.

### Deactivating Users

When someone leaves:
1. Find the user
2. Click **⋮** menu
3. Select **Deactivate**
4. Their tasks will need reassignment

**What happens when deactivated:**
- Cannot log in
- Tasks show "Unassigned"
- Workflow history preserved
- Can be reactivated later

### Removing Users

For permanent removal:
1. Deactivate the user first
2. Click **⋮** menu
3. Select **Remove**
4. Confirm deletion

> **Warning:** This is irreversible. Consider deactivating instead.

---

## Role Permissions

### Owner Permissions

| Action | Allowed |
|--------|---------|
| Manage all users | ✅ |
| Change roles | ✅ |
| Create/delete playbooks | ✅ |
| View all workflows | ✅ |
| Access all analytics | ✅ |
| Manage organization settings | ✅ |
| Billing and subscription | ✅ |

### Manager Permissions

| Action | Allowed |
|--------|---------|
| Invite team members | ✅ |
| Change roles | ❌ (Members only) |
| Create/edit playbooks | ✅ |
| View team workflows | ✅ |
| Access team analytics | ✅ |
| Manage organization settings | ❌ |

### Member Permissions

| Action | Allowed |
|--------|---------|
| View assigned tasks | ✅ |
| Complete tasks | ✅ |
| View participating workflows | ✅ |
| View personal analytics | ✅ |
| Create playbooks | ❌ |
| Manage users | ❌ |

---

## Best Practices

### Onboarding New Users

1. **Send invitation early** - Before their start date
2. **Assign appropriate role** - Start with Member if unsure
3. **Add to relevant tags** - So they see the right workflows
4. **Schedule training** - Walk through key workflows

### Managing Departures

1. **Reassign tasks first** - Don't leave work orphaned
2. **Deactivate account** - Prevent unauthorized access
3. **Update documentation** - If they owned key processes
4. **Consider knowledge transfer** - Before they leave

### Role Assignment Guidelines

| Scenario | Recommended Role |
|----------|------------------|
| New hire, learning the system | Member |
| Team lead, manages others | Manager |
| Experienced, creates workflows | Manager |
| Executive, needs oversight | Owner |
| Contractor, limited access | Member |

### Security Recommendations

- **Review users quarterly** - Remove inactive accounts
- **Audit role changes** - Track who promoted whom
- **Use SSO** if available - Centralized authentication
- **Enable 2FA** - Extra security for all users

---

## Troubleshooting

<details>
<summary><strong>Invitation email not received</strong></summary>

1. Check spam/junk folder
2. Verify email address is correct
3. Resend the invitation
4. Try an alternate email if needed

</details>

<details>
<summary><strong>Can't change a user's role</strong></summary>

Only Owners can change roles. If you're a Manager:
1. Ask an Owner to make the change
2. Or request Owner access if appropriate

</details>

<details>
<summary><strong>User can't see workflows</strong></summary>

Check if:
1. They have the right role
2. They're assigned to relevant tags
3. They're added to the workflow
4. Their account is active

</details>

---

## Next Steps

- **[Tags & Organization](/user-guide/09-tags-organization.md)** - Organize with departments and teams
- **[Analytics](/user-guide/07-analytics.md)** - View team performance
- **[FAQ](/user-guide/10-faq.md)** - Common questions

---

*Need help? Contact your organization admin or visit our [FAQ](/user-guide/10-faq.md).*
