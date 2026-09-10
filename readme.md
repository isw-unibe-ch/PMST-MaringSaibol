# Person Marking in South-Central Trans-Himalayan: Saibol Maring

This PARALEX set contains person markers in Saibol Maring, including inflected verbal forms and pronouns. It constitutes part of the PMST (Person Marking in South-Central Trans-Himalayan) database.
The PMST database is a collection of person forms from a broad sample of South-Central Trans-Himalayan languages collected with a common methodology and published as PARALEX sets. PMST sets can be used both for describing and analyzing language-internal distributions and for comparison of person forms.

The general design principles of PMST are described in Auderset et al. 2026. Files and columns are described here only where they deviate from the PARALEX standard.
For more details about the data, please consult the data\_sheet.md in the docs folder.

* PMST diverges most from the PARALEX standard and design principles in that the verb forms are abstract and do not contain a lexical verb stem. In its place, we use Σ as a placeholder (as is common in Trans-Himalayan linguistics). This means that the data set cannot be used to study variation in verb stems or inflectional classes.
* The source\_form column in the forms file contains the data exactly as it appears in the source. This may include a lexical verb stem (listed in lexemes). In the orthographic and phonological representation, the lexical verb is replaced by a Σ. This placeholder also appears in the graphemes and sounds files for validation purposes.
* The lexemes file is kept relatively minimal and only lists each lexical stem in orthographic form and its meaning. This is because we do not always have access to forms with stems. For pronouns, "no\_stem" is indicated in the lexeme column in the forms file and verb forms without a stem are labeled "abstract\_entry". These are also listed in the lexemes file (for validation purposes).
* To facilitate comparison across PMST data sets, each file has an additional column with a language identifier. This means that files can be combined from different PMST sets without losing information.
* The morphs file contains a list of all morphs that appear in the data set (apart from the stem) in tokenized IPA. For each morph there is a list of all the forms and cells it appears in.
* The docs folder contains the data sheet with more extensive description of how the data was gathered.

## Additional information specific to Saibol Maring

* Tone: The language has tones, but it is not marked in the source form as tonal analysis is still pending.
* Mapping between database paradigm labels and Saibol descriptive labels:

* Database label = Language-specific descriptive label
	* fut.aff = future affirmative
	* fut.neg = future negative
	* nfut.aff = simple (present) aspect
	* nfut.neg = simple (present) negative

* Transcription: Some \[a] are pronounced as \[ə] (schwa). However, in this data set both the vowels are phonemically represented by \[a]. 
* Variation in the data set:

a) There is morphophonological variation involving the coda of the future marker *num* with the person markers for 1SG, 1PLE, and 3PL.

e.g: 	1PLE.FA

	ka-shi-num-ang	(unspecified)

	ka-shi-num-mang	(morphophon)



	1PLE.FN

	shi-mak-num-ang	(unspecified)

	shi-num-mang	(morphophon)



	3PL.FA

	ka-shi-num-ei	(unspecified)

	ka-shi-num-mei	(morphophon)



	3PL.FN

	shi-mak-num-ei	(unspecified)

	shi-mak-num-mei	(morphophon)



## References

Auderset, Sandra, Hunter L. Brown, Jonathan Reich, Pascal Gerber, Muhammad Zakaria, and Linda Konnerth. 2026. “A Database of Person Marking in South-Central Trans-Himalayan”. *Journal of Open Humanities Data* 12 (1): 58. https://doi.org/10.5334/johd.505.