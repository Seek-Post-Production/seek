# SEEK — grab-finding for post-production

**Version 1.0 beta · Windows · free 90-day trial**

SEEK turns your interview transcripts into something you can actually search — by word, by phrase, and by meaning. It's built by a reality TV editor for editors, assistant editors and story producers who are tired of scrolling through transcripts hoping to strike gold.

It runs completely offline. No account, no cloud, no generative AI — nothing leaves your machine.

---

## What it does

- **SEARCH** — fast keyword search across every transcript at once, with timecodes. Filter by speaker or source.
- **SCOUT** — search by *meaning*. Ask for "Billy feeling anxious" and it finds him saying "my hands are sweating" — even though he never said "anxious". Search by mood, tone or topic across every contestant.
- **STITCH** — the Frankengrab builder. Type the line you need and SEEK assembles it from words the person actually said, picking the most natural-sounding joins.
- **STASH** — collect your best grabs under headings, then send them to your edit as markers (Avid, Premiere or Resolve), or save them as a document for your producer.

It also turns timecode-referenced screening notes into markers, so notes can land straight on your sequence.

---

## Installing

**You'll need:** Windows 10 or 11 (64-bit), about 1GB of free disk space, and 8GB of RAM or more recommended.

1. Download **SEEK_Setup_1.0_beta.exe**.
2. Run it. Windows may show **"Windows protected your PC"** — that's because SEEK isn't code-signed yet. Click **More info → Run anyway**.
3. SEEK installs just for you, so you don't need an admin password. Open it from the Start menu.

Everything SEEK needs is included — no extra downloads, and no internet needed after installing.

---

## Getting started

1. **Add your transcripts** — drag them into the SOURCES panel on the left, or click **Browse…**. SEEK reads:
   - Interview transcripts (.docx)
   - Timecoded MIV transcripts (.pdf or .docx)
   - SubCap exports (.txt), subtitles (.srt, .vtt), marker spreadsheets (.csv)
   - Timecode-referenced screening notes (.docx)
2. **Pick a tab** on the right and start searching.
3. **Click a source badge** on any result to copy the source name, ready to paste into your edit. **MATCH SOURCE** narrows your search to that one source.
4. **Stash** the grabs you want, then use **Send to NLE** in the STASH tab.

**Getting markers into your edit:** in the STASH tab, choose **Send to NLE** and pick your system — Avid Marker Text, FCPXML (Premiere / Final Cut) or EDL (Resolve) — then import that file using your editing software's marker or XML/EDL import.

### SCOUT tips
- Describe the grab in plain words: *"someone nervous before judging"*, *"jen feeling happy"*.
- Name a person to focus on them.
- Use the **Tone** menu to find grabs by attitude — competitive, confident, emotional, nervous, angry.
- Add *"not about the judges"* to rule a topic out.

---

## Your trial

SEEK is free for 90 days from your first launch. When the trial ends, SEEK will stop opening and show you how to get your own copy.

**Have an unlock code?** Enter it any time from **Help → Enter unlock code…**, or from the button on the trial-ended message.

Your projects and stashes are kept in your user folder (`%UserProfile%\.seek`), and are kept if you uninstall.

---

## If something's not right

- **SCOUT only seems to match exact words** — check **Help → SCOUT status**. It should mention the bundled language pack.
- **Run a quick health check** — press **Windows + R**, paste this and press Enter:
  `"%LocalAppData%\Programs\SEEK\SEEK.exe" --selftest`
  A checklist pops up (a copy is saved to `%UserProfile%\.seek\SEEK_selftest.txt`). If anything says FAIL, email that file to me.

---

## Feedback

SEEK is in beta and I'd love to hear how it goes — what works, what doesn't, and what you'd want next. A Mac version is on the cards if there's demand.

**Email:** simonw.wright@gmail.com

Cheers, Si

---

© 2026 Simon Wright. All rights reserved. SEEK is beta software, provided as-is during the trial.
