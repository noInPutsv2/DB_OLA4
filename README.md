# DB_OLA4

# Chroma
for vectorise:
takes 6.76 minutes to run with 3 documents and 10 chunks
takes 38.56 minutes to run with 100 documents and 100 chunks
takes 291.46 minutes to run with 1000 documents and 100 chunks 

for asking a question: 
w/3 docs, 10 chunk 1.4911341349283853 minutes
# LanceDB
for vectorise:
w/3 documents and 10 chunk it takes ca. 5.40 minutes
w/100 documents and 100 chunk it takes ca. 39.18 minutes
w/1000 documents and 100 chunk it takes ca. 301.28 minutes
for asking a question: 
w/3 docs, 10 chunk 2.9323415637016295 minutes

# Neo4j
for vectorise:
w/3 documents and 10 chunk it takes ca. 7.49 minutes
for asking a question: 
w/3 docs, 10 chunk 1.801820441087087 minutes

# Conclusions
It's hard to find good guides to vectorise into databases for opensource vector databases
Chroma is the fastest for vectorise data and asking questions
Neo4j to vectorise but not for asking questions