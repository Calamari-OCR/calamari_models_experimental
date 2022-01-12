# calamari_models_experimental

Intermediate results of experiments dealing with the training of mixed models for historical printed and handwritten material which seem to be somewhat promising/useful.

## Models

The deep3 prefix means that the model was trained using a considerably deeper network structure compared to the default one.
Cf. the upcoming [selection of default networks](https://github.com/Calamari-OCR/calamari/tree/calamari/2.1/calamari_ocr/resources/networks) for details.

### Printings

Most of the models focus on printings using Latin script and Antiqua/Fraktur types.
Training data included works from the 15th to 19th century.
Please see the corresponding [paper](https://dl.acm.org/doi/fullHtml/10.1145/3476887.3476910) for details.
The basic model is LSH-4 (Latin Script Historical) which was also used as a starting point to refine the other Antiqua and Fraktur models.

### Manuscripts

The "htr" models focus on the recognition of medieval German manuscripts in gothic and bastard fonts.
More details about the training data etc. to follow.
