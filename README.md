# INLP_Gram-wordsets

[![DOI](https://zenodo.org/badge/992496442.svg)](https://doi.org/10.5281/zenodo.15544008)

Word sets used in the development and experimentation of INLP-Gram (["Preserving Grammatical Gender when Debiasing Word Embeddings in Spanish"](url)).

To cite:

```

@article{morote2025approach,
  title={Preserving Grammatical Gender when Debiasing Word Embeddings in Spanish},
  author={Mart{\'i}nez, Aitana Morote and Consuegra-Ayala, Juan Pablo and Lloret, Elena},
  journal={Procesamiento del Lenguaje Natural},
  volume={75},
  pages={--},
  year={2025}
}

```

## File Specification

* `ES`, `FR` and `VAL` folders divide the word sets that have been retrieved for each language (ES: Spanish, FR: French, VAL: Valencian). The same file structure and name concention has been respected for each folder. As the experimentation for French and Valencian is in course, the files of word sets for these languages are being updated and may be incomplete. The files in the Spanish folder represent the complete datasets used in the paper.
  * `{LANG}/Gram` folder contains word sets related to grammatical gender information
  * `{LANG}/Gram/{LANG}_GGCTest_f.txt` and `{LANG}/Gram/{LANG}_GGCTest_m.txt` are the word sets for the grammatical gender classification test
  * `{LANG}/Gram/{LANG}_gram_LDA_f.txt` and `{LANG}/Gram/{LANG}_gram_LDA_m.txt` are the word sets for computing the grammatical gender direction
  * `{LANG}/{LANG}_WEAT_f` and `{LANG}/{LANG}_WEAT_m` and `{LANG}/{LANG}_definitional_pairs`contain the definitional word pairs used in the WEAT paper and translated.
  * `{LANG}/{LANG}_professions`is the set of professions inflected to the masculine, feminine, singular and plural, used for the visualization experiments (Section 6.3 of the paper).
