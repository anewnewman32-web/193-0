# 193–0 V3.14

V3.4 improves draft randomness and slightly softens the 193-country difficulty.

## Format

- Draft 6 leaders from groups of 3.
- One respin per attempt.
- The squad is tested against all 193 UN member states.
- The world difficulty has been softened slightly from V3.
- All six leader stats are visible while drafting, but only as 10-point bands such as `60–70` or `90–100`.
- Exact underlying ratings remain hidden and are never displayed to the player.

## Leader packs

There is no longer a Core pack. Every character belongs to a themed group:

- Conquerors & Generals — 43
- Presidents & Prime Ministers — 61
- Infamous Leaders — 25
- Current Leaders — 38
- Kings & Queens — 76
- Fictional & Legendary — 20

Total pool: **263 characters**.

The Fictional & Legendary pack contains the 11 existing fictional cards plus 9 additional mythic/literary rulers, bringing it to a full 20-card pack.


## Balance note

Leader and country ratings are abstract entertainment/game-balance values. They are not objective historical, moral, military, economic or political rankings.

## Portraits

Historical cards attempt to load a Wikipedia/Wikimedia thumbnail when internet access is available. If a portrait cannot load, the game uses its built-in medallion artwork. Fictional cards use built-in medallions.

## Draft format

- Six leaders per squad.
- Five choices are offered each draft round.
- One respin per attempt replaces the current five choices.
- All six stats are shown only in 10-point bands.

## V3.4 balance and randomness

- Country success threshold reduced from 9.4 to 8.7, making strong squads slightly more successful without making 193–0 routine.
- Draft selection no longer picks a rarity bucket first. Every eligible card participates directly in one weighted random draw.
- Common cards remain more frequent per card, while Legendary and Mythic cards remain genuinely rarer.
- Any person shown during the immediately previous draft attempt is strongly downweighted on the next attempt.
- No person can appear twice within the same attempt, including the respin.
- Browser cryptographic randomness is used when available, with `Math.random()` as a fallback.


## V3.5 interface redesign

- The visual design now uses a historical archival / parchment theme with serif typography, aged-paper surfaces, muted burgundy accents and framed portrait treatment.
- The title screen has been reduced to the game title plus only two actions: **Play** and **Rules & Scoring**.
- Rules & Scoring now has its own dedicated screen explaining the draft, six stat categories, squad chemistry, hidden country challenges, win logic, rarity and randomness.
- Gameplay balance and the V3.4 random-selection fixes are unchanged.


## V3.6 rarity generation

Draft generation now uses a true rarity-first system for **each individual card slot**:

- Common — 50%
- Uncommon — 20%
- Rare — 15%
- Legendary — 10%
- Mythic — 5%

After the rarity is rolled, the game chooses uniformly from the available people in that rarity.

The rarity pools were expanded/rebalanced to prevent the same few Common cards appearing every attempt:

- Common — 80 cards
- Uncommon — 65 cards
- Rare — 53 cards
- Legendary — 25 cards
- Mythic — 20 cards

A person cannot repeat within the same attempt. People shown in the immediately previous attempt are also excluded whenever there is another available person in the rolled rarity.


## V3.7 navigation

- A persistent **Home** button now appears in the game header on the draft, lock-in and result screens.
- Pressing Home returns to the title screen immediately.
- Returning home does not itself start a new draft; pressing Play begins a fresh attempt.


## V3.8 rarity / ratings alignment

Rarity now represents actual card strength for every non-fictional leader.

The 223 historical/current cards are ranked by their six-stat composite (Military, Logistics, Economy, Diplomacy, Administration and Adaptability) and divided into the existing pool sizes:

- **Common — 80 cards:** composite range 28.7–76.3
- **Uncommon — 65 cards:** composite range 76.5–84.3
- **Rare — 53 cards:** composite range 84.5–88.5
- **Legendary — 25 cards:** composite range 88.5–92.7
- **Mythic — 20 cards:** Fictional & Legendary pack only; deliberately exempt from the strength rule.

This means a non-fictional Legendary is now always stronger overall than a non-fictional Rare, a Rare stronger overall than an Uncommon, and so on.

The individual six stats themselves were preserved so each leader keeps their existing strengths and weaknesses; rarity was rebuilt around the ratings instead of artificially buffing weak historical figures.

The rarity roll probabilities remain unchanged: **50% Common / 20% Uncommon / 15% Rare / 10% Legendary / 5% Mythic**.


## V3.9 interface redesign

- The full interface has been redesigned into a modern, colorful style.
- The old archival / parchment theme has been replaced with a cleaner dark-gradient layout with bright accent colors, rounded panels and more intuitive controls.
- The title screen, rules screen, draft cards, result panels and navigation were all visually refreshed.
- Gameplay, rarity logic, difficulty, roster size and all V3.8 systems are unchanged.


## V3.10 visual tweak

- Leader names on draft cards are now solid white.
- All rarity labels (Common, Uncommon, Rare, Legendary and Mythic) now use solid white text for stronger contrast.


## V3.11 contrast tweak

- Leader names remain solid white.
- Rarity labels remain solid white.
- Strength / tier labels such as Elite, Strong, Solid, Capable, Risky and Disaster are now also solid white.


## V3.12 result readability and rarity odds

- Country names on the final world-results screen are now solid white.
- High-rarity pulls are now significantly less common:
  - Common — 60%
  - Uncommon — 24%
  - Rare — 10%
  - Legendary — 5%
  - Mythic — 1%
- The rarity pool sizes and card ratings are unchanged; only the probability of rolling each rarity has changed.


## V3.13 campaign analysis cleanup

The World Campaign Analysis now contains only four points:
- chemistry modifier
- best team dimension
- weakest team dimension
- the weakest leader / person who held the squad back most, based on their six-stat average

Regional recaps, closest losses and other extra analysis bullets were removed.


## V3.14 postwar presidents and prime ministers expansion

The **Presidents & Prime Ministers** pack now includes every unique U.S. president from Harry S. Truman through Donald Trump and every U.K. prime minister from Clement Attlee through Andy Burnham.

- Added 20 new cards.
- Donald Trump and Andy Burnham were moved from Current Leaders into Presidents & Prime Ministers rather than duplicated.
- Presidents & Prime Ministers now contains 61 cards.
- Current Leaders now contains 38 cards.
- Total roster: 263 cards.
- Rarity roll odds remain 60% Common / 24% Uncommon / 10% Rare / 5% Legendary / 1% Mythic.
