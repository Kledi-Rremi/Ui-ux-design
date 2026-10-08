# Screenshot export guide

This repository currently uses concept artwork in its cover and experience map, not fabricated UI screenshots. To add a genuine product gallery:

1. Open each original design in Figma, select an individual top-level frame, and export to PNG at **2x**.
2. Pick 8–12 representative screens showing the customer journey, hostess check-in, manager dashboards and admin approvals.
3. Name each PNG descriptively and upload it under `screenshots/mobile/` or `screenshots/web/`.
4. Embed with Markdown, for example: `![Event discovery](screenshots/mobile/event-discovery.png)`.
5. Verify the public Figma links work in a signed-out browser and add prototype links when available.

Suggested filenames: `mobile/event-discovery.png`, `mobile/tickets.png`, `mobile/checkout.png`, `web/hostess-checkin.png`, `web/manager-dashboard.png`, `web/admin-approvals.png`.

Do not commit the two large binary `.fig` archives unless the design sources explicitly need to be downloadable; the Figma view links are better for recruiters.