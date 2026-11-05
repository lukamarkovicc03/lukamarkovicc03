# Luka Marković

I run [Atrigen](https://atrigen.rs), a digital agency in Belgrade. We build websites for local businesses and take care of what comes after the launch: SEO, Google and Meta ads, and analytics. I also build AtriBot, an AI assistant that answers a business's customers from the business's own content.

I write most of the code myself, from the front end down to the Cloudflare setup it runs on.

## Projects

### AtriBot

An AI assistant for service businesses such as salons and dental clinics. The business adds its services, prices and pages, and the assistant answers visitors on its website from that material only. When it does not know something, it says so instead of guessing. When a conversation turns into a lead, the owner gets an email with the whole exchange.

Built on Cloudflare Workers, D1, R2 and Vectorize, with an Astro dashboard for the business owner.

Live at [atribotai.com](https://atribotai.com). More in [atribot-showcase](https://github.com/lukamarkovicc03/atribot-showcase).

### Atrigen website

The agency's own site, in Serbian and English: a page for each service, a price list, a blog, and AtriBot answering questions about services and prices. Every page is static HTML built with Astro and served from Cloudflare Pages.

Live at [atrigen.rs](https://atrigen.rs). More in [atrigen-website-showcase](https://github.com/lukamarkovicc03/atrigen-website-showcase).

The source code of both projects is private. The linked repositories describe what they do and how they are built.

## How I work

Every change goes through a pull request, and type checks, linting and tests run before it is merged. In AtriBot, each merge also goes to a staging environment first, and a production release is smoke-tested before it takes traffic. Decisions that would look strange a few months later are written down in the repository, so the reason does not get lost.

## Tools

TypeScript, Astro, React, Next.js, Tailwind CSS, Node.js, Hono, Cloudflare (Workers, Pages, D1, KV, R2, Vectorize, Workers AI), SQLite, PostgreSQL, Python, Vitest, Playwright.

## Contact

- Website: [atrigen.rs](https://atrigen.rs)
- Email: info@atrigen.rs
- Phone: +381 65 374 1300
