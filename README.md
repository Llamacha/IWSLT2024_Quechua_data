# IWSLT2024 - Low-resource Speech Translation Track: Quechua-Spanish Parallel Corpus

Repository for sharing the data in the Quechua language, one of the languages for the low-resource speech translation track at IWSLT 2024.

## Parallel data

This corpus is the Spanish translation of the Huqariq corpus [(Zevallos et al., 2022)](https://arxiv.org/abs/2207.05498). It comprises 51 hours, 16 minutes of clean speech in Quechua, translated into Spanish (que_spa_clean). This version contains a validation and test dataset.

The audio files are located in [link](https://drive.google.com/drive/folders/1Ne1cMvWSUnLzxeksT2OnOJSiPNBhuC7E?usp=sharing)

The raw text transcriptions are located in `que_spa_clean/<split>/txt/<split>.<lang>`.

True-cased Spanish target translations are found in `que_spa_clean/<split>/txt/<split>.spa.tc`.

True-casing was done with a [sacremoses](https://github.com/alvations/sacremoses) Truecaser model trained on the Spanish side of WMT13 EN-ES.


## Additional Parallel Text data

As part of the constrained task, we allow parallel text from previous work.
Participants are also not required to use this data.

The data is found in this repository and called: "additional_mt_text".
They are extracted from the JW300 and Hinantin websites and used in the cited work below.


## Citation 

```
@article{ortega2020neural,
  title={Neural machine translation with a polysynthetic low resource language},
  author={Ortega, John E and Castro Mamani, Richard and Cho, Kyunghyun},
  journal={Machine Translation},
  volume={34},
  number={4},
  pages={325--346},
  year={2020},
  publisher={Springer}
}
```

## License
All audio recordings are property of Siminchikkunarayku and [Llamacha](https://llamacha.pe).

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/3.0/">Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License</a>.

## Acknowledgements

This work has been funded by AmericasNLP-2022 and Llamacha. Special thanks to Eva Mühlbauer, Maximilian Torres and Anku Kichka their support.
