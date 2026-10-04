# Reaction Bloom — The Medicine Maven

Playable browser prototype.

## Run
Open `index.html` in Chrome/Safari/Edge/Firefox.

## Important
This V1 prototype uses local browser storage for the leaderboard so it works immediately with no account, PIN, or backend setup.

For a true global leaderboard across all devices, connect the included leaderboard functions to a backend such as Supabase in the next build. The game timing/UI can remain unchanged.

## Current locked mechanics
- Mobile touch + desktop mouse/pointer
- 36 px targets
- 3 rounds × 15 seconds
- Land → Underwater → Space
- READY → PUMPKIN → GO! before every round
- Fixed target lifetime
- New target during final 20% of previous target's lifetime
- Faster successful reaction → sooner next target
- Missed targets ignored in RT averages
- Minimum 3 successful taps per round
- Final score = average of the 3 round averages
- Animal reward based only on final average
- Subtle per-tap RT + animal feedback
- Tap sound, miss “zoop”, ambient round soundscapes, mobile haptic on successful taps
- Top 20 leaderboard + View More
- Animal ranking list
- Share result
- Local personal best

## Branding
Provisional game name/logo: Reaction Bloom.
This is the first build and the logo/name can be changed after your approval.
