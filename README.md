Release Notes
Release Notes — Digital Design of Service
v1.1 — *(upcoming)*
Release notes for v1.1 will be added here when the next set of features is ready.

v1.0 — April 2026
What's here
Digital Design of Service (DOS) is Sperry Digital's platform for planning and documenting well operations end-to-end. It replaces fragmented spreadsheets, emails, and manual reports with a single structured environment shared across engineering, operations, and management.

What you can do
Design a full DOS from scratch — job details, trajectory, planned operations, engineering models, risk assessments, and commercial data, all in one place.
Build and visualize Bottom Hole Assemblies — BHA Builder is embedded inside Engineering Modeling. Browse 80+ component types (bits, mud motors, MWD, RSS, jars, drill collars, and more), import bit specs directly from HDBS, and see a live SVG schematic update as you build.
Compare two BHA cases side-by-side — select any two cases on the BHA dashboard to open a synchronized comparison view.
Resolve parameter conflicts across domains — the Collaboration Dashboard shows Drilling Engineering, Subsurface, and Operations parameter ranges on the same chart. When they don't overlap, you see it immediately.
Generate final deliverables in one place — Digital Data Outputs produces the final DOS document, well montage, customer reports, and data acquisition program without manual assembly outside the platform.
Track approvals and changes with a permanent record — MOC (Management of Change) entries are auto-numbered and auditable. Approval workflows are built in.
Things worth knowing before you start
#	What	Why it matters
1	Your UI adapts to your role	Sections you can edit, steps in the guided flow, and visibility of commercial data all depend on your permission level. Read-only access on a section is intentional, not a bug.
2	Only one person edits a section at a time	If someone else has a section open, you'll see an editor lock notification. Saves are transactional — partial failures report exactly which components didn't go through.
3	Reference data comes from the data warehouse	Well names, personnel, and country data are pulled live from Databricks. If something looks missing, contact your local data steward — it's a data issue, not an app issue.
4	Documents live in Azure, not your drive	Files attached to a well are stored in Azure Blob Storage. Nothing is saved locally.
5	Work items can be linked to ADO	You can create and link Azure DevOps work items directly from within a DOS job.
6	Light/dark theme and keyboard shortcuts are available	Toggle theme from your profile. Keyboard shortcut reference is in the help menu.
Integrations active in this release
Sperry data warehouse (Databricks) — well, personnel, and reference data
HDBS — bit specifications import in BHA Builder
Azure Blob Storage — document library
Azure DevOps — work item creation and linking
Known limitations
Excel import is available for bulk data migration from legacy workflows during transition.
The in-app tour and guided flow cover onboarding — check those before raising a support ticket for navigation questions.
Use the Feature Request button (available throughout the app) to flag anything you want changed or added. That queue feeds directly into the product backlog.
