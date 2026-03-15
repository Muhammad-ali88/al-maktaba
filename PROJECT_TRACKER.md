# AL-MAKTABA — Islamic Knowledge Platform
# Project Master Tracker — Updated After Session 3
# ═══════════════════════════════════════════════

## PLATFORM STATUS: v2.4 COMPLETE

═══════════════════════════════════════════════════════
## CANONICAL FILE LIST — UPLOAD ALL TO NETLIFY TOGETHER
═══════════════════════════════════════════════════════

  index.html                        ← Dashboard (48% progress)
  Quran_Surah_Explorer_v2.html      ← Quran Explorer (114 surahs + verses)
  prophets_map_NETLIFY.html         ← Interactive World Map (ENHANCED v2)
  prophetic_tree_NETLIFY.html       ← Prophetic Family Tree (REDESIGNED v2)
  prophets_timeline.html            ← 25 Prophets (REBUILT with all tables)
  isra_miraj.html                   ← Al-Isra wal-Mi'raj HTML page
  seal_of_prophets.html             ← Seal of Prophets HTML page
  prophecies.html                   ← Prophecies HTML page
  duas.html                         ← Du'a Collection (75 duas, verified)

RETIRED (do NOT upload):
  prophets_map.html                 ← old map v1
  prophets_map_enhanced.html        ← old map v2
  prophets_map_mobile.html          ← old map mobile
  prophetic_family_tree.html        ← old tree v1
  Prophets_Timeline_Complete.docx   ← replaced by HTML
  Al_Isra_wal_Miraj.docx            ← replaced by HTML
  Muhammad_SAW_Seal_of_Prophets.docx← replaced by HTML
  Prophecies_of_Muhammad_SAW.docx   ← replaced by HTML

═══════════════════════════════════════════════════════
## MODULE STATUS
═══════════════════════════════════════════════════════

[✅ LIVE]  Dashboard                    index.html
[✅ LIVE]  Quran Surah Explorer v2      Quran_Surah_Explorer_v2.html
[✅ LIVE]  Prophets World Map v2        prophets_map_NETLIFY.html
[✅ LIVE]  Prophetic Family Tree v2     prophetic_tree_NETLIFY.html
[✅ LIVE]  25 Prophets Timeline v2      prophets_timeline.html
[✅ LIVE]  Al-Isra wal-Mi'raj           isra_miraj.html
[✅ LIVE]  Seal of Prophets             seal_of_prophets.html
[✅ LIVE]  Prophecies                   prophecies.html
[✅ LIVE]  Du'a Collection              duas.html

[🔜 NEXT]  Urdu throughout all pages   (dedicated session)
[🔜 v3.0]  Reading Mode + Bookmarks    Quran Explorer enhancement
[🔜 v3.1]  Better Search (AR/UR KB)    Quran Explorer enhancement
[🔜 v4.0]  Hadith Explorer             hadith_explorer.html
[🔜 v5.0]  Timeline Tab rebuilt        23-year revelation history
[🔜 v6.0]  Topics Browser              topics.html
[🔜 v7.0]  PWA App Shell               offline install

═══════════════════════════════════════════════════════
## WHAT WAS DONE — SESSION 3 (This Session)
═══════════════════════════════════════════════════════

