# JJC Events — Johnson Japan Club Landing Pages

A branded event landing page for the Johnson Japan Club at Cornell SC Johnson College of Business. Designed to replace generic CampusGroups listings with a premium, conversion-focused experience.

## Live Site

Once deployed: `https://[your-github-username].github.io/jjc-events/`

## Quick Start

### 1. Deploy to GitHub Pages (5 minutes)

1. Create a new repo on GitHub called `jjc-events`
2. Push this code:
   ```bash
   git init
   git add .
   git commit -m "Initial JJC event page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/jjc-events.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Source** → select `main` branch, `/ (root)` folder
4. Click Save. Your site will be live in ~60 seconds.

### 2. Customize for Your Event

Edit `index.html` and update these placeholders:

| What | Where to find it | Replace with |
|---|---|---|
| Event date | Search `March 8` | Your actual date |
| Time | Search `7:00 PM` | Your actual time |
| Venue | Search `Venue TBA` | Khouse / HotpotmeetsKBBQ / etc. |
| Price | Search `$8` | Your ticket price |
| CampusGroups link | Search `YOUR_EVENT_ID` | Your actual CampusGroups RSVP URL |
| Capacity | Search `25 spots` | Your actual cap |

### 3. Share the Link

Instead of sharing the CampusGroups link directly, share:
```
https://[your-username].github.io/jjc-events/
```

The CampusGroups payment link is embedded in the page. Attendees get sold first, then click through to pay.

## Creating New Events

For future events, you can either:
- **Option A:** Edit `index.html` directly (simplest for one event at a time)
- **Option B:** Create separate HTML files like `karaoke.html`, `sushi-night.html` and link to them at `https://[username].github.io/jjc-events/karaoke.html`

## Design System

The page uses a consistent JJC visual identity:

| Element | Value |
|---|---|
| Primary font | Noto Serif JP (Japanese headings) |
| Body font | DM Sans |
| Accent color | `#c23b22` (vermillion red) |
| Gold accent | `#b8860b` |
| Background | `#f5f0e8` (washi paper) |
| Ink | `#1a1a1a` |

## Tech

Zero dependencies. Single HTML file. Hosted free on GitHub Pages. No build step, no framework, no database.

## License

Internal use — Johnson Japan Club, Cornell University.
