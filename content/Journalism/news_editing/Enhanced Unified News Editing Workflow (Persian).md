---
title: "Enhanced Unified News Editing Workflow (Persian)"
category: "Journalism"
tags: ["guide", "checklist", "workflow", "optimization", "intermediate"]
language: "fa (RTL with ZWNJ)"
updated: 2025-11-01
summary: "A production-grade, Persian-focused editing workflow for online newsrooms: structure, verification, legal/risk micro-checks, language/technical fixes (ZWNJ), release, and corrections—with concrete checkpoints and anti-patterns."
---

# Enhanced Unified News Editing Workflow (Persian)

This guide operationalizes a **nine-step** editing workflow for Persian newsrooms. It merges structure, verification, legal/risk control, language and technical polish (including **ZWNJ U+200C**), and a predictable release/corrections process. Every step includes **checkpoints**, **tips**, and **quick fixes** so editors can move fast without breaking trust. :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1}

> **Time budget:** 30–90 min for a standard report; longer for investigations. :contentReference[oaicite:2]{index=2}

---

## Prerequisites

- **Platform:** CMS/editor with RTL rendering and **ZWNJ (U+200C)** support; spellcheck for **فارسی معیار**. :contentReference[oaicite:3]{index=3}
- **Policies & tools:** Style sheet; corrections policy; **verification + risk mini-checklist** accessible to editors. :contentReference[oaicite:4]{index=4}
- **Skills:** ویرایش فنی/زبانی/محتوایی; fact-checking; headline writing. :contentReference[oaicite:5]{index=5}
- **Boundaries:** Editing ≠ authorship—never alter meaning, quotations, or registered names. :contentReference[oaicite:6]{index=6}

---

## Step 1 — Prepare the Editing Environment

**Actions**
1. Load the style sheet + “common errors” list (e.g., «می‌باشد/و یا/بر روی» → «است/یا/روی»). :contentReference[oaicite:7]{index=7}  
2. Map a hotkey for **ZWNJ (U+200C)** and verify rendering for «می/ها/تر/ترین/ی». :contentReference[oaicite:8]{index=8}  
3. Open primary sources (docs, data, audio) for instant verification. :contentReference[oaicite:9]{index=9}  

**Checkpoint:** You can insert ZWNJ, see it in preview, and you have sources at hand.

**Quick fix:** If ZWNJ fails, paste **U+200C** from clipboard; replace stray NBSPs. :contentReference[oaicite:10]{index=10}

---

## Step 2 — Cold Read & Define the Lead (لید)

**Actions**
1. Read once **without editing**; extract 5W+H.  
2. Draft/confirm a **one-sentence لید in paragraph 1** (no background).  
3. Flag all **unattributed/unclear** claims for the verification queue. :contentReference[oaicite:11]{index=11}  

**Checkpoint:** Crisp one-sentence لید + list of flagged items.

**Quick fix:** Park edits during cold read; reading aloud surfaces کژتابی fast. :contentReference[oaicite:12]{index=12}

---

## Step 3 — Restructure to Inverted Pyramid

**Actions**
1. Move essentials up; push context/background down.  
2. Split long paragraphs; **one new fact per paragraph**.  
3. Remove duplication and tangents. :contentReference[oaicite:13]{index=13}  

**Checkpoint:** Each paragraph adds new info; no repeats.

**Tip:** Use outline/drag instead of rewriting to enforce hierarchy. :contentReference[oaicite:14]{index=14}

---

## Step 4 — Verify Facts & Attribute

**Actions**
1. Check **names, titles, numbers, dates** against primary sources.  
2. Attribute every **non-obvious claim** and **all quotes**.  
3. Social-only claims: get a **second corroboration** or **hedge wording** («به گفته… / طبق سند…»). :contentReference[oaicite:15]{index=15}  

**Checkpoint:** Mini-table complete (Claim → Source → Corroboration); all critical claims sourced.

**Quick fix:** Remove/soften uncorroborated absolutes until verified. :contentReference[oaicite:16]{index=16}

---

## Step 5 — Fix Language (ویرایش زبانی)

**Actions**
1. Shorten long sentences (**aim ≤~20 words** for news).  
2. Resolve **کژتابی/ابهام**; propose a clear replacement, not only “reject”.  
3. Normalize register to formal; **preserve author’s مقصود**/voice. :contentReference[oaicite:17]{index=17}  

**Checkpoint:** Readable, unambiguous prose; voice intact.

**Anti-pattern:** Bureaucratese (e.g., «می‌نماید/می‌باشد»)—prefer فعل ساده. :contentReference[oaicite:18]{index=18}

---

## Step 6 — Apply Technical Rules (ویرایش فنی)

**Actions**
1. **Punctuation:** period for declaratives; comma after vocatives/intro clauses; quote marks «…».  
2. **Spacing:** **one space after**, **none before** punctuation; use **ZWNJ** for affixes/compounds.  
3. **Numbers/dates/units** per دستور خط; prevent bad line breaks. :contentReference[oaicite:19]{index=19} :contentReference[oaicite:20]{index=20}  

**Checkpoint:** No spacing/punctuation violations on scan.

**Quick fix:** Regex pass for double spaces and « و یا »; re-insert ZWNJ where kerning collapses. :contentReference[oaicite:21]{index=21}

---

## Step 7 — Finalize Headline, Lede, and Metadata

**Actions**
1. Write headline **≤70 chars**, **no terminal period**; avoid jargon/ambiguity.  
2. Align snippet/لید with the headline’s promise.  
3. Complete **tags, alt text, captions, internal links**, and add a **/corrections** hook in the template. :contentReference[oaicite:22]{index=22}  

