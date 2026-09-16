# Same Set, Different Cut

A frame-level study of the media attached to public creator posts around three
Social Capital Inc. launches — Gamma (Nov 2025), Cartesia (Oct 2025), PlayerZero (Mar 2026).

**Question.** When a wave post carries media, does that media share a production with the
launch's hero film, or not?

**Sample.** 17 posts, 18 attachments, 3 hero films.

**Result.** 0 same cut · 2 related · 16 different · 0 unknown.
No wave video is the hero film. Hero films run 111–172 s; wave videos run 5–33 s.
Two attachments are related to the hero without being cut from it.

## Method

Wave posts come from the public catalogue in
[socap-lens](https://github.com/yashbudhia/socap-lens), which records that a post carried
media but stores no media URLs. Files were recovered per post from the public fxtwitter
JSON endpoint, downloaded under their post ID, and sampled at five evenly spaced frames
with ffmpeg. Every label was assigned by looking at those frames.

Thumbnail hashing was tried first and rejected: a related pair scored 0.0869 and another
related pair scored 0.2979, so the metric cannot settle video identity in either direction.
The scores appear on the page as the reason human review was needed, not as a result.

## What this cannot show

Who made, supplied or paid for any asset. Anything about the breadth or health of the
creator network. Anything beyond these 17 posts.

## Credits

- [socap-lens](https://github.com/yashbudhia/socap-lens) — post catalogue; its timing,
  hero-handle and creator-roster findings are taken as given here rather than re-derived.
- [waveline-socap](https://github.com/atzgg132/waveline-socap) — argues the Wispr Flow wave
  was voice-matched rather than copy-pasted; this page asks the same question of the visual layer.

Independent work, not affiliated with or endorsed by Social Capital Inc. or any client named.
All media remains the property of its owners and is linked to its source.
