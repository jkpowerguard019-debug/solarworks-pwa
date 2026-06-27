# SolarWorks 365 — Internal Team Tracker PWA

A Progressive Web App (PWA) for tracking solar installation work progress across teams.

## Tech Stack
- **Frontend**: Vanilla HTML, CSS, JavaScript (single file)
- **Database**: Supabase (PostgreSQL + Auth + RLS)
- **Offline**: Service Worker + localStorage draft queue
- **PDF**: jsPDF (client-side, no server needed)

## Roles & Access
| Role | Sections |
|------|----------|
| Admin | All (1–6 incl. Payments), Audit Log, Delete |
| Liasoning | Section 1, 2, 3, 4 (no Payments) |
| Installer | Section 1, 3 only (own applications) |

## Features
- 🔒 Secure auth via Supabase — role auto-detected from DB
- 📱 Installable PWA on Android & iOS (Add to Home Screen)
- 📶 Offline support — saves drafts locally, syncs on reconnect  
- 📄 PDF generation + WhatsApp share
- 📜 Audit log for every change (Admin only)
- ✅ Section 2 progress bar across 13 checklist items
- 🔩 Multi-select material items with manual entry fields


