# Same Set, Different Cut

A frame-level study of the media attached to public creator posts around three
Social Capital Inc. launches — Gamma (Nov 2025), Cartesia (Oct 2025), PlayerZero (Mar 2026).

**Live page:** https://cyril-36.github.io/socap-asset-study/

**Question.** When a wave post carries media, does that media share a production with the
launch's hero film, or not?

**Sample.** 17 posts, 18 attachments, 3 hero films.

**Result.** 0 same cut · 2 related · 15 different · 1 unknown.

No wave video reviewed here is the hero film. Hero films run 111–172 s. Wave videos vary
much more widely — from a 5-second GIF to a 52-minute podcast episode — so duration settles
particular pairs rather than the sample as a whole: PlayerZero's hero runs 172 s and its
closest wave post runs 27 s, which rules out an unchanged repost of that film but not an
excerpt of it.

Two attachments are related to the hero without matching any sampled frame. One 52-minute
episode was sampled at only two frames, from a partial download, and is left unlabelled
rather than counted.

## Method

Wave posts come from the public catalogue in
[socap-lens](https://github.com/yashbudhia/socap-lens), which records that a post carried
media but stores no media URLs. Files were recovered per post from the public fxtwitter
JSON endpoint, downloaded under their post ID, and sampled at five evenly spaced frames
with ffmpeg — except the 52-minute episode, which downloaded only partially and yielded two.
Every label was assigned by looking at those frames.

Thumbnail hashing was tried first and rejected: a related pair scored 0.0869 and another
related pair scored 0.2979, so the metric cannot settle video identity in either direction.
The scores appear on the page as the reason human review was needed, not as a result.

## What this cannot show

Who made, supplied or paid for any asset. Anything about the breadth or health of the
creator network. Anything beyond these 17 posts. And, because sampling is five frames per
video, it cannot prove that two files share no footage anywhere — only that the sampled
frames do not match.

## Credits

- [socap-lens](https://github.com/yashbudhia/socap-lens) — post catalogue; its timing,
  hero-handle and creator-roster findings are taken as given here rather than re-derived.
- [waveline-socap](https://github.com/atzgg132/waveline-socap) — argues the Wispr Flow wave
  was voice-matched rather than copy-pasted; this page asks the same question of the visual layer.

Independent work, not affiliated with or endorsed by Social Capital Inc. or any client named.
All media remains the property of its owners and is linked to its source.
