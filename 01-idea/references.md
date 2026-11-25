# Step 1 · Ten references

Screenshots go into 01-idea/img/ and are named ref-01.png, ref-02.png ...

## A. Competitors: what people use today for the same task (4)
### 1. ReelMatch · https://reelmatch.app/
![](img/ref-01.png)
- What it does for my user: Connects friends or couples across phones so everyone swipes privately on movies and TV shows to see which titles overlap.
- What I take from it: Clean card layout with streaming service tags (Netflix, Prime, Disney+) and clear title/genre metadata so users know immediately where a movie can be watched.
- What I would avoid: Auto-playing trailers on every swipe and capping free users at 15 swipes per day, which interrupts a group session mid-flow.

### 2. FlickMate · https://play.google.com/store/apps/details?id=pl.dmq.moviepicker
![](img/ref-02.png)
- What it does for my user: Lets Android users join a shared movie-picking room via QR code and vote or swipe on films together.
- What I take from it: Frictionless QR code / short room code join flow so up to 4 friends can connect in seconds without creating accounts.
- What I would avoid: Cluttering the home screen with extra mini-games (scratch cards, roulette wheels) and heavy couple-only branding.

### 3. Film Queue · https://apps.apple.com/au/app/film-queue-movie-matcher/id6785268514
![](img/ref-03.png)
- What it does for my user: Turns movie night into a shared swipe session with ranked voting to surface a film the group agrees on.
- What I take from it: High-contrast, poster-first card hierarchy and ranked group scoring instead of requiring 100% unanimous matches.
- What I would avoid: Mandatory sign-ups or ad-locked movie collections that slow down getting straight into the swipe deck.

### 4. Letterboxd · https://letterboxd.com/
![](img/ref-04.png)
- What it does for my user: Helps movie fans discover films, read quick synopses, check runtimes, and organize watched/liked lists.
- What I take from it: Crisp poster presentation paired with scannable runtime, genre, and short synopsis typography.
- What I would avoid: Dense social feeds, star-rating math, and long text reviews that overwhelm quick group decision-making.

## B. Patterns: one screen that solves one part of my task well (3)
### 5. Tinder · Swipe Deck & Action Controls · https://tinder.com/
![](img/ref-05.png)
- The pattern: Full-bleed vertical card stack supporting both left/right drag gestures and explicit bottom action buttons.
- Why it fits my app: Matches my wireframe's core interaction—swiping left or tapping Thumbs Down to dislike, and swiping right or tapping Heart to like[span_3](start_span)[span_3](end_span)—while keeping the Figma prototype easy to test with either taps or drags.

### 6. Kahoot! · Group Lobby & Player Slots · https://kahoot.com/
![](img/ref-06.png)
- The pattern: A live room lobby displaying a short join code/QR and visible player slots that light up as each person joins.
- Why it fits my app: Solves Popcorn's "Friends" tab (`max 4 people`) by giving the group clear visual feedback on who is in the room (`1/4` to `4/4`) before starting the swipe round[span_4](start_span)[span_4](end_span).

### 7. Spotify · Liked / History Drawer & Toggle · https://open.spotify.com/
![](img/ref-07.png)
- The pattern: A dedicated list view separated into clear tabs where users can review past choices and toggle their Like status with one tap.
- Why it fits my app: Directly supports my wireframe's right-hand menu icon (`Go to likes` / `Go to dislikes`), letting users review or change their mind on a movie before the group's most-liked winner is calculated[span_5](start_span)[span_5](end_span).

## C. Visual references: colour, type, images, tone (3)
### 8. Material 3 Dark Theme (Android) · https://m3.material.io/
![](img/ref-08.png)
- What fits my users: Deep charcoal/espresso surfaces with high-contrast off-white typography make movie posters pop like a cinema screen and follow native Android navigation standards for the Google Pixel 11 Pro (`412px × 919px`)[span_6](start_span)[span_6](end_span).

### 9.IMDb Mobile Movie Cards · https://www.imdb.com/
![](img/ref-09.png)
- What fits my users: Clear visual hierarchy separating the vertical poster, bold movie title, runtime pill (`Time`), short description, and an explicit on-demand **Watch trailer** button rather than noisy autoplay[span_7](start_span)[span_7](end_span).

### 10. A24 Films Editorial Posters & Branding · https://a24films.com/
![](img/ref-10.png)
- What fits my users: Bold geometric sans-serif headings paired with warm cinema-inspired accents (buttery popcorn gold and warm cream) give Popcorn a playful, modern movie-night personality without visual clutter[span_8](start_span)[span_8](end_span).