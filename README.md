`handwriting_samples` which contains the templates of my handwriting used for the text generation.

`image_parser.ipynb` contains the code to parse the handwriting templates into individual character templates. The outputs are separated into `lowercase_characters`, `uppercase_characters`, and `punctuation`.

`text_builder.ipynb` contains the code to generate texts for each condition using the previously extracted character templates.

`generated_texts` contain the 16 output images used in the pilot study. One for each passage/condition combination.

`preliminary_character_variation.ipynb` and `preliminary_structure_variation.ipynb` were initial attempts to computationally extract structure from existing handwritten texts in different languages and are not used as part of the final paper.

`letterform_variation.ipynb` is an adapted version of `preliminary_character_variation.ipynb` used to calculate variation within my own writing. Its results were purely out of curiosity and are also not referenced as part of the final paper.
