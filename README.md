# Android Apps — MIT App Inventor (2020–21)

Where I started coding: 27 Android apps I built in [MIT App Inventor](https://appinventor.mit.edu/) during the 2020–21 lockdown. Some are full apps, some are quick experiments and tutorial builds — all of them are here as-is.

Part of my portfolio: **[github.com/Shlok-Sinha](https://github.com/Shlok-Sinha)**

## Open an app

1. Go to [ai2.appinventor.mit.edu](https://ai2.appinventor.mit.edu/) and sign in.
2. **Projects → Import project (.aia) from my computer**, pick a file from [`apps/`](apps).
3. Use **Connect → AI Companion** to run it live on your phone, or **Build → Android App (.apk)** to install it.

## Featured

| App | What it does | Built with |
| --- | --- | --- |
| [**All-in-One app**](apps/User_friendly.aia) | Home screen hub: video calling (create / join a meeting with a code on a web page I hosted), a Mole Mash game, text-to-speech and a settings screen. | CustomWebView extension, Sharing, Canvas, Clock |
| [**Find Me**](apps/Find_Me.aia) | Reads incoming text messages aloud and auto-replies with the phone's current GPS location. UI in Spanish. | Texting, LocationSensor, TextToSpeech |
| [**FlappyCopter**](apps/FlappyCopter.aia) | Flappy-style side-scroller: tap to fly a copter through pipes, collisions, sound effects and a saved high score. | Canvas, 15 ImageSprites, 10 Clocks, TinyDB |
| [**Translator multi-tool**](apps/Text_to_speech.aia) | Seven-screen app: translate text, speak it, recognise your speech, flip a coin, a to-do list, a country → capital / currency lookup and a small game; shake detection on the home screen. | YandexTranslate, SpeechRecognizer, TextToSpeech, AccelerometerSensor |
| [**Diary**](apps/Diary.aia) | A diary locked behind the phone's fingerprint sensor. | FingerprintSensor extension |
| [**Reminders**](apps/reminder.aia) | Set reminders that fire real system alarms and notifications, and read them out loud. | TaifunAlarm + TaifunNotification extensions, TextToSpeech |
| [**Video call app**](apps/Video_call_app.aia) | Standalone version of the video calling: create a meeting, share the code, or join one. | CustomWebView extension, Notifier |
| [**Rock Paper Scissors AI**](apps/RockPaperScissors_withAI_Starter.aia) | Plays against you and learns your patterns with a Markov transition matrix. | Lists, Images |
| [**Voice Calculator**](apps/VoiceCalculator_Starter.aia) | Speak a sum, it works it out and says the answer back. | SpeechRecognizer, TextToSpeech |

## More apps

| App | What it does |
| --- | --- |
| [Paint](apps/Paint_app.aia) | Draw in colours and brush sizes, or paint over a photo from the camera. |
| [Sharing](apps/Sharing.aia) | Draw on a canvas or a photo, save it and share it to other apps. |
| [Xylophone](apps/Xylophone.aia) | 8-note xylophone that records what you play and plays the tune back. |
| [Step Counter](apps/Step_Counter.aia) | Pedometer with start / stop / reset. |
| [Mole Mash](apps/Mole_mash.aia) | Whack-a-mole with a score and reset. |
| [Buzz the Bee](apps/Buzz_the_bee.aia) | Tap the bee to make it buzz. |
| [Remember location](apps/something.aia) | Shows your GPS position and address, remembers a spot and gives directions back to it in Maps. |
| [Quiz](apps/Quiz.aia) | Pick a grade and subject, opens the matching quiz. |
| [Country lookup](apps/Listpicker.aia) | Pick a country, see its capital and currency. |
| [Speakly](apps/speakly.aia) | Type anything, the phone says it. |
| [Phone call](apps/phone_call.aia) | Pick a contact or type a number and call it. |
| [Students list](apps/exelextracting.aia) | Pulls a student list from an online spreadsheet into a list view. |
| [All-in-One checkpoint](apps/User_friendly_Screen_checkpoint1.aia) | Earlier checkpoint of the All-in-One app, with a proximity-sensor screen. |

## Experiments

Small tests while learning: [bla](apps/bla.aia), [calculator](apps/calculator.aia), [date](apps/date.aia), [flappy_bird](apps/flappy_bird.aia) (an early start before FlappyCopter), [test](apps/test.aia).

---

Some apps started from MIT App Inventor tutorials (*Starter* projects) and were extended from there. Extensions used: CustomWebView, FingerprintSensor, Taifun Alarm / Notification — they ship inside the `.aia` files.
