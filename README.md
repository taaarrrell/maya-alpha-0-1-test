# M.A.Y.A. Alpha 0.1 — Test Interface

Disposable, synthetic test page for the M.A.Y.A. Alpha 0.1 conversational
interface. Public by design: it contains no secrets, no real memories,
and no live model connection.

## What this is

- A single-page chat interface (`index.html`), prepared from the verified
  Milestone 1 disposable build.
- Replies are SIMULATED by fixed offline rules. No AI model is connected,
  no network requests are made, and nothing leaves the browser.
- Chat history is stored only in this browser, under the single key
  `maya-alpha-conversation-v0.1`. It is never shared or promoted anywhere.

## Public copy — what changed

- The owner's name has been removed from this copy.
- One principle is adapted: Human Agency reads "The owner authorises…"
  here; the verified A3-A6 v1.4 wording names the owner.
- The purpose, personality guidance, and traits are provisional proposals
  pending owner approval. The Identity panel in the page carries a
  disclosure stating all of this.

## What this is not

- Not the live Memory Core. Not a deployed product. No spending, no
  autonomous actions, no delegation, no external-agent access.
- The live Gemini connection (via the Cloudflare Worker proxy) is a
  separate, later step. This page does not call it.

## Identity

The read-only Identity panel in the page states who M.A.Y.A. is. Name,
full name, principles, and boundaries are verified against the A3–A6
design spec v1.4, except the one adapted principle noted above;
purpose, personality guidance, and traits are PROVISIONAL proposals
pending owner approval.

## Test it

Open https://taaarrrell.github.io/maya-alpha-0-1-test/ on a phone or
computer, send a message, reload the page (history is retained), export
history as JSON, and clear it with the in-page confirmation.

## Status

Disposable test artifact for Alpha 0.1 Milestone 3. Delete freely; nothing
here is load-bearing.
