<h1> High-Resolution Speech Restoration with Latent Diffusion Model </h1>

<div align="center">
Tushar Dhyani<sup>1,2</sup>, Florian Lux<sup>2</sup>, Michele Mancusi<sup>1</sup>, Giorgio Fabbro<sup>1</sup>, Fritz Hohl<sup>1</sup>, Ngoc Thang Vu<sup>2</sup><br> 
<sup>1</sup>Sony Europe B.V., Stuttgart, Germany<br>
<sup>2</sup>University of Stuttgart, Germany<br>

<a href="https://arxiv.org/abs/2409.11145"> <img src="https://img.shields.io/badge/cs.SD-2409.11145-b31b1b?logo=arxiv&logoColor=red"></a>
</div>


Welcome to the supplementary page of our paper _High-Resolution Speech Restoration with Latent Diffusion Model_.

This page contains one real-world sample where we compare the performance with other publically available speech-restoration frameworks compared in the paper. 

---

## Abstract
Traditional speech enhancement methods often oversimplify the task of restoration by focusing on a single type of distortion. Generative models that handle multiple distortions frequently struggle with
phone reconstruction and high-frequency harmonics, leading to breathing and gasping artifacts that reduce the intelligibility of reconstructed speech. These models are also computationally demanding, and many solutions are restricted to producing outputs in the wide-band frequency range, which limits their suitability for professional applications. To address these challenges, we propose Hi-ResLDM, a novel generative model based on latent diffusion designed to remove multiple distortions and restore speech recordings to studio quality, sampled at 48kHz. We benchmark Hi-ResLDM against state-of-the-art methods that leverage GAN and Conditional Flow Matching (CFM) components, demonstrating superior performance in regenerating high-frequency-band details. Hi-ResLDM not only excels in non-instrusive metrics but is also consistently preferred in human evaluation and performs competitively on intrusive evaluations, making it ideal for high-resolution speech restoration.

The link below redirects to the video on Youtube.

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/KLXGM_EQbDQ/0.jpg)](https://www.youtube.com/watch?v=KLXGM_EQbDQ)

---
<div style="display: flex; align-items: center;">
      <audio controls>
            <source src="./assets/audio/penny_serende/emotional_orig.wav" type="audio/mpeg" controls="nodownload">
                              Your browser does not support the audio element.
      </audio>
      <img src="./assets/images/penny_serende/emotional_orig.png" alt="original" controls="nodownload">
</div>
<div style="display: flex; align-items: center;">
      <audio controls>
            <source src="./assets/audio/penny_serende/emotional_vf.wav" type="audio/mpeg" controls="nodownload">
            Your browser does not support the audio element.
      </audio>
      <img src="./assets/images/penny_serende/emotional_vf.png" alt="vf">
</div>
<div style="display: flex; align-items: center;">
      <audio controls>
            <source src="./assets/audio/penny_serende/emotional_re.wav" type="audio/mpeg" controls="nodownload">
            Your browser does not support the audio element.
      </audio>
      <img src="./assets/images/penny_serende/emotional_re.png" alt="re">
</div>
<div style="display: flex; align-items: center;">
      <audio controls>
            <source src="./assets/audio/penny_serende/emotional_ours.wav" type="audio/mpeg" controls="nodownload">
            Your browser does not support the audio element.
      </audio>
      <img src="./assets/images/penny_serende/emotional_ours.png" alt="ours">
</div>
![original](./assets/images/penny_serende/emotional_orig.png)
![original](./assets/images/penny_serende/emotional_vf.png)
![original](./assets/images/penny_serende/emotional_re.png)
![original](./assets/images/penny_serende/emotional_ours.png)


## Cite
```bibtex
@misc{dhyani2024highresolutionspeechrestorationlatent,
      title={High-Resolution Speech Restoration with Latent Diffusion Model}, 
      author={Tushar Dhyani and Florian Lux and Michele Mancusi and Giorgio Fabbro and Fritz Hohl and Ngoc Thang Vu},
      booktitle={IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP)},
      year={2025},
      eprint={2409.11145},
      archivePrefix={arXiv},
      primaryClass={cs.SD},
      url={https://arxiv.org/abs/2409.11145}, 
}
```
