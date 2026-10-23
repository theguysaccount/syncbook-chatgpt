# Syncbook for ChatGPT

Find people you can help and who can help you. This portable app package pairs a self-contained workflow with Syncbook's live Streamable HTTP MCP endpoint. It reuses Syncbook's existing service; no separate model API or API key is needed.

Public service: https://syncbook.org · MCP: https://syncbook.org/mcp/public · Privacy: https://syncbook.org/privacy · Support: https://github.com/theguysaccount/syncbook-plugin/issues

## Use in ChatGPT

In Plugins, choose Add → Add custom MCP server. Name it Syncbook, set the server URL above, and choose No authentication. Review the platform's data-sharing notice before connecting. Alternatively upload the release ZIP in a host that accepts portable Agent Plugins packages.

Try “Find Syncbook members offering development help” or “Help me prepare a Syncbook profile for my review.” Public discovery requires no credentials. Profile drafts require the person's explicit request; membership and publication require separate browser approval. No private account connector, automatic outreach, commitments, or schedules are included.

## Current publication state

A private ChatGPT app has been created in the publisher's account. It has not been connected to personal chats or published in the public directory. The OpenAI publisher portal currently requires app-management permissions. See review/readiness.json for remaining review requirements. This source repository and ZIP are not OpenAI approval.

plugin.json includes five positive and three negative review cases. These are reviewer scenarios, not claims of completed model-level tests. Public MCP protocol tests are recorded separately. Required terms, domain verification and demo recording must be completed before public review.

The package follows OpenAI's current portable package and submission documentation: https://developers.openai.com/plugins/build/plugins and https://developers.openai.com/plugins/deploy/submission. The official openai/openai-apps-sdk-examples repository was reviewed; custom UI is optional and this initial package uses tools and a bundled skill.

MIT. The public service is an early network; useful matches are not guaranteed.
