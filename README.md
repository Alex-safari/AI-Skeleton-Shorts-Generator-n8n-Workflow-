# AI-Skeleton-Shorts-Generator-n8n-Workflow-
Turn a single idea into a fully generated viral skeleton short — automatically.

This workflow uses AI scripting, AI voice generation, AI image generation, and AI video animation to produce the core assets for viral educational shorts like:
* What happens if you don’t sleep?
* What happens if you drink too much water?
* What happens if you run every day?

The system automatically generates the script, skeleton visuals, animation clips, and voiceover, then organizes everything in Google Drive so you can assemble the final video in minutes.

Perfect for creators building YouTube Shorts, TikTok channels, or faceless content brands.

## ⚙️ What This Workflow Does

This automation converts one simple idea into a full 6-scene skeleton short video system.

Here’s what happens step-by-step.

### 1. Idea Submission Form
You submit a single idea such as:
> “What happens if you stay awake for 72 hours?”

This triggers the entire automation.

### 2. AI Script Generation (Gemini 2.5 Pro)
The system automatically generates:
* A 6-scene viral script
* Structured prompts for each scene
* Animation instructions
* Voice-over narration text

The output is structured so every scene contains:
* Image prompt
* Animation prompt
* Voiceover text
* Generation type

### 3. Scene Database (Google Sheets)
Every generated scene is stored in a Scenes database that tracks:
* Prompt text
* Animation instructions
* voiceover text
* generation status
* image URLs
* video URLs
* Google Drive asset links

This acts as the production control panel for the system.

### 4. Skeleton Image Generation (Nano Banana Pro)
The workflow generates a cinematic 3D skeleton image for every scene using the Kie.ai image API.

Features:
* 9:16 vertical format
* 2K image resolution
* consistent skeleton character style
* frame-to-frame continuity when required

Images are then automatically:
* downloaded
* uploaded to Google Drive
* logged inside Google Sheets

### 5. AI Voice Generation (ElevenLabs)
Each scene’s narration is converted into voice using ElevenLabs AI voice synthesis.

The workflow:
* Sends the voice text to ElevenLabs
* polls the generation queue
* retrieves the final audio file
* uploads the MP3 to Google Drive
* logs the file link in the database

### 6. AI Video Generation (Kling Image-to-Video)
The workflow converts skeleton images into animated video clips using image-to-video AI.

Each clip includes:
* skeleton character motion
* cinematic camera movement
* atmospheric animation

Clips are automatically:
* downloaded
* uploaded to Google Drive
* tracked in the scene database

### 7. Organized Output
At the end of the workflow you get:
* 6 video clips
* 6 voiceover audio files
* 6 skeleton scene images

All organized in Google Drive and linked inside Google Sheets.

You can then combine everything in CapCut, Premiere, or any video editor to create the final short.

## 🧠 Tech Stack
n8n • Gemini 2.5 Pro • ElevenLabs • Kie.ai • Kling Image-to-Video • Google Sheets • Google Drive

## 📦 What’s Included
When you download this template you’ll get:
✅ Full n8n workflow JSON file
✅ Skeleton video generation pipeline
✅ Gemini scripting prompt system
✅ ElevenLabs voice automation
✅ Image generation automation
✅ Video generation automation
✅ Google Sheets scene database structure

## 💡 Use Cases
This system is perfect for:
* YouTube Shorts automation channels
* TikTok educational content
* faceless content brands
* viral science / health content
* content agencies producing Shorts at scale

## 👨‍💻 Created By
**Alex Safari** — Founder of Loopsera.
I build AI automation systems that generate content, automate workflows, and help creators scale production with AI.

Watch the full tutorial on YouTube: https://www.youtube.com/watch?v=B7BFQkQTPE0

📧 **Contact me:** contact@loopsera.com
Email me directly with questions or custom requests.

🌐 **Website:** https://loopsera.com
Explore more automation templates and services.

📞 **Book a Discovery Call:**
https://cal.com/loopsera/ai-opportunity-audit
For businesses that need a custom AI automation build.

🎓 **1-on-1 Coaching Session:**
https://cal.com/loopsera/ai-coaching-session
Personalized coaching to help you build, troubleshoot, or optimize n8n AI workflows.
Suitable for beginners and advanced users — includes live guidance and actionable tips.
