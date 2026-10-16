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

## 用户修订规则（2026-10-15，优先于上述宽泛规则）
四栏均优先北京时间当天有价值的新信息。禁止以“本期复核/本期分析”把旧资料包装为新消息。目标10条但不能凑数。当日确实缺少重要内容时，才可在栏目最后少量附仍有效的背景，明确原始日期、背景性质及当前意义；默认不收无新进展的历史案例。
人物主要关注以下八人及指定主题：
- 黄仁勋 Jensen Huang：算力、芯片、机器人、数据中心与产业链。
- 李飞飞 Fei-Fei Li：空间智能、三维世界理解、建筑与设计技术。
- Andrej Karpathy：AI能力、智能体、编程和工作方式。
- Sam Altman：AI产品、商业化、基础设施。
- Dario Amodei：模型能力、工作替代、风险治理。
- Demis Hassabis：前沿AI研究、科学发现、AGI。
- 吴恩达 Andrew Ng：企业应用、创业、个人效率。
- Elon Musk：机器人、自动驾驶、航天、能源与AI交叉。
其他人物仅在重大突破/重大事件时收录，不以普通公司负责人发言凑数。先当天，近七天的补充靠后并显示实际日期；未取得可靠新发言不代表本人没有发言，说明检索限制。公司动态不能冒充本人观点。米哈游相关企业仍可进新闻栏，人物优先级服从本名单。
主流媒体必须实际检索，不能只列名字。每次至少尝试国际综合媒体、中文主流媒体及科技媒体，逐篇核实后按新闻价值采用，不硬设引用比例。来源页区分常规检索清单、本轮实际检索/可访问情况、本期引用原文；未检查标未检查，失败标失败。保留Reuters/AP/FT/Bloomberg/WSJ、澎湃/财新/第一财经/界面及主流科技媒体和博客；X/Twitter为同平台，Instagram仅采用可核实原帖。发现文章日期互相矛盾时排除并记录。
提交隐私：优先使用GitHub提供的noreply提交邮箱，不能假定API写入自动遵循邮箱隐私设置；实际提交需复核，不修改或重写历史。

## 新增主流媒体（用户2026-10-15要求）
每日实际检索 The New York Times（纽约时报）、The Washington Post（华盛顿邮报）、BBC、The Guardian（卫报）、The Economist（经济学人），并继续覆盖 Reuters、AP、Financial Times、WSJ、Bloomberg 及中文主流媒体。按报道价值筛选科技、产业、商业与八人相关消息，不把观点专栏当事实、不因品牌免除核实。未取得正文仅作发现线索，不冒充已阅读；不可访问或付费限制如实记录，不自动购买订阅。不能只新增来源名字而不在每日任务中执行检索。

## 全球覆盖与检索记录（用户2026-10-15修订）
选材覆盖世界，不以英美媒体为中心；按新闻价值尝试东亚、东南亚、南亚、中东、非洲、拉美和欧洲当地可靠媒体及行业一手材料。可尝试CNA、Nikkei Asia、Rest of World、TechCabal、Al Jazeera、SCMP等，不能把列名当成已采集。各地区不设凑数配额；未完成地区覆盖如实写入audit.regionalCoverage。已测试结论：2026-10-16 NYT/BBC/Economist受检索或读取限制，Bloomberg失败，X 403，Instagram 429；CNA可读但不少内容为Reuters转载，不算独立证据；Rest of World可读但本轮抽查文章较早；界面今日正文可读；第一财经本轮失败。每次重新验证，不把一次失败当永久结论。来源页只记录当轮实际读取情况，不沿用旧成功状态伪装本轮测试。任务每天持续更新，不因成功发布一期而停用。
