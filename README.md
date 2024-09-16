

**EmbedSearch** is a document retrieval system designed to efficiently search and retrieve documents based on text similarity. The system uses Azure's AI models to convert both documents and user queries into vector embeddings, enabling fast and accurate similarity matching through Supabase's PostgreSQL vector type. To enhance performance, Redis is employed as a caching layer, reducing redundant computations for frequently queried documents and ensuring quicker response times. Additionally, the system includes rate-limiting to manage API usage and prevent overloading. News articles are dynamically scraped in the background to keep the document pool updated. With its optimized architecture, **EmbedSearch** provides a scalable and high-performance solution for text-based document retrieval.

Why used Redis ?

1. as redis stores data in memory, which provides very fast read/write operations
2. redis support types of data structure
3. redis can be used to handle high-workload, so its highly scalable
# EmbedSearch
