# Content Repurposer AI 🎬🔁

**An AI system that transforms long-form content into ready-to-publish short-form assets.**

Content Repurposer AI identifies highlight moments from podcasts or YouTube videos, then generates short-form clips, titles, captions, and thumbnail prompts — helping creators stay consistent without starting from scratch every week.

## Problem:
Long-form content wasn’t being effectively leveraged into short-form clips that matched the brand tone and storytelling style.

## Solution:
Designed an AI system that ingests full episodes, identifies story-driven highlights, and drafts platform-specific titles, captions, and hooks — ready for reels or TikToks.

## Results:
- Higher-quality, more on-brand short content
- Reduced reliance on generic AI clipping tools (e.g., OpusClip)
- Lays foundation for future automation of publishing pipelines

---

## ✨ Features

- 🎯 **Highlight Detection:** Uses AI to identify emotionally engaging or informative segments.
- ✍️ **Auto-Generated Captions & Hooks:** Drafts compelling video hooks and captions for Reels, Shorts, or TikToks.
- 🧠 **Title Suggestions:** Provides 3–5 title options based on clip themes and platform best practices.
- 🎨 **Thumbnail Prompt Ideas:** Outputs suggested facial expressions, key phrases, and style direction for thumbnails.
- 🧾 **Exportable Content Pack:** Outputs content in structured markdown or JSON format, ready for QA and scheduling.

---

## 🔧 Tools & Stack

- **GPT-4** — core logic and prompt chaining
- **NotebookLM** — long-form episode research
- **Google Sheets** — structured data handoff + QA
- **Notion** — reference docs and team approvals
- **n8n** (in progress) — automation layer for inputs, outputs, and notifications

---

## ⚙️ Workflow

1. Upload episode transcript via YouTube or Frame.io.
2. GPT parses the transcript and suggests 3–6 highlight-worthy moments.
3. For each clip, the system generates:
   - Clip title options
   - Hook-style caption drafts
   - Thumbnail visual prompts
   - Optional call-to-action language
4. All assets are reviewed in Google Sheets or Notion before scheduling.

---

## 📦 Status

Currently in real-world use with weekly podcast content. Iterating on prompt logic to improve emotional hook accuracy and clip pacing. n8n automation will be added to streamline ingestion and QA workflows.

---

## 🧠 Creator Notes

This system was designed to **augment a lean creative team**. It reduces the burden of weekly content slicing while keeping the voice and style on-brand. It is not fully automated — a human-in-the-loop always reviews and refines the final cuts.
