# 02: Model provider landscape and upcoming launches

Verified 2026-08-28 unless labelled. Sources in 08_sources.md. Items marked INFERENCE are analysis, not sourced fact. The research environment blocked direct page fetches for some domains, so several rows rest on search-result snippets of the named source; confidence labels reflect that.

## Provider table

| Provider | Latest shipped | Next expected | Cadence | How they announce | Launch-partner behaviour | On CF today? | Contact titles/routes | Conf. |
|---|---|---|---|---|---|---|---|---|
| Google (Veo/Gemini image) | Veo 3.1 (15 Oct 2025); Veo 3.1 Lite (Mar/Apr 2026); Nano Banana Pro (Gemini 3 Pro Image, ~Nov 2025); Gemini Omni introduced at I/O May 2026 | No Veo 4 confirmed; brand steering toward Gemini Omni | ~1 media-model event per quarter | DeepMind/Google blogs, I/O keynotes, Gemini API changelog, X | Names day-one partners (fal, Freepik, Canva, invideo) and quotes partner CPOs in Google Cloud launch posts | Yes (Veo 3.1 Fast, Nano Banana 2 and Pro, Gemini Omni Flash) | Logan Kilpatrick (Product Lead, AI Studio and Gemini API); a Strategic Partner Program Manager role exists for Gemini API | HIGH/MEDIUM |
| Kling (Kuaishou) | Kling 3.0 Turbo + Omni One engine (17 Jun 2026); Kling O3 image on aggregators Jul/Aug | See Kling section below: 3.5-class video refresh predicted, MEDIUM | ~6 to 10 weeks between drops in 2026 | kling.ai blog and release notes, Kuaishou IR releases, @Kling_ai on X, in-app | Own app first (Ultra-tier gated), API days later, third-party wave after (fal, Replicate, Picsart, PixVerse, Pollo) | Yes (Kling 3.0 video, Kling V3 Omni image "New") | API/BD: klingai_api_platform@kuaishou.com (MEDIUM-HIGH); business inquiry form on dev portal; Tony Pu, Community & Partnerships (MEDIUM, verify) | HIGH |
| ByteDance (Seedance/Seedream) | Seedance 2.5 (31 Jul 2026: native 30s single pass); Seedream 5.0 Pro (flagship image tier, Feb 2026 wave) | Cadence suggests a Q4 point release (INFERENCE, LOW) | Major paired image+video drop every 4 to 5 months | seed.bytedance.com blog, Dreamina/CapCut in-app, BytePlus/Volcano for API | fal, Replicate, WaveSpeed, Freepik, Higgsfield near day one | Yes (SeeDance 2.0, SeeDream 5.0 Pro "New") but NOT Seedance 2.5 yet | BytePlus ModelArk sales; Hasnain Gilani, Head of Partnerships BytePlus (MEDIUM) | HIGH |
| Alibaba (Wan/Happy Horse) | Wan 3.0 (24 Aug 2026: 30s, 1080p+audio one pass, doc-to-video Omni-Reference); Happy Horse 1.0/1.1 (Apr 2026 stealth arena drop, attributed to Alibaba) | Quarterly cadence continues | Quarterly | Alibaba Cloud blog, Model Studio docs, @Alibaba_Wan, HuggingFace open weights, stealth arena drops | fal "Official API Partner" for Happy Horse with countdown launch; Atlas Cloud day-one for Wan 2.7 | Happy Horse 1.0 yes; Wan NOT visible on CF API page (gap to close) | Alibaba Cloud Model Studio intl GTM (title); NL presence helps | HIGH/MEDIUM |
| Runway | Gen-4.5 (announced 1 Dec 2025; AA t2v leader; ElevenLabs audio) | Unannounced | ~1 major model/year plus features | Changelog, research blog, CEO on X | Rarely uses third-party launch partners; Adobe locked "preferred API creativity partner" exclusivity Dec 2025 | No | Creative Partners Program; enterprise form | HIGH |
| Luma | Ray3.2 (Jun 2026); Ray3.14 (Jan 2026) | Unannounced | Every 4 to 5 months | lumalabs.ai/news, X, API changelog | Adobe partner model; AWS Bedrock; Envato carries Ray3 | No | Jason Day, Head of EMEA, London (HIGH); best named EMEA target | HIGH |
| MiniMax (Hailuo) | H3 / Hailuo 3.0 (31 Jul 2026, omni-modal, 2K, 15s); base weights open-sourced 3 Aug | Unannounced | ~2 major drops/year | Blog, @Hailuo_AI on X, HuggingFace | Creative Partners Program; aggregators de facto day one via open weights; already partners Envato, fal | No | CPP application form; API@minimaxi.com (LOW, verify) | HIGH |
| xAI (Grok Imagine) | Grok Imagine Video 1.5 GA (16/17 Jun 2026; 720p 15s native audio; $4.20/min) | Unannounced | Fast, in-house only | x.ai/news, Musk/xAI on X | None: closed distribution | Studio tutorial mentions Grok Imagine (MEDIUM) | Skip for partnership: no partner motion | HIGH |
| OpenAI (Sora) | Sora 2 (Sep 2025). WINDING DOWN: app shut 26 Apr 2026, Sora 2 API removal scheduled 24 Sep 2026 | Whatever video ships next is unannounced | n/a | Blog, DevDay | invideo was first official Sora 2 partner (MEDIUM) | No | Do not build on Sora API; watch DevDay 29 Sep | HIGH |
| Black Forest Labs (FLUX) | FLUX 3 (23 Jul 2026: multimodal, first BFL video, early access); FLUX.2 (Nov 2025) | FLUX 3 Image GA + open weights announced for H2 2026: a concrete day-one pitch moment | ~2 flagship waves/year | bfl.ai blog, press wire, HuggingFace | Runs named launch-partner rosters (fal, Replicate, Together, Krea, Freepik, Adobe) | No | Licensing/API pages; EU lab (Freiburg) | HIGH |
| Midjourney | V8.2 default (24 Jul 2026); i2v 5s to 21s | Unannounced | Frequent point releases | Discord office hours, docs | None; no public partner API verified | No | Skip | HIGH |
| Ideogram | Ideogram 4.0 (3 Jun 2026: open-weight, best-in-class in-image text, transparency, 2048px) | Unannounced | ~2 majors/year | ideogram.ai/news, X | Aggregators carry it; open weights broaden | No | partnership@ideogram.ai (published, HIGH) | HIGH |
| Recraft | V4.1 Utility Pro (14 May 2026; #3 lab on AA Image Arena; only native production-ready SVG vector model) | Unannounced | ~2 majors/year | Blog, press releases | Replicate wrote day-one launch blog for V4 | No | API/enterprise contact pages | HIGH |
| PixVerse | V6 (30 Mar 2026) | Unannounced | ~2/year | PR Newswire, blog | Is itself an aggregator (hosts Kling models): conflict | No | Skip (competitor-aggregator) | HIGH |
| Lightricks (LTX) | LTX-2.5 (~11 Aug 2026: 22B open weights, 4K HDR, ~6.8s generation) | Unannounced | ~2 to 3/year | Blog, GitHub, ComfyUI, HuggingFace | ComfyUI day-one workflow templates are their signature | No | DevRel/open-source team | HIGH |
| Tencent Hunyuan | HunyuanImage 3.0 (Jan 2026, open-sourced); HunyuanVideo 1.5 (Nov 2025) | Unannounced | Continuous open source | GitHub/HuggingFace first | Open weights = ComfyUI ecosystem; Tencent now a Kling investor | No | Tencent Cloud intl BD | MEDIUM-HIGH |

## Kling deep dive

### Verified 2026 timeline
- 5 Feb: Kling 3.0 series (Video 3.0, Video 3.0 Omni, Image 3.0, Image 3.0 Omni; up to 15s, native audio in 5 languages, 6-shot storyboard, reference consistency). Ultra subscribers first. 60M+ creators claimed. Source: Kuaishou IR. HIGH.
- Late Jan to early Mar: Video 3.0 Motion Control rollout (dates conflict across sources, MEDIUM).
- 27 Apr: native 4K video generation. HIGH.
- 17 Jun: Kling 3.0 Turbo plus upgraded 3.0 Omni ("Omni One" engine, 3 to 15s, 4K editing). HIGH.
- 2 to 3 Jul: ~$3B financing at $18B post-money valuation; investors include Tencent, Alibaba, Baidu. HIGH.
- Jul/Aug: Kling O3 / V3 Omni image live on fal, Replicate, Pollo (this is CF's "Kling V3 Omni, New" listing). HIGH.
- 19 Aug (inside the 14-day window): Kuaishou Q2 earnings: Kling quarterly revenue over RMB 850M, up 200%+ YoY; H1 cumulative over RMB 1.5B; management reaffirmed deepening AI investment in H2. HIGH.
- 14 to 28 Aug: no new-model teaser found on kling.ai blog, X coverage, or IR. Blog posts of 13 and 20 Aug could not be read (fetch blocked); a teaser hidden there would change this read. MEDIUM.

### The "next model" read
The CEO's "Kling is launching a new model next week, maybe" is not publicly corroborated: treat the specific model as UNANNOUNCED (the CEO's words, plus inference below).

Most plausible: a Kling 3.5-class video refresh (or Omni One engine rev), headlined by longer duration (30s-class) and stronger native audio/4K, possibly with Turbo tiers. Confidence: MEDIUM. Evidence:
1. Cadence: major drops every 6 to 10 weeks all 2026; by early Sept the gap since 17 Jun is the longest of the year. HIGH facts.
2. September precedent: Kling 1.5 shipped Sept 2024, Kling 2.5 Turbo Sept 2025. MEDIUM-HIGH.
3. Competitive forcing: in the last four weeks every rival leapfrogged Kling's 15s cap (Seedance 2.5 native 30s on 31 Jul; MiniMax H3 31 Jul; Wan 3.0 30s on 24 Aug; LTX-2.5 4K on 11 Aug). A duration/audio response is the obvious gap-closer. HIGH facts, MEDIUM inference.
4. Pressure: the $3B round and the earnings narrative (Kling growth carrying the story) demand a H2 headline event. MEDIUM inference.

### The three capability directions Concept 1 must cover
Design the challenge so it works whichever ships:
1. Longer duration (30s-class): challenge format = "full make-along in one clip" (a craft project start to finish, multi-shot storyboard).
2. Audio upgrade (multilingual speech, sound): challenge format = "narrated maker story" or craft ASMR; templates carry voice-over prompts.
3. Image/Omni or Motion Control refresh: challenge format = "bring your design to life" (animate a marketplace design or product photo; motion-transfer a mascot).
All three share the same infrastructure: landing page, template pack, hashtag, tracking. Only the template pack's headline prompt changes on launch day.

### Kling partner routes
- API/developer platform: klingai.com/global/dev; business-inquiry form; API/BD email klingai_api_platform@kuaishou.com (MEDIUM-HIGH).
- Affiliate program (kling.ai/explore/kling_affiliate_program); Creative Partner Program (application-based); partnership page for creator networks (kling.ai/app/future-partner/creator); NextGen fund (up to $1M project funding). All HIGH.
- "Talent Network" under that exact name: could not verify.
- Named person: Tony Pu, "Community & Partnerships @ Kling AI, ex-CapCut" per public LinkedIn headline (MEDIUM; verify before outreach).
- Pattern: CF's current V3 Omni listing is the standard post-launch API wave. The upgrade to pitch is a named launch-partner slot in the announcement itself, with keys 2+ weeks pre-launch. INFERENCE.

## How day-one launch partnerships work in 2026

The pattern: a lab picks 3 to 10 platforms 1 to 4 weeks pre-launch; partners get keys or weights under NDA embargo, build, prepare demo content, and publish within the same hour as the lab's own post. Labs get reach and third-party validation; partners get the "day-1" badge, an SEO landing page, and a traffic spike. Chinese labs stage-launch (own app first, sometimes top-tier subscribers only; API days later; third-party wave after). Open-weight labs treat ComfyUI and HuggingFace as the launch partners. 2026 wrinkle: stealth arena drops (ship anonymously to Artificial Analysis Arena, farm a #1, then a chosen partner "reveals" with a countdown, as with Happy Horse).

What partners give: launch-week credits or contests, co-branded posts, dedicated model landing pages, tutorials, sometimes committed inference volume. What labs give: early access, embargoed briefings, co-marketing, occasionally short exclusivity.

Real examples (last 12 months, sources in 08):
1. fal x Happy Horse 1.0 (Apr 2026): countdown launch, "Official API Partner" branding. HIGH.
2. fal x Kling 3.0 (Feb 2026): day-one blog while Kling's own app was still Ultra-gated. HIGH.
3. Picsart x Kling 3.0 Omni (2026): consumer platform integration with own launch blog. HIGH.
4. Atlas Cloud x Wan 2.7 (Mar 2026): "available from day one". HIGH.
5. ComfyUI x LTX-2.5 (11 Aug 2026): official workflow templates day one. HIGH.
6. Runway x ElevenLabs (Dec 2025): capability partnership announced at model launch. MEDIUM.
7. Replicate x Recraft V4 (Feb 2026): aggregator launch blog in the release window. HIGH.
8. WaveSpeed x Happy Horse (Apr 2026): parallel day-one carrier; labs stack multiple partners. HIGH.

What CF should offer to enter rosters (INFERENCE): committed inference volume, a launch-week credits contest for a vertical audience labs cannot reach (crafters), co-branded tutorials, embargo discipline. Ask for keys 2+ weeks early and a named slot in the lab's announcement post. Calendar hooks now: the predicted Kling September drop, and FLUX 3 Image GA/open weights (announced for H2 2026).

## Providers CF does not have: day-one pitch shortlist

1. Recraft: only native production-ready SVG model; crafters need cut files. Best single audience fit. HIGH fit.
2. Ideogram: best in-image text rendering plus transparency; ideal for POD, stickers, typography crafts; published partnership email. HIGH fit.
3. Black Forest Labs: FLUX 3 Image GA/open weights landing H2 2026 = concrete pitchable day-one moment; runs named partner rosters; EU lab. HIGH fit.
4. Alibaba Wan 3.0: freshest flagship (30s, audio, doc-to-video); CEO already names Alibaba as partner; not on CF API page yet. MEDIUM-HIGH.
5. MiniMax H3: 2K video, open weights (self-host option for margin). MEDIUM-HIGH.
6. Lightricks LTX-2.5: open weights, 4K, cheap and fast; consumer-creative adjacency. MEDIUM-HIGH.
7. Luma Ray3.2: named EMEA BD lead in London; Envato (direct competitor) already carries Ray3, so parity matters. MEDIUM.
8. Runway Gen-4.5: prestige anchor, but Adobe exclusivity limits depth. MEDIUM.
Plus non-image/video lanes: ElevenLabs (voice/sfx for tutorials), Tripo or Meshy (text-to-3D for 3D print and laser cut: uniquely on-brand, no other aggregator serves it well). Skip: Sora (API dies 24 Sep 2026), Midjourney (no partner API), xAI (closed), PixVerse (competitor).
