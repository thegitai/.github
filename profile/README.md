<div align="center">

<img src="https://raw.githubusercontent.com/thegitai/.github/main/assets/banner.png" alt="TheGitAI — an agentic AI coding tool for your terminal" width="900">

[![npm](https://img.shields.io/npm/v/@thegitai/cli?color=3fc7c7&label=%40thegitai%2Fcli&logo=npm&logoColor=white&style=flat-square)](https://www.npmjs.com/package/@thegitai/cli)
[![node](https://img.shields.io/badge/node-%E2%89%A524-3fc7c7?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org)
[![platforms](https://img.shields.io/badge/macOS%20%C2%B7%20Linux%20%C2%B7%20Windows-3fc7c7?style=flat-square)](https://thegit.ai/docs/getting-started/installation)

**[Website](https://thegit.ai)** · **[Docs](https://thegit.ai/docs)** · **[Engineering notes](https://thegit.ai/blog)** · **[npm](https://www.npmjs.com/package/@thegitai/cli)**

</div>

---

**TheGitAI is an agentic AI coding tool for your terminal.** It reads and searches your repository, writes and edits files, runs your tests and build commands, and verifies the change before handing it back — in one session, without leaving the shell.

```bash
npm i -g @thegitai/cli
```

```text
ai                  start a session in the current repo
ai "fix the tests"  start with a request
```

No API keys to manage · Curated frontier models · macOS, Linux, Windows

## What it does

|  | |
| --- | --- |
| **Understand** | Searches the repository and reads the surrounding conventions before it changes anything. |
| **Change** | Targeted patches, replacements, and full-file writes across many files at once. |
| **Verify** | Reproduces failures and uses your own tests, linters, and typecheckers as evidence. |
| **Ship** | Works with Git, reviews the resulting diff, and hands off a verified change. |

It is an autonomous coding agent in the sense that matters: it decides what to look at next from what it just found, rather than working from a fixed plan or a pre-built index of your code. We wrote about why that choice was made in [Why We Abandoned Repository Indexing](https://thegit.ai/blog/why-we-abandoned-repository-indexing).

## A source-visible client

The client that runs on your machine is source-visible, so you can read exactly what it does before trusting it with your repository and your shell — local file and shell tools, path containment, redaction, approvals, and session storage.

Server-owned behavior is not included: provider access, model routing, prompts, orchestration, and entitlement enforcement stay on the server. The client is untrusted by design — every security decision is enforced server-side.

→ [**Read the client source**](https://github.com/thegitai/thegitai-cli) · [Trust & Privacy](https://thegit.ai/docs/safety/trust-and-privacy)

<div align="center">
<sub>TheGitAI is a product of Atlast Technologies. Source-visible, not open source — see the repository licence.</sub>
</div>
