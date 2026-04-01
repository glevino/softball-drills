# 🌀 Black Rock Hurricanes — Drill Library

A searchable, filterable softball drill reference for the Hurricanes coaching staff (12U, Black Rock Little League).

**Live site:** `https://YOUR-USERNAME.github.io/hurricanes-drills`

---

## What's in here

- **67 drills** across 7 categories
- Sourced from 10 coaching websites
- Filterable by category, IQ level, and competitive/non-competitive
- Fully searchable by drill name, skill, or source
- Mobile-friendly — works great on the sideline

### Categories
| Category | Drills |
|---|---|
| 🗣️ Communication & Focus | 11 |
| 💪 Throwing | 10 |
| ⬇️ Fielding: Ground Balls | 10 |
| ⬆️ Fielding: Pop Flies | 9 |
| 🥎 Hitting | 11 |
| 🧠 Base Running & Softball IQ | 10 |
| 🏟️ Game Simulation | 6 |

---

## How to add new drills

1. Open `index.html` in any text editor
2. Find the line that starts with `const DRILLS = [`
3. Add a new drill object to the array following this template:

```js
{
  "id": 68,                          // next number in sequence
  "name": "Drill Name",
  "category": "Throwing",            // must match an existing category exactly
  "skills": ["Skill 1", "Skill 2"],
  "competitive": false,              // true or false
  "iqLevel": "Low",                  // "Low", "Medium", or "High"
  "duration": "10 min",
  "players": "Partners",
  "equipment": "Balls, gloves",
  "description": "Full description of how the drill works.",
  "coachingCue": "The cue you say to the players.",
  "source": "Website Name",
  "progressions": ["Progression 1", "Progression 2"],
  "intro": "Practice 3+"
}
```

4. Save the file
5. Commit and push — the site updates automatically

---

## Setup (first time)

### 1. Create the repo
- Go to github.com → **New repository**
- Name it `hurricanes-drills`
- Set to **Public**
- Don't initialize with a README (you already have one)

### 2. Push the files
```bash
cd hurricanes-drills
git init
git add .
git commit -m "Initial drill library — 67 drills"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/hurricanes-drills.git
git push -u origin main
```

### 3. Enable GitHub Pages
- Go to your repo → **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: `main` / `/ (root)`
- Click **Save**
- Wait ~60 seconds → your site is live at `https://YOUR-USERNAME.github.io/hurricanes-drills`

### 4. Share with coaches
Drop the link in GameChanger. Done.

---

## Updating the library going forward

```bash
# Make your edits to index.html, then:
git add index.html
git commit -m "Add [drill name] to [category]"
git push
```

Site updates within ~30 seconds.

---

## Coaching staff
- **Head Coach:** Helbert Paneto
- **Assistant Coaches:** Grayson Levino, Pete Almanzar, Carlos Padilla, Joe Beauregard
- **Team:** Black Rock Hurricanes, Black Rock Little League
- **Practice:** Tuesdays & Thursdays, 5:30–7pm, Ellsworth Park

---

*Sources: GoRout · SkillShark · Revolution Softball Camp · Softball Tutor · Softball Spot · JustBats · Discuss Fastpitch · Coaching Youth Softball · Rush Order Tees · The Hitting Vault*
