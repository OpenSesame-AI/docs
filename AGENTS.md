> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- Customer-facing documentation for **Edward**, General Magic's AI underwriting assistant
- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Audience splits into two guides: the **Admin guide** (`edward/admin/`) for brokerage admins and the **Broker guide** (`edward/broker/`) for brokers
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- **Edward** (also "Ed"): the product; never call it a person
- **Brokerage** is the customer tenant; a **broker** is an end user within a brokerage
- Roles are **admin** and **broker** (use "broker," not "user")
- **Carriers**, **products**, and **regions** are the scopes that control what a broker can access
- **Manuals / supplementary / general** are the document types, in order of authority
- Prefer "underwriting question" and "cited answer" over generic "query"/"response"

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise; one idea per sentence
- **Do not use em-dashes (—).** Use commas, colons, parentheses, or separate sentences instead
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Document only the customer-facing experience (admins and brokers), not internal architecture, retrieval internals, infrastructure, or eng process
- Onboarding is white-glove: the General Magic team provisions workspaces and ingests/verifies documents. Frame those steps as "we handle this for you," and keep customer instructions to what admins and brokers actually do in-app
- Don't invent exact UI labels or screenshots that haven't been confirmed against the live app; describe actions functionally until verified
