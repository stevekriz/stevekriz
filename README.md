# Hi, I'm Steve 👋

I'm a frontend-first product engineer with 5+ years shipping web and mobile apps on Django backends, working AI-first with Claude Code. From 2021 to 2026 I was a Senior Software Engineer at **Quant Five**, a five-person product studio in San Francisco, where I was the founding web engineer of client Noble Mobile's app (11,000+ phone lines activated) and most recently built AI agent-chat and live-preview UIs for CodePress. Almost all of that work lives in private repos (the contribution graph counts it), so here's the short tour.

**Open to senior product and frontend engineering roles, remote-first.** [LinkedIn](https://www.linkedin.com/in/stevekriz) · steve.kriz@gmail.com

## Selected work

**[Noble Mobile](https://noblemobile.com)**, a mobile carrier that pays members for less screen time, and a Quant Five client (2024–26)
- Founding engineer of the Next.js web app that also runs as the iOS and Android UI. Built the original checkout and eSIM activation flow.
- Cut homepage first-load JavaScript about 70% (2.56 MB → ~768 KB) after finding a shared import that pulled the payment SDK onto the homepage, then lazy-loaded below-fold sections.
- Built flicker-free A/B testing by evaluating PostHog flags server-side.
- Built the screen-time rewards app in Expo and React Native: iOS and Android usage tracking, widgets and a leaderboard.
- Built self-serve data top-ups (a flag-gated React purchase flow on permissioned Django endpoints), and web eSIM activation and transfer for Helium Mobile after Noble acquired it.

**[CodePress](https://codepress.dev)**, Quant Five's AI coding-agent platform (2025–26)
- Built key human-in-the-loop controls for the agent chat: plan-approval cards, in-chat question prompts, and a Stop button that keeps partial output. Batched token streaming to one render per frame.
- Stopped long agent chats from jumping mid-scroll by replacing list virtualization with CSS containment and native scroll anchoring (worst jump 512 px → 0 in lab tests, at up to 2,810 messages).
- Shipped Figma-style comments on live app previews in five days: pins that re-anchor across hot reloads inside a sandboxed cross-origin iframe, with realtime multi-viewer sync.
- Built the web app's Playwright end-to-end harness and CI-blocking bundle-size limits on every route, and took **[CodePress Mobile](https://apps.apple.com/us/app/codepress-mobile/id6762484518)** from zero to the App Store on Expo.

**Earlier at Quant Five** (2021–24)
- **AnyTLDR:** the Next.js frontend for streamed LLM summaries and Q&A of YouTube videos and podcasts (2024).
- **AutoCPT:** an AI captioning iOS app I built in React Native from first commit to App Store launch (2023).
- **Samarity:** a volunteer-rewards web app I created in Next.js and launched publicly within three months (2022–23).
- Client work: TypeScript project references for **Replo** (editor type-check time down 36%), and user management in a React/Okta SSO app for **LookingGlass Cyber**.

## How I work

I write the spec and the test plan, direct Claude Code and Codex agents, keep PRs small, and own verification: end-to-end and unit tests, CI and AI review, and before/after screenshots on UI changes.

## Toolbox

TypeScript · React/Next.js · React Native/Expo · Tailwind CSS · Playwright · Vitest/Jest · PostHog · Stripe & Plaid · OpenAI & Anthropic APIs · Claude Code & Codex · Python/Django REST APIs
