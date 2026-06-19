# Awesome Built-in AI
> A curated, chronological directory of cool projects, tools, presentations, and guides leveraging native, client-side AI APIs built directly into the web platform.

[Built-in AI APIs](https://developer.chrome.com/docs/ai/built-in-apis) such as the Prompt, Summarizer, and Translator APIs enable zero-inference-cost execution, absolute user privacy by design, and instant local execution without API keys.

## Contents
- [Official Documentation & Specifications](#official-documentation--specifications)
- [Applications & Demos](#applications--demos)
- [Developer Tools](#developer-tools)
- [Media: Presentations, Videos & Blogs](#media-presentations-videos--blogs)
- [Contributing](#contributing)

---

## Official Documentation & Specifications
* [Web Machine Learning CG Explainers](https://github.com/webmachinelearning/) - The raw specifications and community issue trackers shaping future AI/ML APIs.
* [Chrome Built-in AI Documentation](https://developer.chrome.com/docs/ai/built-in) - The Chrome team’s core entry point for developers getting started with built-in AI.
* [Microsoft Edge AI Documentation](https://learn.microsoft.com/en-us/microsoft-edge/web-platform/prompt-api) - The Edge team’s documentation for developers getting started with the various APIs that are part of the built-in AI effort.

## Applications & Demos
*"Note: This roster tracks implementations verified as of the date listed. Entries may be periodically rolled off."*

* [JimakuChan Subtitles](https://sayonari.github.io/jimakuChan/) - Real-time speech recognition and translation of captions for streamers and content creators. [As of: 2026.06]
* [Elk Mastodon Client](https://github.com/elk-zone/elk) and [Phanpy](https://github.com/cheeaun/phanpy) - Deliver seamless, single-click social feed localization directly inside user timelines using the Language Detector and Translator APIs. [As of: 2026.06]
* [WACAO](https://github.com/nuefunnel/WACAO) - Summarization and translation for WhatsApp Web messages. [As of: 2026.06]
* [Chrome AI Playground](https://github.com/oslook/chrome-ai-playground) - An interactive sandbox allowing developers to experiment live with the Prompt, Summarizer, Translator, and Writer APIs directly in their browser. [As of: 2026.06]

## Developer Tools
*"Note: This roster tracks client-side implementations verified as of the date listed. To protect against technical rot and project pivots, entries are systematically rolled off after 12 months."*

* [@types/dom-chromium-ai](https://www.npmjs.com/package/@types/dom-chromium-ai?activeTab=readme) - TypeScript definition types for the built-in AI APIs. [As of: 2026.06]
* [Browser AI model providers for Vercel AI SDK](https://github.com/jakobhoeg/browser-ai) - TypeScript libraries that provide access to in-browser AI model providers with seamless fallback to using server-side models. [As of: 2026.06]
* [Built-in AI Skills.md](https://github.com/GoogleChromeLabs/web-ai-demos/tree/main/built-in-ai-skills-md-agent-md) - An npm package that automatically teaches your AI agent about the latest Built-in AI APIs and their polyfills. [As of: 2026.06]

## Media: Presentations, Videos & Blogs
*An educational library of community tutorials, deep-dives, and tech talks.*

### Videos & Presentations
* [2024.10] [Smart Form Filler - Spice Up Your Forms With Generative AI and LLMs](https://speakerdeck.com/christianliebel/smart-form-filler-spice-up-your-forms-with-generative-ai-and-llms) - A practical deep-dive into how the Prompt API enables zero-inference-cost, offline-ready form filling, leveraging the latest mobile LLMs like Gemini Nano for superior UX and privacy.
* [2026.06] [Presentation in Chinese for Hangzhou Developer Meetup talking about AI, the web, and web standards. The talk touches upon built-in AI APIs and WebNN.](https://www.youtube.com/watch?v=ZJSmi_YL7Yo) - by Hidde de Vries (Logius). Does the Web need AI or does AI need the Web? Well, both! And we are going to need standards to make the two work better together... [As of: 2026.06]
* [2025.10] [フロントエンド開発のためのブラウザ組み込みAI入門 / Introduction to Browser Built-in AI for Frontend Development](https://speakerdeck.com/masashi/browser-built-in-ai-for-frontend) - A deep dive by [Masashi Hirano](https://www.shisama.dev/) analyzing client-side AI integration strategies, comparing heavy WASM-delivered models against zero-dependency, browser-native inference.

### Technical Articles & Blogs
* [2026.06] [Chrome Built-in AI（Gemini Nano）だけで利用規約チェックはできるのか検証してみた / Verifying if Chrome Built-in AI (Gemini Nano) Alone Can Check Terms of Service](https://alpaca-press.com/posts/tech/gemini-nano-terms-check/) - A highly practical validation study testing the local context window constraints of the Prompt API to analyze and extract cancellation policies from dense legal documents.
* [2026.05] [【Chrome組み込みAI】ブラウザでGemini Nanoを動かす！Web開発を劇的に変える「Built-in AI」の最新動向と活用法 / 【Chrome Built-in AI】 Running Gemini Nano in the Browser! Latest Trends and Practical Use Cases of "Built-in AI" Dramatically Changing Web Development](https://note.com/masa_cloud/n/nd01a531c148f?hl=en) - A comprehensive architectural deep-dive analyzing offline privacy boundaries, JSON Schema structured output enforcement, and multi-device routing via Hybrid Inference.
* [2025.07] [爆速で動作する翻訳・要約Chrome拡張を作った / Built a Blazing-Fast Translation and Summarization Chrome Extension](https://zenn.dev/yu_yukk_y/articles/7a7512b38a4df4) - A practical introduction to a local English-to-Japanese translation and summarization extension using Chrome's built-in Gemini Nano model, highlighting the zero-network latency and sub-second response times made possible by browser-native inference.
* [2025.07] [Google I/O 2025 注目のWebフロントエンド技術 / Google I/O 2025 Featured Web Frontend Technologies](https://techblog.lycorp.co.jp/ja/20250709a) - A comprehensive overview of the latest web frontend technologies announced at Google I/O 2025, including Chrome Built-in AI, by the lead front-end developer for Yahoo! Chiebukuro.
* [2025.05] [Zennの記事一覧からAI関連の記事をAIの力によって滅ぼし、そして私も消えよう / Using AI to Eliminate AI Articles from Zenn, and Then Disappear Myself](https://zenn.dev/sora_kumo/articles/zenn-ai-filter?locale=en) - A comprehensive technical deep dive into architecting a client-side Chrome extension using the native Prompt and Summarizer APIs, detailing production strategies for local LLM challenges like latency, formatting breakage, and logical contradictions.

---

## Contributing
Contributions are what make the open-source community an amazing place! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a Pull Request.

License: [CC0-1.0](LICENSE)
