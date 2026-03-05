notesAI 📝
A beautiful, AI-powered note-taking web app built with React. Write notes, dictate with your voice, and generate smart todo lists — all powered by the Gemini AI API / Anthropic API.
<img width="918" height="1498" alt="image" src="https://github.com/user-attachments/assets/3906a419-6eb8-4439-bdbb-fae93088c15b" />


**Features**
**Notes**

Create, edit, and organize rich text notes
Full formatting toolbar — bold, italic, underline, strikethrough, headings, lists, blockquotes, code blocks, colors, highlights, and more
Smart color-coded banners that auto-change based on your note's topic (food, travel, work, fitness, etc.)
Organize notes into folders: Work, Personal, Ideas
Tag notes with labels like #work, #urgent, #health, and more
Mark notes as favorites
Trash and restore notes
Search across all notes instantly

**NTVoice AI**

Tap the mic and speak your topic — AI writes a full structured note for you
Or type a topic and let AI generate the note

<img width="918" height="1612" alt="image" src="https://github.com/user-attachments/assets/203f9a12-2a76-4f2a-9440-56c4d4bff27b" />

**AI Todo Lists**

Say or type what you need (e.g. "make an omelette") — AI generates a complete checklist
For recipes: lists all ingredients with quantities
For shopping: lists all items
For projects: lists all tasks and steps
Add items to an existing list or create a new one
Check off items, delete, and organize multiple lists
<img width="916" height="1556" alt="image" src="https://github.com/user-attachments/assets/e91990ca-be7b-4e0e-af25-041e7cb9e544" />


**Auth & Persistence**

Sign up and log in with email and password
All notes and todos are saved persistently across sessions
Session is remembered so you stay logged in


**Tech Stack**

LayerTechnologyUI FrameworkReact 18 (via Claude.ai artifact runner)StylingPlain CSS-in-JS (no Tailwind, no libraries)FontsGoogle Fonts — Lora + DM SansAIGoogle Gemini 2.0 Flash APIStorageClaude.ai artifact persistent storage (key-value)Rich TextcontentEditable + document.execCommandVoiceWeb Speech Recognition API (browser built-in)

