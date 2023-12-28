# Fake News Detection Project

## Project Overview

This project aims to detect fake news by leveraging information from reputable fact-checking websites. The workflow involves data extraction, embedding generation, database storage, and a similarity chain to respond to user queries regarding the authenticity of a given statement.

## Tasks

### 1. Data Extraction
- Collect news articles from fact-checking websites:
  - [Lupa UOL](https://lupa.uol.com.br/jornalismo/categoria/verifica%C3%A7%C3%A3o)
  - [G1 Globo - Fato ou Fake](https://g1.globo.com/fato-ou-fake/)
  - [Agência Pública - Entrelinhas do Poder](https://apublica.org/tipo_nota/entrelinhas-do-poder/)
  - [e-Farsas](https://www.e-farsas.com/)

### 2. Embedding Generation
- Utilize OpenAI's language model and LangChain to create embeddings for the extracted news articles.

### 3. Database Storage
- Save generated embeddings in a vectorized database for efficient retrieval and comparison.

### 4. Similarity Chain
- Develop a chain that analyzes user queries, identifies similar results from the vectorized database, and ranks them based on relevance.

### 5. Noise Filtering
- Implement a noise-filtering mechanism to enhance result accuracy.

### 6. Verdict and Source Identification
- Provide a clear verdict (fact or fake) based on the analysis and identify supporting sources.

## Technologies Used
- OpenAI Language Model
- LangChain
- Vectorized Database (Turing)
- NLP Techniques
- Fact-Checking Websites' APIs

## Future Improvements
- Continuous model training for enhanced accuracy.
- Integration with additional fact-checking sources.
- User interface development for ease of interaction.
- Real-time news monitoring and analysis.


