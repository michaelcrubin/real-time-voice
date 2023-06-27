# Real-Time Voice Cloning
This repository is an implementation of a deep learning framework for real-time voice cloning. The framework is based on a research paper titled "Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis" (SV2TTS). The implementation includes a vocoder that enables real-time voice synthesis. The original work was conducted as a master's thesis.

The framework consists of three stages. In the first stage, a digital representation of a voice is created using a few seconds of audio. In the second and third stages, this representation is used as a reference to generate speech for any given text.

The repository includes a video demonstration showcasing the capabilities of the framework. The demonstration can be accessed by clicking the provided link.

The implementation incorporates several research papers related to voice synthesis, including SV2TTS, WaveRNN (vocoder), Tacotron (synthesizer), and GE2E (encoder). The implementation source for each paper is indicated in the table provided.

It's important to note that this repository may not be the most up-to-date or provide the highest audio quality for voice cloning. For improved audio quality and additional functionalities, alternative solutions are recommended. These include the open-source repository CoquiTTS, other repositories available on paperswithcode, and the state-of-the-art voice cloning solution provided by Resemble.ai.

To set up the framework, follow the provided steps:

1. Install the necessary requirements, including Python 3.7, ffmpeg, and PyTorch.
2. Optionally, download the pretrained models. If automatic download fails, manual download links are provided.
3. Optionally, test the configuration using the provided command.
4. Optionally, download datasets for experimentation. The recommended dataset is LibriSpeech/train-clean-100, but other datasets are supported as well.
5. Launch the toolbox using the provided command. The datasets root directory should be specified if datasets were downloaded.

By following these steps, users can utilize the toolbox for voice cloning purposes. It's worth noting that certain considerations should be taken into account, such as X-server configuration or troubleshooting the "Aborted (core dumped)" error, as detailed in the provided issue link.
