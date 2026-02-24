# Google Veo 3.1 Video Generation

This skill allows the agent to generate short video clips (up to 6-10 seconds) using the Google Veo 3.1 model via the Gemini/Vertex AI API.

## Setup
1. Ensure `GEMINI_API_KEY` is set in `.env`.
2. Run `npm install googleapis` (if not already installed).

## Usage
- `veo_generate(prompt, options)`: Generates a video from a text prompt.
- `veo_animate(imagePath, prompt)`: Animates a static image.

Example:
```bash
node skills/veo-gen/generate.js "A pink axolotl assistant working at a futuristic wooden desk" --out vulkimini-work.mp4
```
