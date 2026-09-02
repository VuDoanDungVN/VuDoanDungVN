# MASTER PROMPT: BUILD A PREMIUM GITHUB PROFILE README

You are an expert GitHub Profile README designer, developer branding specialist, Markdown engineer, SVG designer, and GitHub Actions engineer.

Your task is to build a complete, polished, visually impressive GitHub Profile README for my GitHub profile.

The result should feel like a premium developer landing page inside GitHub, while remaining fully compatible with GitHub Markdown.

---

# 1. MY INFORMATION

Use the following information:

- GitHub username: `[GITHUB_USERNAME]`
- Name / Display name: `[YOUR_NAME]`
- Job title: `[JOB_TITLE]`
- Location: `[LOCATION]`
- Short introduction: `[SHORT_INTRODUCTION]`
- Main tech stack: `[TECH_STACK]`
- Current focus: `[CURRENT_FOCUS]`
- Website: `[WEBSITE_URL]`
- Email: `[EMAIL]`
- LinkedIn: `[LINKEDIN_URL]`
- X / Twitter: `[TWITTER_URL]`
- Blog: `[BLOG_URL]`

If any information is missing, do not block the task.

Use sensible placeholders and clearly mark where I should replace them later.

---

# 2. PRIMARY GOAL

Create a GitHub profile that immediately communicates:

1. Who I am
2. What I build
3. What technologies I use
4. What I am currently working on
5. My GitHub activity
6. My strongest projects
7. How people can contact me

The profile should look modern, premium, developer-focused, technical, and memorable.

Avoid a generic README that looks copied from a template.

The page should have visual hierarchy and feel intentionally designed.

---

# 3. DESIGN DIRECTION

Use a style inspired by:

- modern developer portfolio
- terminal interfaces
- cyber / futuristic UI
- clean SaaS landing pages
- GitHub-native aesthetics
- tasteful glassmorphism-inspired visuals where possible
- minimal but visually rich layout

Do NOT make it childish.

Do NOT overload the README with hundreds of badges.

Do NOT use excessive emoji.

Do NOT create visual clutter.

Favor:

- strong typography
- spacing
- centered hero section
- elegant SVGs
- consistent icon style
- balanced sections
- useful GitHub statistics
- subtle animation
- clean section dividers

The design should work well with both GitHub dark mode and light mode whenever possible.

---

# 4. FILES TO CREATE

Inspect the current repository first.

Then create or update everything necessary.

At minimum:

```text
README.md

assets/
  banner.svg
  coding-animation.svg
  divider.svg

.github/
  workflows/
    snake.yml
```

You may create additional files if they improve the profile.

For example:

```text
assets/
  terminal.svg
  quote.svg
  footer.svg
  profile-header.svg

.github/workflows/
  metrics.yml
```

Do not create unnecessary files.

Keep the repository clean.

---

# 5. README STRUCTURE

Build the README with the following overall structure.

## A. Hero Section

Create a strong opening section.

Include:

- custom SVG/banner
- my name
- professional title
- short positioning statement
- optional typing animation
- links to website/social/contact

Example concept:

```text
Hi, I'm Dung 👋

Software Engineer
Building scalable products, developer tools and experiments.

TypeScript • React • Node.js • Python
```

Do not copy this text literally unless appropriate.

Make the actual copy stronger and personalized.

---

## B. Animated Typing Header

Add an animated typing element using a stable service such as:

```text
readme-typing-svg
```

Potential messages:

- Software Engineer
- Full Stack Developer
- Building products that scale
- Open Source Enthusiast
- Always learning, always shipping

Use my actual profile information when possible.

Avoid cheesy phrases.

---

## C. About Me

Create a concise "About Me" section.

Use a clean layout.

Possible content:

```text
🔭 Currently working on ...
🌱 Currently learning ...
💡 Interested in ...
⚡ Building ...
```

Do not overuse emojis.

Keep the copy professional but personal.

---

# 6. TECH STACK

Create a visually appealing Tech Stack section.

Group technologies logically.

For example:

### Languages

TypeScript
JavaScript
Python
Go
Java

### Frontend

React
Next.js
Vue
Tailwind CSS

### Backend

Node.js
NestJS
FastAPI

### Databases

PostgreSQL
MongoDB
Redis

### DevOps & Cloud

Docker
GitHub Actions
AWS
Cloudflare

### Tools

Git
Linux
VS Code

Use icons from a reliable source such as:

```text
skillicons.dev
```

or another stable icon provider.

Prefer grouped icon rows rather than dozens of individual badges.

Do not include technologies that I did not provide unless clearly marked as placeholders.

---

# 7. GITHUB STATISTICS

Create a GitHub statistics section.

Include useful cards such as:

- GitHub Stats
- Top Languages
- GitHub Streak
- Contribution Activity

