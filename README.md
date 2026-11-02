# hefestus-apps

Public information pages for internal apps of Hefestus Technologies Ltd., served by GitHub Pages at
https://leor-hefestus.github.io/hefestus-apps/

| Folder | App | Source |
|--------|-----|--------|
| `priority-to-quickbooks/` | Priority To QuickBooks: launch/connect/disconnect info, EULA, privacy policy, and the HTTPS sign-in relay page (`callback.html`) registered with Intuit | `HefestusPDMERPIntegration/Tools/PriorityToQuickBooks/web/` |

Edit the pages in the source repo, then copy them here. Static files only: no secrets, no build step.
`callback.html` forwards Intuit's sign-in reply to the app on the same PC; it stores nothing.
