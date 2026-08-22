<div align="center">

<img src="https://raw.githubusercontent.com/thegitai/.github/main/assets/banner.png" alt="TheGitAI" width="820">

### The whole engineering loop. One terminal.

Investigate in parallel. Build. Verify. Document. Recover.

[**Website**](https://thegit.ai) · [**Docs**](https://thegit.ai/docs) · [**npm**](https://www.npmjs.com/package/@thegitai/cli)

</div>

---

TheGitAI is an AI coding agent for your terminal. It reads and searches your
repository, writes and edits files, runs commands, and builds features with you.

```bash
npm i -g @thegitai/cli
```

```text
ai                  start a session in the current repo
ai "fix the tests"  start with a request
```

No API keys to manage · Curated frontier models · macOS, Linux, Windows

### What it does

- **Understand** — searches the repo and reads the surrounding conventions before it changes anything.
- **Change** — targeted patches, replacements, and full-file writes across many files at once.
- **Verify** — reproduces failures and uses your own tests, linters, and typecheckers as evidence.
- **Ship** — works with Git, reviews the resulting diff, and hands off a verified change.

### A source-visible client

The client that runs on your machine is source-visible, so you can read exactly
what it does before trusting it with your repo and your shell — local file and
shell tools, path containment, redaction, approvals, and session storage.

Server-owned behavior is not included: provider access, model routing, prompts,
orchestration, retrieval, and entitlement enforcement stay on the server. The
client is untrusted by design — every security decision is enforced server-side.

→ [**thegitai-cli**](https://github.com/thegitai/thegitai-cli) · [Trust & Privacy](https://thegit.ai/docs/safety/trust-and-privacy)

<div align="center">
<sub>TheGitAI is a product of Atlast Technologies. Source-visible, not open source — see the repository licence.</sub>
</div>
