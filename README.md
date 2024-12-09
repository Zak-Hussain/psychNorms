## psychNorms

A systematically-derived metabase of 292 psychological word norms, obtained for the sake of interpretability analyses in the following paper (please cite if you use the data):

```
@misc{hussain2024probingcontentssemanticrepresentations,
      title={Probing the contents of semantic representations from text, behavior, and brain data using the psychNorms metabase}, 
      author={Zak Hussain and Rui Mata and Ben R. Newell and Dirk U. Wulff},
      year={2024},
      eprint={2412.04936},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2412.04936}, 
}
```

The metabase was developed through a systematic literature search for psychological word norms. 
A total of 3,056 Web of Science articles matching the query `((word OR words) NEAR/10 (norm OR norms)) OR ((word OR words) NEAR/10 (rating OR ratings))` were screened 
in multiple rounds to identify primary data containing human-rated (behavioral) word properties in English.
Following several rounds of screening, the results were combined with various psychological norms from the 
South Carolina Psycholinguistic Metabases ([SCOPE](https://www.sc.edu/study/colleges_schools/artsandsciences/psychology/research_clinical_facilities/scope/)) and 
a [dataset](https://doi.org/10.1080/02643294.2016.1147426) of 65 human-rated experiential attributes. The final metabase contains 292 norms, 130 of which 
are the unique result of the systematic literature search. The search returned 171 norms, 41 of which also exist in SCOPE.   

| Source                  | # Norms | # Ratings     |
|-------------------------|---------|---------------|
| Literature search       | 181     | 871,510       |
| SCOPE                   | 97      | 2,675,855     |
| Experiential attributes | 65      | 34,710        |
| **Total (unique)**      | **292** | **2,859,410** |

It should be noted that we draw on the [publicly available](https://www.sc.edu/study/colleges_schools/artsandsciences/psychology/research_clinical_facilities/scope/search.php) version of SCOPE, 
which contains ratings for a reduced set of (higher frequency) words to limit the size of the dataset for practical, data sharing reasons. This mainly impacts
the more objective (non-human rated) norms in the metabase (e.g., frequency, part of speech), which contain a higher proportion of lower frequency words.

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
- `psychNorms_metadata.csv`: Contains metadata for each of the norms in `psychNorms.csv`, with the following columns:
  - `norm`: Name of the norm.
  - `description`: Description of the norm.
  - `citation`: Original source of the norm.
  - `category`: High-level category for the norm.
  - `source`: (Meta-)Source of the norm (`SCOPE`, `experiential_attributes`, or `lit_search`).



