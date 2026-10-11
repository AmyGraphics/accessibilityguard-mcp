# ♿ AccessibilityGuard MCP

Live website accessibility screening and WCAG evidence collection.

ChatGPT can explain WCAG. AccessibilityGuard scans live HTML and returns URLs, evidence and prioritized remediation signals for images, language, headings, forms, links and accessible names.

## Tools

- `accessibility.architect`
- `site.accessibility_scan_live`
- `contrast.check_live`
- `forms.audit_live`
- `links.keyboard_audit_live`
- `accessibility.report_live`

## Quick start

```json
{
  "mcpServers": {
    "accessibilityguard": {
      "url": "https://accessibilityguard65-api.agentweb-hub.workers.dev/mcp"
    }
  }
}
```

Start free — 10 requests/day, no signup, no card.

Automated screening is not legal certification of WCAG conformance. Confirm computed contrast, keyboard navigation and screen-reader behavior manually.

Gumroad: https://amygraphics.gumroad.com/l/mcp-pro — $7.99 single or $14.99 all-access.

Solana USDC:

```text
8sDLX3okSV974wdjdeKhN9uWLZDr45DeGCJ28zgTLEdJ
```


## Report evidence

Every finding includes URL, WCAG criterion, severity, evidence and whether manual keyboard, screen-reader or computed-contrast verification is still required. Automated screening is not legal certification.


## Why this MCP is worth using

Live page → URL-level WCAG criterion, severity, evidence, fix and manual-verification flag.

This outcome is the product value; the tool count is only an implementation detail.
