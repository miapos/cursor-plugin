# miaPOS plugin for Cursor

Accept **instant account-to-account bank payments** with [miaPOS](https://miapos.eu): buyers pay by QR code or straight from their banking app through **MIA**, Moldova's instant payment system. No cards.

**The plugin never moves real money:** its payment tools work only on the miaPOS test environment.

## What you can ask

- "Take a test payment of 15 MDL and tell me when it is paid."
- "Add miaPOS checkout to my Express shop."
- "Why does my miaPOS callback signature check fail?"
- "Review my miaPOS integration before we go live."

## MCP server

`https://mcp.miapos.eu/mcp`, no login.

| Tool | What it does |
|---|---|
| `search_docs` | Search the miaPOS developer documentation |
| `get_api_reference` | Endpoints, fields, statuses and errors |
| `check_site` | Check a shop's site for checkout readiness |
| `sandbox_create_payment` | Create a test payment with checkout page and QR |
| `sandbox_simulate_payment` | Simulate the buyer paying a test payment |
| `sandbox_payment_status` | Current status plus the signed callback |
| `verify_callback_signature` | Verify a callback body and signature |

## Skills

`integrate-miapos-checkout`, `verify-miapos-callback`, `miapos-go-live`, `miapos-lovable-checkout`.

## Support

[miapos.eu/en/support](https://miapos.eu/en/support) · info@miapos.eu · Published by Finergy Tech S.R.L.
