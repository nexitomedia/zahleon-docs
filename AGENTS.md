# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- It documents Zahleon, a bookkeeping and payment-reconciliation SaaS for
  Shopify merchants in Germany and Austria.
- The public site is `https://developer.zahleon.com`.
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- Use "Händler" for the customer company and "Kunde" for the merchant's buyer.
- Use "Mandant" only for technical tenancy or accounting context.
- Distinguish Zahleon's own Stripe billing from a merchant's Stripe connection.
- Distinguish Shopify return events from successful financial refunds.
- Call immutable corrections "Stornorechnung" or "Korrekturrechnung", never
  silently edited invoices.

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Do not publish internal admin routes, secrets, filesystem paths, test
  credentials, or unfinished API endpoints.
- Mark preview functionality honestly. Never describe a planned integration as
  generally available.
- Do not give individual tax or legal advice.
