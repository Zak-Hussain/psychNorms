# psychNorms

A systematically-derived metabase of XX psychological word norms, obtained for the sake of interpretability analyses in the following paper:

```
@article{hussain2024probing,
  title={Probing the contents of text, brain, and behavior data toward improving human-LLM alignment},
  author={Zak Hussain and Rui Mata and Ben Newell and Dirk U. Wulff},
  journal={arXiv},
  year={2024}
  url={https://arxiv.org/XX}
}
```

The metabase is the result of a systematic literature search for psychological word norms, in which 3056 articles containing relevant keywords were screened
(see section 'psychNorms' in the paper for more details). Following several rounds of screening, the results were combined with various psychological norms from the 
South Carolina Psycholinguistic Metabases ([SCOPE](https://www.sc.edu/study/colleges_schools/artsandsciences/psychology/research_clinical_facilities/scope/)) and 
a [dataset](https://doi.org/10.1080/02643294.2016.1147426) of 65 human-rated experiential attributes. The final metabase contains 292 norms, with a total of 2,859,287 ratings:

| Source                 | # norms | # ratings     |
|------------------------|---------|---------------|
| SCOPE                  | 97      | 2,710,387     |
| Experiential attributes | 65      | 34,710        |
| Literature search      | 130     | 148,900       |
| **Total**  | **292** | **2,859,287** |

Norms were manually grouped into 27 categories, which are listed below along with the number of norms and ratings in each category:

| Category                   | # Norms | # Ratings    |
|----------------------------|---------|--------------|
| Age of acquisition         | 16      | 73,084       |
| Animacy                    | 14      | 11,689       |
| Arousal                    | 9       | 43,053       |
| Associatability            | 3       | 1,546        |
| Auditory lexical decision  | 4       | 73,459       |
| Concreteness               | 6       | 45,707       |
| Dominance                  | 3       | 37,834       |
| Emotion                    | 31      | 155,246      |
| Familiarity                | 22      | 130,526      |
| Frequency                  | 10      | 596,385      |
| Goals/needs                | 3       | 2,128        |
| Iconicity/transparency     | 5       | 22,036       |
| Imageability               | 14      | 18,723       |
| Motor                      | 16      | 239,976      |
| Naming                     | 2       | 80,960       |
| Number of features         | 1       | 4,381        |
| Part of speech             | 2       | 118,999      |
| Recognition memory         | 1       | 4,743        |
| Semantic decision          | 10      | 32,631       |
| Semantic diversity         | 11      | 444,598      |
| Semantic neighborhood      | 7       | 153,554      |
| Sensory                    | 36      | 207,538      |
| Social/moral               | 16      | 25,774       |
| Space/time/quantity        | 25      | 18,096       |
| This/that                  | 1       | 535          |
| Valence                    | 18      | 54,052       |
| Visual lexical decision    | 6       | 262,034      |




The metabase is composed of two files:
- `psychNorms.csv.zip`: Contains XX psychological norms (columns) at the word level (rows).
- `psychNorms_metadata.csv`: Contains metadata for each of the norms in `psychNorms.csv`.

Norms with title cased names are norms that also exist in SCOPE or the experiential attributes dataset. The remaining norms are uniquely derived from the systematic literature search.
