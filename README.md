# awesome-speech-generation-corpus

Each entry distinguishes real-recorded audio, synthetic speech, annotation-only resources, reconstruction manifests, and evaluation benchmarks. Reported scale follows the original authors; access conditions and source-data terms may vary by subset.

## Datasets

- openslr.org [[`https://openslr.org/resources.php`](https://openslr.org/resources.php)].
- emotion-tts-dataset [[`https://github.com/skit-ai/emotion-tts-dataset`](https://github.com/skit-ai/emotion-tts-dataset)].
- Kokoro-speech [[`https://github.com/kaiidams/Kokoro-Speech-Dataset`](https://github.com/kaiidams/Kokoro-Speech-Dataset)].
- Portuguese [[`https://github.com/Edresson/TTS-Portuguese-Corpus`](https://github.com/Edresson/TTS-Portuguese-Corpus)].
- libriSpeech [[`https://www.openslr.org/12/`](https://www.openslr.org/12/)].
- Genshin_Datasets [[`https://github.com/AI-Hobbyist/Genshin_Datasets`](https://github.com/AI-Hobbyist/Genshin_Datasets)].
- Mozilla datasets [[`https://commonvoice.mozilla.org/zh-CN`](https://commonvoice.mozilla.org/zh-CN)].
- StarRail datasets [[`https://github.com/AI-Hobbyist/StarRail_Datasets`](https://github.com/AI-Hobbyist/StarRail_Datasets)].
- Emilia / Emilia-Large [[`Dataset`](https://huggingface.co/datasets/amphion/Emilia-Dataset)]. Multilingual in-the-wild speech for speech generation. Emilia-Large combines the original 101K-hour Emilia corpus with the 114K-hour Emilia-YODAS corpus. Emilia uses CC BY-NC 4.0, while Emilia-YODAS uses CC BY 4.0.
### Large-scale Multilingual Speech

- YODAS v3 [[`Dataset`](https://huggingface.co/datasets/espnet/yodas3)]. Over 1.1 million hours of web-crawled audio across 100+ languages, with transcripts, timestamps, and translations where available. Approximately 75% of the audio has transcripts; further filtering and segmentation are needed for TTS.
- LEMAS [[`Dataset`](https://huggingface.co/datasets/LEMAS-Project/LEMAS-Dataset-train)] [[`Paper`](https://arxiv.org/abs/2601.04233)]. A 150K+ hour multilingual speech corpus covering 10 languages, with word-level alignments, supporting multilingual TTS and speech editing research.

### Mandarin and Chinese Dialect Speech

- WenetSpeech4TTS [[`Project & download`](https://wenetspeech4tts.github.io/wenetspeech4tts/)]. A 12,800-hour Mandarin audio-text corpus specifically refined for TTS, with quality-graded subsets.
- WenetSpeech-Wu [[`Project & data`](https://github.com/ASLP-lab/WenetSpeech-Wu-Repo)]. Approximately 8,000 hours of Wu dialect speech covering eight sub-dialects, with multi-dimensional annotations and benchmarks for TTS and instruction-following TTS.
- WenetSpeech-Min [[`Project & data`](https://github.com/ASLP-lab/WenetSpeech-Min-Repo)]. Approximately 10,000 hours of Minnan speech with paired Minnan and Mandarin transcripts, together with ASR and Minnan TTS benchmarks.

### Expressive, Instruction-conditioned and Non-verbal Speech

- Emilia-NV [[`Dataset`](https://huggingface.co/datasets/amphion/Emilia-NV)] [[`Code`](https://github.com/AmphionTeam/Emilia-NV)]. Mandarin speech with word-level annotations for lexical content and 18 types of paralinguistic vocalizations, including laughter, breathing, and interjections.
- SpeechCraft [[`Project & data`](https://github.com/thuhcsi/SpeechCraft)]. A bilingual expressive speech resource with natural-language descriptions, instructions, and fine-grained attributes. Source speech corpora and annotation downloads are documented separately.
- EARS [[`Project & download`](https://github.com/facebookresearch/ears_dataset)]. Expressive Anechoic Recordings of Speech, covering diverse speaking styles and vocal behaviors, including whispering and yelling.

### English TTS

- LibriTTS-R [[`Download link`](https://www.openslr.org/141/)]. A sound-quality-restored version of the approximately 585-hour LibriTTS corpus, designed for multi-speaker English TTS. It shares the same constituent samples as LibriTTS.

### Audio Captioning and Text-to-Audio Resources

- ACAVCaps [[`Project & annotations`](https://github.com/xiaomi-research/acavcaps)]. Approximately 4.7 million audio-caption pairs covering speech, music, sound events, and their mixtures. Primarily designed for audio understanding; captions and metadata are released, while source audio must be obtained separately.
- WavCaps [[`Dataset`](https://huggingface.co/datasets/cvssp/WavCaps)] [[`Code`](https://github.com/XinhaoMei/WavCaps)]. Approximately 400K audio clips with machine-assisted captions, useful for audio-language research and text-conditioned audio generation. Source-specific usage terms apply.
- AudioCaps [[`Project & data`](https://audiocaps.github.io/)]. AudioSet-derived audio clips with human-written captions, useful for audio captioning and text-to-audio research.
- Clotho v2.1 [[`Download link`](https://zenodo.org/records/4783391)]. An audio captioning dataset containing 6,974 audio samples, each paired with five human-written captions.

### Paralinguistic and Non-verbal Speech

- SMIIP-NV [[`Dataset`](https://huggingface.co/datasets/xunyi/SMIIP-NV)] [[`Project`](https://axunyii.github.io/SMIIP-NV/)]. Approximately 33 hours of expressive speech with five emotion categories, three non-verbal sound categories (laughter, crying, and coughing), and event-level timestamps.
- NonVerbalSpeech-38K (NVS-38K) [[`Dataset`](https://huggingface.co/datasets/nonverbalspeech/nonverbalspeech38k)] [[`Project`](https://nonverbalspeech38k.github.io/nonverspeech38k/)]. A Chinese-English corpus containing 38,718 samples / approximately 131 hours from real-world media, with automatic annotations for 10 non-verbal categories. Supports both non-verbal speech generation and understanding.
- SynParaSpeech [[`Dataset`](https://huggingface.co/datasets/shawnpi/SynParaSpeech)] [[`Paper`](https://arxiv.org/abs/2509.14946)]. A synthetic paralinguistic speech dataset containing approximately 118.75 hours across six categories: sigh, throat clearing, laugh, pause, tsk, and gasp, with fine-grained temporal annotations.

### Style-captioned and Instruction-controlled Speech

- ParaSpeechCaps [[`Dataset`](https://huggingface.co/datasets/ajd12342/paraspeechcaps)] [[`Code`](https://github.com/ajd12342/paraspeechcaps)]. Speech with natural-language style captions and 59 style tags covering speaker-level and utterance-level characteristics, including pitch, rhythm, and emotion. Contains human-annotated Base and automatically annotated Scaled subsets.
- CapSpeech [[`Project & data instructions`](https://github.com/WangHelin1997/CapSpeech)]. A collection of datasets and benchmarks for style-captioned TTS, covering emotion, accent, sound events, and chat-agent speech. Includes machine-annotated and human-annotated resources organized by task.
- UltraVoice [[`Dataset`](https://huggingface.co/datasets/tutu0604/UltraVoice)] [[`Code`](https://github.com/bigai-nlco/UltraVoice)]. Approximately 833 hours of synthetic spoken dialogue with instructions for emotion, speed, volume, accent, language, and composite style control. Suitable for controllable speech generation and spoken-dialogue instruction tuning.

### Natural Conversational and Full-duplex Speech

- otoSpeech Full-Duplex 280h [[`Dataset`](https://huggingface.co/datasets/otoearth/otoSpeech-full-duplex-280h)]. Approximately 280 hours of real English spontaneous conversation, recorded as 48 kHz stereo audio with one speaker per channel. Access requires approval.
- Basis Conversations 1500 [[`Dataset`](https://huggingface.co/datasets/basis-ai/basis-conversations-1500)]. Approximately 1,502 hours of real multilingual, multi-party full-duplex conversation across 22 languages, with separate 48 kHz speaker tracks. Approximately 100 hours include human annotations for interactional behaviors. Access is gated under a custom data license.
- DuplexChat [[`Manifests`](https://huggingface.co/datasets/sarulab-speech/DuplexChat)] [[`Paper`](https://arxiv.org/abs/2607.04941)]. Large-scale English and Japanese conversational speech mined from public podcasts. The release contains reconstruction manifests, not audio; source episodes must be downloaded and speech separation/restoration rerun.
- CELSDS [[`Annotations & processing code`](https://github.com/lijin0120/CELSDS)]. A Chinese expressive long-dialogue speech resource with scripts and a data construction pipeline. Source audio needs to be obtained and reconstructed using the released resources.

### Synthetic Multi-speaker and Interactive Dialogue

- MultiTalkPT / MultiTalkFT [[`Pre-training data`](https://huggingface.co/datasets/MultiTalk/MultiTalkPT)] [[`Fine-tuning data`](https://huggingface.co/datasets/MultiTalk/MultiTalkFT)] [[`Paper`](https://arxiv.org/abs/2609.36903)]. Approximately 57.6K hours of synthetic English-Chinese full-duplex dialogue, supporting long-form and multi-party interactions with controllable overlaps, backchannels, interruptions, and turn-taking.

### Paralinguistic and Controllability Benchmarks

- SpeechParaling-Bench [[`Dataset`](https://huggingface.co/datasets/Ruohan2/SpeechParaling-Bench)] [[`Project`](https://speechparaling-bench.github.io/)]. An evaluation benchmark with over 1,000 English-Chinese parallel speech queries covering more than 100 paralinguistic features. Intended for evaluating paralinguistic-aware speech generation.
- MED-TTS [[`Text dataset`](https://huggingface.co/datasets/Chanson-0803/MED-TTS)] [[`Code`](https://github.com/Simon-leong/TED-TTS)]. A 30,000-sample English-Chinese text dataset with segment-level emotion descriptions and duration annotations for intra-utterance control. This is a text/annotation resource rather than a paired speech corpus.

### Music Generation and Understanding

- Internet Archive Music Dataset (IAMD) [[`Dataset`](https://huggingface.co/datasets/Telecom-Paris/iamd_v0)] [[`Paper`](https://arxiv.org/abs/2609.20870)]. Over 34,000 hours of music segments with machine-generated captions and source metadata. The linked release includes audio; Creative Commons licenses vary by sample.

## others
- https://huggingface.co/datasets/TTS-AGI/vocal-bursts-taxonomy-DACVAE


## TTS Frontend dataset
- https://github.com/danielwei0214/Chinese-TTS-Dataset
- https://github.com/Jackiexiao/tts-frontend-dataset

## Reference:
- https://zhuanlan.zhihu.com/p/267372288
- https://github.com/candlewill/Speech-Corpus-Collection

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=taichuai/awesome-audio-speech-generation-corpus&type=Date)](https://star-history.com/#taichuai/awesome-audio-speech-generation-corpus&Date)
