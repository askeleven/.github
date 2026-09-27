## AskEleven

We build and run AI employees for businesses: people-shaped roles that answer, follow up, book, screen and report inside the tools a business already uses. Not a chatbot, not a template agent. [askeleven.com](https://askeleven.com)

Running agents on real customers teaches you things a demo never will. What we learn in production and can share, we publish here, free and MIT licensed, for anyone running agents, on any stack.

### Open source

| | |
|---|---|
| **[agent-proof](https://github.com/askeleven/agent-proof)** | Record your agent doing a real task as one uncut vertical video. Every caption comes from the agent's own step events, not an editor. `npx @askeleven/agent-proof run` |
| **[agent-autonomy-levels](https://github.com/askeleven/agent-autonomy-levels)** | A shared vocabulary for how much an AI agent may do without a human. Six levels, L0 to L5, and the design errors that make "autonomous" meaningless. |
| **[deliverability-check](https://github.com/askeleven/deliverability-check)** | Find out why your email goes to spam, and what specifically to change. SPF, DKIM, DMARC, MX, BIMI, blocklists. `npx @askeleven/deliverability-check yourdomain.com` |
| **[send-guard](https://github.com/askeleven/send-guard)** | Check an email list before your agent sends to it: what will bounce, what is a trap, and why. CLI and MCP server; free local checks, mailbox checks via [Analyzemail](https://analyzemail.com). `npx @askeleven/send-guard leads.csv` |
| **[agent-pulse](https://github.com/askeleven/agent-pulse)** | Know your agent stopped working before your customer does. Alerts on missing activity, failure streaks and accepted-but-undelivered messages, not just errors. `npx @askeleven/agent-pulse check` |
| **[sms-guard](https://github.com/askeleven/sms-guard)** | Check a text before your agent sends it: encoding, segment count, the recipient's quiet hours, shorteners, opt-out wording. Splits long texts into parts carriers will deliver. `npx @askeleven/sms-guard msg.txt` |
| **[send-once](https://github.com/askeleven/send-once)** | A send happens once, and only while the approval behind it is still true. Idempotency ledger plus approval expiry and fact re-checks at dispatch. `npm i @askeleven/send-once` |

### What we hold ourselves to

- **Show the work.** An agent's claim is worth what you can verify. Everything here makes an agent's behaviour inspectable, not more impressive.
- **Name the failure.** Each tool exists because something went wrong on a real account first. The READMEs say what it does not do.
- **No lock-in.** Nothing here needs an AskEleven account, and none of it phones home.

Issues and pull requests are welcome on every repo.
