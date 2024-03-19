# pyesl
hybrid (ml + rule-based) grammar checker using spaCy's dependency parser
- parse input sentence into dependency tree
- walk tree, enforce predefined grammar rules

### primary goals
- hybrid grammar checking model will be deployed on cloud and available to use via web interface
- etl pipeline for analytics on grammar mistakes