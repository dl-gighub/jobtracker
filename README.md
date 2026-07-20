# Job Application Tracker

A lightweight, self-contained job tracker built as a single HTML file. No framework, no backend, no build step — just drop it in a browser and it works.

Built to track a multi-track job search across Cloud FinOps, AI Strategy, APM/PM, BizOps, and CS/TAM roles.

![Job Tracker Screenshot](screenshot.png)

## Features

- Filter by track, tier, or application status
- Expandable rows with role notes, red flags, and direct LinkedIn links
- Status dropdowns that persist across sessions via localStorage
- Tier scoring (A / B / C) with color-coded badges
- Dark mode support out of the box
- Fully responsive — works on mobile

## Live Demo

[View live →](https://yourusername.github.io/job-tracker)

## Usage

Clone the repo and open `job_tracker.html` in any browser:

```bash
git clone https://github.com/yourusername/job-tracker.git
cd job-tracker
open job_tracker.html
```

Or deploy to GitHub Pages for a shareable live URL.

## Customizing

All job data lives in the `JOBS` array at the bottom of `job_tracker.html`. Each entry follows this shape:

```js
{
  title: "Role title",
  co: "Company name",
  tier: "A",           // A, B, or C
  track: "FinOps",     // FinOps | AI Ops | APM/PM | BizOps | CS/TAM
  resume: "Cloud_2026",
  comp: "$120k–$160k",
  loc: "Remote",
  why: "Why this role fits",
  watch: "Red flag or gap to address",
  link: "https://linkedin.com/jobs/view/..."
}
```

## Stack

Pure HTML, CSS, and vanilla JS. Icons via [Tabler Icons](https://tabler-icons.io). No npm, no bundler, no dependencies to maintain.

## About

Part of a broader personal OS project — a portfolio site, job tracker, and morning brief system built to manage a senior remote job search in Cloud FinOps and AI Strategy.

Built by [David Lun](https://linkedin.com/in/davidlun22).
