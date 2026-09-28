<div align="center">

# Ayodapo Adesiyan

**Senior Cybersecurity Engineer** · `dapslegend`

I write PoCs of wild bugs in the wild. Authorized targets only. Evidence in the body, or it stays open.

</div>

---

## What I actually do

I take a live bug class, reproduce the smallest case that proves it, and write the closure bar. A title is not a finding. A fork of someone else's repo is not my work, so those are not listed here.

| Track | Public lab |
|---|---|
| WEB2 + WEB3 sandbox | [`pentagi-public`](https://github.com/dapslegend/pentagi-public) — dumb local sandbox. Fixtures only. Not the private stack. |
| Wild bug PoCs | [`poc`](https://github.com/dapslegend/poc) — notes on bugs I reproduced. Lab harness, not a kit. |
| Address poisoning class | [`runity`](https://github.com/dapslegend/runity) — defensive note on lookalike-address fraud. No poisoning runner. |
| Session / cookie class | [`MicrosoftApp`](https://github.com/dapslegend/MicrosoftApp) — defensive note on OAuth session theft. No grabber steps. |

---

## How a finding gets closed

- **WEB2:** `USER()`, `SYSTEM_USER()`, `@@version`, or a real account/PII effect in the HTTP **body**. A canary in the payload title does not count.
- **WEB3:** measured code, storage, or a fork test. No broadcasts. Empty explorer pages are not criticals.
- **Fix:** bound the input, fail closed, and rerun the same check. If the class still scales with attacker-chosen size, it is not fixed.

---

## Stack I use on real reviews

Go · Rust · Python · Solidity · Docker sandboxes · Burp · PostgreSQL · Linux

Web authorization, injection, session handling. Chain measurement on forks. Ops: isolation, log caps, least privilege.

---

<div align="center">

Ayodapo Adesiyan · [github.com/dapslegend](https://github.com/dapslegend) · [x.com/0xd4ps](https://x.com/0xd4ps)

PoCs of wild bugs. Sandbox first. No forks on this page.

</div>
