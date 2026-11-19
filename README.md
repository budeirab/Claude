# Masjid Al Momineen CRM

A single-page community CRM for Masjid Al Momineen, in `crm/index.html`.

- **Members & households**: directory with status (Active / Inactive / Visitor), roles, contact details and notes. Each member opens a profile with their giving history, pledges and follow-ups.
- **Donations**: recorded against a fund (General Fund, Zakat, Sadaqah, Zakat al-Fitr, Building Fund, Ramadan Iftar, Education, Janazah Fund), with method and receipt number. Filter by fund and year, and export to CSV.
- **Giving statements**: a year-end statement of contributions for any member, ready to copy or download.
- **Pledges**: campaign pledges whose progress is calculated from the member's donations to that fund.
- **Events & programs**: halaqas, classes, Jumu'ah, iftars and Eid, with Hijri dates and attendance.
- **Follow-ups**: welcome calls, hospital visits, condolences and pledge reminders, with due dates and overdue flags.

When published as a Claude artifact it uses the shared artifact database, so everyone with Contributor access sees the same records. Opened directly in a browser, it saves records in that browser's local storage instead.
