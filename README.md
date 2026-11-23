## Victor Zhang

At Clover Health I built the voice and text AI agent for the main helpline of nearly 160K Medicare members. I'm on leave from physics at Carnegie Mellon.

### Projects

- **[NexusGTO](https://nexusgto.com)**: a six-player no-limit hold'em AI modeled on Pluribus. It plays a blueprint trained offline over 8.05 billion Monte Carlo CFR iterations and searches once two or three players are left after the flop. Against five copies of its own blueprint, the search won 5.73 bb/100 over 14,250 deals (95% interval 2.74 to 8.72). A program built to exploit it won about 115 bb/100 from the blueprint alone, and the search held it to statistically zero (9.2). The trainer, the search and every result are [on GitHub](https://github.com/ZHANGV25/nexusgto), with a script that recomputes each result.
- **[DREWT](https://www.drewt.co)**: the store for our custom Corvette parts and tail lights, with $24.6K from 39 orders. I also built an MCP server with 63 scoped tools, so our nontechnical founder can edit the site through an AI assistant.
- **[Brier Trading Group](https://briertradinggroup.com)**: the platform for a prediction-market prop firm, where traders prove themselves on a simulated $50,000 account. Its engine fills simulated orders against Polymarket's live order books at Kalshi's taker fee. Sign-up opened in November 2026.
- **[BibleBuddy Kids](https://apps.apple.com/us/app/biblebuddy-kids/id6755739837)**: an iPhone app of Bible lessons and quizzes for kids, with 1,416 accounts and 4.8 stars from 127 ratings.
- **[WatchTower](https://github.com/ZHANGV25/yhack-watchtower)**: a camera monitor for elder care that takes its rules in plain English, built on YOLOv8 and Claude by a team of four at YHack 2026.
- **[Jump Trading poker bot](https://github.com/ZHANGV25/poker-engine-2026)**: a bot for a 27-card poker variant, built for the CMU × Jump Trading AI tournament.
- **[Ringpad](https://github.com/ZHANGV25/ringpad)**: a Windows soundboard with instant replay for voice chat, built with Rust and Tauri ([v0.1.1 release](https://github.com/ZHANGV25/ringpad/releases)).

### Open source

- **[livekit/agents #8668](https://github.com/livekit/agents/pull/8668)** (open, in review): voice agents on Claude went silent, or read their reasoning aloud, when `<thinking>` tags arrived split across stream chunks. The fix swaps the plugin's flag for the shared thinking-token filter and adds 7 tests, 5 of which fail on main.

`Python` `TypeScript` `C` `Swift` · Next.js · Django · PostgreSQL · AWS

[vzhang.dev](https://vzhang.dev) · [LinkedIn](https://www.linkedin.com/in/victor-zhang-663928229/) · vhzhang2020@gmail.com
