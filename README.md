# SubSleuth

Find every subscription hiding in your inbox — before it charges you again.

**Live demo:** https://aoe-dav3.github.io/subsleuth/

## What it does

- Connect your real Gmail (read-only) and SubSleuth searches it for receipts, renewals and trials, then shows what you're paying, when it renews, and where to cancel.
- Monthly and yearly totals, a renewal calendar, insights, and a cancel/manage link per subscription.
- Newsletters & mailing lists with one-click Unsubscribe.
- Ended subscriptions — receipts with no recent renewal, shown separately and never counted in your totals.
- Sample mode — a built-in demo inbox (24 emails, 12 subscriptions, $190.40/month) so you can see the full scan with no sign-in.
- Mark subscriptions as cancelled; export everything as CSV.

## How it works

- **Real Gmail:** sign in with Google (read-only scope). The app searches your inbox live and parses everything in your browser.
- **Sample mode:** no sign-in — runs on built-in demo data.

## Tech

One HTML page — HTML, CSS and JavaScript, no framework, no backend, no database. Gmail API + Google Identity Services. Hosted on GitHub Pages.

## Run it

Open the live demo: https://aoe-dav3.github.io/subsleuth/

Or download `index.html` and open it in a browser. (The real Gmail connection only works from the registered demo address.)

## Privacy

Read-only. Everything is parsed on your device; nothing is uploaded or stored. Close the tab and it's gone.

## Credits

Built for LaunchPad Hacks. AI assistance was used in building it.
