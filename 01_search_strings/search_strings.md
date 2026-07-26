# Search Strings

## Conceptual Structure

Boolean queries combined two concept groups with AND; synonyms within each group combined with OR.

- **LLM terms:** large language model, LLM, GPT, CodeLlama, StarCoder, Codex, transformer model, PLM, language model, CodeT5, pretrained, pre-trained
- **Repair terms:** program repair, automatic repair, bug fix, patch generation, code repair, defect repair, APR, automated program repair, bug repair
- **Prompt terms:** prompt engineering, prompting, few-shot, zero-shot, CoT, ToT, React, RAG, instruction tuning

## Per-Database Query Strings

### ACM Digital Library
- **Search date:** [June 30, 2026]
- **Fields searched:** [Title, Abstract]
- **Exact query string:**
```
[(Title:("large language model" OR llm OR gpt OR codellama OR starcoder OR codex OR "transformer model" OR plm OR "language model" OR codet5 OR pretrained OR "pre-trained") OR Abstract:("large language model" OR llm OR gpt OR codellama OR starcoder OR codex OR "transformer model" OR plm OR "language model" OR codet5 OR pretrained OR "pre-trained")) AND (Title:("program repair" OR "automatic repair" OR "bug fix" OR "patch generation" OR "code repair" OR "defect repair" OR apr OR "automated program repair" OR "bug repair") OR Abstract:("program repair" OR "automatic repair" OR "bug fix" OR "patch generation" OR "code repair" OR "defect repair" OR apr OR "automated program repair" OR "bug repair")) AND (Title:("prompt engineering" OR prompting OR "few-shot" OR "zero-shot" OR cot OR tot OR react OR rag OR "instruction tuning") OR Abstract:("prompt engineering" OR prompting OR "few-shot" OR "zero-shot" OR cot OR tot OR react OR rag OR "instruction tuning"))]
```
- **Filters applied:** [Publication years 2022–2026]
- **Records retrieved:** [185]

### IEEE Xplore
- **Search date:** [June 30, 2026]
- **Fields searched:** [Title, Abstract]
- **Exact query string:**
```
[(("Document Title":"large language model" OR "Document Title":LLM OR "Document Title":GPT OR "Document Title":CodeLlama OR "Document Title":StarCoder OR "Document Title":Codex OR "Document Title":"transformer model" OR "Document Title":PLM OR "Document Title":"language model" OR "Document Title":CodeT5 OR "Document Title":pretrained OR "Document Title":"pre-trained" OR "Abstract":"large language model" OR "Abstract":LLM OR "Abstract":GPT OR "Abstract":CodeLlama OR "Abstract":StarCoder OR "Abstract":Codex OR "Abstract":"transformer model" OR "Abstract":PLM OR "Abstract":"language model" OR "Abstract":CodeT5 OR "Abstract":pretrained OR "Abstract":"pre-trained") AND ("Document Title":"program repair" OR "Document Title":"automatic repair" OR "Document Title":"bug fix" OR "Document Title":"patch generation" OR "Document Title":"code repair" OR "Document Title":"defect repair" OR "Document Title":APR OR "Document Title":"automated program repair" OR "Document Title":"bug repair" OR "Abstract":"program repair" OR "Abstract":"automatic repair" OR "Abstract":"bug fix" OR "Abstract":"patch generation" OR "Abstract":"code repair" OR "Abstract":"defect repair" OR "Abstract":APR OR "Abstract":"automated program repair" OR "Abstract":"bug repair") AND ("Document Title":"prompt engineering" OR "Document Title":prompting OR "Document Title":"few-shot" OR "Document Title":"zero-shot" OR "Document Title":CoT OR "Document Title":ToT OR "Document Title":React OR "Document Title":RAG OR "Document Title":"instruction tuning" OR "Abstract":"prompt engineering" OR "Abstract":prompting OR "Abstract":"few-shot" OR "Abstract":"zero-shot" OR "Abstract":CoT OR "Abstract":ToT OR "Abstract":React OR "Abstract":RAG OR "Abstract":"instruction tuning"))]
```
- **Filters applied:** [Publication years 2022–2026]
- **Records retrieved:** [166]

### Scopus
- **Search date:** [June 30, 2026]
- **Fields searched:** [title, abstract, keywords]
- **Exact query string:**
```
[TITLE-ABS-KEY("large language model" OR LLM OR GPT OR CodeLlama OR StarCoder OR Codex OR "transformer model" OR PLM OR "language model" OR CodeT5 OR pretrained OR "pre-trained") AND TITLE-ABS-KEY("program repair" OR "automatic repair" OR "bug fix" OR "patch generation" OR "code repair" OR "defect repair" OR APR OR "automated program repair" OR "bug repair") AND TITLE-ABS-KEY("prompt engineering" OR prompting OR "few-shot" OR "zero-shot" OR CoT OR ToT OR React OR RAG OR "instruction tuning")]
```
- **Filters applied:** [Publication years 2022–2026]
- **Records retrieved:** [551]

### Google Scholar
- **Search date:** [June 30, 2026]
- **Query string / search terms used:**
```
[("large language model" OR LLM OR GPT OR CodeLlama OR StarCoder OR Codex OR "transformer model" OR PLM OR "language model" OR CodeT5 OR pretrained OR "pre-trained") AND ("program repair" OR "automatic repair" OR "bug fix" OR "patch generation" OR "code repair" OR "defect repair" OR APR OR "automated program repair" OR "bug repair") AND (Title:("prompt engineering" OR prompting OR "few-shot" OR "zero-shot" OR cot OR tot OR react OR rag OR "instruction tuning") OR Abstract:("prompt engineering" OR prompting OR "few-shot" OR "zero-shot" OR cot OR tot OR react OR rag OR "instruction tuning"))]
```
- **Notes:** Google Scholar does not support full Boolean field-restricted queries; note any
  manual adaptation (e.g., searching in batches, using quoted phrases only).
- **Records retrieved:** [8610] 

## Snowballing (Manual Search)

- **Seed papers:** [11]
- **Method:** Backward (references) and forward (citations) snowballing.
- **Additional records identified:** [21]
