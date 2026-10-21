# Security and configuration

This repository contains sanitized n8n workflow exports. Before importing, configure your own n8n credentials and API endpoints. The externship research APIs may no longer be available. Never commit API keys or access tokens.

If an original export exposed a token, **revoke and rotate that token** with its issuing provider; removing it from public workflow files does not invalidate it.

For safe reuse, review all HTTP Request authorization headers, credential selectors, webhooks, and data-service URLs after import.
