## It is basically the implementation of Elastic Search.
Elasticsearch is built on top of Apache Lucene, which is a high performance text search engine library. Although Elasticsearch can perform the storage and retrieval of data, its main purpose is not to serve as a database, rather it is a search engine (server) with the main goal of indexing, searching, and providing real-time statistics on the data.

Elasticsearch has a distributed architecture that allows horizontal scaling by adding more nodes and taking advantage of the extra hardware. It supports thousands of nodes for processing petabytes(PB) of data. Its horizontal scaling also means that it has a high availability by rebalancing the data if ever any nodes fail.

## List of files in this repository:

1. `data.json`: sample data file
2. `index.js`: script for indexing the data in elasticsearch
3. `indices.js`: script to check indexing was successful
4. `search_all.js`: return all documents in one or more indices
5. `search_match.js`: match documents that contain specific values in a field
6. `search_multi_match.js`: search within multiple fields
7. `search_match_phrase.js`: match a complete phrase
8. `search_bool.js`: combining multiple queries
9. `filter.js`: basic filter functionality
10. `aggregations.js`: demonstration of how aggregations work
11. `suggest_term.js`: generate suggestions for search terms
12. `suggest_phrase.js`: generate suggestions for search phrases


