Reference: 

[NVIDIA/tacotron2](https://github.com/NVIDIA/tacotron2)

[jik876/hifi-gan: HiFi-GAN: Generative Adversarial Networks for Efficient and High Fidelity Speech Synthesis (github.com)](https://github.com/jik876/hifi-gan)

[luoyily/MoeTTS: Speech synthesis model repo for galgame characters based on Tacotron2, Hifigan and VITS (github.com)](https://github.com/luoyily/MoeTTS)

[CjangCjengh/tacotron2-japanese: Tacotron2 implementation of Japanese (github.com)](https://github.com/CjangCjengh/tacotron2-japanese)

<h3>Filelist</h3>

Yuuki Noa without Hscene.

## How to use
1. Put raw Japanese texts in ./filelists
2. Put WAV files in ./wav
3. (Optional) Download NVIDIA's [pretrained model](https://drive.google.com/file/d/1c5ZTuT7J08wLUoVZ2KkUs_VdZuJ86ZqA/view?usp=sharing)
4. Open ./train.ipynb to install requirements and start training
5. Download NVIDIA's [WaveGlow model](https://drive.google.com/open?id=1rpK8CzAAirq9sWZhe9nlfvxMF1dRgFbF)
6. Open ./inference.ipynb to generate voice with waveglow or open ./inference-tacotron2-Japanese-hifigan.ipynb to generate voice with Hifigan.
