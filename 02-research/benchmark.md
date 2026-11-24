# Step 2 · Benchmark of three competitors

Main task I tested: <the one task of my app, written as a goal>
Device and width: <Google Pixel 11 Pro 412px x 919px>

| | Competitor A | Competitor B | Competitor C |
|---|---|---|---|
| Name and link [ReelMatch](https://reelmatch.app/) | [Queue](https://queue.co/) | [FlickMate](https://play.google.com/store/apps/details?id=pl.dmq.moviepicker) |
| Taps from start to goal | 6 taps (Open → Create Room → Share Invite → Filter → Swipe → View Matches) | 8 taps (Sign Up → Skip Onboarding → Friends Tab → Start Swipe Session → Invite → Swipe → Match List) | 5 taps (Open → Group Voting → QR/Code Join → Filter → Vote/Swipe) |
| Screenshots of every step | img/a-01.png ... | img/b-01.png ... | img/c-01.png ... |
| 3 things that work | Trailer previews will work if you tap on them. | Likes or dislikes will build the match. | after all votes the app will give you most liked movie to watch. |
| 3 things that fail | | | |
| 2 quotes from 1 or 2 star reviews | | | |

## Patterns I will reuse
- **Static poster-first card with optional tap-to-play "Watch trailer" button:** Instead of noisy auto-playing videos, Popcorn displays a clean Movie Poster with Movie Name, Genre, and runtime.
- **Dual gesture + button controls (Swipe Left/Dislike & Swipe Right/Like)** alongside explicit **Thumbs Down** and **Heart** buttons so the Figma prototype works smoothly via both drag gestures and single taps.
- **Android 3-tab bottom navigation** separating **Friends** (up to 4-person room lobby), **Home** (active swipe deck), and **Lists** (quick access to *Likes* and *Dislikes* history).

## Gaps nobody solves (my opportunity)
- **Ranked "Most-Liked" Winner for up to 4 Friends:** Existing Android apps either require 100% unanimous right-swipes (which fails in groups of 3–4) or dump unranked lists. Popcorn's prototype tracks up to 4 friends' Likes and Dislikes to automatically surface the single **most-liked movie** (e.g., 4/4 or 3/4 votes) as the recommended watch.
- **Reversible Likes & Dislikes Drawer:** Unlike competitors where accidental swipes disappear forever, Popcorn's right-hand menu lets users review and toggle their **Likes** and **Dislikes** before the final group tally locks in.

## AI use in this step
<Gemini · Helping with some layout · Nothing>
