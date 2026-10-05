# audio-transcription

Mirror of the **NVIDIA Parakeet TDT 0.6B v3** speech-to-text model (Q8_0 GGUF), so it can be downloaded without Hugging Face access.

## Download the model

From the [Releases page](../../releases/tag/model-v1), or:

```bash
mkdir -p models
curl -L -o models/parakeet-tdt-0.6b-v3.q8_0.gguf \
  https://github.com/alidotabedi/audio-transcription/releases/download/model-v1/parakeet-tdt-0.6b-v3.q8_0.gguf
```

Or with the GitHub CLI: `gh release download model-v1 -R alidotabedi/audio-transcription -D models`

| File | Size | SHA-256 |
|---|---|---|
| `parakeet-tdt-0.6b-v3.q8_0.gguf` | 714 MB | `e3880d0aaaaf2c308ea2c35016b2b895c423eb3fda924c1b463d1c19b7f4d32e` |

Verify: `sha256sum models/parakeet-tdt-0.6b-v3.q8_0.gguf`

## Source & license

Original: [nvidia/parakeet-tdt-0.6b-v3](https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3) by NVIDIA, licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/). Redistributed unmodified.
