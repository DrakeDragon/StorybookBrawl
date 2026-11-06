# 📖 Storybook Brawl

**A fairy-tale gacha team auto-battler for your phone.** Collect 250 heroes from classic British and American stories, build a squad of four, and fight through **750 story stages across 25 realms** to restore Mother Goose's bleeding Book.

## Quick start

1. Extract the entire ZIP.
2. Open `storybook-brawl/index.html` in a browser. Keep the `assets` folder next to `index.html`.
3. Select **Open the Book** to start. The game runs offline.

To move an existing save, use **Menu → Settings → Export save code** in your old copy. In the new copy, choose **Menu → Settings → Import save code** and paste the code. Import replaces the progress in the copy you are opening.

For web hosting, upload the contents of the `storybook-brawl` folder together.

---

## ✨ Features

### The story: *The Unwritten*
- Mother Goose's Book is bleeding ink (the Blot). Each of the **25 realms** hides one torn **Page**, guarded by a boss. You are the **Reader**, and you put the Book back together.
- **Every one of the 750 stages has its own written chapter**, shown on the stage card. Boss stages and the start of each realm open with a story scene.
- Finishing a realm restores a Page and sets up the next one.
- **Menu → Story** is a replay log of every chapter you have cleared.
- A long-running mystery about the Narrator pays off in the final realm.
- After the last realm the game loops into a harder "Second Reading".

### 250 collectible heroes
- Heroes and side characters from British and American tales and legends: Robin Hood, King Arthur, Alice, Peter Pan, Pooh, Sherlock Holmes, Dorothy, Santa, Pecos Bill and many more.
- Every hero has a **profile**: an epithet, a quote and a backstory, plus star-unlocked "Hero tales".
- Every hero has a **stats card** (stat bars, role, growth, star perks and bonds).
- Every hero has **their own four moves**, including a signature ultimate. No two heroes share a kit.
- Rarity is extreme: **80 Common, 70 Uncommon, 55 Rare, 30 Epic, 15 Legendary**. Completing the whole roster takes a very long time.

### 25 realms that match their stories
1. **Sherwood Forest**, guarded by *Sheriff of Nottingham*
2. **Camelot**, guarded by *Morgan le Fay*
3. **Wonderland**, guarded by *Queen of Hearts*
4. **Looking-Glass Land**, guarded by *Jabberwock*
5. **Neverland**, guarded by *Captain Hook*
6. **Hundred Acre Wood**, guarded by *The Great Backson*
7. **Wild Wood and River Bank**, guarded by *Chief Weasel*
8. **Garden of Beatrix**, guarded by *Farmer McGregor*
9. **Beanstalk Heights**, guarded by *The Beanstalk Giant*
10. **Cottage Country**, guarded by *The Big Bad Wolf*
11. **Mother Goose Lane**, guarded by *The Queen of Tarts*
12. **Dickens' London**, guarded by *Bill Sikes*
13. **Baker Street Fog**, guarded by *Professor Moriarty*
14. **Treasure Island**, guarded by *Captain Flint's Ghost*
15. **Midsummer Wood**, guarded by *Oberon's Shade*
16. **Scottish Highlands**, guarded by *Lady Macbeth*
17. **Celtic Marches**, guarded by *Arawn, Lord of Annwn*
18. **Dragon's Peak**, guarded by *The Great Dragon*
19. **Gothic Whitby**, guarded by *Count Dracula*
20. **Sleepy Hollow**, guarded by *The Headless Horseman*
21. **Yellow Brick Road**, guarded by *Wicked Witch of the West*
22. **Emerald City**, guarded by *The Nome King*
23. **Tall Tale Frontier**, guarded by *Cave Bandit*
24. **North Pole Workshop**, guarded by *Jack Frost*
25. **The Last Page**, guarded by *The Author of Endings*

Each realm has 3 areas of 10 stages, a mini boss at stage 5 and an area boss at stage 10 of every area.

### Battle
- Turn-based combat with a front row and back row, cooldowns, charged signature moves, enemy weaknesses and resistances, and enemy specials.
- **Auto-Battle** and **auto-farm** (x5/x10/x25) unlock after the stage 1-5 mini boss.
- Speed control and a battle log.

