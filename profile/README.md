<h1 align="center">HybridMind Labs</h1>

<p align="center">
  <strong>Building modular self-hosted platforms, developer tools, and gaming-community systems.</strong>
</p>

<p align="center">
  <a href="https://hybridmarket.org/"><img src="https://img.shields.io/badge/website-hybridmarket.org-3b82f6?style=flat-square" alt="Website"></a>
  <a href="mailto:support@hybridmarket.org"><img src="https://img.shields.io/badge/support-email-6366f1?style=flat-square" alt="Support"></a>
  <!-- TODO: swap in the real invite — https://img.shields.io/discord/<server-id>?style=flat-square&logo=discord&logoColor=white&label=Discord -->
  <img src="https://img.shields.io/badge/license-Proprietary-64748b?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/extensions-10-22c55e?style=flat-square" alt="10 extensions">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue.js">
  <img src="https://img.shields.io/badge/Inertia.js-9553E9?style=flat-square&logo=inertia&logoColor=white" alt="Inertia.js">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL">
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/HybridMindLabs/HybridCore?style=flat-square&logo=github&color=f59e0b" alt="Core repo stars">
  <img src="https://img.shields.io/github/followers/HybridMindLabs?style=flat-square&logo=github&label=followers" alt="Org followers">
</p>

---

## HybridCore

**HybridCore** is a modular, self-hosted platform for gaming communities — accounts
and roles, OAuth (Steam/Discord/Google), a live server browser, news, profiles,
private messaging, achievements, moderation tools, an admin panel, and a full
**Extension SDK** so the platform grows with your community.

At its heart is a secure **game-server bridge**: the site queues commands
(vote/store/giveaway rewards, bans) and a lightweight in-game plugin pulls,
executes and confirms them — so what happens on the website happens in-game.

**→ [HybridMindLabs/HybridCore](https://github.com/HybridMindLabs/HybridCore)**

### Why HybridCore

- **You own it.** Self-hosted on your own server — no vendor lock-in, no monthly
  platform fee, your community's data stays yours.
- **It grows with you.** The Extension SDK is the same interface every official
  extension is built on — Shop, Tournaments, Stats and the rest aren't
  special-cased, so anything they can do, a custom extension can too.
- **The website and the game server agree.** The bridge's poll/ack protocol
  means a reward, a ban, or a match result isn't "eventually consistent" —
  it's confirmed.

## Extensions

Official extensions built on the HybridCore SDK — each installs into any HybridCore
site and ships with its own auto-versioned releases.

| Extension | What it does | License |
| --- | --- | --- |
| **[Shop](https://github.com/HybridMindLabs/hybridcore-shop)** | Cart-based store for one-time and recurring packages — bundles, sale pricing, gift-to-friend, wishlist, discount codes, per-server reward delivery | Premium |
| **[Tournaments](https://github.com/HybridMindLabs/hybridcore-tournaments)** | Team tournaments with invitations, single-elimination brackets, automatic server assignment, and hands-free match tracking via the bridge | Free |
| **[Giveaways](https://github.com/HybridMindLabs/hybridcore-giveaways)** | Prize giveaways with eligibility rules, weighted entries, automatic/manual draws and in-game delivery | Free |
| **[Vote](https://github.com/HybridMindLabs/hybridcore-vote)** | Reward players for voting on server listing sites, with in-game rewards and a top-voters leaderboard | Free |
| **[Donations](https://github.com/HybridMindLabs/hybridcore-donations)** | Freeform community donations with a monthly goal, a public donor wall, and a homepage progress widget | Free |
| **[Staff](https://github.com/HybridMindLabs/hybridcore-staff)** | A polished public team page — grouped members with roles, bios and socials | Free |
| **[FAQ](https://github.com/HybridMindLabs/hybridcore-faq)** | Admin-managed, categorized FAQ page with search, category icons, and helpful/not-helpful feedback | Free |
| **[ServerCast](https://github.com/HybridMindLabs/ServerCast)** | Send a message from the admin panel to one, several, or all game servers at once, over the bridge | Free |
| **[Player Stats](https://github.com/HybridMindLabs/hybridcore-stats)** | HLstatsX-style player statistics for every bridge-connected server — Hall of Fame, seasons, ranks, per-player pages | Premium |
| **[HybridGuard](https://github.com/HybridMindLabs/HybridCore-HybridGuard-web)** | Production web console and API for HybridGuard CS 1.6 — moderation records, player intelligence, realtime updates, appeals API | Premium |

## Game-server bridge plugins

The same secure poll/ack protocol, one plugin per game:

| Game | Tech |
| --- | --- |
| **Counter-Strike 1.6** | AMX Mod X (Pawn) |
| **Counter-Strike 2** | CounterStrikeSharp (C#) *(coming soon)* |
| **Rust** | Oxide / uMod (C#) |
| **FiveM** | CitizenFX (Lua) |
| **Minecraft** | Spigot / Paper (Java) |

## Support

- **Issues / bugs** — open an issue on the relevant repo above.
- **Email** — [support@hybridmarket.org](mailto:support@hybridmarket.org)
<!-- - **Discord** — join the community: <link> -->

---

<p align="center">
  <em>Own your community. Self-hosted, extensible, yours.</em>
</p>
