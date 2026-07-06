# Purrfect Match AI: Hackathon Submission & Video Demo Guide

This document contains the official **Judge Testing Instructions** and a **Video Demonstration Narration Script** to help you complete your submission for #hackthekitty 2026.

---

## Part 1: Official Testing Instructions for Judges

*To satisfy the requirement: "If your project requires login credentials or special access to test, include testing instructions in your submission. Judges must be able to access and test your project free of charge."*

### Live Deployment Links
* **Live Website (Frontend)**: [https://purrfect-match-ai.vercel.app/](https://purrfect-match-ai.vercel.app/)
* **Backend API (Swagger Docs)**: [https://purrfect-match-backend.onrender.com/docs](https://purrfect-match-backend.onrender.com/docs)
* **Access Cost**: 100% Free of charge.

### Step-by-Step Testing Guide for Judges

1. **Instant Account Creation**:
   * Navigate to [https://purrfect-match-ai.vercel.app/](https://purrfect-match-ai.vercel.app/).
   * Click **Sign In / Register** in the top right.
   * Click **Sign Up**, choose your role (**Adopter** or **Shelter Manager**), enter a test email, and choose a password.
   * **Convenience Bypass**: Accounts are automatically verified on registration for judge convenience. You can log in immediately with your credentials!
2. **Kizuna AI: Floating Advisor (Global Access)**:
   * Click the pulsing cat-eared chat button in the bottom right.
   * Type a question (e.g. *"How can I help my shy cat settle in?"*).
   * Click **Speak** to hear natural speech synthesis. Click **Pause**, **Play**, or **Stop** to manage the audio.
   * Click the mic icon to test **Speech-to-Text transcription** (requires microphone permissions).
   * Click the menu icon (`☰`) to open the **Past Conversations Sidebar** to save, swap, or delete chat logs.
3. **Feline Personality Match Test**:
   * Go to **Match Test** (or `/questionnaire`).
   * Complete the lifestyle questions and submit.
   * Review your compatibility matching scores and see your recommended shelter companions.
4. **Behavior Intelligence Diagnostics**:
   * Go to **AI Behavior Hub** (or `/behaviour`).
   * Click **Use Camera** to capture an image using your webcam (handled securely via WebRTC with standard fallbacks), or drag-and-drop a video file.
   * Run the analysis to get instant motion diagnostics, contour logs, and care suggestions.

---

## Part 2: 5-to-10 Minute Video Demo Narration Script

Use this screen walkthrough and script to record your demonstration video. 

### Video Outline & Storyboard

| Chapter | Time | Action on Screen | Narration Script (What to say) |
| :--- | :--- | :--- | :--- |
| **1. Hook & Intro** | 0:00 - 1:00 | Start on the homepage. Highlight the fixed cat-heart parallax watermark and the clean linen dark/light mode toggles. | *"Hello judges! Welcome to Purrfect Match AI—a platform designed to look like a premium cat adoption system, but designed under the hood by felines to optimize and train human caretakers. Our project stands for World Cat Domination Day. We match humans and cats not on appearance, but on behavioral personality, and support them throughout their entire lifecycle."* |
| **2. Adopter Match Test** | 1:00 - 2:30 | Go to **Match Test** / `/questionnaire`. Fill out the lifestyle survey (house size, work hours, noise tolerance). Click submit and review the matches. | *"Let’s start with the matching engine. Standard adoption relies on looks. Here, a pre-adoption compatibility test matches your daily routine and housing space with a cat's energy and social needs. As you see, we get a breakdown of compatibility scores and a list of our best feline matches. Clicking into a cat profile lets us apply for adoption instantly."* |
| **3. AI Advisor & TTS** | 2:30 - 4:30 | Open the floating chatbot. Ask a behavior question. Play/Pause/Mute the TTS voice reply. Open the Sidebar menu. | *"Next, we have the Kizuna AI Advisor. It features real-time speech recognition showing your voice transcription as you speak. When the AI replies, it leverages speech synthesis. Let's listen... [Play a brief clip]. We have built inline Play, Pause, Resume, and Stop controls to manage the speech queue. We also have a ChatGPT-style sidebar where you can manage separate chat logs, start new chats, and delete past conversations."* |
| **4. AI Behavior Hub & WebRTC** | 4:30 - 6:00 | Go to **AI Behavior Hub**. Click **Use Camera**, show webcam stream, click **Snap Photo**. Run diagnostics. | *"For post-adoption support, the AI Behavior Hub decodes your cat's mood. We built a custom WebRTC camera module that works on any laptop or phone. I'll take a quick picture... and run the analysis. The backend OpenCV computer vision engine processes contours and behavior metrics to deliver instant visual feedback and care tips."* |
| **5. Shelter Dashboard** | 6:00 - 7:00 | Log out. Log in as a **Shelter Manager**. Show the cat registration forms and list of placed adopters. | *"Finally, for the community, we have a Shelter Directory and a Manager Dashboard. Shelter staff can register new cats, specify behavioral scores, and track placed adopters to ensure every household is managed perfectly."* |
| **6. Summary & Tech Stack** | 7:00 - 8:00 | Open the Swagger Docs or the GitHub repo files page. | *"Purrfect Match AI is built on Next.js, FastAPI, SQLite, Supabase PostgreSQL, and OpenCV. We engineered zero-config fallback runtimes so judges can run it locally with ease. Thank you for your time, and let's help cats rule the world!"* |

---

### Tips for Recording:
* **No Copyright Music**: Do not add background music unless it is fully royalty-free. Let your voice speak clearly!
* **High Contrast**: Toggle between Light Mode and Dark Mode during the intro to show off the dynamic contrast logo swaps.
