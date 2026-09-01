# LDAR Calendar — Initial Source of Truth

**Status:** Concept / idea capture  
**Captured:** 2026-09-01  
**Primary idea owner:** Janice Human C.  
**Channel context:** Discord `#ldar-calendar`  
**Source type:** Messenger chat between idea owner (Janice) and collaborator (phena109). Screenshots archived under `sources/chats/`.

This document is the **initial source of truth** extracted from the idea-owner conversation. Prefer this over later assumptions until superseded by explicit product decisions.

---

## 1. Problem statement (idea owner)

- Janice uses **Android**; partner (“死佬”) uses **Apple**.
- She has long wanted a **shared calendar** both can **input into and sync**.
- Existing options exist but are **not ideal / not to her taste** (唔多岩心水).
- Fallback considered: a **shared notes**-style place.
- Pain: each keeps a separate calendar; she has said the schedule “十九萬次” but there is still **no common place**, so the other person keeps asking.

Collaborator note in chat: calendars feel under-researched — some things seem easy but somehow nobody has done them well.

---

## 2. Core product thesis

**Not “tracking the other person.”** Packaging is **explicit, proactive sharing** (擺到明、主動 share).

- Idea is **valuable and practical** (實用性強); worth trying to build.
- Market can be **larger if packaged correctly** (not as a stalking/tracking app).
- Collaborator: plain “tracking apps” are everywhere; **calendar-level sharing is a smaller / different** play.
- Conceptual blend: **several existing ideas combined** (幾個現有 idea 撈埋一齊); collaborator has not seen anyone play it this way yet.
- Chat line 「合久必分 分久必合」: **idea-owner intent (clarified by collaborator 2026-09-01)** = product/services pattern — functions get **bundled together**, later **split apart** (and the cycle repeats). **Not** a metaphor about human relationships forming/breaking. Earlier SoT misread that line; corrected here.

Reference mental model: **something like Outlook Calendar + Page** (calendar structure + social/page surface), but **not work-first** (Outlook 太 work base).

---

## 3. Relationship & multi-party model

| Principle | Detail from chat |
|-----------|------------------|
| Beyond couples | Must work for **family** and **kids**, not only romantic couples |
| Multi relationships | Sharing can be **multi** (不止一對一) |
| Entering a relationship | Question raised: does joining a relationship mean **always share**, then decide **item-by-item** what to share or not? → Answer direction: **can be multi**; selective control |
| Meeting invites | **Meeting invites are required** (要 meeting invite) |
| One calendar per person | Collaborator synthesis accepted in thread: **from the start, one person ↔ one calendar** (由始至終一個人一個 calendar), with sharing/filters on top — not one merged mega-calendar as the identity |

---

## 4. Sharing mechanics (must-have intent)

### 4.1 Free / busy without full detail (Outlook-like)

Example (Janice): Next month back in town, wants dinner with friends.

- Others may **not** see what each slot is for.
- Others **can** see which evenings are **free**.
- Group can **lock an evening** for dinner.

### 4.2 Graduated access levels (not only “busy”)

- Can **delegate** or **be delegated**.
- Not only “busy” — some people can see **what the event is**.
- **Different people → different access levels**.

### 4.3 Open / discoverable events

Example: hike or party.

- Want certain **daring friends** along.
- Also want to **meet new people** → event can be **open so others can join**.

### 4.4 Push into group contexts (family examples)

Active share into the right group/calendar surface:

| Example | Behavior |
|---------|----------|
| Family festival / 做節 | One person drops into **family group** → that set of people sees it |
| Couple outing (e.g. movie with husband) | Drop into **the couple’s shared calendar** |
| Mum’s doctor appointment | Mum (or someone) drops it in → **family all see it** |

### 4.5 Personal calendar + filters

- Each person keeps **their own calendar**.
- Can **filter who sees what** (我有我自己一個 calendar，可以 filter 到我同邊個見到).

---

## 5. UX / presentation requirements

- **Shared data, different layouts** (data 可以 share，但版面可以唔同).
- Example: her UI can be **少女心 / cute**; partner’s UI can feel **Office Outlook**.
- Implies: one app (or tightly coupled apps) with **skin/layout personalization**, not forcing one visual identity on all participants.
- Cross-platform: **Android + Apple** first-class (idea owner’s real constraint).
- Google Calendar alone is discussed as insufficient / not the desired end state for this problem (raised and set aside in chat).

---

## 6. Scope boundaries & positioning (from chat)

**In scope (intent):**

- Proactive multi-party calendar sharing
- Free/busy + event-detail access tiers
- Meeting invites
- Family / couple / friend group surfaces
- Open join for some events
- Personal calendar identity + filters
- Dual layout personality on shared data
- Practical everyday coordination (meals, outings, medical, festivals)

**Out of scope / explicit anti-positioning:**

- Framing as **covert tracking / 跟蹤 app**
- Pure work-OS clone of Outlook
- “We already fully researched calendars” — treated as open product space

