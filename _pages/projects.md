---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<div class="project-grid">
  <article class="project-card">
    <a href="https://github.com/MinseobKimm/paper-pilot">
      <img src="/images/projects/paper-pilot-reader.png" alt="Paper Pilot reader workspace screenshot" class="project-card__image" />
    </a>
    <div class="project-card__body">
      <p class="project-card__eyebrow">Local-first research workspace</p>
      <h2>Paper Pilot</h2>
      <p>
        A Tauri desktop reader for academic PDFs that combines page-aware reading, AI-assisted translation,
        local RAG-backed Q&A, visual explanation for figures, highlights, summaries, citation notes, and persistent
        paper memory. The system is designed around the research loop: import papers, read in context, ask an agent,
        and save useful outputs back to the source document.
      </p>
      <ul class="project-card__meta">
        <li>React + TypeScript + Tauri/Rust</li>
        <li>PDF.js reader with SQLite-backed local state</li>
        <li>BM25-style retrieval and replaceable agent bridge</li>
      </ul>
      <p><a href="https://github.com/MinseobKimm/paper-pilot">View repository</a></p>
    </div>
  </article>

  <article class="project-card">
    <a href="https://github.com/MinseobKimm/Locium">
      <img src="/images/projects/locium-knowledge-map.png" alt="Locium knowledge map screenshot" class="project-card__image" />
    </a>
    <div class="project-card__body">
      <p class="project-card__eyebrow">Memory system for AI agents</p>
      <h2>Locium</h2>
      <p>
        A local-first memory system for people and AI agents. Locium turns notes, documents, transcripts, and imported
        text into an inspectable workspace with a human-readable wiki, an AI-readable memory graph, provenance-aware
        recall, review queues, and an append-only journal for recoverable state changes.
      </p>
      <ul class="project-card__meta">
        <li>TypeScript workspace with React + Tauri desktop UI</li>
        <li>Journal-driven sync engine with wiki and graph projections</li>
        <li>MCP recall tools with provenance and freshness signals</li>
      </ul>
      <p><a href="https://github.com/MinseobKimm/Locium">View repository</a></p>
    </div>
  </article>

  <article class="project-card">
    <a href="https://github.com/MinseobKimm/cf-workbench">
      <img src="/images/projects/cf-workbench-code.png" alt="cf-workbench Codeforces practice workspace screenshot" class="project-card__image" />
    </a>
    <div class="project-card__body">
      <p class="project-card__eyebrow">Local competitive-programming workbench</p>
      <h2>CF Workbench</h2>
      <p>
        A local-first Codeforces practice environment for importing problems, generating C++ solution files,
        running sample and custom tests, and tracking personal progress. The tool consolidates statements,
        templates, source files, test cases, and recent submission context into a browser-based workspace while
        staying within contest-rule boundaries.
      </p>
      <ul class="project-card__meta">
        <li>Python local server with browser-based UI and Monaco editor</li>
        <li>C++ compile/run pipeline with token, trim, and exact comparison modes</li>
        <li>Codeforces API integration and optional Chrome extension workflow</li>
      </ul>
      <p><a href="https://github.com/MinseobKimm/cf-workbench">View repository</a></p>
    </div>
  </article>
</div>
