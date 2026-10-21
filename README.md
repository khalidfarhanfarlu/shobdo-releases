# Shobdo (শব্দ)

Free Bangla and English dictation for Mac and Windows, by [Khalid Farhan](https://khalidfarhan.com).

Hold **Right Command** and speak Bangla, or hold **Fn** and speak English. Let go, and the text appears wherever you are typing.

**Download and instructions: [khalidfarhan.com/shobdo](https://khalidfarhan.com/shobdo)**

This repository only hosts the installers, the update feed and the offline speech models. It contains no source code.

## Credits and licences

- Shobdo is built on [Handy](https://github.com/cjpais/Handy) by CJ Pais, released under the MIT License. Handy's licence notice is reproduced below.
- The offline Bangla model is the Bengali.AI speech recognition model by tugstugi ([bengaliAI/tugstugi_bengaliai-asr_whisper-medium](https://huggingface.co/bengaliAI/tugstugi_bengaliai-asr_whisper-medium)), a fine-tune of OpenAI Whisper Medium, released under the Apache License 2.0. It is redistributed here converted to GGUF format and quantised to 8 bits; the weights are otherwise unchanged.
- The offline English model is NVIDIA Parakeet TDT 0.6B v2 (CC BY 4.0), downloaded from its public source on first use.

### Handy licence

```
MIT License

Copyright (c) 2025 CJ Pais

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