**Later extension mentioned (idea owner):**

- Could extend toward seeing others’ schedules more deeply — **only if packaging stays honest/active-share**, not creepy tracking.

---

## 7. Roles in the conversation

| Person | Role in source |
|--------|----------------|
| **Janice Human C.** | Idea owner / primary problem + feature voice |
| **phena109** (collaborator) | Challenge framing, synthesis (“one person one calendar”), willingness to try building (“我可以挑戰一下”), market packaging caution |

Agreement signals: Janice will “排 calendar 先”; both “諗諗佢” / “得閒諗下” / “好呀”.

---

## 8. Raw message map (chronological reconstruction)

Order inferred from timestamps and reply continuity across six screenshots (≈12:59 → ≈2:04).

1. **Problem:** Android + Apple; want shared calendar both can input/sync; existing not ideal; shared notes alt; no common place despite repeated asks.
2. **Collaborator:** Calendars under-researched; things that seem easy often missing. Google Calendar? (dismissed as “if it worked you wouldn’t be talking”).
3. **UX split:** Shared data, different layouts (cute vs Outlook feel). One app; collaborator finds it solid and is willing to challenge/build. Janice: think when free.
4. **Value:** Idea is valuable; try it. Janice prioritizes practical calendar first; strong practicality; later extend could look like “tracking” if said poorly. Collaborator: tracking apps common; calendar-level is different. Market bigger with right packaging. **Active, explicit share** — not hidden tracking.
5. **Family multi-party:** Not only couples — family, kids. Festival → family group; couple movie → couple calendar; mum doctor → all see. Own calendar + filter who sees. Like Outlook but not work-based. Collaborator: one person one calendar end-to-end. **Need meeting invite.**
6. **Selective multi-share:** Always-share vs item-by-item? → can be multi. Free/busy lock dinner slots. Delegate + see event content by access level. Open hike/party for new friends to join. Feels like **Outlook calendar + page**.
7. **Close:** Combining several existing ideas; Janice agrees; 「合久必分 分久必合」; not seen done this way; think on it; OK.

One outgoing bubble in the earliest screenshot was green-scribbled/redacted — content unknown; not used as truth.

---

## 9. Working product name

**LDAR Calendar** (from Discord channel `#ldar-calendar`). Expand acronym only when idea owner confirms.

---

## 10. Open questions (not answered in source chat)

These are **gaps**, not decisions:

1. Official product name / acronym meaning  
2. Auth identity model (phone, Apple/Google ID, couple/family graph)  
3. Who owns an event when shared across groups  
4. Invite + RSVP flow details  
5. Privacy defaults (private vs free-busy vs full detail)  
6. Whether “Page” means social feed, event page, or group wall  
7. Offline / conflict sync rules across Android–iOS  
8. Monetization  
9. Build approach (native vs cross-platform vs wrapper on Google/Apple calendars)  
10. MVP slice (couple-only first vs family-first)  
11. Invite-only vs subscription-style follow of a calendar (and controls) — see §12  
12. Product metaphor (email-like vs contacts+calendar, etc.) — defer; observe in use

---

## 11. How to use this document

- Treat sections **1–6** as **requirements intent** from the idea owner until revised.  
- Do not silently reframe as a generic shared Google Calendar wrapper.  
- Do not position as employee monitoring or secret location/schedule tracking.  
- Section **12** is **collaborator working notes only** — may not fully align with Janice; nothing set in stone.  
- When specs diverge from this file, update this file or add a dated Decision Record.

---

## 12. Collaborator working notes (provisional — 2026-09-01)

**Authority:** Below is phena109 filling gaps. **May not fully align with Janice.** Prefer §1–6 on conflict. Nothing locked.

| Note | Stance |
|------|--------|
| Calendar ≈ account | One calendar identity ≈ one person (email-like). Plausible; multi-calendar *under* one account left open for later. |
| 合久必分 分久必合 | Services **bundle then split** functions over time — product evolution, not relationship graph. |
| Invites | Needed (matches Janice). |
| Subscriptions | Also a possibility (follow someone’s free-busy / calendar stream); should be **controllable** (what others can subscribe to, revoke, tier). Not validated with Janice yet. |
| Metaphor | Don’t freeze “email vs phone+calendar”; observe later. |
| POC bar | Interaction sketch > MVP. **Locally workable** static page; cookie/localStorage; clear/reset → **same seed**. Fake week labels OK (no real dates). UI should feel appetising, not wireframe-ugly. |
| Groups (new) | **Permission profiles** with default access behaviour. POC set: **Partner**, **Direct family**, **Extended family**. |
| i18n | **English + Hong Kong Traditional Chinese** (zh-HK). Prefer **most common HK terms**; not TW-specific, not Mainland simplified/phrasing; generic Traditional only if no HK-friendly term. |

**Last updated:** 2026-09-01 (SoT extract + 合久必分 correction + provisional collaborator notes).
