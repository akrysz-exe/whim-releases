# Changelog

## 0.6.11
- **Add to queue from quick search (Ctrl+Alt+S):** each result has an add-to-queue button. It turns into a green check once added, and the bar stays open so you can add several songs.
- **No more messages over the player card** (like "Playing: ..." or "Added to queue").

## 0.6.10
- **Adding to the queue works again after Whim sat idle:** after a few hours paused, adding a song to the queue failed. Whim now reconnects to Spotify by itself and adds it.
- After reconnecting, what you were listening to comes back (still playing if it was). If you're listening on your phone, Whim leaves it there.

## 0.6.9
- **Songs play again after Whim sat idle:** after a few hours paused, clicking a song in search, in quick search (Ctrl+Alt+S) or in your library did nothing until you restarted Whim. Whim now reconnects to Spotify by itself and plays the song.
- Shuffle and play/pause recover the same way.

## 0.6.8
- **The card slides out of the record:** hover the record and the card comes out of it like a drawer, with everything on it sliding out from behind the record. It tucks back in when it closes.
- **No more blue strip:** the flash that showed up while the card, the panels or a message opened is gone.
- **Smoother panels:** the library switches between playlists and songs at once, and search results fade in together instead of one by one.
- The play/pause icon now crossfades, and the buttons give a light press feedback.
- **Reduce animations:** new switch in *Settings â†’ General*. Whim now animates even when Windows' animation effects are off; use this switch if you want less movement.
## 0.6.7
- **Terms of use in the installer:** new installs now show the terms (English and Portuguese) and need you to tick *I accept the terms* before installing. They explain that Whim is unofficial and that using it, especially with a Free account, can get your Spotify account limited or banned. Updates skip this page.

## 0.6.6
- **Quick search bar:** press <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>S</kbd> anywhere to open a search bar in the middle of the screen. Type a song, pick it with the arrows and Enter (or click it) and it plays. <kbd>Esc</kbd> or clicking away closes it.
- **Waves shortcut:** <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>W</kbd> turns the neon waves on and off (the neon stays on). Both new shortcuts can be changed in the settings.
- **Play now from the queue:** click a song in *Up next* and it starts right away; the rest of the queue and the playlist stay as they were.
- The queue now updates by itself when the song changes.
- The record's card always closes when you click outside it, and hides when the mouse leaves even after clicking the record.
- Whim now installs to its own folder (`Programs\whim`).

## 0.6.5
- **Whim is now in English:** every screen, button, message and the tray menu.
- Updates now come from the new home of the project, `akrysz-exe/whim-releases`.

## 0.6.4
- **Free accounts now get the library on the record:** browse your playlists and Liked Songs, play a whole playlist or start from a given song, and add songs to your playlists. The queue is still Premium-only.

## 0.6.3
- **Free accounts:** the Spotify login window no longer disappears when you go to type the code sent by email.

## 0.6.2
- **Free accounts:** if you still need to log in to the Spotify player, the record tells you and has a button to open the login window (also in the tray menu). No more restarting Whim.
- The web player reopens by itself if its window disappears.

## 0.6.1
- Internal improvements to the auto-updater.

## 0.6.0 â€” automatic updates
- Whim now updates itself. It checks for new versions on start and every 4 hours, downloads them in the background and installs them when you close it. You can also update right away from the tray menu.

## Before 0.6
- **Neon in the album's true colours.** Skin, hair and wood tones no longer turn orange. Black-and-white covers give a silver neon.
- **Reliable shortcuts.** One press is always one action, even on keyboards that "bounce". The app no longer freezes for half a second when the music resumes.
- **Volume shortcuts:** <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>â†‘</kbd> / <kbd>â†“</kbd>.
- **A big record, fixed in the corner** of the desktop, with a card that slides smoothly out of it.
- **Monitor choice** in the tray menu for anyone with more than one, including portrait monitors.
- **Adjustable neon wave height.**
- **Playlists:** clicking a playlist opens its songs; â–¶ plays all of it.
- **Lyrics always in sync,** at 100 fps.
- **Much lighter:** animations pause when a game or a window covers the screen, and the backdrop and neon use far less CPU and memory.
- **A new minimal look** for the record and Settings. Your Spotify profile picture shows on the account.
