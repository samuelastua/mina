
```
mina/
├── voice/                  # Voice interaction (STT, TTS, wake word)
│   ├── stt/                # Speech-to-text (Whisper.cpp)
│   ├── tts/                # Text-to-speech (Piper)
│   └── wake_word/          # Wake word detection (Porcupine)
├── neural/                 # Neural intelligence (LLM, NLP)
│   ├── llm/                # Local LLM (Mistral, Llama)
│   ├── intent/             # Intent classification (spaCy)
│   └── memory/             # Conversation history (SQLite)
├── system/                 # System automation
│   ├── file_manager/       # File operations
│   ├── process/            # App control
│   └── home_auto/          # IoT integration
├── security/               # Privacy and security
│   ├── sanitization/       # Input sanitization
│   └── encryption/         # Data encryption (SQLCipher)
└── main.py                 # Entry point

```