**Checkpoint:** Title truncates cleanly on mobile; metadata complete.

**Quick fix:** Front-load the key noun; convert stacked nouns to verb phrasing; A/B two headlines (news vs utility). :contentReference[oaicite:23]{index=23}

---

## Step 8 — Pre-Publish Quality Gate

**Actions**
1. Run **verification mini-check** (each critical claim ↔ source/corroboration).  
2. Run **legal/risk** micro-pass (defamation/privacy flags → mitigation).  
3. **Second-pair** proof for sensitive lines. :contentReference[oaicite:24]{index=24}  

**Checkpoint:** Zero unresolved flags; editor sign-off recorded.

**Kill switch (use ruthlessly):**  
- Unverified number  
- Unbalanced quote  
- Legal red flag

---

## Step 9 — Publish & Corrections Protocol

**Actions**
1. Publish; re-scan the **live** page for formatting/links.  
2. If error: add **timestamped Correction** block + link to prior snapshot; log in the register (**SLA ≤48h** after verified error). :contentReference[oaicite:25]{index=25}  
3. Record what changed and why; keep snapshot links permanent. :contentReference[oaicite:26]{index=26}  

**Checkpoint:** Correction visible publicly; log updated.

**Quick fix:** Roll back to last good snapshot if needed; republish with annotation.

---

## Quick Reference (print/desk)

| Area | Action | Validation | KPI |
|---|---|---|---|
| ZWNJ/RTL | Hotkey mapped; preview OK | Sample line renders correctly | 0 ZWNJ errors | 
| Lead | One-sentence لید in ¶1 | 5W+H present | No background in ¶1 |
| Structure | Inverted pyramid | No repeated info | Each ¶ adds new fact |
| Verification | Claim→Source→Corroboration | Table complete | 100% critical claims sourced |
| Language | ≤~20 words; no کژتابی | Read-aloud passes | 0 ambiguous sentences |
| Technical | Punct./spacing/ZWNJ | Regex scan clean | 0 violations |
| Headline | ≤70 chars; no period | Mobile truncation clean | CTR improvement |
| Quality Gate | Verif + legal + peer | Sign-off recorded | 0 open flags |
| Corrections | Timestamped note + link | Entry in log | SLA ≤48h |

---

## Examples (before → after)

- «وی اظهار می‌نماید که…» → «او گفت که…» *(clear verb; shorter)* :contentReference[oaicite:27]{index=27}  
- «بر روی این موضوع تاکید می‌باشد» → «روی این موضوع تأکید شد» *(remove «بر روی/می‌باشد»)* :contentReference[oaicite:28]{index=28}  
- «شورای عالی…» (quote) → keep as registered name; **do not** normalize spelling variants. :contentReference[oaicite:29]{index=29}

---

## Best Practices vs Anti-Patterns

**Do**
- Gate “Publish” on **verification + legal/risk** mini-checks. :contentReference[oaicite:30]{index=30}  
- Use **ZWNJ** consistently; keep a test snippet in every doc. :contentReference[oaicite:31]{index=31}  
- Log corrections with timestamps and previous-version links. :contentReference[oaicite:32]{index=32}

**Don’t**
- Rewrite for taste; protect author voice and meaning. :contentReference[oaicite:33]{index=33}  
- Treat social posts as sources without independent corroboration. :contentReference[oaicite:34]{index=34}  
- Hide corrections in CMS history—**surface them publicly.** :contentReference[oaicite:35]{index=35}

---

## Related Guides

- **Unified News Editing Workflow (baseline):** step-by-step with checkpoints and warnings. :contentReference[oaicite:36]{index=36}  
- **Editorial Principles — 20 Tips:** spacing, punctuation, ZWNJ, and “اصل یکدستی”. :contentReference[oaicite:37]{index=37}  
- **درست‌نویس (ویراستاران):** rules & checklists; what to change vs what not to. :contentReference[oaicite:38]{index=38}

---

## References

- Prompt-2 baseline workflow and checkpoints. :contentReference[oaicite:39]{index=39}  
- Prompt-3 enhanced workflow (parameters, tips, quick fixes, time). :contentReference[oaicite:40]{index=40}  
- Persian editorial resources (spacing, ZWNJ, punctuation; rules & boundaries). :contentReference[oaicite:41]{index=41} :contentReference[oaicite:42]{index=42} :contentReference[oaicite:43]{index=43}

---

## Final Pre-Publish Checklist

- [ ] لید: یک جمله، 5W+H، بدون زمینه  
- [ ] ساختار: هرم وارونه، بدون تکرار  
- [ ] راستی‌آزمایی: جدول ادعا→منبع→تأیید  
- [ ] زبان: ≤~20 واژه؛ بی‌کژتابی؛ لحن رسمی  
- [ ] فنی: نشانه‌گذاری/فاصله/نیم‌فاصله درست  
- [ ] عنوان: ≤70 کاراکتر؛ بی‌نقطه؛ هم‌راستا با لید  
- [ ] درگاه کیفیت: حقوقی/ریسک/بازخوانی ثانویه انجام شد  
- [ ] انتشار: صفحه زنده بدون خطای قالب/پیوند  
- [ ] اصلاحات: سازوکار اصلاح با مُهر زمان فعال

> **Outcome:** Fast, clean, **defensible** copy—verified claims, legal/risk sanity checks, correct Persian technicals, transparent attributions, and a visible, timestamped corrections trail. :contentReference[oaicite:44]{index=44}
