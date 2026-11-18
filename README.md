# VOSKA

VOSKA is my personal AI assistant, built in Python. The current prototype runs from the terminal, listens through a microphone, and speaks its replies out loud. I'm building it one feature at a time, with the goal of making it the voice of my VOSKA robot.

## What works today

- Records audio from a microphone.
- Processes spoken input and generates a response.
- Reads responses aloud using text-to-speech.
- Supports a spoken shutdown command.

## Run the prototype

On macOS, open Terminal in the project folder. Activate your Python virtual environment and run the assistant. If your environment folder is named `venv` instead of `.venv`, use `source venv/bin/activate` in the first line.

```bash
source .venv/bin/activate
python main.py
```

Use the project's existing dependency and API configuration. Keep API keys out of Git. When the assistant is ready, ask a simple question and check that you hear a spoken reply.

## Roadmap

- [ ] Add image input so VOSKA can answer questions about what it sees.
- [ ] Add automation for everyday tasks.
- [ ] Build a mobile interface.
- [ ] Connect the voice assistant to the VOSKA desktop robot head.

## Author

Jeremy Johnson