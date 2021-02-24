# opus-2021-02-19.zip

* dataset: opus
* model: transformer
* source language(s): fin hun
* target language(s): ind jak msa zlm zsm
* model: transformer
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* valid language labels: >>zlm_Latn<< >>ind<< >>msa_Latn<< >>jak_Latn<< >>zlm<<
* download: [opus-2021-02-19.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/fiu-pqw/opus-2021-02-19.zip)
* test set translations: [opus-2021-02-19.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/fiu-pqw/opus-2021-02-19.test.txt)
* test set scores: [opus-2021-02-19.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/fiu-pqw/opus-2021-02-19.eval.txt)

## Benchmarks

| testset | BLEU  | chr-F | #sent | #words | BP |
|---------|-------|-------|-------|--------|----|
| Tatoeba-test.fin-msa 	| 20.7 	| 0.518 	| 24 	| 140 	| 0.964 |
| Tatoeba-test.hun-msa 	| 11.5 	| 0.416 	| 51 	| 358 	| 1.000 |
| Tatoeba-test.multi-multi 	| 13.2 	| 0.442 	| 75 	| 498 	| 1.000 |
