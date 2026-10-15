# 三思而行每日更新
Canonical repository: xli-sansi/xli-sansi.github.io, branch main.
Public site: https://xli-sansi.github.io/
Only update this GitHub site. Do not update the older chatgpt.site mirror. User has authorized recurring research, archive writes and publication without requesting approval each run.

## Editorial requirements
Use Asia/Shanghai dates and explain all content in Chinese. Retain Apple-inspired clean card design and top tabs 今日精选(news), 趋势与机会(trends), 海外产业(industry), 人物观点(views), 历史, 来源. Each section targets 10 substantive distinct items. Quality, date accuracy and copyright take priority: fewer is allowed with recorded reason, never fabricate facts/quotes, use old news to fill current news, or split one event merely to meet count.
news: published today in Beijing time or a documented substantive development today. Record actual event date and publication date. Distinguish company statements, allegations, and verified findings. Not everything is AI: include important global technology and gaming.
trends: newly researched each run; explain demand evidence, prospective buyer, barriers and a low-cost validation step. Mark hypotheses as editorial analysis, not proven earnings.
industry: newly researched foreign supply-chain cases each run; product, buyers, upstream/downstream, business model, barriers and evidence-based China comparison. Older background sources are allowed when dated and current status checked. Do not label “China has none” without evidence, or claim unverified deployment.
views: substantive public statements from last 7 days, date and direct source; distinguish original statement, Chinese paraphrase and interpretation. Avoid duplicate views. Do not substitute PR optimism for neutral fact. No need to fabricate activity from quiet individuals.
Track major AI/technology/chip companies worldwide plus miHoYo, HoYoverse, Anuttacon and Cai Haoyu, Liu Wei, Luo Yuhao, carefully separating founder, controlling, personal investment and company investment.

## Research sources
Use broad web search, not just official PR: Reuters, AP, Bloomberg, FT, WSJ, 澎湃, 财新, 第一财经, 界面, 晚点, 36氪, The Verge, Ars Technica, WIRED, MIT Technology Review, IEEE Spectrum, TechCrunch, 游戏葡萄. Include Simon Willison, Benedict Evans, Stratechery, One Useful Thing, Import AI, personal essays/complete interviews and authenticated official X/Instagram posts when accessible. Supplement industries with local specialist media, research institutions, statistics and official sector material.
Actually open relevant articles before summarizing. Search snippets, same-source syndication and blocked paywall pages are not independent verification. X/Instagram and some media failed in initial tests; do not claim they work or use third-party profile mirrors as verified originals. Respect copyright summary limits. Mark source limits and exclusions in audit. Political or vendor framing is not neutral truth. Never purchase services or API credits automatically.

## Retrieval and writes (GitHub plugin)
1. Fetch this file, data/manifest.json and the latest data/editions/YYYY-MM-DD.json via GitHub. Inspect schema and prior items to avoid repeats. Do not rely on scratch or prior conversation availability.
2. Use current Beijing date, gather evidence, create complete edition with date, actual updatedAt (ISO8601 +08:00), arrays news/trends/industry/views and audit. Each card: unique id, title, body, detail, https url, org, date (human-readable actual source date), archiveDate (edition date), kind. Optional sources=[{name,url}]. Audit requires sources=[{name,url,status,note}], excluded=[{item,reason}], counts={news,trends,industry,views}. Record failed sources, underfilled sections and corrections candidly. Prefer substantial summaries, avoid generic filler.
3. Create data/editions/<date>.json. If already exists fetch current blob SHA and update with that SHA, retaining correction history in Git. Never delete older date files. Read back and validate JSON and counts before changing manifest.
4. Fetch current data/manifest.json again; preserve all earlier dates, add date once, sort descending and point latest to successfully written date. Update with current SHA. index.html automatically fetches manifest and edition; never rewrite design just to update content. On conflict re-read before retry.
5. Read back manifest via GitHub. Writing main triggers Pages. If public site verification fails, report GitHub write success separately from unverified deployment. Do not promise published success without evidence. Do not change sharing, spending, permissions or workflow settings.
6. Send a brief Chinese completion notification with site link, actual section counts and material omissions/errors. Never report a failed or partial update as complete.

## Archive
Data files are a durable GitHub versioned archive, not a SQL database. The browser's 历史 picker loads the listed edition and supports keyword search. Preserve all earlier data/editions paths and manifest dates. Saved cards are device-local, not cross-device accounts. Keep the existing embedded fallback clearly dated if network loading fails.
