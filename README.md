Clear Speech

Learn what to say, and how to say it clearly.

Clear Speech is a free speaking and articulation practice app that runs entirely in your browser. You hear someone say something, choose a reply, read it aloud, and get instant feedback on your words, your pace and your pauses.

Live app: https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/

Created by Venkateswara Rao Banday, built with Claude (Anthropic).

What you can do
Reply practice: hear a line such as "Good morning!" or "Do you have any questions?", pick a suggested reply, and say it aloud. Situations include greetings, thank you and please, asking questions, work and meetings, phone calls, shops and restaurants, apologies and disagreeing, small talk, travel and directions, health and doctor, and job interviews.
Sound drills: tongue twisters, TH / R / L, S / SH / CH / J, V / W / P / B, word endings, and longer passages.
Your own text: type or paste any sentence and practise it.
Feedback you get
Accuracy score and stars for every attempt, plus your best score on each sentence.
Word-by-word colours: green for clear, amber for a word heard as a different word, red for a skipped word. Tap any word to hear it spoken slowly.
Sound tips that explain the mistake, for example how to place your tongue for "th".
Pace in words per minute, with a comfortable range of 110 to 160.
Pause check: marks pauses that are too long, too short, in the wrong place, or missing at commas and full stops.
Hear yourself: play back your recording and compare it with the model voice.
Progress: day streak, daily goal of 5 tries, and number of sentences mastered.
Choice of accent: American, British, Indian or Australian English.
How to use
Choose a situation in Reply practice, or a sound in Sound drills.
Press Hear a model to listen.
Tap the round microphone button, wait for "Listening…", and read the sentence aloud. Tap again to stop.
Fix the amber, red and pause marks, then try again until the sentence is clean.
Run it

It is a single file with no build step and no dependencies.

On your computer

bash
python3 -m http.server 8000

Then open http://localhost:8000 in Chrome or Edge. Opening the file directly (file://) often blocks the microphone, so use a local server.

On GitHub Pages

Upload index.html to a public repository.
Go to Settings, then Pages, choose Deploy from a branch, select main and / (root), and save.
After about a minute your app is live at https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/.
Browser support
Browser	Support
Chrome, Edge (computer and Android)	Full
Safari (Mac and iPhone)	Speech feedback works; pause check may be limited
Firefox	Does not support speech recognition

The page must be served over https (or localhost) for the microphone to work.

Troubleshooting the microphone
Open the page in Chrome, Edge or Safari, not inside an in-app browser such as WhatsApp or Instagram.
Click the lock icon beside the address, set Microphone to Allow, and reload.
Choose the correct microphone in your browser and system sound settings.
Allow your browser to use the microphone in Windows or macOS privacy settings.
Close other apps that use the microphone, such as Zoom or Teams.
Press Test mic in the app. If you keep seeing "No speech detected", switch off Pause check & playback in the footer and try again.
Privacy

There is no account, no server and no tracking. Your progress is saved only in your own browser. Speech recognition is provided by your browser; in Chrome, audio is sent to Google's speech service to turn it into text.

Customise
Add or edit sentences in the CONV (replies) and DRILL (sound drills) lists near the top of the script in index.html.
Reply entries use this format: "What they say|Reply 1|Reply 2".
License

Free to use and share.
