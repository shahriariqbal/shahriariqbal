> **Preview 02 · Dynamic cards** — a separate alternative to [Preview 01](OPEN-SOURCE-DEMO.md). The main profile README is unchanged.

## 🌍 Open Source

**Small changes. Upstream impact.**  
Contributing to game engines, AI memory, web documentation, and developer tooling.

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/stride3d/stride/pull/3577"><img width="100%" src="https://github-stats-extended.vercel.app/api/pin/?username=stride3d&amp;repo=stride&amp;theme=tokyonight&amp;hide_border=true&amp;border_radius=14" alt="Live repository card: Stride" /></a>
<p><strong>CONTRIBUTOR · ENGINE & TOOLKIT</strong></p>
<p>Fixed script-cancellation handling after scheduler shutdown. Improved the community toolkit's example launcher.</p>
<p><a href="https://github.com/stride3d/stride/pull/3577">Engine contribution ↗</a> · <a href="https://github.com/stride3d/stride-community-toolkit/pull/455">Toolkit contribution ↗</a></p>
</td>
<td width="50%" valign="top">
<a href="https://github.com/mnemosyne-oss/mnemosyne/pull/1221"><img width="100%" src="https://github-stats-extended.vercel.app/api/pin/?username=mnemosyne-oss&amp;repo=mnemosyne&amp;theme=tokyonight&amp;hide_border=true&amp;border_radius=14" alt="Live repository card: Mnemosyne" /></a>
<p><strong>CONTRIBUTOR · PERFORMANCE</strong></p>
<p>Precompiled Hangul detection on the lexical-recall path.</p>
<p><a href="https://github.com/mnemosyne-oss/mnemosyne/pull/1221">Merged performance improvement ↗</a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/mdn/content/pull/45663"><img width="100%" src="https://github-stats-extended.vercel.app/api/pin/?username=mdn&amp;repo=content&amp;theme=tokyonight&amp;hide_border=true&amp;border_radius=14" alt="Live repository card: MDN Web Docs content" /></a>
<p><strong>CONTRIBUTOR · MDN WEB DOCS</strong></p>
<p>Fixed undefined helpers in the MediaSession play/pause example and made it a runnable live sample.</p>
<p><a href="https://github.com/mdn/content/pull/45663">Merged documentation fix ↗</a></p>
</td>
<td width="50%" valign="top">
<a href="https://github.com/conorbronsdon/avoid-ai-writing/pull/162"><img width="100%" src="https://github-stats-extended.vercel.app/api/pin/?username=conorbronsdon&amp;repo=avoid-ai-writing&amp;theme=tokyonight&amp;hide_border=true&amp;border_radius=14" alt="Live repository card: avoid-ai-writing" /></a>
<p><strong>CONTRIBUTOR & CREDITED CO-AUTHOR</strong></p>
<p>Added a zero-dependency CLI for files and stdin. Separately credited as co-author on an upstream documentation commit.</p>
<p><a href="https://github.com/conorbronsdon/avoid-ai-writing/pull/162">CLI contribution ↗</a> · <a href="https://github.com/conorbronsdon/avoid-ai-writing/commit/e61e8280f05bb16cb61f13af166ad78d5a86cc6f">Co-author credit ↗</a></p>
</td>
</tr>
</table>

**Recent merges**  
[Stride Toolkit #455](https://github.com/stride3d/stride-community-toolkit/pull/455) · [Mnemosyne #1221](https://github.com/mnemosyne-oss/mnemosyne/pull/1221) · [Stride #3577](https://github.com/stride3d/stride/pull/3577)

---

<details>
<summary><strong>What is actually dynamic here?</strong></summary>

**Live tool:** [GitHub Stats Extended](https://github.com/stats-organization/github-stats-extended), the maintained successor recommended by the original GitHub Readme Stats repository.

- The four images are real hosted SVG repository cards, not screenshots or fabricated stats. All four endpoints returned HTTP 200 and valid SVG containing the expected repository data during creation.
- Repository descriptions, languages, star counts, and fork counts come from the card service. They are **project-wide metadata, not my contribution counts**.
- Updates are subject to the provider's caching and GitHub's image proxy; they are not instantaneous.
- The selected projects, role labels, impact summaries, contribution links, and recent-merge links are curated in this preview. New PRs will **not** appear automatically yet.
- Clicking a card opens my linked contribution, rather than implying I own the upstream repository.
- No token, new account, deployed server, or scheduled workflow was added. Embedding images depends on a third-party public service, which can experience outages or rate limits.

**Why not the automatic contributed-repositories widget?**  
The public endpoint for [GitHub Repository Contribution Stats](https://github.com/HwangTaehyun/github-repository-contribution-stats) returned HTTP 402 during testing. It was deliberately omitted rather than leaving a broken widget in the preview. This does not establish that its source code is unusable or that payment would fix the hosted instance.

**My production preference:** keep this visual style, but eventually generate contribution-specific SVG cards in a scheduled GitHub Action and commit the results into the repository. That could show verified merged work and update the recent-merge list while avoiding a third-party image service at viewing time. That workflow is a proposed next step, not something enabled by this demo.

</details>
