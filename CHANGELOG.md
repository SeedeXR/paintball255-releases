# Paintball 255 - Release Notes

All notable changes to Paintball 255 are documented here. Newest release first.
Paintball 255 is a VR paintball range on the beach for Meta Quest.

## [1.4.1] - 2026-10-06
A stability and performance update: smoother play when pots break, music that recovers on its own, and cleaner paint splats.

### Changed
- African pots break into fewer, larger pieces that clear away after two to three seconds. This keeps the picture smoother when several pots break at once, most of all on older headsets.
- The game does less work on every frame, which leaves more headroom on Quest 2.
- Paint splats land only on solid scenery such as the sand, the table and the fence. Pots and bottles no longer keep a splat, because they break or move when hit.
- Automatic performance reports are more accurate. They no longer count time when the headset is off or the game is paused.

### Fixed
- DJ Booth music could stop with an error after about ten minutes of play. It now refreshes its connection and carries on.
- DJ Booth music now comes back by itself after you take the headset off and put it back on.
- If the DJ Booth could not connect, the Play button could stay stuck. It now recovers so you can try again.
- Paint splats no longer hang in the air in front of you.

### Known Issues
- The on-screen keyboard does not open in the feedback form. Use the voice button to dictate your message and your email.
- Quest 2 can still drop below full frame rate in busy moments.
- DJ Booth music is made by an experimental Google service. It may change or stop working without notice.

## [1.4.0] - 2026-04-01
Fairer game modes, sound for winning and running out of time, a tidier DJ Booth, and a smaller download.

### Added
- Cheering when you win, in both game modes.
- A warning sound when 30 seconds remain in Countdown mode.
- A Try Again sticker when the time runs out in Countdown mode.
- A Clear button on the DJ Booth. It empties the current prompt and deselects the presets.
- A notice on the DJ Booth: your voice is sent to Groq to be turned into text, and your music prompt is sent to Google to make the music. Both need an internet connection.
- A white line on the sand that marks the shooting zone.

### Changed
- Target Count mode: the gun stays active after you win, so you can keep shooting for fun.
- Countdown mode: hitting every target stops the timer straight away.
- Countdown mode: the gun locks when you win or run out of time. Pop the bubble to unlock it and start again.
- The Reset button now does everything in one press: targets come back, the hit count returns to zero, stickers hide and any playing sound stops.
- Paint splats stay where they land instead of vanishing after three seconds. Up to 100 are kept. After that the oldest one is replaced.
- Paint splats appear when the ball arrives, so far shots take a moment longer than near ones.
- Hands now use a stylised green colour.
- Voice commands always use the internet. The on-device voice model was removed, which makes the download about 77 MB smaller.

### Fixed
- The gun could lock by mistake in Target Count mode. It no longer does.
- Winning in Countdown mode could count the win twice when the clock reached zero. It now counts once.
- The clock now hides on both a win and a loss.

### Known Issues
- DJ Booth music is made by an experimental Google service. It may change or stop working without notice.
