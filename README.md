# Phoenix T. Bird

I build AI tools where a person stays in charge of the output, and I test whether that check is actually holding. Washington State.

## What I'm working on

**Manuscript injection eval** (Python, Claude API; code and results to follow)
Does an AI copy editor obey instructions hidden inside the manuscript it's editing? Six attack types (fake publisher notes, hidden HTML comments, fake end-of-manuscript tags, an in-story character addressing the AI, instruction-leak requests) against three system-prompt defenses, scored with canary strings so no LLM judge is needed. Wilson intervals, refusals counted separately, limitations stated up front.

**Bōcere** (TypeScript, Electron; source private, [installers public](https://github.com/justhurkledurkling-max/bocere-releases))
A desktop writing app for book authors. The design question: how do you let a model help with a whole book without letting it change a word the author didn't approve?
- The model can only *propose* edits through a tool call. They appear as tracked changes; the author accepts or rejects each one, and every decision is recorded and fed back to the model.
- Only the main process talks to the model; the page has no network access, and the API key sits in the OS keychain, never in the book or the page.
- Before anything is sent, the app shows exactly which text the model will read.
- The accounts server's row-level security is tested by running the real SQL in an in-memory Postgres and having an author, an editor, a stranger and a publisher each try what they should and shouldn't be able to do.

**[Gigflow](https://github.com/justhurkledurkling-max/gigflow)** (TypeScript, Supabase)
A booking workspace for independent musicians, co-built with a collaborator, each of us working with Claude Code.

**[More projects](https://github.com/phoenixthomasbird/phoenixbird-portfolio)**: a Claude tool-use research agent, a Hebrew speaking tutor, an Agent SDK experiment, and the Python I wrote while learning.

## How I work

- I write the spec, direct the build with Claude Code, and verify the result myself: tests, a dry run, or driving the real app. If I haven't checked something, I say so.
- I treat model input as untrusted. Manuscripts, web pages and emails are data, not instructions.
- Before I build open-source code on my machine, I read it. Most recently: a source review of seven open-source Rust apps for malware before building them locally.

## Also

Cartoonist (drawn by hand) and home inspector in Washington. → [phoenixtbird.com](https://phoenixtbird.com)
