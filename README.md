# Fufu for Mama

**By Ivy Newton, The African Gourmet**

> Every culture has a food that doesn't count as a meal without it. **What's your fufu?** Would you recognize it in someone else's kitchen?

You're a Nigerian living in South Korea. Your mother's flight is landing, she eats fufu with every meal (no exceptions), and she will know if it's wrong. Run through a Korean market, find the closest ingredients you can afford, cook them under the clock, and see her face.

There's no failing. Mama's face is the score.

## Play

Open `index.html` in any modern browser, on a phone or a computer. It's one file with no login, no backend, no external images or fonts, and no network requests.

## How to play

1. **Shop.** Ingredient tiles slide past on market rows. The first time you tap an ingredient, its info card opens. After that, a tap drops it in your basket. The basket holds **5**, and you can tap a basket slot to put something back for a refund.
2. **Watch your wallet.** You pay in Korean won notes and coins (with rough ~$ hints), and sellers give change. Some tiles are **품절 · SOLD OUT**, and in Level 3 the Dry Goods stall takes a **점심시간** (lunch break) now and then.
3. **Gold ★ tiles** (puna yam, cassava, plantain, fufu flour) are the real thing. They're rare, pricey and quicker than the other tiles, and they carry a star badge so you don't have to rely on color.
4. **Mama's texts are the clock:** baggage claim → taxi → "Five minutes, my child." → she's at the door. Tap **Go cook** when you're ready, or cook when she arrives.
5. **Cook.** **Pound** (tap on the beat), **Add water** (choose a little at a time, or all at once), then **Turn** (tap on the beat). The timing is forgiving. The water choice and a steady beat make it smooth.
6. **Taste test.** You get sentences, not stat bars. Your ingredients decide the *pull* (stretch) and the *taste*, and they matter most. Your technique and the ingredients' own texture decide the *smoothness*.
7. **Serve Mama.** She has four reactions, and every one comes with a gentle, accurate tip:
   1. A long silence. "Ah. My child."
   2. "So-so."
   3. A smile. "Good try, my child."
   4. A star. "Yes, my child, you listened."

**Balance beats stacking gold.** Each duplicate counts for less (1, ½, ¼…), and a blend of two or three good starches earns a bonus. Real fufu is often a blend.

### Levels (v1.3)

| Level | What's new |
|---|---|
| 1 · First trip | Tutorial. One slow row and plenty of money. |
| 2 · Tight budget | Two rows moving in opposite directions, ₩26,000 and 70 s, and some stalls sell out. Unlocks at 2 ⭐ on Level 1. |
| 3 · Itaewon run | ₩20,000 and 55 s, a lunch break at Dry Goods, and unlocks at 2 ⭐ on Level 2. Adds a vertical row (the Itaewon African shop, the only place that sells garri and semolina). Rows are coded by **color and shape/pattern**: Produce is green with a leaf pattern and round tiles, Dry goods is blue with a grid pattern and square, dashed-edge tiles, and Itaewon is orange with stripes and notched corners. |

### Also in v1