Use reliable README services.

Configure them using:

```text
[GITHUB_USERNAME]
```

Make themes visually consistent.

Do not expose tokens or secrets.

If a service requires private API credentials, either:

1. implement it safely using GitHub Actions and repository secrets, or
2. skip it and explain why.

The public README must never contain private API keys.

---

# 8. CONTRIBUTION GRAPH

Add an attractive GitHub contribution graph.

Use something such as:

```text
github-readme-activity-graph
```

Make it visually compatible with the rest of the README.

If possible, choose parameters that look good in GitHub dark and light themes.

---

# 9. SNAKE CONTRIBUTION ANIMATION

Implement the famous GitHub contribution snake animation.

Create:

```text
.github/workflows/snake.yml
```

Use a maintained GitHub Action.

Generate:

```text
github-contribution-grid-snake.svg
```

and optionally:

```text
github-contribution-grid-snake-dark.svg
```

Make the workflow run:

- automatically on a schedule
- manually using workflow_dispatch
- after pushes when appropriate

Use GitHub Actions permissions correctly.

Avoid deprecated actions.

Do not hardcode credentials.

Add the generated animation to README.md.

---

# 10. FEATURED PROJECTS

Create a Featured Projects section.

If repository information is available locally or from the GitHub repository context, inspect it and select meaningful projects.

Prefer projects that demonstrate:

- architecture
- real-world usefulness
- engineering depth
- open source work
- product thinking

For each project show:

- name
- one-line description
- main technologies
- repository link

If possible use GitHub repository cards.

Keep this section curated.

Maximum approximately 4-6 projects.

Do not dump every repository.

---

# 11. DEVELOPER METRICS

If practical, add additional developer metrics.

Possible options:

- profile views
- coding statistics
- contribution metrics
- achievements
- trophies

However:

Do not add metrics purely for decoration.

Only use them if they improve the profile.

Avoid unreliable services.

Avoid services that frequently break.

Avoid extremely slow external images.

---

# 12. TROPHIES

If a stable GitHub Trophy service is available, add a tasteful trophy section.

Do not let trophies dominate the profile.

Maximum one compact row.

If the service seems unreliable or abandoned, omit it.

Reliability is more important than visual gimmicks.

---

# 13. PROFILE VIEW COUNTER

Add a subtle profile views counter if appropriate.

Do not put it prominently in the hero section.

Place it near the bottom.

---

# 14. CONTACT SECTION

Create a clean "Connect With Me" section.

Include available links:

- GitHub
- LinkedIn
- Website
- Blog
- Email
- X/Twitter

Use consistent badges/icons.

Do not include empty links.

Do not expose sensitive personal information.

---

# 15. FOOTER

Create a memorable but minimal footer.

Possible ideas:

- animated SVG
- small developer quote
- coding-themed visual
- contribution snake
- clean separator

Avoid generic quotes such as:

"Code is like humor..."

Prefer either no quote or a concise original line.

---

# 16. CUSTOM SVG ASSETS

Create custom SVG assets when useful.

SVGs should:

- render correctly on GitHub
- use safe fonts
- avoid unsupported JavaScript
- not rely on external scripts
- have reasonable dimensions
- not be enormous
- work reasonably in dark/light modes

Use subtle gradients and animation if supported.

Do not create seizure-inducing animation.

Animations should be slow and tasteful.

---

# 17. RESPONSIVENESS

GitHub README is viewed on:

- desktop
- tablet
- mobile

Design with that in mind.

Avoid layouts that only work at 1200px width.

For side-by-side images use sizes that gracefully collapse or remain readable on mobile.

Do not use fragile HTML tricks.

---

# 18. MARKDOWN / HTML RULES

GitHub allows limited HTML inside Markdown.

Use HTML only when it improves layout.

Allowed examples:

```html
<div align="center">
  <p>
    <a>
      <img />
      picture source</a
    >
  </p>
</div>
```

Avoid unsupported:

```html
<script>
<style>
iframe
JavaScript
```

Do not rely on CSS classes because GitHub strips custom styling.

---

# 19. DARK / LIGHT MODE

Where possible use:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" ... />
  <source media="(prefers-color-scheme: light)" ... />
  <img ... />
