# Team Standup Board

A full-featured **Daily Standup (DSU)** widget for the ServiceNow Service Portal. Provides a structured standup experience with blocker escalation, team reactions, analytics, and manager oversight.

![Team Standup Board](screenshot.png)

---

## Features

- **Standup Entry Form** - Yesterday, Today, and Blockers fields with optional task reference linking
- **Blocker Escalation** - Flag urgent blockers that surface to managers and trigger notifications
- **Team Reactions** - Celebrate, support, or acknowledge teammates' standup entries
- **Analytics Dashboard** - Visual charts for team participation, blocker trends, and submission patterns
- **Manager View** - Dedicated dashboard for managers to review team standup data across sprints
- **Digest Email** - Automated daily summary email with all team entries and blockers
- **Historical Browsing** - Browse and filter past standup entries by date, team, or user
- **Announcements** - Integrated announcement panel for team-wide updates

---

## Custom Tables

| Table | Purpose |
|-------|---------|
| `u_standup_entry` | Stores daily standup submissions (yesterday, today, blockers, user, team, date) |
| `u_standup_reaction` | Stores team reactions (celebrate, support, acknowledge) linked to entries |

---

## Tech Stack

- **AngularJS** - Client-side controller with two-way data binding
- **GlideRecord / GlideAggregate** - Server-side data queries
- **CSS Variables** - Themeable design tokens for portal consistency
- **Service Portal** - Widget, page, and instance components

---

## Installation

1. Download `SNLab_dsu_widget.xml` from this folder.
2. In your ServiceNow instance, go to **System Update Sets > Retrieved Update Sets**.
3. Click **Import Update Set from XML** and upload the file.
4. **Preview** the update set - review any conflicts.
5. **Commit** the update set.
6. Navigate to your Service Portal and add the **Team Standup Board** widget to a page.

### Post-Install

- Assign the `u_standup_entry_user` role to users who should submit standups.
- Configure team records as needed for your organization.

---

## What's Included

The update set contains:

- Service Portal widget (HTML template, client script, server script, CSS)
- Portal page and layout configuration
- Custom table definitions (`u_standup_entry`, `u_standup_reaction`)
- Field labels and dictionary entries
- Sample data for demonstration
- Application menu and module entries
- Cross-scope privileges

---

## Author

**iDevOpsLLC**

## License

[MIT](../LICENSE)
