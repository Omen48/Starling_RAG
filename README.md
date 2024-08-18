Starling_RAG Project
**Description**
In this project, the Retrieval-Augmented Generation (RAG) approach is implemented for fine-tuning the Llama model. As an example, the project uses text files in the .txt format as a source of information for query processing. These text documents are processed using embeddings, allowing the model to more effectively retrieve and utilize information for generating responses.

**Clarification:**
llama-cpp-python==0.2.61 is used for generating embeddings and fine-tuning the model. This version was chosen due to current compatibility issues with newer versions, as described in [issue #1126.](https://github.com/abetlen/llama-cpp-python/issues/1126)
