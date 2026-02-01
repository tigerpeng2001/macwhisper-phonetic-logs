# Japanese Mastery Roadmap (AJATT Style)

## 1. Accelerated Foundation (The Hanzi Advantage)
* **Current Deck:** [jp1k](https://ankiuser.net/study)
* **Target:** 50 new cards per day.
* **Strategy:** Treat this as a pure **Reading and Listening** exercise. Since you already understand Hanzi, focus only on the Japanese pronunciation and audio.
* **Action:** Suspend any cards that only test character meaning to maintain maximum speed.

## 2. Audio vs. Text Priority (The Roadmap Plan)
* **Immediate Phase:** Continue with **Text on Front**. Use the [Toggle Readings] feature on [AnkiWeb](https://ankiuser.net/study) sparingly to force your brain to map Japanese sounds (Onyomi/Kunyomi) to Kanji.
* **Transition Point:** Switch to **Audio-Only Fronts** after reaching ~500 mature cards in the [jp1k](https://ankiuser.net/study) deck.
* **Sentence Mining Rule:** Use **Audio-Only Fronts** immediately for work emails and high-priority listening targets to bypass "Hanzi-reading" dependency.

## 3. Sentence Mining Sources
Harvest "1-Unknown" (1T) sentences from these high-value sources:
* **Professional:** Work emails from Japanese customers and coworkers.
* **Literary:** 聖書 新共同訳 (Bible 1987, 1988).
* **Immersion:** Podcasts (N3/N4 level) and Anime (1-2 hours/week).
* **Daily Practice:** Duolingo (limit to 15 mins/day to fill basic grammar gaps).

## 4. Passive Immersion (The Podcast Engine)
* **Strategy:** Use "Dead Time" (running, commuting, chores) for listening.
* **Primary Source:** [Let’s Talk in Japanese! (Tomo)](https://podbay.fm/p/lets-talk-in-japanese).
    * **Filtering:** Use the search bar in Spotify/Podcast app to search for **"N3"** or **"N4"**. 
    * **Note:** As a Chinese speaker, start with **N3**; N5/N4 may be too slow for your comprehension level.
* **Supplemental Sources:**
    * **[Nihongo con Teppei](https://nihongoconteppei.com/):** Use for "High-Frequency" listening. Best for getting used to natural Japanese rhythm and speed without complex grammar.
    * **[Learn Japanese with Masa Sensei](https://www.facebook.com/learnjapanesewithmasasensei/):** Use as a "Grammar Reference." If you encounter a confusing particle or verb conjugation in a work email, find his corresponding episode to clarify the rule.

## 5. Technical Audio & Pitch Stack
For every mined sentence, build a card using this integrated workflow:
1. **Native Reference:** Generate high-quality audio using **ElevenLabs**.
2. **Self-Audit:** Record your own voice and process it through [MacWhisper](https://github.com/tigerpeng2001/macwhisper-phonetic-logs) to generate phonetic logs.
3. **Pitch Visualizer:** Paste your sentence into [Suzuki-kun: Prosody Tutor](https://www.gavo.t.u-tokyo.ac.jp/ojad/eng/phrasing/index) to generate a pitch contour.

## 6. Anki Card Template

### Front
- {{Sentence_Text}}
- [▶️ Native_ElevenLabs_Audio]

---

### Back
**Pitch Accent Contour:**
- (Insert screenshot from [OJAD Suzuki-kun](https://www.gavo.t.u-tokyo.ac.jp/ojad/eng/phrasing/index))

**My Pronunciation Audit:**
- [▶️ My_Voice_Recording](https://github.com/user-attachments/assets/87f0c2ca-f489-4d3c-9210-9b9fcc866dfd)

**Phonetic Logs (MacWhisper):**
> {{Transcription_Logs_from_GitHub}}

**Context:**
- {{Source_Email_or_Bible_Verse}}

## 7. Success Metrics
* **Anki Efficiency:** Keep daily review time under 30 minutes.
* **Massive Input:** 2+ hours of passive listening using the audio from your own mined sentences.
* **Final Goal:** Transition to a Monolingual (Japanese-only) dictionary once you hit 2,000 sentences.