# Speech-Kinyarwanda-dataset

This dataset was collected in kinyarwanda language using the android application [lig-aikuma]{https://lig-aikuma.imag.fr/download/} as part of speech recognition project under the guidance of __Laurent Besacier__, Univ. Grenoble Alpes. This dataset contains $971$ utterances and is 2.9 (~ 3) hours long. It was splited into train, validation and test sets with 1.4, 0.35 and 1.15 hours long respectively.

## Use case
```
- [x] git clone https://github.com/jp-ishimwe/Speech-Kinyarwanda-dataset.git
- [] cd Speech-Kinyarwanda-dataset or 
- [] get the link towards the file you want to use.

```
The charset json file contains all possible characters and numbers in the <span style="color:gray;">text-file.txt</span> which you need to use in decoding. 

You can also try to build your language model using <span style="color:gray;">text-file.txt</span> for kenlm model.
 
## Limitations

+ Lack of enough resources
+ Misspelled texts
+ Unfriendly android app through which you can skip an utterance and no way to come back.
+ Variations of speech (low and high) during recording due to fatigue






&copy copyrights reserved 2020 under MIT license!