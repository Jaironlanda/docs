# Screenshot checklist

Screenshots still missing from the docs, gathered from the `TODO: screenshot` comments in the `.mdx` pages. For each one:

1. Capture the screen in the console and save it at the suggested path under `images/`.
2. Replace the `{/* TODO: ... */}` comment with the image, for example:
   `<Frame><img src="/images/quick-start/get-started.png" alt="Get started screen" /></Frame>`
3. Tick the box here.

**Progress: 18 / 20**

## Getting started

- [x] **Get started screen**: `images/quick-start/get-started.png` ([quick-start.mdx:18](quick-start.mdx#L18))
- [x] **Silo Overview tab with the URL and Details cards**: `images/quick-start/silo-overview.png` ([quick-start.mdx:79](quick-start.mdx#L79))
- [x] **Console with the sidebar and the Silos screen**: `images/console/overview.png` ([how-to/console-overview.mdx:10](how-to/console-overview.mdx#L10))

## Silos

- [x] **Silos screen with the Create silo button**: `images/create-silo/silos-list.png` ([how-to/create-silo.mdx:16](how-to/create-silo.mdx#L16))
- [x] **Create a new silo dialog**: `images/create-silo/create-dialog.png` ([how-to/create-silo.mdx:45](how-to/create-silo.mdx#L45))
- [x] **Silos list**: `images/view-silo/silos-list.png` ([how-to/manage-silo.mdx:14](how-to/manage-silo.mdx#L14))
- [x] **Silo Overview tab**: `images/view-silo/overview.png` ([how-to/manage-silo.mdx:40](how-to/manage-silo.mdx#L40))
- [x] **Silo Settings tab**: `images/view-silo/settings.png` ([how-to/manage-silo.mdx:59](how-to/manage-silo.mdx#L59))
- [x] **Region setting on the silo Settings tab**: `images/change-region/settings-region.png` ([regions.mdx:61](regions.mdx#L61))

## Editor and Schema Lock

- [x] **Data & schema tab in the side-by-side layout**: `images/json-editor/data-and-schema.png` ([editor/json-editor.mdx:13](editor/json-editor.mdx#L13))
- [x] **Schema pane showing "Schema is off" with the Enable button**: `images/schema-lock/enable.png` ([features/schema-lock.mdx:56](features/schema-lock.mdx#L56))
- [x] **Schema pane with the schema locked**: `images/schema-lock/locked.png` ([features/schema-lock.mdx:68](features/schema-lock.mdx#L68))

## Analytics and logs

- [x] **Analytics screen**: `images/analytics/overview.png` ([features/analytics.mdx:16](features/analytics.mdx#L16))
- [x] **Logs screen**: `images/logs/overview.png` ([features/activity-logs.mdx:16](features/activity-logs.mdx#L16))

## Keys

- [x] **Keys screen, Manage keys card selected**: `images/keys/manage-key/keys-screen.png` ([keys/manage-keys.mdx:26](keys/manage-keys.mdx#L26))
- [x] **Keys screen, Access keys card selected**: `images/keys/access-key/keys-screen.png` ([keys/access-keys.mdx:28](keys/access-keys.mdx#L28))
- [x] **Keys screen, MCP keys card selected**: `images/keys/mcp-key/keys-screen.png` ([keys/mcp-keys.mdx:20](keys/mcp-keys.mdx#L20))
- [x] **MCP key created dialog**: `images/keys/mcp-key/created.png` ([keys/mcp-keys.mdx:41](keys/mcp-keys.mdx#L41))

## Billing

- [ ] **Billing page with the Current plan and Plans sections**: `images/billing/billing-page.png` ([billing/upgrade-plan.mdx:16](billing/upgrade-plan.mdx#L16))
- [ ] **Cancel subscription link at the bottom of the Billing page**: `images/billing/cancel-subscription.png` ([billing/cancel-subscription.mdx:17](billing/cancel-subscription.mdx#L17))

---

Find any that are left: `grep -rn "TODO: screenshot" --include="*.mdx" .`
