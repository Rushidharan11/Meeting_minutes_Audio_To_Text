# Meeting minutes (Audio to text)

This project transcribes audio recordings and generates structured meeting minutes automatically.

The project utilizes Hugging Face pipelines with the Whisper model for open-source speech-to-text transcription, along with OpenAI’s GPT-4o mini transcription model as an alternative for higher accuracy.

For summarization and structuring, the project uses the LLaMA 3.2 model to convert raw transcriptions into clear, organized meeting minutes using prompt-based instructions.

The implementation demonstrates an end-to-end LLM pipeline combining speech recognition, prompt engineering, and text generation for real-world productivity use cases.
