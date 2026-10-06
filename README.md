# Duarte

My background is in Industrial Engineering and Management, including work in R&D and innovation consulting. I build software for research and operational workflows, with a focus on controlled execution, traceable evidence and geospatial data.

## Featured work

- **[WildfireWatch](https://github.com/WhiteBlindness/wildfire-watch):** Geospatial monitoring for NASA FIRMS thermal detections, which are observations rather than confirmed fires. It separates measured, derived and operational data, tracks provenance and feed freshness separately from ingestion health, and retains last-known-good snapshots. Includes API/CSP safeguards, accessibility, MapLibre 6 and WebGL2 fallback. [Live map](https://wildfire-watch.duartemonteiro.workers.dev)
- **[JARVIS](https://github.com/WhiteBlindness/jarvis):** Local-first Rust execution core with a supervised Python worker, versioned typed protocol, default-deny capabilities, human approval, local RPC, SQLite audit and hostile-worker tests. No model is integrated yet.
- **[CallBrief](https://github.com/WhiteBlindness/callbrief):** Python CLI for screening R&D funding calls against local documents, with bounded model/tool orchestration, citation-validated findings and offline evaluations. Remote providers require explicit approval.

## Building now

- **JARVIS:** Windows AppContainer and Linux Landlock/seccomp isolation is proposed in [open PR #3](https://github.com/WhiteBlindness/jarvis/pull/3).
- **WildfireWatch:** ANEPC operational incidents and deterministic reconciliation are proposed in [open PR #6](https://github.com/WhiteBlindness/wildfire-watch/pull/6).

## More projects

- **[Murdoku / Alibi](https://github.com/WhiteBlindness/murdoku):** Deterministic puzzle generation, a unique-solution TypeScript solver and structural validation. The hand-authored catalogue of 60 isometric cases passed visual QA on the branch in [open PR #1](https://github.com/WhiteBlindness/murdoku/pull/1). [Play Alibi](https://murdoku-seven.vercel.app)
- **[Atlas Arcade](https://github.com/WhiteBlindness/atlas-arcade):** Live geography games with real-world data and distance scoring. [Play](https://atlasarcade.app)
- **[Roundcraft](https://github.com/WhiteBlindness/roundcraft):** CS2 round-decision modelling from demo files. Its deterministic 100-point score allocates 50 points to the main decision, 20 to evidence and 30 to follow-up; human tactical review is separate from automated scoring. No case has completed tactical review; no public demo yet.
- **[OmniQuiz](https://github.com/WhiteBlindness/omniquiz):** Browser trivia with deterministic scoring, themed worlds and server-side answer data. [Play](https://omniquiz-nine.vercel.app)

## Technologies

Rust · Python · TypeScript · React · Next.js · Cloudflare Workers, KV and D1 · SQLite · MapLibre · Playwright · GitHub Actions
