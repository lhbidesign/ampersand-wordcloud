# Ampersand Word Cloud — Event Experience Prototype

Live interactive word cloud where attendees answer a multiple-choice question and
their answers flow along the shape of an **&**, sized by how many people picked each one.

**Live demo:** https://lhbidesign.github.io/ampersand-wordcloud/

- Tap answers in the left panel to simulate responses.
- Words trace the ampersand; the most-picked answer renders largest.
- "Open display screen" pops the &-only view for a projector (syncs across tabs on the same machine).

> Note: cross-*device* sync (attendees' phones → one projector) needs a small realtime
> backend (Firebase/Supabase). This static demo syncs across windows on one machine.
