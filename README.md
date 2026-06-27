# syntts

SOTA Hinglish (89M parameters) code-switching text-to-speech that runs **entirely in your browser**
on WebGPU. No server, no upload; your text never leaves the device.

Live: https://harrrshall.github.io/syntts/

- One-time ~396 MB model download (from the Hugging Face Hub), cached after first visit.
- 4 fixed voices; type romanized Hinglish ("yaar kal ka match dekha") or Devanagari, it auto-converts
  Hindi to Devanagari and keeps English in Roman for correct pronunciation.
- Bit-exact to the reference PyTorch model (verified). Weights: https://huggingface.co/harrrshall/syntts-webgpu
