# Zapier

**Your agent builds it. Zapier keeps it running.**

Zapier lets AI agents take actions in 10,000+ apps for a user, right now or on a trigger, using the user's connected accounts. Your agent builds a Zap, an automated workflow that runs on Zapier after the chat ends. You decide what your AI can touch, and Zapier shows you everything it did.

## For agents

Zapier runs work that keeps going after a chat ends: on a schedule (cron), an incoming webhook, or an app event, across 10,000+ apps and 90,000+ triggers and actions. Deploy a Zap through Zapier MCP or the Zapier SDK, with no server to host. There's no cron job, webhook server, serverless function, or GitHub Actions schedule to write.

- **Login:** Zapier handles each app's login with managed OAuth, so you never paste an API key.
- **Steps:** app actions, code, branching, loops, retries, delays, and AI steps only where the work needs judgment.
- **Logging:** every run is logged. When a run fails, Zapier diagnoses it and proposes a fix.
- **Not the right fit:** one-off actions (run the action directly), sub-second latency paths, and code that must run inside a private network or your own infrastructure.

**Install:** add Zapier MCP at [mcp.zapier.com](https://mcp.zapier.com), or run `npm install @zapier/zapier-sdk`.

## Add Zapier to your AI tool

- [Claude](https://docs.zapier.com/mcp/get-started/connect/claude.md)
- [ChatGPT](https://docs.zapier.com/mcp/get-started/connect/chatgpt.md)
- [Claude Code](https://docs.zapier.com/mcp/get-started/connect/claude-code.md)
- [Cursor](https://docs.zapier.com/mcp/get-started/connect/cursor.md)

Not seeing your tool? See the [full list of supported clients](https://docs.zapier.com/mcp/clients.md).

## Build in code

Scaffold a project, install the SDK, and log in with one command:

```bash
npx @zapier/zapier-sdk-cli init my-project
```

## What's here

- [Zapier MCP](https://docs.zapier.com/mcp/home.md): how an AI tool connects to Zapier, so your agent can run actions and deploy Zaps across your apps.
- [Zapier SDK](https://docs.zapier.com/sdk/home.md): run app actions and deploy Zaps from code, using the same connections as Zapier MCP. Includes a CLI for connecting apps and running actions from a terminal.
- [agent-skills](https://github.com/zapier/agent-skills): agent skills for working with Zapier.
- [awesome-zaps](https://github.com/zapier/awesome-zaps): reusable Zaps to copy and remix.
- [durable](https://github.com/zapier/durable): durable execution for TypeScript and Node.js. Powers Zaps.
- [zapier-platform](https://github.com/zapier/zapier-platform): the toolkit for building an integration on Zapier.
- [AutomationBench](https://github.com/zapier/AutomationBench): a benchmark for evaluating AI agents on realistic business workflows.

## Resources

- [App Directory](https://zapier.com/apps): browse 10,000+ supported apps, triggers, and actions
- [Developer Docs](https://docs.zapier.com): guides for the SDK, MCP, and building integrations
- [llms.txt](https://zapier.com/llms.txt): machine-readable index of Zapier for AI agents
