# 🗣️ Accessible Voice-Navigable Web App

A modern, accessibility-first, multi-page web application designed for inclusive interaction. Built using pure HTML, CSS, and JavaScript, the app supports keyboard navigation, flexible voice commands, and an intuitive microphone toggle button — creating a seamless and accessible experience for all users.

---

## 🚀 Features

### 🔄 Navigation
- ⬅️➡️ Keyboard Support: Use ArrowRight and ArrowLeft keys (also d and a) to navigate between pages.

- 🎙️ Voice Commands:

  - "Next page" – Go forward

  - "Previous page" – Go back

  - "Hey Ash" – Triggers a custom greeting alert

  - "Go to contact" / "Contact us" – Jump directly to the contact form page

- 🎛️ Voice Toggle Button: A microphone icon button to start/stop voice recognition with clear visual and ARIA states.

- 🎧 Listening Indicator: Animated dots show when the app is actively listening.

- 🛑 Error Handling: Displays recognition errors and disables voice toggle gracefully when needed.

### 📄 Pages
- Page 1 – Welcome screen with usage instructions

- Page 2 – Informational content

- Page 3 – Additional page content

- Contact Us – Accessible contact form with simple submission feedback

---

## ♿ Accessibility Highlights

- ✅ Semantic HTML with proper ARIA roles and aria-labelledby for screen readers

- ✅ Keyboard + voice navigation for full user control

- ✅ Focus management moves focus to page headings after navigation

- ✅ Visual and ARIA feedback on voice recognition toggle and listening state

- ✅ Responsive design with viewport meta tag for mobile devices


---

## 🛠 Tech Stack

- HTML5

- CSS3

- JavaScript (Web Speech API / SpeechRecognition)

- 💡 Framework-free and fully browser-based — no backend required

---

## 📖 Instructions

1. Open index.html in Google Chrome (best voice recognition support).

2. Navigate using:

- ⌨️ Arrow keys (ArrowRight, ArrowLeft) or keys d and a

- 🗣️ Voice commands by clicking the microphone button to start/stop listening.

3. Use voice commands like:

- "Next page"

- "Previous page"

- "Hey Ash"

- "Go to contact" or "Contact us"

4. Fill out and submit the Contact Us form to see confirmation feedback.

---

## 🗣️ Voice Commands Reference

| Command       | Action                                |
| ------------- | ------------------------------------- |
| Next page     | Moves to the next page                |
| Previous page | Goes back one page                    |
| Hey Ash       | Triggers a friendly greeting          |
| Go to contact | Navigates directly to Contact Us page |

---

## 🔮 Future Enhancements

- ✅ Form submission success feedback (implemented)

- ✅ Expanded voice commands for deeper navigation and interaction

- ✅ Dark mode toggle for improved visual accessibility

- Voice command error recovery and retry options

---

## 🌐 Compatibility

| Feature                | Chrome | Firefox | Safari | Edge  |
|------------------------|--------|---------|--------|-------|
| Keyboard Navigation    | ✅ Yes | ✅ Yes  | ✅ Yes | ✅ Yes |
| SpeechRecognition API  | ✅ Yes | ❌ No   | ❌ No  | ⚠️ Partial |

> ⚠️ Best experienced in **Google Chrome** due to Web Speech API compatibility.

---

## 📜 License

Open-source under the **MIT License**.  
Use responsibly and contribute to a more inclusive web! 🌍

---

👤 Developed by **Ashley** – Empowering accessibility through code.
