Project Description: Wikipedia Content Storage Using Embedding Techniques
This project focuses on efficiently storing Wikipedia page content in a vector database using advanced embedding techniques. The objective is to enable quick and accurate retrieval of semantic information from Wikipedia articles, supporting tasks such as search, recommendation, and knowledge discovery.

Key Components:
Embedding Technique:

Utilized OpenAI's embedding model to convert Wikipedia page content into high-dimensional vector representations.
Each vector captures the semantic essence of the corresponding content, ensuring contextual understanding.
Vector Database:

Integrated Pinecone as the vector database for storing and managing the embeddings.
Pinecone's high-performance indexing and querying capabilities allow for fast and scalable similarity searches across the stored embeddings.
Workflow:
Extracted content from selected Wikipedia pages.
Processed the text to create embeddings using OpenAI's API.
Stored the resulting embeddings in Pinecone, indexed for efficient retrieval.
Enabled semantic search by querying Pinecone with user-provided text or phrases to find the most relevant Wikipedia content.
Use Cases:
Semantic search engines for Wikipedia content.
Building AI-powered tools for knowledge management.
Enhancing applications requiring contextual understanding of textual data.
This implementation demonstrates the practical application of state-of-the-art embedding and vector database technologies, showcasing their potential in large-scale information retrieval and AI-driven solutions.

Steps to follow - 
1. Create a virtual environment - python3 -m venv virtual-env-name
2. Activate the virtual environment - source virtual-env-name/bin/activate
3. Install all the dependencies using the requirements.txt file - pip install -r requirements.txt
4. Replace the page title based on your use case. I have used Amazon.com company's wiki page.
5. Make sure you use a unique web agent ID using the format mentioned in the code for easy access to the wiki API.
6. I have used the pinecone database as my vector database. Create one account and start using it. Sign Up here - https://app.pinecone.io/
7. For storing vectors in Pinecone we need an index so add your own index name in the code before running it.
8. Here OpenAPI is used as the embedding model.
9. Keep your OPENAI_API_KEY and PINECONE_API_KEY handy.
