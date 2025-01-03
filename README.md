# Store-Wiki-Page-in-Vector-Database

Steps to follow - 
1. Create a virtual environment
2. Activate the virtual environment
3. Install all the dependencies using requirements.txt file
4. Replace the page title based on your use case. I have used Amazon.com company's wiki page.
5. Make sure you use a unique web agent ID using the formar mentioned in the code for easy access of the wiki api.
6. I have used pinecone database as my vector database. Create one account and start using it. Sign Up here - https://app.pinecone.io/
7. For storing vectors in pinecone we need an index so add your own index name before running the code.
8. Here OpenAPI is used as the embedding model.
9. Keep your OPENAI_API_KEY and PINECONE_API_KEY handy.
