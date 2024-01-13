# IWSLT2024 - Low-resource Speech Translation Track: Quechua-Spanish Parallel Corpus

Repository for sharing the data in the Quechua language, one of the languages for the low-resource speech translation track at IWSLT 2024.

## Parallel data


This corpus is a small fraction of the Siminchik corpus [(Cardenas et al., 2018)](http://lrec-conf.org/workshops/lrec2018/W14/pdf/book_of_proceedings.pdf#page=28) translated into Spanish. It comprises 1 hour, 40 minutes of clean speech in Quechua, translated into Spanish (que_spa_clean_siminchik_filter). This version contains a validation and test data set.

The raw text transcriptions are located in `que_spa_clean_siminchik_filter/<split>/txt/<split>.<lang>`.

True-cased Spanish target translations are found in `que_spa_clean_siminchik_filter/<split>/txt/<split>.spa.tc`.

hola mundo

True-casing was done with a [sacremoses](https://github.com/alvations/sacremoses) Truecaser model trained on the Spanish side of WMT13 EN-ES.

In addition, we are making available a new corpus. This corpus is the Spanish translation of the Siminchik and Huqariq corpus [(Zevallos et al., 2022)](https://arxiv.org/abs/2207.05498). It comprises 51 hours, 16 minutes of clean speech in Quechua, translated into Spanish. The corpus is located in [link](https://github.com/Llamacha/quechua_spanish_speech_translation_corpus).


## Additional Audio data

In addition to the 1 hour, 40 minutes of Quechua audio data aligned with Spanish translations, we also provided participants with a corpus of 48 hours of fully transcribed Quechua audio. All of this data comes from the filter Siminchik corpus  [link](https://drive.google.com/file/d/1ZwBE5LlwCHJaxkAw2IM97hkh-NFO-k0C/view?usp=sharing).

Participants are not required to use any of this data.

## Citation 

```
@article{cardenas2018siminchik,
  title={Siminchik: A speech corpus for preservation of southern quechua},
  author={Cardenas, Ronald and Zevallos, Rodolfo and Baquerizo, Reynaldo and Camacho, Luis},
  journal={ISI-NLP 2},
  pages={21},
  year={2018}
}
```


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