- 1 to 3 stars and a best score per level (score = Mama's happiness plus a small *patience bonus*)
- A **retry hook** that lists what you missed (the good ingredients that went by, and swap ideas)
- A **shareable result card** drawn on a canvas, downloadable as a PNG
- A **recipe book** of 17 ingredient fact cards, each unlocked by buying that ingredient
- A **collection of Mama's faces**
- **Relaxed mode** (no clock), a **reduced-motion** toggle (it follows your OS setting by default), and **mute**
- Progress saved in `localStorage`
- A portrait, phone-first layout using pointer events. The keyboard works too: Space/Enter while cooking, Esc to pause.
- All sound is synthesized with WebAudio: coin clink, basket bounce, text ping, pound thud, and light market ambience

### Ingredients

| Group | Ingredients |
|---|---|
| Best (gold ★) | puna yam, cassava, plantain, fufu flour |
| Good stand-ins | Korean yam (ma), potato starch, glutinous rice flour, sweet potato, tapioca starch, Korean taro (toran), kudzu starch (chik) |
| Valid but different swallows | wheat flour (wheat meal), semolina (semo), garri (eba). Garri and semolina are only at the Itaewon African shop. |
| Wrong category | bean flour (that's for moin moin and akara) |
| Decoys | tteok (pounded, but sets firm and chewy), regular potato |

Tapioca starch *is* cassava starch, but on its own it's gummy ("Close, but too gluey"). Chik is called kudzu starch, not arrowroot.

## What's new in v1.3

Changes from an outside playtest, approved by Ivy.

- **First tap = learn.** The first time you tap an ingredient (remembered across visits), its card opens with a big **Buy ₩X (~$Y)** button and a **Not now** button. After that, one tap buys it. Press and hold, or tap the ⓘ (now in the top-right corner, with a large invisible touch area), to read the card again.
- **Simpler Level 1 tutorial**, one step at a time: tap to learn, then the meter, then Go cook. A one-time tip at 3 items reminds you that the basket holds 5 and you can Go cook anytime.
- **Forgiving cooking, about technique.** Timing windows are much wider (Perfect within about 200 ms, Good within about 350 ms). A new **Add water** step asks you to choose: *a little at a time* (smooth) or *pour it all in* (soggy and lumpy), with a one-line reason. Rhythm only nudges the score; what you bought matters most. In Relaxed mode an **Auto-pound** button keeps the beat for you.
- **Mama's patience bonus** replaces the time bonus: finishing with time to spare gives her a moment to sit down with tea.
- **Faster to Mama's face.** Taste-test lines appear every quarter second (tap to show them all), and Serve shows Mama's reaction right away.
- **Did you know?** The results show one fact about something you bought, preferring same-plant, different-name facts (ma and African yams are both *Dioscorea*; toran is taro, which Nigerians call cocoyam). It also goes on the share card.
- **Words.** The title now says: *In Nigeria, 'fufu' can mean many things. Mama means the cassava kind. What does it mean in your house?* The tutorial and recipe book define **swallow** and mention **iyan** (pounded yam).
- **The market ajumma.** A drawn stall owner greets you (어서오세요! Welcome!), comments on some choices in English with a little Korean, and sometimes gives **서비스** (service), a small cash-back freebie, with a note on this Korean market custom.
- **No more exact change.** Sellers give change. Instead, some tiles are **품절 · SOLD OUT** (Levels 2 and 3), and in Level 3 the Dry Goods stall closes now and then for **점심시간** (lunch break).
- **Balance.** Level 2: ₩26,000 and 70 s. Level 3: ₩20,000 and 55 s, plus three rows and the lunch break. A top-reaction basket still fits each budget (for example, Korean yam + potato starch + tapioca starch is ₩10,500). The next level unlocks at **2 ⭐**, with a clear "Get 2 ⭐ to unlock" message. Relaxed mode opens every level.

## What's new in v1.2

- **Share your result.** The result card now has a **Share** button that sends the card picture, a short message and the game link through your phone's share sheet (Web Share API). Where that isn't supported, the button hides itself, and the message and link are copied instead if sharing fails.
- **Post on X** and **Facebook** buttons open a new tab with a ready-made post (your score, Mama's reaction and #FufuForMama). **Copy link** and **Download** are there too. Nothing is contacted until you tap one of them.
- **Dollar hints.** Prices are still in Korean won, but tiles, the wallet, the info card and the money toasts show a rough US dollar amount, like ₩3,000 (~$2). It uses one fixed rate (₩1,400 ≈ $1), rounded to the nearest 50 cents, or to whole dollars from $10 up. You can turn the hints off under ⚙️ Settings → *Show ~$ hints*.
- **Mama's gele fits better.** Her head wrap now sits snugly on her hairline and wraps around the sides of her head, with a small knot and fan, instead of perching on top.
- **Cleaner tiles.** The ⓘ badge moved to the top corner so it no longer covers the picture, and the Garri and Semo bag labels no longer hide behind the cut slice.

## What's new in v1.1

- **Ingredient info card:** press and hold a tile (about 0.4 s), or tap its **ⓘ** badge. The card shows the name, a plain one-line description, what the ingredient adds (Pull, Smooth, Taste in words), the price and any exact-change note, and you can buy from it. A plain tap still buys right away. While the card is open the rows slow down a lot, or stop in relaxed mode. Mama's clock keeps running.
- **Basket meter:** live Pull, Smooth and Taste bars, plus a one-line verdict that updates as you shop (for example "Good pull, but needs something smooth").
- **Mama's hint texts:** each level opens with a shopping goal, and she nudges you twice mid-shop based on your basket. The texts are part of the same clock. Tap her bubble to reread them.
- **Combo pop-ups:** good pairs and blends ("Yam + cassava = classic pull!") and gentle warnings ("Bean flour is for moin moin, not swallow", "Too much tapioca gets gluey").
- **Level 1 tutorial:** it teaches the info card, buying and the meter.
- Smoothness now depends on the ingredients' smoothness potential (garri and tteok come out grainy or firm) as well as your cooking.

## Coming later (deferred from v1)

- **Daily market:** a date-seeded shopping list, the same for every player that day
- **Vendor characters** at the stalls
- **"Your fufu" input** on the result card, so players can name their own staple (rice, bread, tortilla, poi…)
- **Level 6, sold out:** the good stuff is gone, and you have to make the best of weak ingredients and learn *why* they're weak

## Tech notes

- `index.html` at the root with relative paths only, so it works on GitHub Pages, itch.io (zip with `index.html` at the root) and GamePix.
- All art is flat vector, drawn in canvas code. Fonts use the system stack.
- `window.FUFU` is a small read-only hook used by automated browser tests.

## Credits

Game concept and design: **Ivy Newton, The African Gourmet**.
