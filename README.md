# AI Voice API: TTS + STT Comparison (12 providers)

ElevenLabs, OpenAI TTS, Google Cloud TTS, Azure Speech, AWS Polly, etc. Voice quality, latency, price.

## What we tested

12 voice APIs (ElevenLabs, OpenAI TTS, Google Cloud TTS, Azure Speech, AWS Polly, etc.). 50 audio samples for TTS, 100 audio files for STT.

## TTS quality

Naturalness (MOS), pronunciation accuracy, latency p50/p99.

## STT accuracy

Word error rate on 5 languages (English, Mandarin, Spanish, French, Arabic).

## Real-time vs batch

Sub-300ms latency for conversational vs batch for offline transcription.

## Code

Per-provider client in `clients/`. Unified STT and TTS abstractions.

## Network

apiguider.com covers the AI API market. See [apex.apiguider.com](https://apex.apiguider.com) for editorial.

---

Part of the apiguider.com network:
- Apex (editorial home): https://apex.apiguider.com
- All 22 stations: https://apex.apiguider.com/22-stations/
- Editorial standards: https://apex.apiguider.com/editorial-standards/

**Author**: apiguider.com editorial team (see apex.apiguider.com/about/)

Topics: ai-api, tts, stt, voice, speech