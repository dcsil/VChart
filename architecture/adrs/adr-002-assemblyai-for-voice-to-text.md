## ADR 002: AssemblyAI for Voice-to-Text

## Context
We plan to develop a web application that automatically generates structured medical charts from voice recordings. To achieve this, we require a real-time speech-to-text transcription service that supports medical terminology and offers high accuracy.

Several mainstream transcription services are available, including AssemblyAI, Google Speech-to-Text, Whisper, Rev AI, and Deepgram.

Among these options, Google Speech-to-Text and Rev AI have been reported to suffer from either slow speeds or inefficiencies. Deepgram is noted for its speed but does not necessarily offer the highest accuracy. In contrast, AssemblyAI has been reported to provide the best accuracy among all options.

### Options
AssemblyAI, Google Speech-to-Text, Whisper, Rev AI, Deepgram

## Decision
We will use AssemblyAI as our speech-to-text API.

## Status
Accepted.

## Consequences
AssemblyAI offers the distinct advantage of being the most accurate transcription model among the available options. Given the critical importance of accurate transcription in the medical domain, it appears to be the best choice. However, we will need to conduct further testing to determine whether its speed meets our real-time processing requirements.