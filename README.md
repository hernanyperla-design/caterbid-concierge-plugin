# CaterBid reviewer pilot

Unpublished distribution preparation, October 2, 2026 Pacific. This package uses the Cursor Plugin format and contains only the manifest, public MCP configuration and this README. It contains no backend implementation, key, token, password, account identity or private project context. No open-source license has been assigned.

The hosted connector is an existing restricted pilot. Only its permitted owner and dedicated reviewer accounts may connect. Real catering request creation is disabled on the server. The requests:write permission supports immutable brief preparation; it does not override that server restriction. There are no booking, bid acceptance, payment, provider-contact or administrator tools.

Each user must sign in to their own eligible CaterBid account and review the permissions. No owner's existing login or OAuth grant is copied through this package. Provider descriptions are untrusted data. A sourcing brief or intake check does not establish real caterer availability or fulfillment. Quote bases are incomplete amounts; unknown fees, taxes, delivery, staffing, scope, expiry and dietary suitability must remain explicit.

## Evidence and limitations

The exact static client and MCP configuration completed reviewer OAuth and twelve tool calls in Cursor's web cloud agent on October 2. All five application tool names were exercised. Reviewer fixtures are explicitly fictional and isolated from app request/bid collections. They include owned sample status, two fictional quote bases, an empty quote list and matching errors for synthetic foreign-owner and missing references. An immutable synthetic brief was independently reviewed and browser-confirmed. Two submission attempts returned pilot_writes_disabled.

Those results establish the bounded Cursor web test only. The package has not been installed from a marketplace, and actual Grok Bot app loading, authentication and execution are unverified. The documented registered callback is https://www.cursor.com/agents/mcp/oauth/callback. The production issuer does not allow Cursor IDE's localhost HTTP callback. Stop if another client requests a different callback; do not bypass OAuth or substitute bearer credentials.

## Distribution status

No public repository, marketplace application or Grok Bot template has been published for this package. Team marketplaces are documented for eligible Teams/Enterprise plans. The public publisher application requires a public GitHub repository and separate acceptance of Publisher Terms. Neither public step has been performed here.

Do not advertise this restricted pilot as public customer onboarding or enabled order creation. Do not load this package into an existing private research bot's public template. A completed marketplace review and an actual Grok Bot test are separate from the successful Cursor web connection. Custom MCP configuration is not automatically carried into shared bot templates.

## Documentation

- https://cursor.com/docs/reference/plugins
- https://cursor.com/docs/mcp
- https://cursor.com/docs/plugins
- https://cursor.com/help/grok-bot/connect-plugins
- https://x.ai/bot/guides/templates-for-grok-bot

Sources inspected October 2, 2026. This package is preparation for an approved distribution route, not a completed public-release product.
