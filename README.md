# community-concerns

# Ulat Barangay

A website where residents report problems in their barangay, such as a broken streetlight or a clogged canal, and see if the problem has been fixed. Barangay officials log in as admin to update each report.

**Live site:** https://community-concerns.vercel.app

## What it does

**Residents can:**
- Send a report with a category, location, description and an optional name
- See all reports and their status: Pending, In Progress or Resolved
- Search and filter the reports
- Use the site in Tagalog or English

**The admin can:**
- Log in with an email and password
- Change the status of a report
- Leave a note for residents
- Delete a report

## Tools used

- **HTML, CSS and JavaScript** for the website
- **Supabase** for the database and the admin login
- **Vercel** to put the website online
- **GitHub** to store the code

## Files

- `index.html` is the main page
- `privacy.html` is the privacy page
- `favicon.svg` is the icon in the browser tab

## Database

One table called `concerns`. Each row is one report.

| Column | What it stores |
|---|---|
| id | Automatic number for the report |
| reporter_name | Name of the resident (optional) |
| category | Type of problem |
| location | Where the problem is |
| description | What the problem is |
| status | Pending, In Progress or Resolved |
| admin_remarks | Note from the officials |
| created_at | Date and time of the report |

Anyone can read and send reports. Only the logged-in admin can update or delete them.

## How to run

Open `index.html` in a browser. An internet connection is needed because the data is online.

## Note

This is a class project and not an official government system.
