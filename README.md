# Ajeer Mohammed

Senior full-stack engineer. I ship production software with AI coding agents, build
the checks that keep it safe, and stay on to run it. Since July 2026 about nine
in ten of my commits are written with an agent; my part is the architecture, the
review, and the checks that stop its mistakes reaching production.

Right now I lead a multi-tenant e-commerce platform: three apps and two shared
packages in one monorepo, 60 data models, four to six developers around it. Before
that, an infant health app for a US state department of health that is live on both
app stores, a Shopify storefront serving over 10,000 people a day, and training and
event platforms for Abbott and L'Oreal.

Most of that is private client code, so this profile shows a fraction of what I do.
The write-ups are at **[ajeer.website](https://ajeer.website)**.

### What I am good at

**Owning the whole thing.** Schema, API, frontend, deploy pipeline, and the pager
afterwards. I have never much liked the handoff where someone else runs what I
wrote.

**Making correctness automatic instead of remembered.** Most of what goes wrong in
production is something a person knew and forgot at the wrong moment. I would
rather spend a day writing the check than a year hoping everyone remembers.

**Making codebases safe for AI agents to work in.** Not prompting. Changing the
repository so the consequences of an agent being wrong are contained: hooks that
keep it out of secrets, review skills for what static checks miss, and CI gates
that hold it to the same bar as a person. Agent instructions in eight production
repos, blocking gates where a mistake costs money, and the generalised version is
the first thing below. The whole workflow, with the numbers, is at
**[ajeer.website/how-i-work](https://ajeer.website/how-i-work)**.

### Building in public

- **[bouncer-gates](https://github.com/ajeermahmood/bouncer-gates)** - CI gates that
  let anyone contribute without being able to break things. Also runs inside Claude
  Code and Cursor, so an agent hears about a leaked key or a cross-tenant query in
  the same turn it wrote one. Listed in the official MCP Registry
- **[agent-ready-repo](https://github.com/ajeermahmood/agent-ready-repo)** - a template
  for a repository AI agents can work in safely: AGENTS.md, a secret-read hook,
  review skills and CI
- **[estate](https://github.com/ajeermahmood/estate)** - a linter for your
  repositories rather than your code, in one Go binary
- **[web-element-scraper](https://npmjs.com/package/web-element-scraper)** and
  **[nodejs-performance-profiler](https://npmjs.com/package/nodejs-performance-profiler)**
  on npm
- **[How I build software with AI agents](https://ajeer.website/how-i-work)** - the
  workflow layer by layer, with the commit data and what went wrong
- **[What my coding agents got wrong, and what caught it](https://ajeer.website/blog/what-my-coding-agents-got-wrong)** -
  six real mistakes from agent-written code
- **[Making a codebase safe for AI coding agents](https://ajeer.website/blog/coding-agents-in-production-repositories)**,
  which rules belong in a gate and which in an instructions file

### Stack

**Front end** `TypeScript` `React` `Next.js` `React Router` `Astro` `Vite` `Tailwind` `SCSS`

**Back end** `Node` `NestJS` `Fastify` `Prisma` `PostgreSQL` `Redis` `GraphQL`

**Mobile and data** `Flutter` `Dart` `Python`

**Infra** `Docker` `GitHub Actions` `Cloudflare` `Vercel` `Railway` `AWS`

Happy to learn whatever the problem actually needs.

### Say hi

[ajeermahmood@outlook.com](mailto:ajeermahmood@outlook.com) ·
[LinkedIn](https://linkedin.com/in/ajeermahmood) ·
[Portfolio](https://ajeer.website)
