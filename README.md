# StreamAvatar — Live2D AI Companion (web frontend)

Thin browser frontend for a Live2D desktop AI companion. The page loads a Live2D
model and connects over WebSocket to a backend (LLM + TTS + behavior system) that
runs separately. Open the GitHub Pages link; the backend host is configured in
`index.html` (or override with `?backend=<host>`).
