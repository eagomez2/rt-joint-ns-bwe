# Demo: Real-time joint noise suppression and bandwidth extension of noisy reverberant wideband speech

This is the demo page of the paper **Real-time joint noise suppression and bandwidth extension of noisy reverberant wideband speech** currently accepted to be published at the **International Workshop on Acoustic Signal Enhancement IWAENC 2024**.

[[Demo page](https://eagomez2.github.io/rt-joint-ns-bwe/)] [[Paper](https://research.aalto.fi/en/publications/real-time-joint-noise-suppression-and-bandwidth-extension-of-nois)]

## Abstract
Artificially extending the bandwidth of speech in band-limited scenarios using 16kHz (known as wideband) or lower sample rates such as in VoIP or some Bluetooth applications, can significantly improve its perceptual quality. Typically, clean speech is assumed as input to estimate the missing spectral information. However, such an assumption falls short if it has been contaminated by noise or reverb, resulting in audible artifacts. We propose a low-complexity multitasking neural network capable of performing noise suppression and bandwidth extension 16kHz to 48kHz (fullband) in real-time on a CPU, mitigating such issues even if the noise cannot be completely removed from the input. Instead of employing a monolithic model, we adopt a modular approach and complexity reduction methods that result in a more compact model than the sum of its parts while improving its performance.

## Cite
If this work contributed to your research, please consider citing it as follows:

```bibtex
@inproceedings{10694458,
  author={Gómez, Esteban and Bäckström, Tom},
  booktitle={2024 18th International Workshop on Acoustic Signal Enhancement (IWAENC)}, 
  title={Real-Time Joint Noise Suppression and Bandwidth Extension of Noisy Reverberant Wideband Speech}, 
  year={2024},
  volume={},
  number={},
  pages={6-10},
  keywords={Training;Computational modeling;Noise reduction;Noise;Neural networks;Speech enhancement;Real-time systems;Acoustics;Complexity theory;Wideband;Bandwidth extension;noise suppression;real-time;deep learning;multitasking},
  doi={10.1109/IWAENC61483.2024.10694458}
}
```

## Acknowledgement
The calculations presented in this publication were carried out using the computer resources of the Aalto University of Science “Science-IT” project.
