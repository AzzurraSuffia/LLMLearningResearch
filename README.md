# LLMLearningResearch

Investigation of Gemini Pro on Vertex AI for accurate, university-level problem solving.

## Documentation

The analytical results and discussion of the experiments are available in the PDF report:
- `docs/thesis_analysis.pdf`

The analysis was conducted using two Jupyter notebooks:
- `gemini-notebook.ipynb` (Italian)
- `gemini-notebook (en).ipynb` (English)

Both notebooks pose the **same set of questions on Logical Networks topics**, in Italian and English respectively. The goal is to evaluate the model’s answers and **compare response quality across languages and different prompt modalities**.

The following **model augmentation techniques** are tested:
- Prompt with no context or examples  
- Prompt with direct retrieval (RAG)  
- Prompt with direct retrieval (RAG) and solution video  
- Prompt with solution video  
- Prompt with textbook  
- Prompt with textbook and solution video  
- Prompt with tool-based retrieval (RAG)  
- Prompt with examples (few-shot prompting)  
- Prompt with examples, textbook, and solution video  

### Privacy and Copyright Notice

To protect account privacy and respect copyrighted materials, the notebooks include **placeholders** (e.g., `<PROJECT-ID>`, `<REGION>`) and **anonymized paths** for images, videos, and other external resources. These placeholders indicate where project-specific or protected resources should be configured by the user.
