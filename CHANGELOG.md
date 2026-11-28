# Changelog

Every Kroma Studio release, newest first, written for the people who use Kroma.

Each version's section is that release's notes: it's written here first, before the release, and the GitHub release on [Heang-Dev/kroma](https://github.com/Heang-Dev/kroma/releases) uses it word for word. The same notes appear on the website's [Changelog](https://heang-dev.github.io/kroma/changelog/).

## 0.2.3 — 2026-11-28

Notification banners on the Mac.

- **Notification banners on the Mac.** Kroma now asks your Mac for permission to show notifications, and appears in **System Settings → Notifications** as **Kroma Studio**. Before, macOS refused Kroma's notifications without asking. After updating, press **Send test** in **Settings → Notifications** and choose **Allow** when your Mac asks; then pick **Banners** for Kroma Studio in System Settings.
- **Kroma tells you when notifications are blocked.** If your computer refuses Kroma's notifications, a notice says so with **Open settings**, and **Settings → Notifications** shows a warning until one gets through.

## 0.2.2 — 2026-11-28

Cancelling a voice-over really stops it.

- **Fixed: a cancelled voice-over kept the voice engine busy.** Before, pressing cancel stopped it in Kroma, but the voice engine went on voicing every remaining line, so your next voice-over sat at **Waiting in line** until it finished. Now the engine stops after the line it's speaking, and the next voice-over starts straight away.

## 0.2.1 — 2026-11-28

Notifications you hear and see, even when your Mac hides them.

- **The notification sound always plays.** On the Mac, Kroma now plays the sound you chose in **Settings → Notifications** itself, inside Kroma and while you're in another app, even when macOS mutes Kroma's notifications. You never hear it twice.
- **Unread count on the Dock icon.** Kroma's icon shows how many notifications you haven't seen, so finished or failed work stands out even without banners. It bounces once when something fails while you're in another app.
- **Help when banners don't pop up.** **Settings → Notifications → Not seeing them?** explains the alert style (**Banners** or **Alerts**) and Focus, and **Notification log** shows what Kroma sent and whether your computer showed it.

## 0.2.0 — 2026-11-28

Tools for whole series: hide the original subtitles automatically, animated captions, one spelling for every name, your own styles, and numbered episode covers.

- **Hide original subtitles.** In **Objects**, **Hide original subtitles** now finds the Chinese subtitles burned into the video and puts a blur box exactly over them for the whole video, whether the video uses **Blur**, **Bars** or **Crop**. If it finds none it says so. Batch can do it too: turn on **Hide original subtitles** in its steps.
- **Animated captions.** In **Style → Subtitle style → Animation**, choose how each line appears: **Fade in**, **Pop** or **Slide up**. Or let the words follow the voice: **Spoken word** lights up the word being said (pick its colour in **Spoken word colour**), and **Word by word** shows words as they're said. The preview and the exported video move the same way.
- **Series glossary.** In **Translate → Series glossary**, names and terms get one spelling that every episode in the same folder uses. Kroma fills it in after a series' first translation, **Find names** adds more, and you can fix or remove any name. Gemini and Claude follow it; with Google Translate, the names are swapped in before translating.
- **Save as my style.** In **Style**, **Save as my style** keeps your whole subtitle look (font, colours, size, position, animation) under **My styles**, for every project and for Batch.
- **Episode covers.** In **Post → Cover**, make a thumbnail with the episode number (**ភាគ ៥**, **EP 5**, **Part 5** or your own word) and the series title, in four designs (**Badge**, **Big number**, **Banner**, **Minimal**) and any colour. The number is read from the episode's name ("05 - …", "EP12", "第27集"). Kroma picks a sharp frame, keeps hidden subtitles blurred, and **Save covers** saves 16:9 (YouTube) and 9:16 (TikTok, Reels) covers next to the exported videos. Batch can make covers for a whole series with **Make covers**.

## 0.1.13 — 2026-11-28

Many more subtitle styles, with Khmer display fonts, shadows and glows.

- **33 subtitle styles** in **Style → Subtitle style → Preset**, in four groups: **Outlined**, **Glow**, **Khmer fonts** and **On a box**. Each one shows as a small preview, drawn exactly as it will look in your exported video. Picking one changes the colours, outline, box, shadow and font; your size, position and **Bilingual** setting stay as they are.
- **Khmer display fonts.** Seven fonts now come with Kroma: Koulen, Moul, Battambang, Bayon, Dangrek, Fasthand and Hanuman. Choose one in **Font**, or pick a style that uses it, such as **Moul gold**, **Poster**, **Comic**, **Serif** or **Handwritten**.
- **Shadow and glow.** A new **Shadow** slider adds a soft shadow under the text. **Shadow colour** turns it into a glow, as in **Gold glow**, **Fire**, **Ice** and **Magic**.
- More boxes: **Light box**, **White box**, **Highlight**, **Violet box**, **Red box**, **News**, **Blue box** and **Green box**.
- **Batch** offers every style in its **Subtitle style** list.
- Your existing projects keep exactly the look they had.

## 0.1.12 — 2026-11-28

More reliable updates on the Mac.

- **Updates download once.** Checking for updates while a download is already running no longer starts a second download of the same file, which could make the progress jump back and forth and spoil the download.
- **A damaged download is caught.** Kroma checks the downloaded update against the one on GitHub, and downloads it again instead of installing a broken copy.
- **A downloaded update survives a restart.** If you quit Kroma before pressing **Restart to update**, the update is ready straight away next time, without downloading it again.
- **If an update can't be installed, Kroma says why.** When your Mac doesn't let Kroma replace itself in Applications, Kroma reopens as before, tells you what happened, and opens the new Kroma Studio in Finder so you can drag it into Applications. You can also allow Kroma Studio in **System Settings → Privacy & Security → App Management**.

## 0.1.11 — 2026-11-28

Your API keys stay saved through updates, Kroma opens where you work, and notifications can make a sound.

- **API keys no longer disappear after an update.** If a new version of Kroma can't read a saved key from the Mac's keychain, the key is kept instead of being lost, and **Settings** says so. Paste it again, or choose **Always Allow** when your Mac asks. If your keys went missing after an earlier update, paste them once more in **Settings → Translation**, **Speech to Text** and **Posting**.
- **Kroma opens where you work.** **Settings → Translation** now opens only the very first time you start Kroma, not after every restart or update.
- **Notification sounds.** In **Settings → Notifications**, choose a sound for **When work is done** and **When something fails** (on the Mac, from its own sounds), and press **Play** to hear it. Notices shown inside Kroma play the sound too.
- **Not seeing notifications?** **Settings → Notifications → Not seeing them?** opens your system's notification settings, where you can allow Kroma Studio and its sound.
- The notification bell now sits after **New**, **Open** and **Save** in the title bar.

## 0.1.10 — 2026-11-27

**Batch: process many videos at once**

- New **Batch** page. Add videos from the Download Center (or any project files), choose the steps once: subtitles, translate, find characters, voice-over, remove original voices, subtitle style, export, post text. Then press **Process**. Each video goes through every step, one after another, while you do something else.
- It stops before posting, so you check each video first. Finished videos wait in **Ready to post**.
- Follow every video's progress step by step. If a step fails, Kroma says why and you can **Retry from here** or **Fix by hand**. The list is kept, so after a restart you see where things stopped.
- In the Download Center, tick finished downloads and send them to Batch.
- You get a notification for each video and a summary when the batch is done.

**The right format for each platform**

- When posting, choose the format for each platform: YouTube 16:9, and TikTok, Facebook and Reels 9:16 by default. Kroma exports each format it needs and uploads the right file to each platform. This works in the Post panel and in Ready to post.

**Nicer empty pages**

- Pages with nothing in them yet now show a small illustration and say what to do next.

Only post videos you have the right to use, and only clone voices with the speaker's permission.

## 0.1.9 — 2026-11-27

Notifications, and a better list of supported sites.

- **Notifications.** A bell in the title bar keeps everything that finished or failed — downloads, subtitles, translation, voice-overs, exports, posts, stories — with a button to retry or open it. When Kroma is in the background, your computer tells you too.
- **Settings → Notifications**: turn notifications or their sound off, only be told about failures, choose which kinds you want, and send a test.
- **Supported sites** is now a grid: Chinese sites first, what works on each, and **Open site** to visit it.
- **Check for updates follows "Update automatically".** With it off, checking only tells you a new version is out; you choose when to download.


## 0.1.8 — 2026-11-27

Dropdowns you can search, and adding characters to a story.

- **Every dropdown can be searched.** Lists open with a search box: type "king", "girl" or "narrator" to find a voice. The current choice has a ✓ and is shown straight away; voices are grouped (your voices, then the presets by kind, then instant voices) with a line about how each one sounds.
- **Story → Add character.** Type a name in the Cast panel and press Add: a new line starts for them in the script, with a fitting voice you can change.
- A character shows up in the cast as soon as you start their line.


## 0.1.7 — 2026-11-27

The Download Center, and one look for every page.

- **Download Center** (Downloads in the left menu). Paste links — a Bilibili, Douyin or YouTube video, a whole series, a collection, a multi-part upload or a channel; share messages work too. **Find videos** lists them all; tick the ones you want, choose the quality, and **Download**. Each video becomes **its own project**, numbered in a folder for the series, ready to translate and voice.
- **The queue** downloads 1–3 at a time with speed and time left, keeps going while you work, picks up after a restart, never downloads the same video twice, and waits when a site asks it to slow down.
- **Import files / a folder**: episodes you already have become one project each, in the right order (EP1, EP2 … EP10), with their .srt subtitles.
- **Supported sites**: Chinese sites first; ✓ means it works, **Free only** means free episodes download and VIP episodes are locked.
- **YouTube** works without installing anything else.
- **One look for every page**: the same header on Voices, Story and Downloads; Voices has filters and search; a wider left menu so every label fits.


## 0.1.6 — 2026-11-27

Kroma's own voice engine, and a cleaner, steadier interface.

- **The voice engine is built in.** Settings → Voice Engine → **Install voice engine** sets it up once (about 2 GB, a few minutes); then **Start**. Nothing else to install or run. The first start downloads the voice model (about 5 GB). Turn on **Start the engine with Kroma** to have voices ready every time.
- **Free Colab GPU, in one click.** Choose **Google Colab** and press **Open in Colab**; paste the address it prints.
- **Story studio, laid out like an editor.** Your stories on the left; **Write** (the script with Insert Pause and speaker buttons, and the cast beside it) and **Listen** (the player and every line with ↻ to speak it again).
- **Voice engine status in the status bar** on every page: start it from there.
- **Settings → Voice Engine** shows what to do next: Install, Start, Stop, Update or Remove.
- **Everything lines up**: one height for every button, field and dropdown, borders instead of shadows, side panels that open wide enough and stretch their switches, button labels that fit, long names that end in "…".
- The **status bar is on every page**, and the voice players look the same everywhere.
- Importing from Khmer Voice Studio is gone: Kroma has everything itself, and makes its preset voice samples on its own.


## 0.1.5 — 2026-11-27

Story studio, and updates you can follow.

- **Story studio.** A new **Story** page in the left menu: write a story one line per speaker (`Sokha: …` or `សុខា៖ …`), give every character their own voice and style, and Kroma reads it with the Khmer Voice Studio engine. Add `[pause 2s]` for a pause and `Sokha (whisper): …` for one line's own style. Not happy with one line? Press ↻ to speak just that line again; the rest stays the same and the earlier version is kept. Save the audio (with its .srt subtitles) wherever you like.
- **Updates you can follow.** The update card shows the speed and time left, and a dropped connection picks up where it stopped instead of starting over. Minimize the card into the status bar and keep working; click it to open it again.
- **Check for updates** from the status bar at any time.
- **Settings** in the left menu has its label like the other items, and the Settings page shows which version you're running.
- **The purple Kroma icon** in the title bar. After an update, the Dock and Finder show the new icon straight away.
- The **Next** hint sits right after the steps in the status bar.


## 0.1.4 — 2026-11-27

A new look, and fixes that matter when Kroma runs on your computer.

- **New logo.** The purple Kroma Studio icon.
- **Your edits are safe.** **Get subtitles**, **Translate all** and **Import .srt** now ask before replacing lines you already have (and Undo brings them back).
- **Any language from the site.** Kroma uses the site's own subtitles in English or other languages too, not only Chinese.
- **Words follow your language.** "Make Thai subtitles", "the original line above the translation", and so on.
- **Shortcuts on Windows and Linux** show Ctrl, Shift and Backspace. **Save as a new file** and **New window** are listed in Settings → Shortcuts.
- **Khmer Voice Studio import** has its own folder setting in **Settings → Voice Engine**.
- The **Export** step stays ticked after a restart. Deleting a cloned voice moves the project and its characters to an instant voice.

Kroma updates itself: this version downloads in the background and asks you to restart.


## 0.1.3 — 2026-11-27

A cleaner editor, laid out like Orca.

- **Steps at the bottom.** The step bar (Video → Subtitles → Khmer → Characters → Voices → Style → Export) is now a slim status bar along the bottom of the window, with **Next** at the right end.
- **Updates in a card.** New versions now show in a card in the bottom-right corner: download progress, then **Restart to update** or **Later**. After **Later**, a small **Restart to update** stays in the status bar.
- Notices sit just above the status bar.

Kroma updates itself: if you have 0.1.1 or 0.1.2, this version downloads in the background and asks you to restart.


## 0.1.2 — 2026-11-27

Fixes automatic updates on Windows and Linux (AppImage). macOS updates were already working.

From now on Kroma updates itself: it downloads new versions in the background and shows **Restart to update** in the title bar.


## 0.1.1 — 2026-11-27

Automatic updates: Kroma now checks for new versions, downloads them in the background and shows **Restart to update** in the title bar. From this version on, you'll never need to download Kroma again by hand.

- Settings → About → Updates: check now, update automatically on or off
- The code is open source (MIT): https://github.com/Heang-Dev/KROMA.STUDIO

If you have 0.1.0, download this version once; after that updates come by themselves.


## 0.1.0 — 2026-11-27

First release for macOS (Apple silicon), Windows 10/11 and Linux.

- Download from 1,000+ sites, subtitles from the site or cloud speech-to-text
- Translate to Khmer (or Thai, Vietnamese, Lao, English, Indonesian, Malay)
- Characters with their own voices: 36 Khmer preset voices, voice cloning, instant voices
- Remove the original voices, blur burned-in subtitles, add logos and text
- Export Small / Standard / High, and post to YouTube, Facebook and TikTok in one click
- Free translation and speech to text: Gemini (free tier) or Google Translate, with Groq or OpenAI Whisper for speech to text
- Find who says each line, record your own voice to clone, and timing that never cuts a voice line short
- Paste a share message and Kroma pulls out the link and the title; download errors are explained in plain words
- A timeline that shows frames of the video and its waveform
- Light, dark or system theme, interface zoom (⌘ + / − / 0), resizable panels, and several windows at once

The installers aren't code-signed yet: see the README for opening them on each system.
