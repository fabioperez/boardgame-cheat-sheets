
# Dice Throne

These rules are for 1v1 only.
Strongly inspired by [https://rulepop.com/dice-throne/](https://rulepop.com/dice-throne/#final-dmg-total), which is a great official reference for the game.

## Setup

- Choose a hero: place your Hero Board, Leaflet, Health/CP dials, dice, and deck in front of you
    - Set Health to **50** and CP to **2**
    - Draw **4** cards
    - Arrange hero-specific tokens on your Leaflet
- Roll 1 die each; highest roll becomes **Start Player**
    - **Start Player** skips their first **Income Phase**

## Turn Sequence

- **Upkeep Phase**: Resolve any hero or token effects that occur in Upkeep
- **Income Phase**: Gain **1 CP** and draw **1 card**
    - Start Player skips this on their first turn
- **Main Phase (1)**:
    - Play **Main Phase Action cards** or **Hero Upgrades** by paying CP
    - **Sell** (discard) unwanted cards for +1 CP each
- **Offensive Roll Phase**:
    - Roll up to **3 times**, setting aside any dice you wish between rolls
    - Announce one Offensive Ability if your final dice match its requirement
    - Opponents may modify dice with **Roll Phase Action** or **Instant** cards
- **Targeting Roll Phase**~ (skipped in 1v1)
- **Defensive Roll Phase**:
    - Defender activates their **Defensive Ability** if the damage is defendable
    - Both players may play additional **Roll Phase Action** or **Instant** cards
    - Apply final damage **simultaneously** after all modifications
- **Main Phase (2)**: Repeat the same options as Main Phase (1)
- **Discard Phase**: Sell cards to gain +1 CP each until you have **6** or fewer in hand

## Damage & Modifiers

- **Normal**: Defendable, avoidable, and modifiable
- **Undefendable**: Not defendable but can be avoided or prevented; can be modified
- **Pure**: Undefendable and unmodifiable; can be avoided or prevented
- **Collateral**: Affects multiple players without targeting; not defendable or modifiable
- **Ultimate**: Cannot be prevented, reduced, or avoided in any way; you may still enhance your own Ultimate if a rule explicitly allows it
- **Attack Modifiers**: Cards or effects that increase or alter Attack damage; typically played after the Defensive Roll

| Damage Type             | Defendable | Avoidable | Modifiable | Special Targeting |
| ----------------------- | ---------: | --------: | ---------: | ----------------: |
| **Normal Damage**       |        Yes |       Yes |        Yes |                No |
| **Undefendable Damage** |         No |       Yes |        Yes |                No |
| **Pure Damage**         |         No |       Yes |         No |                No |
| **Collateral Damage**   |         No |       Yes |         No |               Yes |
| **Ultimate Damage**     |         No |        No |        Yes |                No |

Damage outside of an Attack (e.g., via status effect or Defensive Ability) has no designated type. Such damage may be avoided, but cannot be enhanced with an Attack Modifier nor defended against with a Defensive Ability.

## Cards

- **Action Cards** (single-use):
    - **Blue (Main Phase)**: Play only during your Main Phases
    - **Orange (Roll Phase)**: Play only during Offensive/Defensive/Targeting Roll Phases
    - **Red (Instant)**: Play at any time, even to interrupt most actions
- **Hero Upgrades**: Permanently improve one of your abilities
    - Can upgrade directly to level III
    - If upgrading from level II to III, pay only the cost difference
- **Selling**: Discard any card for +1 CP

## Status Effects

- **Positive** effects benefit you
- **Negative** effects hinder foes
- **Spendable** tokens are removed when used for their effect
- **Persistent** tokens remain until removed by a card or effect
- **Stack Limit** restricts how many identical tokens can be on a single hero

## Final Damage Calculation

1. **Incoming Damage**: Determine total damage about to be dealt
2. **Add/Subtract**: Apply all plus or minus effects (e.g. +2, -1) to form a subtotal
3. **Multiply/Divide**: Apply all multipliers or division simultaneously using that subtotal (round up any fractions)
4. Result is the final damage applied simultaneously

## FAQ

Q: **My opponent's ability applies some effects but doesn't actually deal damage. Can I still roll for defense?** ([source](https://dice-throne.rulepop.com/#faq))
 A: No. To use your Defensive Ability, you must be Attacked for at least **1 point of defendable damage**.

Q: **Am I required to activate an ability during my Offensive Roll Phase?** ([source](https://dice-throne.rulepop.com/#faq))
 A: No. You may choose **not** to activate any ability, and sometimes that's the best strategic option.

Q: **If my Attack is undefendable and I apply an Attack Modifier, does the extra damage become defendable?** ([source](https://dice-throne.rulepop.com/#faq))
 A: Damage added by an Attack Modifier is always the same **type** as the original Attack, so it stays **undefendable**.

Q: **Can I spend a token if I'm already at stack limit before gaining a new one?**
 A: It is possible. **Spending tokens is an Instant Action**, so you may spend a token immediately to free a slot before the new one arrives, **provided** the timing is valid for that particular token (see next question).

Q: **Does "spendable" mean I can use tokens anytime I wish?**
 A: Not necessarily. You must still follow each token's usage rules. For example, there are tokens (e.g. Protect, for the Paladin) you can only spend when there's actual incoming damage. You cannot preemptively spend a token for future damage.

Q: **What if something instructs "Gain 4 tokens" and I'm at or near the stack limit?**
 A: You must **gain all 4 at once** and cannot partially gain and then spend. If you can't free slots beforehand, you will only receive as many as your stack limit allows.

Q: **Is the stack limit shared among all players?**
 A: No. The limit applies **per hero board**. For instance, if a token has a stack limit of 1, you can inflict it on each opponent separately, even if it's the same status effect.

Q: **What if I run out of physical tokens?**
 A: You have an **infinite supply** on your leaflet. If a token leaves your board (e.g., it's transferred), you may still gain another copy of the same token later.

Q: **Are all tokens spendable?**
 A: No. Some tokens are strictly **Positive** or **Negative** and do not include a "spend" mechanic. Always follow the hero board, token text, or cards for usage instructions.

Q: **Do Unique Status Effects behave like Positive or Negative ones?**
 A: **No.** Unique tokens form their own category and are not considered Positive or Negative unless specifically stated.

Q: **What happens if multiple players use Instant Actions at the same time?**  
 A: The player whose turn it is has **priority**, meaning their Instant Actions resolve first. Then, in turn order, other players may resolve theirs. Spending a status effect token also counts as an Instant Action. For example, if your opponent wants to avoid your Attack by spending a token, and then you play an Instant Action card to remove your opponent's token, your card would resolve first, because it's your turn.

Q: **Can my opponent interrupt my Main Phase Action card with an Instant Action?**  
 A: Yes. Any non‑Instant Action (like a Main Phase card) is **interruptible**. An opponent may spend valid status effects or play an Instant Action card before your Main Phase Action fully resolves.
