---
title: How Deckz.gg Works
description: Understand the full gameplay and system flow behind Deckz.gg — from wallet connection to pack opening, economy management, and fairness verification.
---

# How Deckz.gg Works

Deckz.gg connects the intuitive experience of a trading-card game with the verifiable logic of blockchain systems.  
Here’s how everything fits together.

## 1. Connect Your Wallet

Start by connecting a supported wallet — **Phantom**, **Trust Wallet**, or any Web3-compatible provider.  
Your wallet serves as both your identity and vault. It authenticates you, tracks your balance, and signs every on-chain action.

Once connected, the platform defaults to **Real Mode**, showing your live Gold Coin balance.  
You can switch to **F2P Mode** anytime to experiment using free demo coins.

---

## 2. Choose a Pack

Navigate to the **Packs** section and browse tiers such as **Bronze**, **Silver**, or **Gold**.  
Each pack displays:
- Entry cost in Gold Coins or F2P coins  
- Number of cards included  
- Rarity odds  
- Potential highlights or featured drops  

Selecting a pack triggers a short confirmation step before opening begins.

---

## 3. The Deterministic Reel

After confirmation, the backend generates (or retrieves) your **SpinPlan** — a data record defining the exact card results and reel sequence.  
The animation you see on-screen is simply a visual representation of that plan, running at 60 fps for cinematic effect.

Because every SpinPlan is stored before the animation plays, no outcome can change mid-spin.  
This guarantees **provable fairness** for every user, every time.

---

## 4. Inventory and Value

Once the reel stops, your revealed cards are minted into your **inventory**.  
Here you can:
- View card stats and rarity  
- Sell unwanted items for Gold Coins or F2P credits  
- Track total pack-opening history and earnings  

In Real Mode, proceeds appear in your wallet instantly after sale confirmation.

---

## 5. Leaderboards and Rewards

Each action — opening, selling, or trading — contributes to your **Deckz Dash** points.  
Weekly leaderboards highlight the most active and lucky players, distributing tiered rewards at reset.

---

## 6. Transparency and Verification

Every transaction (purchase, sale, or pack outcome) is logged through the Supabase backend and reflected in on-chain records where applicable.  
Players can view or audit their data directly from their profile history.

Deckz.gg keeps gameplay simple while the system beneath it ensures absolute integrity.
