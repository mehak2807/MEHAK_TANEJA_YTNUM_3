# MEHAK_TANEJA_YTNUM_3
# AI-Organized Comment Layer with Real-Time Video Context
Made by:Mehak Taneja


Reimagining YouTube’s comment section for clarity, inclusivity, and real-time relevance.
USER SIDE DESIGN LINK: https://www.figma.com/proto/laoy313K8NxGkmtxNymHKC/USER_VIEW?node-id=0-1&t=sUhVbg5pWMWyP85y-1
CREATOR SIDE DESIGN LINK:  https://www.figma.com/proto/kYMMDwEEgStU0wb2fsM3i3/CREATOR_VIEW?node-id=1-2&t=GtvYDERftMkxiMjN-1

## Problem Statement (Prompt 3)

**Goal:** Redesign YouTube’s comment section to dynamically reorganize in real-time based on what the viewer is currently watching — making it more readable, context-aware, and engaging.

---

## Key Features for User

### 1. Smart Timestamped Comments

- Comments are automatically categorized by video timestamps.
- Smart comment sorting based on relevance, likes, and video context.
- Comments related to specific timestamps appear in a focused section when the video reaches that moment.

### 2. Emotion Bar Over Timeline

- Sentiment analysis is used to generate an emotion-based bar over the video timeline (e.g., happy, sad, excited).
- Viewers can visually scan emotional highlights and reactions without pausing the video.

### 3. Real-Time Translated Comments

- Top-rated or relevant comments are auto-translated into the user's preferred language.
- Displayed in real time with smooth pop-ups to ensure inclusivity for a global audience.

### 4. Audio Comment Mode (For Visually Impaired)

- Enables an accessibility mode where the video pauses and comments are read aloud.
- Supports blind users or those with visual impairments.
- Toggle option to turn this feature on or off at any point.

### 5. Live Reaction Layer

- Allows influencers or creators to add a transparent commentary layer that plays alongside the main video.
- Creators can collaborate with others to offer multi-perspective reactions on the same video content.

### 6. Expandable Floating Comments

- Floating comments are synced to specific moments.
- Tapping on a floating comment expands the thread for replies and discussions, all time-linked.

### 7. AI Summary and Poll Integration

- AI-generated summaries highlight key discussion points at different timestamps.
- Creators can insert interactive polls tied to specific moments, allowing viewers to vote once they reach that point in the video.

### 8. Monetized Comments

- Introduces comment monetization for specific timestamps (similar to SuperChat).
- Viewers can pin paid comments at key moments, supporting creators and enhancing community engagement.

---



## Key Features for Creator

### 1. Pin Favorite Comments

- Creators can **pin favorite fan comments** to specific timestamps.
- Highlights standout feedback or responses directly in sync with video content.

### 2. AI Feedback Summarization

- AI auto-generates **summary insights** from top feedback across various video points.
- Helps creators quickly understand viewer sentiment and engagement without manually reading hundreds of comments.

### 3. Toxic Comment Moderation

- Sentiment filtering enables **automatic flagging and moderation** of toxic or inappropriate comments.
- Ensures a safer and more constructive discussion environment.

### 4. Comment Timing Insights

- Dashboard shows **when viewers are most likely to comment** during a video.
- Creators can use this to identify high-engagement moments and plan future content more strategically.

### 5. Emotional Reaction Trends

- AI tracks **emotional reactions** (e.g., excitement, sadness, confusion) throughout the video timeline.
- Data is visualized in a **sentiment wheel** showing crowd mood at any given timestamp.

### 6. Creator Questions at Timestamps

- Creators can insert questions at specific video times such as:
  - “What do you think will happen next?” at 4:00
- Viewers respond or vote in real-time, increasing interactivity and retention.

### 7. Monetizable Comment Shoutouts

- Viewers can **sponsor pinned comments** at specific timestamps (similar to Super Chats, but time-linked).
- Great for fans, brands, and creators:
  - Brands can highlight fan comments during key promo scenes.
  - Fans can pay to leave a top-level visible comment at a certain video moment.

---

## How It Works

1. **Sentiment Analysis:**
   - Each comment is analyzed using classification models (Positive, Negative, Neutral, Emotional, Funny).
   - Sentiment tags are stored in the backend, invisible to viewers.

2. **Time-Synced Filtering:**
   - Only the comments relevant to the current viewing timestamp (±5 seconds) are shown to the user.
   - Ensures focused and context-aware interaction.

3. **Sentiment Wheel Visualization:**
   - A circular timeline at the bottom shows the **dominant emotional tone** of viewers across the video.
   - Helps creators and viewers understand how different parts of the video resonated with the audience.

---
## Tech Stack & Implementation

**Frontend:** React.js with Tailwind CSS for dynamic, responsive UI. HTML5 video API used for overlays, emotion bars, and synced comments.

**Backend:** Node.js with Express, MongoDB for storing comments, polls, translations, and user data. Socket.io enables real-time updates.

**AI/ML:** Python-based sentiment analysis, comment summarization (BERT/GPT), translation (Google Translate API), and toxicity detection.

**Creator Dashboard:** Aggregates viewer data using lightweight analytics pipelines. Polls, monetized comments, and emotion tracking linked to video timestamps.

---

## Future Goals

- YouTube Studio integration for direct access to insights  
- Offline and low-bandwidth comment support  
- AI-based suggestions to improve creator content  
- Voice/emoji-based reactions and enhanced accessibility tools  
- Blockchain for monetized comment transparency and ownership  

---

**Thank you for exploring this project!**

