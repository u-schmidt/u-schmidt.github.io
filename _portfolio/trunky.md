---
layout: post
title: Trunky
hide-title: false
feature-img: "assets/img/portfolio/trunky-01.jpg"
img: "assets/img/posts/Screenshot 2026-04-07 at 00.22.16.png"
date: 2026-04-12
tags: [AI, RAG, Experimental, Chat, Electron]
---

Trunky is an experimental desktop app built with Electron, React, and TypeScript to explore AI-powered chat and workspace workflows. It connects a local OpenAI-compatible host to provide chat completions and embeddings. The app organizes conversations, allows message editing, and stores workspace data in SQLite. It includes tools for semantic search, workspace inspection, and prompt orchestration. Trunky supports local LLM and embedding models, with tested compatibility for models like hermes-3-llama-3.1-8b, qwen3.5-9b, and text-embedding-bge-m3. 

The renderer uses React hooks and memoization to manage chat performance. The main process handles model requests, persistence, and workspace management. Developers can extend it with custom workspace tools and data integrations. Overall, Trunky is a hands-on sandbox for building and testing AI desktop app architecture.

![alt text](<../assets/img/posts/Screenshot 2026-04-07 at 00.22.16.png>)

