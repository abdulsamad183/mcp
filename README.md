# MCP Tutorial — Model Context Protocol

A complete, beginner-friendly tutorial on the Model Context Protocol (MCP) — built as a
static site ready to publish on GitHub Pages.

## Live site

Once published, the site is accessible at:
`https://abdulsamad183.github.io/mcp/`

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
