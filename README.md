# social-network-analysis

### Intro
Through movie reviews by users, social network between movie review keywords is established, and through this, insight such as topology, relationships, and interesting elements of keywords according to the genre of the movie is derived

### data

#### movi_noun.pkl
공조 / 아이캔스피크 / 완벽한 타인

### preprocessing

- OpenKoreanText analysis on Konlpv
- Noun extraction using morpheme analysis
- Removing disuse term
- ID, review, rating variable extraction

### analysis with frequency-word curve graph

- Compare frequency with the number of word by frequency, grouped with unique words

### analysis with 

- Change reviewer-review (2-mode) data to review-review (1-mode) data and establish a network
- For the relationship between review keywords, use Betweeness centrality because common keywords are important regardless of review propensity or intention
- Express by EqualEdge and Gower scaling
