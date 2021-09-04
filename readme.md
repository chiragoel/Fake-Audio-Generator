Fake Audio Generator
This repo contains the training scripts for creating a fake audio generator that converts any given text to an obama speech using 
-TTS: Using Tacotron 2 model with MB-MelGAN as vocoder
-Voice conversion: Mask-CycleGAN-VC
The mozilla TTS repository has been used for text to speech conversion. (https://github.com/mozilla/TTS)
The code for MaskCycleGAN-VC is inspired from https://github.com/GANtastic3/MaskCycleGAN-VC

The dataset used for training
-The TTS model is LjSpeech, available here https://keithito.com/LJ-Speech-Dataset/
-The voice conversion model is available here https://drive.google.com/drive/u/4/folders/1nzAkrI14zCi9jIoEw_eUY_hlyBxMzAYM

Note: The voice conversion dataset is self created using youtube-dl,ffmpeg and pyaudio.