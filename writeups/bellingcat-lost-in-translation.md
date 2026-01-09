# Bellingcat Challenge: Lost in Translation

**Date Completed:** January 2025  
**Difficulty:** Easy  
**Source:** https://challenge.bellingcat.com/

## Challenge Description

Audio file provided with voices speaking in a language I do not speak. Task was to identify the speakers and locate the source video.

## Methodology

### Initial Analysis

First listen revealed two male voices speaking Russian. One voice had distinctive characteristics that immediately suggested a high-profile Russian speaker - vocal patterns, cadence, and tone were familiar from news coverage.

**Initial hypothesis:** One speaker is Vladimir Putin based on voice recognition.

### Investigation Steps

1. **Step 1: Voice Verification**
   - What I did: Searched for recent Putin video content on YouTube
   - Method: Played video with eyes closed to focus purely on voice characteristics (removes visual bias)
   - What I found: Voice patterns matched the first speaker in the challenge audio
   - Why this mattered: Confirmed initial hypothesis about Putin's presence, narrowed timeframe to recent content

2. **Step 2: AI-Assisted Audio Analysis**
   - What I did: Uploaded audio file to Google Gemini with prompt: "I think one of the voices on this is Putin and in Russian - can you check that for me?"
   - What I found: Gemini confirmed Putin's voice and identified the second speaker as Kim Jong Un
   - Why this mattered: AI transcription/translation capabilities provided rapid language analysis without needing Russian fluency; identified both speakers

3. **Step 3: Event Correlation**
   - What I did: Searched for Putin-Kim meetings/summits
   - What I found: Located recent diplomatic meeting between the two leaders
   - Why this mattered: High-profile meetings between these leaders are well-documented, making source video easy to locate

4. **Step 4: Source Video Location**
   - What I did: Searched for video footage from the identified meeting
   - What I found: Located original source video matching the audio clip
   - Why this mattered: Completed chain of verification from audio → speakers → event → source

## Tools Used

- **YouTube** - Reference material for voice comparison
- **Google Gemini** - Audio transcription, translation, and speaker identification
- **Search engines** - Event correlation and source video location

## Key Findings

Audio featured Vladimir Putin and Kim Jong Un from a recent diplomatic meeting. The combination of voice recognition, AI-assisted analysis, and event correlation provided multiple verification points.

## Answer

Speakers: Vladimir Putin and Kim Jong Un  
Source: [Specific meeting/event and video source]

## Lessons Learned

- **Voice analysis technique**: Closing eyes during comparison removes visual bias and sharpens audio focus
- **AI as verification tool**: LLMs with multimodal capabilities (audio + context) can rapidly verify hypotheses, especially for language barriers
- **High-profile subjects advantage**: Well-documented public figures have abundant reference material, making verification easier
- **Layered verification**: Multiple independent verification methods (human voice recognition + AI analysis + event correlation) provide confidence in findings

## Technical Notes

Gemini's audio analysis capabilities handled both transcription and speaker identification in a single query. This is particularly valuable for OSINT work involving languages you don't speak - the AI can provide translation context while you focus on analytical reasoning and correlation.

For future audio investigations: consider building a reference library of voice samples for commonly encountered public figures, similar to how visual OSINT practitioners maintain geolocation reference materials.