1. PROPHETS TIMELINE — Complete Rebuild
   - All 52 Word document tables extracted and rendered
   - Master Summary Table: all 25 prophets in one grid
     (#, Name, Arabic, People Sent To, Era, Quran Mentions, Scripture)
   - Individual Prophet Cards: each with full facts table
     (Title, Born, People Sent To, Ulul Azm, Scripture, Miracles, Buried)
   - Quranic verses (Arabic + English translation) for every prophet
   - 3 tabs: Overview Table / Prophet Profiles (searchable grid) / By Era
   - Era color-coding: Primordial / Patriarch / Exodus / Kingdom / Final

2. PROPHETS MAP — Full Enhancement
   - Prophet List Sidebar: click any name → map flies to location
   - Era Filter Buttons: filter by Primordial/Patriarch/Exodus/Kingdom/Final
   - Layer toggles: Migration Routes / Destroyed Nations (independent)
   - Improved popups: full prophet info with Arabic names
   - Mobile sidebar with hamburger toggle + overlay close
   - Custom Leaflet markers with era-color coding
   - Reset view + go-to-top/bottom controls

3. FAMILY TREE — Complete Redesign
   - New architecture: positioned nodes with bezier SVG edges
   - Prophet nodes: large gold cards with Arabic name, era, number
   - Ulul Azm nodes: enhanced gold with special glow border
   - Intermediate generation nodes: subtle grey (genealogy context)
   - Detail Panel: click any prophet → side panel opens with
     full biography, Quranic verse (Arabic + translation), era badge
   - Smooth pan (mouse drag + touch drag)
   - Pinch-to-zoom on mobile, scroll-wheel zoom on desktop
   - Search: type name → dims non-matches, flies to match
   - Jump buttons: Adam ↑ / Muhammad ﷺ ↓
   - No more blank canvas — fully rendered HTML/SVG nodes

4. DU'A COLLECTION — All verified
   - 4 flagged duas reviewed:
     Abu Dawud 5081 → ✅ Sahih (al-Albani authenticated)
     Abu Dawud 2603 → ✅ Sahih (al-Albani authenticated)
     Musnad Ahmad 3712 → ✅ Sahih (primary ref: Bukhari 6346)
     Tirmidhi 3428 → 🟡 Hasan (Ibn Hibban 2374 authenticated)
   - 7 new duas added (all Sahih):
     + Entering/Leaving Home (Muslim 2018)
     + After Adhan (Bukhari 614)
     + After Wudu (Muslim 234)
     + When it Rains (Bukhari 1032)
     + For Anxiety - Full dua (Bukhari 6346)
     + Seeing Someone in Trial (Tirmidhi 3431, Hasan Sahih)
     + For the Deceased / Inna Lillahi (Muslim 919)

5. DOCUMENT HTML CONVERSIONS (from previous session, finalized)
   - isra_miraj.html: heaven cards, full narrative
   - seal_of_prophets.html: 9 sections
   - prophecies.html: scripture analysis
   - Dashboard updated: all .docx links replaced with .html

═══════════════════════════════════════════════════════
## URDU PLAN — NEXT DEDICATED SESSION
═══════════════════════════════════════════════════════

Files that need Urdu added (EN/UR toggle button):
  - prophets_timeline.html    (all prophet descriptions + table data)
  - isra_miraj.html           (full narrative, heaven cards)
  - seal_of_prophets.html     (all 9 sections)
  - prophecies.html           (scripture analysis sections)

Method: Embedded Urdu (not API) — works offline, highest quality.
Estimated: 1 full dedicated session per file, or 2 sessions for all 4.

═══════════════════════════════════════════════════════
## NETLIFY DEPLOYMENT CHECKLIST
═══════════════════════════════════════════════════════

Upload these 9 files as one folder to Netlify:

  □ index.html
  □ Quran_Surah_Explorer_v2.html
  □ prophets_map_NETLIFY.html        ← updated this session
  □ prophetic_tree_NETLIFY.html      ← updated this session
  □ prophets_timeline.html           ← updated this session
  □ isra_miraj.html
  □ seal_of_prophets.html
  □ prophecies.html
  □ duas.html

NOTE: Always upload ALL 9 files together. Netlify replaces entire site.

═══════════════════════════════════════════════════════
## SESSION STARTER PROMPT (copy for next session)
═══════════════════════════════════════════════════════

"Continue Al-Maktaba Islamic Knowledge Platform — v2.4 complete.
9 live files on Netlify. Next task: Urdu translation session.
Add EN/UR language toggle to: prophets_timeline.html,
isra_miraj.html, seal_of_prophets.html, prophecies.html.
Embedded Urdu (not API), works offline. Same dark gold aesthetic.
Start with prophets_timeline.html as highest priority."

