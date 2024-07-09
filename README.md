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

| Category                   | # Norms | # Ratings | 
|----------------------------|---------|-----------|
| Age of Acquisition         | 16      | 73084     |
| Animacy                    | 14      | 11689     |
| Arousal                    | 9       | 43053     |
| Associatability            | 3       | 1546      |
| Autidtory Lexical Decision | 4       | 73459     |
| Concreteness               | 6       | 45707     |
| Dominance                  | 3       | 37834     |
| Emotion                    | 31      | 155246    |
| Familiarity                | 22      | 130526    |
| Frequency                  | 10      | 596385    |
| Goals/Needs                | 3       | 2128      |
| Iconicity/Transparency     | 5       | 22036     |
| Imageability               | 14      | 18723     |
| Motor                      | 16      | 239976    |
| Naming                     | 2       | 80960     |
| Number of Features         | 1       | 4381      |
| Part of Speech             | 2       | 118999    |
| Recognition Memory         | 1       | 4743      |
| Semantic Decision          | 10      | 32631     |
| Semantic Diversity         | 11      | 444598    |
| Semantic Neighborhood      | 7       | 153554    |
| Sensory                    | 36      | 207538    |
| Social/Moral               | 16      | 25774     |
| Space/Time/Quantity        | 25      | 18096     |
| This/That                  | 1       | 535       |
| Valence                    | 18      | 54052     |
| Visual Lexical Decision    | 6       | 262034    |



The metabase is composed of two files:
- `psychNorms.csv.zip`: Contains XX psychological norms (columns) at the word level (rows).
- `psychNorms_metadata.csv`: Contains metadata for each of the norms in `psychNorms.csv`.

Norms with title cased names are norms that also exist in SCOPE or the experiential attributes dataset. The remaining norms are uniquely derived from the systematic literature search.
