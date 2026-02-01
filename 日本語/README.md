# Japanese Mastery Roadmap (AJATT Style)

## 1. Accelerated Foundation (The Hanzi Advantage)
* **Current Deck:** [jp1k](https://ankiuser.net/study) 
* **Target:** 50 new cards per day[cite: 1].
* **Strategy:** Treat this as a pure **Reading and Listening** exercise. Since you already understand Hanzi, focus only on the Japanese pronunciation and audio. 
* **Action:** Suspend any cards that only test character meaning to maintain maximum speed.

## 2. Sentence Mining Sources
Harvest "1-Unknown" (1T) sentences from these high-value sources:
* **Professional:** Work emails from Japanese customers and coworkers.
* **Literary:** 聖書 新共同訳 (Bible 1987, 1988).
* **Daily Practice:** Duolingo (limit to 15 mins/day to fill basic grammar gaps).

## 3. Technical Audio & Pitch Stack
For every mined sentence, build a card using this integrated workflow:

1.  **Native Reference:** Generate high-quality audio using **ElevenLabs**.
2.  **Self-Audit:** Record your own voice and process it through [MacWhisper](https://github.com/tigerpeng2001/macwhisper-phonetic-logs) to generate phonetic logs.
3.  **Pitch Visualizer:** Paste your sentence into [Suzuki-kun: Prosody Tutor](https://www.gavo.t.u-tokyo.ac.jp/ojad/eng/phrasing/index) to generate a pitch contour.

## 4. Anki Card Template

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

## 5. Success Metrics
* **Anki Efficiency:** Keep daily review time under 30 minutes.
* **Massive Input:** 2+ hours of passive listening using the audio from your own mined sentences.
* **Final Goal:** Transition to a Monolingual (Japanese-only) dictionary once you hit 2,000 sentences.