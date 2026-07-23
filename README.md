# Edward documentation

Customer-facing documentation for **Edward**, General Magic's AI underwriting assistant. Built with [Mintlify](https://mintlify.com).

## Structure

- `index.mdx`: landing page
- `edward/admin/`: Admin guide (workspace setup, team access, document management)
- `edward/broker/`: Broker guide (asking questions, understanding answers)
- `docs.json`: site configuration and navigation

## Local development

The Mintlify CLI requires an LTS version of Node (it does **not** support Node 25+).

```bash
npm install -g mint
mint dev
```

View the local preview at `http://localhost:3000` (or the next free port).

## Publishing changes

With the Mintlify GitHub app connected, changes are deployed to production automatically after pushing to the default branch.

## Resources

- [Mintlify documentation](https://mintlify.com/docs)