</picture>
```

for assets that need different versions.

Use this especially for:

- contribution snake
- banners
- graphs

Make sure there is always a fallback `<img>`.

---

# 20. SECURITY REQUIREMENTS

Absolutely do not:

- commit API keys
- commit GitHub PATs
- expose private email credentials
- expose environment secrets
- inject untrusted JavaScript
- use suspicious external scripts

If credentials are necessary:

use:

```text
GitHub repository Settings
→ Secrets and variables
→ Actions
```

and reference them as:

```yaml
${{ secrets.SECRET_NAME }}
```

Explain every required secret clearly.

---

# 21. RELIABILITY

Prefer services with a strong reputation.

Do not blindly use every README generator found online.

Before depending on an external URL, verify that the service/API structure is reasonable.

Prefer:

- shields.io
- skillicons.dev
- GitHub-hosted assets
- widely used GitHub README services
- maintained GitHub Actions

Avoid obscure dependencies unless necessary.

The README should still look decent if one external card temporarily fails.

---

# 22. PERFORMANCE

Do not create a README that downloads dozens of large external images.

Optimize for:

- fast loading
- small SVG files
- limited external requests
- GitHub cache friendliness

Target approximately:

5-12 meaningful visual resources

instead of 30-50 random badges.

---

# 23. ACCESSIBILITY

Add meaningful `alt` text to images.

Do not communicate important information purely through color.

Make text readable.

Avoid extremely low contrast.

---

# 24. COPYWRITING

Improve my supplied text where necessary.

The profile language should sound:

- confident
- technical
- concise
- approachable
- product-oriented
- experienced

Avoid:

- buzzword soup
- "coding ninja"
- "rockstar developer"
- "10x developer"
- fake corporate language
- generic motivational quotes

Make the copy sound like a real engineer.

---

# 25. PROFILE README REPOSITORY REQUIREMENT

Remember:

For GitHub to show this README on my profile, the repository must have the exact same name as my GitHub username.

For example:

```text
username:
dungdev

profile repository:
github.com/dungdev/dungdev
```

If the current repository name is incorrect, tell me clearly.

Do not silently assume it is correct.

---

# 26. IMPLEMENTATION PROCESS

Perform the work directly.

Step 1:
Inspect the current repository.

Step 2:
Identify existing README/assets/workflows.

Step 3:
Preserve useful existing content.

Step 4:
Design the profile structure.

Step 5:
Create or rewrite README.md.

Step 6:
Create required SVG assets.

Step 7:
Create GitHub Actions workflows.

Step 8:
Validate image URLs and relative asset paths.

Step 9:
Validate YAML syntax.

Step 10:
Review README visually from top to bottom.

Step 11:
Remove unnecessary clutter.

Step 12:
Give me a concise summary of what was created.

Do not stop after giving me instructions.

Actually modify/create the files.

---

# 27. DO NOT ASK ME ABOUT MINOR DESIGN DECISIONS

Use your own judgment for:

- spacing
- alignment
- section order
- icon size
- card width
- SVG dimensions
- typography hierarchy
- separators
- visual composition

Only ask me something if the missing information makes implementation impossible.

Otherwise make a sensible decision and continue.

---

# 28. QUALITY BAR

Before completing the task, evaluate the README against this checklist:

- Does the hero immediately explain who I am?
- Does it look good in dark mode?
- Does it look reasonable in light mode?
- Is the Tech Stack easy to scan?
- Are GitHub statistics useful rather than decorative?
- Is the profile mobile-friendly?
- Are external dependencies reasonable?
- Are there broken image URLs?
- Are GitHub Actions valid?
- Are secrets handled safely?
- Is the README visually consistent?
- Does anything look obviously copied from a generic template?
- Is there excessive visual clutter?
- Is every section actually useful?

Fix any issues before finishing.

---

# 29. FINAL EXPECTED STRUCTURE

Aim for something approximately like:

```text
┌─────────────────────────────────────┐
│             HERO / BANNER           │
│                                     │
│       Hi, I'm [YOUR_NAME]           │
│       Software Engineer             │
│                                     │
│       Animated typing text          │
│                                     │
│       Social / Website links        │
└─────────────────────────────────────┘

              About Me

             Tech Stack

          GitHub Statistics

         Contribution Graph

          Featured Projects

       Contribution Snake

          Connect With Me

             Footer
```

This is a conceptual layout, not literal output.

---

# 30. OPTIONAL PREMIUM TOUCHES

If they genuinely improve the profile, consider implementing:

- custom terminal-style SVG
- animated code snippet SVG
- custom username logo
- developer status widget
- dynamic local-time indicator
- WakaTime statistics
- Spotify currently playing
- blog article feed
- latest GitHub activity
- custom metrics generated through GitHub Actions

Do NOT implement all of them blindly.

Choose only those that provide meaningful value.

---

# 31. IMPORTANT

Do not merely generate a README template and tell me to finish it.

You are responsible for producing a complete usable implementation.

Inspect the repository.

Create the files.

Write the Markdown.

Create the SVG assets.

Create the GitHub Actions.

Check the paths.

Check the YAML.

Check the README.

Make the end result production-ready.

When finished, show:

1. Files created/modified
2. Important design decisions
3. Any placeholders I still need to replace
4. Any GitHub Secrets I need to configure
5. Any GitHub settings I need to enable
6. The final repository structure
7. Any potential limitations of external README services

Then stop.