### Collecting and the draw
- You earn a 🎟️ **ticket** the first time you clear every 3rd stage, with extra tickets for area and realm bosses.
- Heroes you have not met are **twice as likely** to appear in the draw.
- 🍀 **Fate's Favor**: after a win, a random chance to receive a free duplicate card for a hero you own, and a very small chance for a brand new hero. Bosses roll better odds.
- Duplicates become promotion cards.

### Progression
- **Levels**, **5-star promotion** (+25% stats and a higher level cap per star), **skill ranks** that you train by using moves, and **Awakening** at 5★ and level 50.
- **Gear**: forge it in the **Workshop** (a timed crafting queue and a material chain), equip 3 slots, enchant, and collect sets (of Sherwood, Camelot, Wonderland, Neverland, Baker Street, the Highlands, Oz, the Frontier) for bonuses.
- **47 Bonds**: squadmates from the same tale give team bonuses (themed bonds plus "complete the cast of a realm" bonds).
- **Squad presets** for quick swaps.

### Endgame and daily play
- 🗼 **Endless Tower**, 🐲 **Boss Raid** (daily boss, 3 phases), ⚔️ **Arena** (rival squads, weekly ranking).
- 📜 Daily and weekly quests, 🔥 login streak, 🧭 timed expeditions, 🏆 collection milestone rewards.

### A menu where nothing is hidden
- Five tabs: **Adventure, Heroes, Draw, Gear, Menu**.
- **Heroes** combines your Squad and the Collection. Tapping a ❓ shows a hero's home realm.
- **Menu** opens on a **Today** to-do list with badges, then a tile grid for every feature. Locked features tell you exactly how to unlock them.
- **Help & Guide** covers how to play, where everything is, and the unlock timeline.

---

## 🕹️ How to play
1. Open **Adventure**, pick a stage and tap **FIGHT**.
2. On your hero's turn, tap a move, then tap a villain to target.
3. Win to earn gold, XP, materials and tickets.
4. Spend tickets in **Draw**, build a squad in **Heroes**, and gear up in **Gear**.
5. Check **Menu → Today** each visit for rewards waiting.

### Unlock timeline
| Stage | Unlocks |
|---|---|
| Start | Quests, Expeditions, Workshop |
| 1-5 | Auto-Battle and auto-farm |
| 1-10 | Endless Tower |
| 2-5 | Arena (needs 2+ squad heroes) |
| 2-10 | Boss Raid |

---

## 🚀 Publish on GitHub Pages
1. Create a new GitHub repository (public).
2. Upload everything in this folder (`index.html`, `README.md`, `.nojekyll`, etc.).
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
4. After a minute your game is live at `https://<your-username>.github.io/<repo-name>/`.
5. Open it on your phone and use **Add to Home Screen** for a full-screen app feel.

## 💾 Saving
- Progress saves automatically in your browser (`localStorage`, key `storybookBrawl_v4`).
- **Menu → Settings** lets you export and import a save code to back up or move devices.
- Clearing your browser data erases your save, so export a code now and then.

## 🧱 Tech
- One self-contained `index.html` (HTML, CSS and vanilla JavaScript). No build step, no dependencies, no network calls.
- Mobile-first, designed for portrait phones (tested at 390px wide).
- Hero data is defined in compact tables inside the file, and each hero's move effects are generated from effect pools with a uniqueness check.

## ⚠️ Known limitations
- Difficulty is tuned and tested through roughly stage 60-70. Later realms are playable but not balance-tested.
- Leaderboards (Tower and Arena) are local and seeded, not online.
- Saves live on one device, so use export and import to move them.
- Version 4 uses a new save key, so progress from earlier versions does not carry over.

## 📜 Credits and content
All characters come from public-domain folklore, legends and classic literature (British and American). All hero profiles, story chapters, moves and art (emoji) in this project are original. See [CHANGELOG.md](CHANGELOG.md) and [HEROES.md](HEROES.md).

## 📄 License
Copyright © 2026 Tim. All rights reserved. See [LICENSE](LICENSE). Replace this with the license you prefer (MIT, for example) before inviting contributions.
