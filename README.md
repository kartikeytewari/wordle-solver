# Wordle Solver
- A wordle solver in rust
- Official wordle [link](https://www.nytimes.com/games/wordle/index.html).

# Google n-gram Dataset
- Dataset downloaded from here: http://storage.googleapis.com/books/ngrams/books/20200217/eng/eng-1-ngrams_exports.html
- Store all files in a folder google-ngram-dataset
- Run for sample files: `zcat < 1-00000-of-00024.gz | head`
- Run for getting 5-letter words: `rg -z "^[a-zA-Z]{5}_[A-Z]+\t" 1-000*-of-00024.gz > 5-letter.txt`
