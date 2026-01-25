# 🎙️ whisper-phonetic-logs

A data-driven approach to mastering English and Chinese pronunciation using the M4 Max Neural Engine and "Honest AI" feedback.

---

## 🛠️ The Toolkit
* **Hardware:** MacBook Pro (M4 Max)
* **Transcription:** [MacWhisper](https://macwhisper.com) (Tiny Model) - used as the "Honest Ear."
* **Benchmarking:** [ElevenLabs](https://elevenlabs.io/) - used for generating "Gold Standard" audio for comparison.
* **Storage:** GitHub with **Git LFS** for audio tracking.
* **Analysis:** Gemini AI - used for phonetic coaching and mouth-positioning.

---

## 📂 File Structure
```text
.
├── 日本語
├── audio
│   └── English
│       └── 2026
│           └── 01
│               ├── 25.s1.m4a
│               └── 25.s2.m4a
├── English
│   └── 2026
│       └── 01
│           └── 25.md
├── español
└── README.md
```

## ⚙️ Workflow & Technical Setup

1. **Recording & Exporting (MacWhisper)**
	 - Open MacWhisper: Select the Tiny model for maximum phonetic honesty.
	 - Record: Use the microphone icon to record your verse.
	 - Export Audio:
		 1. Right-click the recording in the sidebar.
		 2. Select Export Audio...
		 3. Save as .m4a or .mp3 to the corresponding path: audio/[Language]/[Year]/[Month]/[Day].s[Number].m4a.
	 - Export Transcript: Copy the text directly or export as a text file to [Language]/[Year]/[Month]/[Day].md.

2. **Tracking Audio (Git LFS)**

   Since audio files are binary and large, we use Git Large File Storage to prevent the repository from bloating.
   - Initialize LFS (Once): git lfs install
   - Track Audio Formats:
        ```
        git lfs track "audio/**/*.m4a"
        git lfs track "audio/**/*.mp3"
        git add .gitattributes
        ```
3. **Syncing to GitHub**

    Always follow this sequence to ensure your "Journey" is saved:
        ```
        # Move to repo root
        cd ~/personal/git/macwhisper-phonetic-logs

        # Add all changes
        git add .

        # Commit with a meaningful note
        git commit -m "Practice [Date]: Fixed vowel clarity in 1 John 4"

        # Push to the cloud (using SSH Alias)
        git push origin main
        ```
---
*“If the Tiny model understands me, the world will too.”*