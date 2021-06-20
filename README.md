# DISCO PAL: Diachronic Spanish Sonnet Corpus with Psychological and Affective Labels 

This dataset contains a Spanish corporus of 274 sonnets annotated with affective and psychological features.

## Source corpus
The source corpus for the annotations is DISCO [1].

## Participants
POSTDATA reasearch group (UNED) is responsible for providing this dataset thanks to the annotations made by three of their domain experts (Laura Alises, Marie Olivier y Aroa Rabdán).

## Description of DISCO PAL
**Affectives**: 
- They represent the ability for the sonnet to evoke that affection 
- The affective features have a scale range of 1 for minimum to 4 for maximum
- The features are:

| Happiness  |  Anger | Sadness  | Fear | Disgust  |
|---|---|---|---|---|
|  **Valence** |  **Arousal** |  **Concreteness** | **Imageability**  | **Context Availability**  |


**Psychological**:
- Together with this, the experts have annotated some psychological features that have been defined as relevant in the literature [2]. 
- These annotations are binary, indicating with a 1 in case the sonnet refers to that concept and 0 otherwise.
- The features are

| Solitude  |  Illusion | Dreaming  | Greatness | Pride  |
|---|---|---|---|---|
|  **Irritability** |  **Anxiety** |  **Anger** | **Instability**  | **Idealization**  |
|  **Depression** |  **Disappointment** |  **Dislike** | **Insecurity**  | **Impotence**  |
|  **Vulnerability** |  **Fear** |  **Obsession** | **Compulsion**  | **Prejudice**  |
|  **Dramatization** |  |  |   |   |

## Folder structure
- The folder 'POSTDATA annotations' contains the raw annotations provided by the experts, in an Excel format and using different sheet names.
- The folder 'Processed annotations' contains the same data but inside a CSV file, standarizing the raw information provided by the experts. There is an additional file, 'poem_corpus_all.csv' that contains the median value from the annotations of the three experts.

## Authors and citation
* Alberto Barbado González (alberto.barbado.gonzalez@gmail.com)
* Víctor Fresno Fernández (vfresno@lsi.uned.es)
* Ángeles Manjarrés Riesco (amanja@dia.uned.es)
* Salvador Ros Muñoz (sros@scc.uned.es)

Barbado González, Alberto. Fresno Fernández, Víctor. Manjarrés Riesco, Ángeles. Ros Muñoz, Salvador. 2019. DISCO PAL: Diachronic Spanish Sonnet Corpus with Psychological and Affective Labels. Madrid. UNED. https://github.com/AlbertoBarbado/DISCO_PAL. [![DOI](https://zenodo.org/badge/207177683.svg)](https://zenodo.org/badge/latestdoi/207177683)

You can cite this dataset through its publication:
@article{barbado2020disco,
  title={DISCO PAL: Diachronic Spanish Sonnet Corpus with Psychological and Affective Labels},
  author={Barbado, Alberto and Fresno, V{\'\i}ctor and Riesco, {\'A}ngeles Manjarr{\'e}s and Ros, Salvador},
  journal={arXiv preprint arXiv:2007.04626},
  year={2020}
}

## License
This project is licensed under the Apache License 2.0 - see the LICENSE file for details

## References
* [1] Ruiz Fabo, Pablo, Helena Bermúdez Sabel, Clara Martínez Cantón, and José Calvo Tello. 2017. Diachronic Spanish Sonnet Corpus (DISCO). Madrid: UNED. https://github.com/pruizf/disco. DOI 10.5281/zenodo.1069844
* [2] García Franco, J. D., & Manjarrés Riesco, Á. (2016). Modelado de los trastornos de la personalidad en OWL - lógica descriptiva y aplicación al desarrollo de un sistema experto de diagnóstico clínico y educativo; Universidad Nacional de Educación a Distancia (UNED).

## Acknowledgements
Thanks to POSTDATA research group in general, and in particular the experts Laura Alises, Marie Olivier and Aroa Rabdán, for providing the annotations for these sonnets.
