# 🎙️ Voice Interpreter

> *"Is it possible to create a tool you can speak into and have it interpret to any other language?"*
>, The question that started it all.

A real-time AI-powered voice interpretation web app, built entirely through conversation, curiosity, and creative prompting. No coding background required.

**Live app:** [jenvic96.github.io/voice-translator](https://jenvic96.github.io/voice-translator)

---

## 💡 The Idea

This project started with a single question and evolved through dozens of thoughtful follow-ups. Every feature in this tool came from the creator's instinct to push further:

- *"Can it automatically play the audio after translating?"*
- *"Can it switch languages automatically so the other person can reply?"*
- *"Could this help an ASL person?"*
- *"Can we make it a 2-step tool, one page per action?"*
- *"What about people in Belgium, what language do they speak?"*
- *"Can we order the flags by accuracy without advertising it?"*
- *"Could this eventually become an app?"*

Each of these questions shaped the tool into something genuinely useful, accessible, and polished. That's AI literacy in action, knowing what to ask, when to push, and how to iterate.

---

## ✨ Features

- 🎤 **Voice recognition**, speak naturally, transcribes instantly
- 🌍 **41 languages**, ordered silently by translation accuracy
- 🔄 **Auto language swap**, flips speakers automatically after each interpretation
- 🔊 **Natural AI voices**, powered by ElevenLabs, with browser voice fallback
- ▶️ **Auto-play**, speaks the interpretation out loud immediately
- ⌨️ **Type mode**, works without a microphone
- 🤟 **ASL Mode**, text-to-text for deaf/hard-of-hearing users, auto-sets English for Speaker 1
- 🔠 **Font size controls**, A / A+ / A++ for readability (available in ASL mode)
- ⬤ **ASL Contrast**, high contrast mode for better visibility
- 🔒 **Access code protected**, only people with the code can enter
- 📊 **Accuracy breakdown**, tap ℹ️ to see all 41 languages grouped by translation quality
- 🎨 **Custom design**, mint & pink palette from ColorHunt
- 2️⃣ **Two-step flow**, Step 1: choose languages · Step 2: interpret
- 📱 **PWA, installable**, works like a native app on Android and iPhone
- 🍎 **iOS audio unlock**, handles Apple's auto-play restrictions gracefully
- 🌐 **Cross-platform**, Android, iPhone, Mac, Windows, all browsers

---

## 🚀 How to use

1. Open the link and enter the access code
2. On iPhone, tap **Enable Audio** once to unlock playback
3. **Step 1**, each speaker taps their flag to set their language
4. Tap **Start Interpreting →**
5. **Step 2**, tap **Hold to Speak** and say something
6. The interpretation appears and plays out loud automatically
7. Languages swap so the other person can reply right away
8. For ASL users, tap 🤟 **ASL Mode** to switch to text-to-text

---

## 📲 Install as an app

**Android Chrome:**
1. Open the link in Chrome
2. Tap ⋮ menu → **Add to Home Screen**
3. Done, icon on your home screen, opens fullscreen

**iPhone Safari:**
1. Open the link
2. Tap the Share button → **Add to Home Screen**

**Mac/Desktop Chrome:**
1. Open the link
2. Click the ⊕ install icon in the address bar

---

## 🛠️ Built with

- **HTML / CSS / JavaScript**, single file, no framework
- **Web Speech API**, browser-native voice recognition
- **Google Translate API**, free, no key required, 41 languages
- **ElevenLabs API**, AI-powered natural voice (with browser TTS fallback)
- **GitHub Pages**, free HTTPS hosting
- **PWA**, manifest + service worker for native app experience

---

## 📱 Device compatibility

| Device | Voice input | Translation | Audio playback |
|--------|-------------|-------------|----------------|
| Android Chrome | ✅ | ✅ | ✅ Auto-plays |
| iPhone Safari | ⚠️ May vary | ✅ | ✅ After one tap |
| Mac Chrome | ✅ | ✅ | ✅ Auto-plays |
| Desktop Safari | ⚠️ May vary | ✅ | ✅ After one tap |
| Firefox | ❌ Type mode only | ✅ | ✅ |

---

## 🌐 Languages supported (ordered by accuracy)

**Excellent**, English · Spanish · French · German · Portuguese · Italian · Japanese · Chinese · Korean · Russian · Arabic

**Good**, Dutch · Flemish · Polish · Swedish · Turkish · Vietnamese · Indonesian · Hindi · Ukrainian · Thai

**Decent**, Greek · Hebrew · Romanian · Hungarian · Czech · Danish · Finnish · Norwegian · Bengali · Urdu · Persian · Malay · Tamil · Slovak · Bulgarian · Croatian

**Limited**, Swahili · Afrikaans · Catalan · Amharic · Latin ⚜️

---

## 🤟 ASL Accessibility

When ASL Mode is activated:
- Speaker 1 is automatically set to English
- Speaker 2 can choose any language
- Both speakers get independent text input boxes
- Translations appear instantly as you type (no mic needed)
- Font size controls appear (A / A+ / A++) for readability
- High contrast mode available for better visibility

---

## 📝 Notes

- Microphone access requires **HTTPS**, works best on **Chrome**
- ElevenLabs free tier: 10,000 characters/month · falls back to browser voice automatically
- Google Translate: effectively unlimited for normal use
- Page stays unlocked for the full browser session after entering the code
- Translation quality improves automatically as Google updates their models

---

## 🤝 Credits

**Concept, vision & direction**, @jenvic96

Every feature in this tool was driven by the creator's questions, instincts, and iterative thinking. From the initial idea to ASL accessibility, from color palettes to PWA installation, this project is a testament to what's possible when curiosity meets the right tools.

**Built with**, [Claude](https://claude.ai) by Anthropic

This entire project was built through natural conversation, no IDE, no coding environment, no technical background needed. Just clear thinking, good questions, and the willingness to keep pushing.

> *"What a project huh"*, @jenvic96, after session 1 😄

---

*A love letter to AI literacy. Anyone can build something remarkable, you just have to know what to ask.*
