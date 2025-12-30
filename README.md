# audio-fc-annotation
Audio-based evaluation of LLM function calling behavior with structured QA methodology

## Project Overview
Evaluate AI assistant function calls triggered by voice input.
Record 4–8.5 minutes of conversation and verify if the model calls the right functions.

## Goals
- Verify function calls are correct and timely
- Track audio issues (clipping, cutoff, interruptions)
- Ensure up to 12 function calls per session
- Provide detailed QA logs

## Repo Structure
- `preparation/` → Conversation plans, function call definitions, trigger phrases
- `labeling/` → Logs for function calls, model issues, Q14 notes
- `audio_guidelines/` → Definitions and references for audio issues
- `samples/` → Example transcripts

