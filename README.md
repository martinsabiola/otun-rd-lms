# OTUN RD — Life & Ministry Meeting Part Assignment App 2026

A web app for automatically assigning meeting parts to congregation members for all 52 Thursdays in 2026.

## Features
- ✅ Auto-assigns all 52 Thursday meetings using rotating name pools
- ✅ Fetches live part titles from JW.org via AI
- ✅ Loads congregation names from `names.json` (this repo)
- ✅ 9 role categories: Ministerial Servant, Elder, Chairman, Treasures/Digging, Bible Reading, Apply to Ministry, Talks, CBS Reader, Closing Prayer
- ✅ WhatsApp / Email / SMS notification previews per assignee
- ✅ Export weekly schedule as text file
- ✅ Toggle availability, add/delete names per pool

## Live App
👉 **https://martinsabiola.github.io/otun-rd-lms-data**

## Data
Names are stored in [`names.json`](./names.json).  
To update names: edit `names.json` and commit — the app will pick up changes on next sync.

## Role → Part mapping
| Role | Parts |
|------|-------|
| Ministerial Servant | 1 (Opening) |
| Elder | 1, 10, 12 |
| Chairman | 1, 12 |
| Treasures / Digging | 2, 3 (Elders + MS combined) |
| Bible Reading | 4 |
| Apply to Ministry | 5, 6, 7, 8 |
| Talks | 10 |
| CBS Reader | 11 |
| Closing Prayer | 12 |

## Setup (GitHub Pages)
1. Go to **Settings → Pages**
2. Set Source to **main branch / root**
3. Save — app is live at `https://martinsabiola.github.io/otun-rd-lms-data`

---
_OTUN RD Congregation 2026_
