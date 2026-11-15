# Port Townsend This Weekend

A weekly guide to things to do in Port Townsend and East Jefferson County (Fri–Sun).

## How it updates
1. Every Thursday, the week's events are gathered and checked against organizer pages.
2. Jen reviews the list and adds anything from Facebook.
3. After her OK, `events.json` is updated and the site refreshes on its own.

## events.json fields
| Field | Meaning |
|---|---|
| `date` | `YYYY-MM-DD`, or `all` for things on view all weekend |
| `start` / `sort` | Display time (e.g. `7:30 pm`) / 24h sort key (e.g. `19:30`) |
| `title`, `venue`, `address`, `cost`, `blurb`, `url` | Listing details |
| `category` | Music · Stage & Film · Art · Markets & Food · Outdoors & Maritime · Family · Talks & Community |
| `source` | Shown when there's no `url`, e.g. `Facebook (shared by a reader)` |
| `verified` | `true` if confirmed on the organizer's own page; otherwise shows "Check before you go" |
