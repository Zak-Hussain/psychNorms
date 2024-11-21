# psychNorms

A systematically-derived metabase of 292 psychological word norms, obtained for the sake of interpretability analyses in the following paper:

```
@article{hussain2024probing,
  title={Probing the contents of text, brain, and behavior data toward improving human-LLM alignment},
  author={Zak Hussain and Rui Mata and Ben R. Newell and Dirk U. Wulff},
  journal={arXiv},
  year={2024}
  url={https://arxiv.org/XX}
}
```

The metabase is the result of a systematic literature search for psychological word norms, in which 3056 articles containing relevant keywords were screened
(see section 'psychNorms' in the paper for more details). Following several rounds of screening, the results were combined with various psychological norms from the 
South Carolina Psycholinguistic Metabases ([SCOPE](https://www.sc.edu/study/colleges_schools/artsandsciences/psychology/research_clinical_facilities/scope/)) and 
a [dataset](https://doi.org/10.1080/02643294.2016.1147426) of 65 human-rated experiential attributes. The final metabase contains 292 norms, 130 of which 
are the unique result of the systematic literature search. The search returned 171 norms, 41 of which also exist in SCOPE.   

| Source                  | # Norms | # Ratings     |
|-------------------------|---------|---------------|
| Literature search       | 181     | 871,510       |
| SCOPE                   | 97      | 2,675,855     |
| Experiential attributes | 65      | 34,710        |
| **Total (unique)**      | **292** | **2,859,410** |

Norms were manually grouped into 27 categories, which are listed below along with the number of norms and ratings in each category:

| Category                  | # Norms | # Ratings  |
|---------------------------|---------|------------|
| Age of Acquisition        | 16      | 73,084     |
| Animacy                   | 14      | 11,689     |
| Arousal                   | 9       | 43,053     |
| Associatability           | 3       | 1,546      |
| Auditory Lexical Decision | 4       | 73,459     |
| Concreteness              | 6       | 45,707     |
| Dominance                 | 3       | 37,834     |
| Emotion                   | 31      | 155,246    |
| Familiarity               | 22      | 130,592    |
| Frequency                 | 10      | 596,385    |
| Goals/Needs               | 3       | 2,128      |
| Iconicity/Transparency    | 5       | 22,036     |
| Imageability              | 14      | 18,713     |
| Motor                     | 16      | 239,976    |
| Naming                    | 2       | 80,960     |
| Number of Features        | 1       | 4,381      |
| Part of Speech            | 2       | 118,999    |
| Recognition Memory        | 1       | 4,743      |
| Semantic Decision         | 10      | 32,631     |
| Semantic Diversity        | 11      | 444,598    |
| Semantic Neighborhood     | 7       | 153,554    |
| Sensory                   | 36      | 207,538    |
| Social/Moral              | 16      | 25,841     |
| Space/Time/Quantity       | 25      | 18,096     |
| This/That                 | 1       | 535        |
| Valence                   | 18      | 54,052     |
| Visual Lexical Decision   | 6       | 262,034    |
| **Total**                 | **292** | **2,859,410** |


The metabase is composed of two files:
- `psychNorms.zip`: Contains 292 psychological norms (columns) at the word level (rows).
- `psychNorms_metadata.csv`: Contains metadata for each of the norms in `psychNorms.csv`.

Norms with title cased names are norms that also exist in SCOPE or the experiential attributes dataset.  The remaining norms are uniquely derived from the systematic literature search.
