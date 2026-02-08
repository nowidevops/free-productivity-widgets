# Free ServiceNow Widgets

Open-source Service Portal widgets built by **iDevOps LLC** for the ServiceNow community.

Each widget is packaged as an **Update Set XML** file that can be imported directly into any ServiceNow instance.

---

## Available Widgets

| Widget | Description | Folder |
|--------|-------------|--------|
| [Team Standup Board](./team-standup-board/) | Daily standup (DSU) widget with blocker escalation, reactions, analytics dashboard, manager view, and digest email notifications. | `team-standup-board/` |
| [Voice Navigation](./voice-navigation/) | Push-to-talk voice command widget with Ctrl+K command palette, record navigation, multi-language support, and audio waveform visualization. | `voice-navigation/` |

---

## Installation

1. Download the `.xml` file from the widget folder.
2. In your ServiceNow instance, navigate to **System Update Sets > Retrieved Update Sets**.
3. Click **Import Update Set from XML** and upload the file.
4. Preview the update set and commit it.

For detailed installation steps, see each widget's README.

---

## Requirements

- ServiceNow **Madrid** or later (Service Portal)
- Admin role for update set import

---

## License

[MIT License](./LICENSE) - Free to use, modify, and distribute.

---

## Disclaimer

These widgets are **community contributions** and are not affiliated with, endorsed by, or supported by ServiceNow, Inc. Use at your own discretion. Always test in a sub-production instance before deploying to production.

---

Built with purpose by **iDevOps LLC** | [YouTube - @AgenticServiceNow](https://www.youtube.com/@AgenticServiceNow)
