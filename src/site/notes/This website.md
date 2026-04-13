---
{"dg-publish":true,"permalink":"/this-website/","dg-note-properties":{}}
---

I opted for a [[Hypermedia\|hypermedia]] structure for this website because by this time in my life I’ve realized I can’t describe myself in a linear way.

It's currently published in the following way:

- Markdown files written on any of my devices in [Obsidian](https://obsidian.md/) synced via [Obsidian Sync](https://obsidian.md/sync) (Plus to support multiple vaults, to keep the site separate from my personal notes vault)
- Published to GitHub via [Obsidian Digital Garden](https://docs.forestry.md/)
- [Vercel](https://vercel.com)  deploys the main branch to a preview subdomain automatically
- After reviewing the preview site, I merge the changes to a live site git branch
- Vercel deploys the live site branch to the live site

It’s not a perfect setup; I may still someday revive an old project TypeLink for live editing of a personal wiki web site. But the Obsidian ecosystem does provide a lot of advantages.

Goals:

- Sourced from Markdown files
- Good UX to edit on macOS, Linux, iPad, and iPhone
- Reliable deploys. It doesn’t need to be perfect as it’s a personal web site. But if things are regularly breaking I will be disincentivized to post
- Minimal steps to deploy from mobile
- No or low cost