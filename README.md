# MCP Tutorial — Model Context Protocol

A complete, beginner-friendly tutorial on the Model Context Protocol (MCP) — built as a
static site ready to publish on GitHub Pages.

## Live site

Once published, the site is accessible at:
`https://<your-username>.github.io/<repository-name>/`

## Structure

```
├── index.html                  # Landing page
├── docs/
│   ├── 01-introduction.html    # What MCP is
│   ├── 02-problem.html         # The problem MCP solves
│   ├── 03-architecture.html    # Components & architecture
│   ├── 04-transport.html       # Transport & message types
│   ├── 05-flow.html            # End-to-end request flow
│   └── 06-faq.html             # FAQ & common misconceptions
└── assets/
    ├── style.css               # Shared stylesheet
    └── nav.js                  # Sidebar active-link highlighting
```

## Publishing to GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages** in your repository.
3. Under **Source**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder.
5. Click **Save**. Your site will be live within a minute or two.

No build step required — this is a pure HTML/CSS/JS static site.

## Topics covered

- What MCP is and the mental model behind it
- The integration problem MCP solves
- Hosts, clients, servers — architecture breakdown
- Transport options (stdio, HTTP+SSE, WebSockets)
- JSON-RPC message types (`tools/list`, `tools/call`, etc.)
- End-to-end request flow walkthrough
- FAQ: misconceptions, comparisons, practical questions

## License

MIT
